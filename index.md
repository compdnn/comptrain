<img width="150" img align="right" alt="NSF-logo" src="https://user-images.githubusercontent.com/5705572/95711667-1d953c00-0c18-11eb-817b-1cc6a90d504d.png">

**Project Title**: CRII: OAC: An Efficient Lossy Compression Framework for Reducing Memory Footprint for Extreme-Scale Deep Learning on GPU-Based HPC Systems

**PI**: [Dingwen Tao](https://www.dingwentao.com/) (Indiana University)

**Awards**: [1948447](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1948447), [2034169](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2034169), [2303820](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2303820) (UA, WSU, IU, $190K)

**Project Duration**: 5/01/2020 - 4/30/2023

## Overview
<img width="1382" alt="sec-4 1-1" src="https://user-images.githubusercontent.com/5705572/199804940-7342d3b1-034d-4de3-80ad-c24314a29369.png">


## Abstract

Deep learning (DL) has rapidly evolved to a state-of-the-art technique in many science and technology disciplines, such as scientific exploration, national security, smart environment, and healthcare. Many of these DL applications require using high-performance computing (HPC) resources to process large amounts of data. Researchers and scientists, for instance, are employing extreme-scale DL applications in HPC infrastructures to classify extreme weather patterns and high-energy particles. In recent years, using Graphics Processing Units (GPUs) to accelerate DL applications has attracted increasing attention. However, the ever-increasing scales of DL applications bring many challenges to today’s GPU-based HPC infrastructures. The key challenge is the huge gap (e.g., one to two orders of magnitude) between the memory requirement and its availability on GPUs. This project aims to fill this gap by developing a novel framework to reduce the memory demand effectively and efficiently via data compression technologies for extreme-scale DL applications. The proposed research will enhance the GPU-based HPC infrastructures in broad communities for many scientific disciplines that rely on DL technologies. The project will connect machine learning and HPC communities and increase interactions between them. Educational and engagement activities include developing new curriculum related to data compression, mentoring a selected group of high school students in a year-long research project for a regional Science Fair competition, and increasing the community's understanding of leveraging HPC infrastructures for DL technologies. The project will also encourage student interest in research related to DL technologies on HPC environment and promote research collaborations with multiple national laboratories. 

Existing state-of-the-art GPU memory saving methods for training extreme-scale deep neural networks (DNNs) suffer from high performance overhead and/or low memory footprint reduction. Error-bounded lossy compression is a promising approach to significantly reduce the memory footprint while still meeting the required analysis accuracy. This project will explore how to leverage error-bounded lossy compression on DNN intermediate data to reduce the memory footprint for extreme-scale DNN training. The project has a three-stage research plan. First, the team will comprehensively investigate the impacts of applying error-bounded lossy compression to DNN intermediate data on both validation accuracy and training performance, using different error-bounded lossy compressors, compression modes, and error bounds on the targeted DNNs and datasets. Second, the team will optimize the compression quality of suitable error-bounded lossy compressors on different intermediate data based on the impact analysis outcome, and design an efficient scheme to adaptively apply a best-fit compression solution. Finally, the team will optimize the compression performance on the proposed lossy compression framework for state-of-the-art GPUs. The team will evaluate the proposed framework on high-resolution climate analytics and high-energy particle physics applications and compare it with existing state-of-the-art techniques based on both the memory footprint reduction ratio and training performance improvements (e.g., throughput, time, epoch number). The project will enable scientists and researchers to train extreme-scale DNNs with a given set of computing resources in a fast and efficient manner, opening opportunities for new discoveries.
## Team

### Principal Investigator

<img width="200" alt="dingwen-photo" src="https://user-images.githubusercontent.com/5705572/127750258-6646a6a7-ecb2-4b25-9e6a-2657bc1efbc1.jpg">

**Prof. Dingwen Tao (Indiana University)**

[Dingwen Tao](https://luddy.indiana.edu/contact/profile/index.html?Dingwen_Tao) is an associate professor in the Luddy School of Informatics, Computing, and Engineering at Indiana University Bloomington. He has published in the top-tier HPC and big data conferences and journals, including SC, ICS, HPDC, PPoPP, PACT, IPDPS, CLUSTER, DAC, BigData, ICPP, MSST, TPDS, TC, JPDC, IJHPCA, etc. He is the recipient of Meta Research Award (2022), R&D100 Awards Winner (2021), IEEE Computer Society TCHPC Early Career Researchers Award for Excellence in High Performance Computing (2020),  NSF CISE Research Initiation Initiative (CRII) Award (2020), IEEE CLUSTER Best Paper Award (2018), and UCR Dissertation Year Program (DYP) Award (2017).

### Students

<img width="200" alt="sian-photo" src="https://user-images.githubusercontent.com/5705572/199806903-a5151c80-74d1-40db-874c-c423e3d7fa4d.jpeg">

**Sian Jin (Indiana University)**

<img width="200" alt="chengming-photo" src="https://user-images.githubusercontent.com/5705572/199807003-73023c75-85e4-463b-8601-9083618bcfe4.png">

**Chengming Zhang (Indiana University)**

### Collaborators

<img width="200" alt="yanzhi-photo" src="https://web.northeastern.edu/yanzhiwang/wp-content/uploads/2019/02/Dr_Yanzhi_Wang_photo-210x300.jpeg">

**Prof. Yanzhi Wang (Northeastern University)**: Collaboration on model pruning approaches

<img width="200" alt="bo-photo" src="https://www.ece.rutgers.edu/sites/default/files/styles/image-large/public/stories/Bo-Yuan-563x728.jpg">

**Prof. Bo Yuan (Rutgers University)**: Collaboration on tensor decomposition based approaches

<img width="200" alt="bin-photo" src="https://user-images.githubusercontent.com/5705572/199806629-f9e41659-c390-40ef-958f-682608fdb7ec.jpeg">

**Prof. Bin Ren (College of William and Mary)**: Collaboration on compiler optimizations for compressed DNN models

<img width="200" alt="leon-photo" src="https://shuaiwen-leon-song.github.io/images/Shuaiwen-Leon-Song.png">

**Prof. Shuaiwen Leon Song (University of Sydney)**: Collaboration on algorithm-system co-design

## Publications
- [**FPL '22**] Chengming Zhang, Tong Geng, Anqi Guo, Jiannan Tian, Martin Herbordt, Ang Li, Dingwen Tao*. “H-GCN: A Graph Convolutional Network Accelerator on Xilinx Versal AI Engines.” In *The 32nd International Conference on Field-Programmable Logic and Applications*, 2022. [https://doi.org/10.1109/FPL57034.2022.00040](https://doi.org/10.1109/FPL57034.2022.00040)
- [**VLDB '22**] Sian Jin, Chengming Zhang, Jiannan Tian, Yunhe Feng, Hui Guan, Guanpeng Li, Shuaiwen Leon Song, and Dingwen Tao. "COMET: A novel memory-efficient deep learning training framework by using error-bounded lossy compression." In *Proceedings of the VLDB Endowment*, 15(4), pp.886-899. 2021. [https://doi.org/10.14778/3503585.3503597](https://doi.org/10.14778/3503585.3503597)
- [**ICS '21**] Chengming Zhang, Geng Yuan, Wei Niu, Jiannan Tian, Sian Jin, Donglin Zhuang, Zhe Jiang, Yanzhi Wang, Bin Ren, Shuaiwen Leon Song, and DIngwen Tao. "Clicktrain: Efficient and accurate end-to-end deep learning training via fine-grained architecture-preserving pruning." In *Proceedings of the ACM International Conference on Supercomputing*, pp. 266-278. 2021. [https://doi.org/10.1145/3447818.3459988](https://doi.org/10.1145/3447818.3459988)
- [**HPDC '19**] Sian Jin, Sheng Di, Xin Liang, Jiannan Tian, Dingwen Tao, and Franck Cappello. "DeepSZ: A novel framework to compress deep neural networks by using error-bounded lossy compression." In *Proceedings of the 28th international symposium on high-performance parallel and distributed computing*, pp. 159-170. 2019. [https://doi.org/10.1145/3307681.3326608](https://doi.org/10.1145/3307681.3326608)

## Software
- COMET: A novel memory-efficient deep learning training framework by using error-bounded lossy compression ([https://github.com/jinsian/VLDB22-COMET](https://github.com/jinsian/VLDB22-COMET))
- ClickTrain: Enabling efficient and accurate end-to-end deep learning training via patter-based pruning ([https://github.com/hipdac-lab/ClickTrain](https://github.com/hipdac-lab/ClickTrain))

## Outreach Activities
- Invited talk on "Advancing HPC and ML Systems via Efficient Data Management" at University of California, Merced [[Link](https://eecs.ucmerced.edu/seminars)]
- Invited talk on "Advancing HPC and ML Systems via Efficient Data Management" at University of Rochester [[Link](https://events.rochester.edu/event/advancing_hpc_and_ml_systems_via_efficient_data_management)]

## Acknowledgement & Disclaimer

This material is based upon work supported by the National Science Foundation under Grants No. 1948447, 2034169, 2303820. Any opinions, findings, and conclusions or recommendations expressed in this material are those of the author(s) and do not necessarily reflect the views of the National Science Foundation.
