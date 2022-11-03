<img width="150" img align="right" alt="NSF-logo" src="https://user-images.githubusercontent.com/5705572/95711667-1d953c00-0c18-11eb-817b-1cc6a90d504d.png">

**Project Title**: CSSI: Elements: ROCCI: Integrated Cyberinfrastructure for In Situ Lossy Compression Optimization Based on Post Hoc Analysis Requirements

**PIs**: [Sheng Di](https://www.mcs.anl.gov/~shdi/), [Franck Cappello](https://www.anl.gov/profile/franck-cappello) (UChicago), [Dingwen Tao](https://www.dingwentao.com/) (WSU)

**Awards**: [2104023](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2104023) (UChicago, $320K), [2104024](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2104024) (WSU, $280K)

**Project Duration**: 9/15/2021 - 8/31/2024

## Overview
![Overview](https://user-images.githubusercontent.com/5705572/127583380-211a8c53-e35e-4eec-b934-81be021890ce.jpg)

## Abstract

Today’s simulations and advanced instruments are producing vast volumes of data, presenting a major storage and I/O burden for scientists. Error-bounded lossy compressors, which can significantly reduce the data volume while controlling data distortion with a constant error bound, have been developed for years. However, a significant gap still remains in practice. On the one hand, the impact of the compression errors on scientific research is yet not well understood, so that how to set an appropriate error bound for lossy compression is very challenging to scientists. On the other hand, how to select the bestfit compression technology and run it automatically in scientific application codes is non-trivial because of pros and cons of different compression techniques and diverse characteristics of applications and datasets. This project aims to develop a Requirement-Oriented Compression Cyber-Infrastructure (ROCCI) for data-intensive domains such as astrophysics and materials science, which can select and run the bestfit lossy compressor automatically at runtime, in terms of user's requirement on their post hoc analysis.

The overarching goal of this project is to offer a complete series of automatic functions/services allowing users transparently running the bestfit compressor at runtime during the scientific simulations or data acquisition. This project advances knowledge and understanding with three key thrusts. (1) It builds an efficient layer to interoperate with different lossy compressors and diverse post hoc analysis requirements on data fidelity by leveraging existing compression adaptor library - LibPressio and compression assessment library - Z-checker. (2) It develops an efficient engine to determine the bestfit compressor with optimized settings based on user’s post-hoc analysis requirements. (3) It develops a user-friendly infrastructure that integrates compression optimization and execution via the HDF5 dynamic filter mechanism. This project particularly targets cosmology and materials science applications and their specific requirements of using lossy compressors in practice.

## Team

### Principal Investigators

<img width="200" alt="sheng-photo" src="https://user-images.githubusercontent.com/5705572/95699426-3cd0a100-0bf9-11eb-9e61-fcaed9698b20.jpg">

**Sheng Di (University of Chicago and Argonne National Lab)**: UChicago PI

[Sheng Di](https://www.anl.gov/profile/sheng-di) is a computer scientist at Argonne National Laboratory, USA. He is an IEEE senior member. He is a scientist at Large through the Consortium for Advanced Science and Engineering (CASE) at the University of Chicago. He is an institute fellow of Northwestern-Argonne Institute of Science and Engineering (NAISE). He has published 100+ refereed journal and conference papers, including TPDS, TC, TCC, TKDE, JPDC, IJHPCA, PPoPP, SC, IPDPS, HPDC, PACT, MSST, DSN, ICPP, CLUSTER, BigData, IWQoS, CCGrid, HiPC, Grid, CLOUD, UCC, EuroPar, ICPADS, Europar, etc. He is the receipient of DOE 2021 Early Career Research Program Award Winner, 2018 IEEE-Chicago Distinguished Mentoring Award, and 2019 IEEE-Chicago Distinguished R&D Award.

**Franck Cappello (University of Chicago and Argonne National Lab)**: UChicago Co-PI

<img width="200" alt="franck-photo" src="https://user-images.githubusercontent.com/5705572/127581061-a6be2a17-21e0-4798-a954-2982ee5229b2.jpeg">

[Franck Cappello](https://www.anl.gov/profile/franck-cappello) is the director of the Joint-Laboratory on Extreme Scale Computing gathering six of the leading HPC institutions in the world: ANL, NCSA, Inria, BSC, JSC, and Riken. He is a senior computer scientist at Argonne National Laboratory and an adjunct associate professor in the Department of Computer Science at the University of Illinois at Urbana-Champaign. He is an expert in resilience and fault tolerance for scientific computing and data analytics. Recently he started investigating lossy compression for scientific data sets to respond to the pressing needs of scientist performing large-scale simulations and experiments. His contribution to this domain is one of the best lossy compressors for scientific data set respecting user-set error bounds. He is a member of the editorial board of the IEEE TPDS and of the ACM HPDC and IEEE CCGRID steering committees. He is a fellow of the IEEE.

<img width="200" alt="dingwen-photo" src="https://user-images.githubusercontent.com/5705572/127750258-6646a6a7-ecb2-4b25-9e6a-2657bc1efbc1.jpg">

**Dingwen Tao (Washington State University)**: WSU PI

[Dingwen Tao](https://luddy.indiana.edu/contact/profile/index.html?Dingwen_Tao) is an associate professor in the Luddy School of Informatics, Computing, and Engineering at Indiana University Bloomington. He has published in the top-tier HPC and big data conferences and journals, including SC, ICS, HPDC, PPoPP, PACT, IPDPS, CLUSTER, DAC, BigData, ICPP, MSST, TPDS, TC, JPDC, IJHPCA, etc. He is the recipient of the R&D100 Awards Winner (2021), IEEE Computer Society TCHPC Early Career Researchers Award for Excellence in High Performance Computing (2020),  NSF CISE Research Initiation Initiative (CRII) Award (2020), IEEE CLUSTER Best Paper Award (2018), and UCR Dissertation Year Program (DYP) Award (2017).


### Collaborators

<img width="200" alt="robert-photo" src="https://user-images.githubusercontent.com/5705572/178408357-b993df84-0109-4ab6-ab8d-b4200737f192.jpeg">

**Robert Underwood (Argonne National Lab)**: Development of Compressor Adapter

<img width="200" alt="robert-photo" src="https://user-images.githubusercontent.com/5705572/178408803-aab65eec-e0bd-42b1-80f1-c9923d6044ae.jpeg">

**Xiaodong Yu (Argonne National Lab)**: Development of Compressor Assessment Engine

<img width="200" alt="junjing-photo" src="https://user-images.githubusercontent.com/5705572/127582392-7a199ab1-166e-4ec8-8246-6901e519d30b.jpeg">

**Junjing Deng (Argonne National Lab)**: Evaluation on Synchrotron Coherent X-ray Experiments

<img width="200" alt="zarija-photo" src="https://user-images.githubusercontent.com/5705572/127582343-9bfb70c1-d2b0-4a13-83e1-50a9fac0ca2f.png">

**Zarija Lukic (Lawrence Berkeley National Lab)**: Evaluation on Cosmological Simulations

<img width="200" alt="suren-photo" src="https://user-images.githubusercontent.com/5705572/127582532-2f4463ac-3e78-41a7-8d24-dd373c4cd27c.jpeg">

**Suren Byna (Lawrence Berkeley National Lab)**: Integration with HDF5

### Students

<img width="200" alt="suren-photo" src="https://user-images.githubusercontent.com/5705572/156077654-cb723709-8486-4eb5-b8c8-a9fe8bb34eed.jpg">

**Arham Khan (University of Chicago)**

<img width="200" alt="suren-photo" src="https://user-images.githubusercontent.com/5705572/156077826-562dee5b-87e5-4319-802b-29e89eeff758.jpg">

**Pei-Yau Weng (Washington State University)**

## Publications
- [**TPDS '22**] Robert Underwood, Jon C Calhoun, Sheng Di, Amy Apon, and Franck Cappello. "OptZConfig: Efficient Parallel Optimization of Lossy Compression Configuration." *IEEE Transactions on Parallel and Distributed Systems*. [https://doi.org/10.1109/TPDS.2022.3154096](https://doi.org/10.1109/TPDS.2022.3154096)
- [**DRBSD-7**] Robert Underwood, Victoriana Malvoso, Jon C. Calhoun, Sheng Di, and Franck Cappello. "Productive and Performant Generic Lossy Data Compression with LibPressio." In *2021 7th International Workshop on Data Analysis and Reduction for Big Scientific Data (DRBSD-7)*, pp. 1-10. IEEE, 2021. [https://doi.org/10.1109/DRBSD754563.2021.00005](https://doi.org/10.1109/DRBSD754563.2021.00005)
- [**CLUSTER '21**] Xiaodong Yu, Sheng Di, Ali Murat Gok, Dingwen Tao, and Franck Cappello. "cuZ-Checker: A GPU-Based Ultra-Fast Assessment System for Lossy Compressions." In *2021 IEEE International Conference on Cluster Computing (CLUSTER)*, pp. 307-319. IEEE, 2021. [https://doi.org/10.1109/Cluster48925.2021.00065](https://doi.org/10.1109/Cluster48925.2021.00065)
- [**HiPC '21**] Yuanjian Liu, Sheng Di, Kai Zhao, Sian Jin, Chen Wang, Kyle Chard, Dingwen Tao, Ian Foster, and Franck Cappello. Optimizing Multi-Range based Error-Bounded Lossy Compression for Scientific Datasets. In *2021 IEEE 28th International Conference on High Performance Computing, Data, and Analytics (HiPC)*, pp. 394-399. IEEE, 2021. [https://doi.org/10.1109/HiPC53243.2021.00036](https://doi.org/10.1109/HiPC53243.2021.00036)
- [**BigData '21**] Jinyang Liu, Sihuan Li, Sheng Di, Xin Liang, Kai Zhao, Dingwen Tao, Zizhong Chen, and Franck Cappello. "Improving Lossy Compression for SZ by Exploring the Best-Fit Lossless Compression Techniques." In *2021 IEEE International Conference on Big Data (Big Data)*, pp. 2986-2991. IEEE, 2021. [https://doi.org/10.1109/BigData52589.2021.9671954](https://doi.org/10.1109/BigData52589.2021.9671954])

## Software
- cuZ-Checker: A GPU-based ultrafast assessment system for lossy compressions ([https://github.com/CODARcode/cuZ-checker](https://github.com/CODARcode/cuZ-checker))
- LibPressio: A Library to abstract between different lossless and lossy compressors ([https://github.com/robertu94/libpressio](https://github.com/robertu94/libpressio))

## Outreach
- [The 8th International Workshop on Data Analysis and Reduction for Big Scientific Data](https://drbsd.github.io/) held with 2022 ACM/IEEE SC conference.
![DRBSD-8](https://user-images.githubusercontent.com/5705572/178805244-ca212f02-ec0f-4ba6-a74e-42455a20ff2e.png)

- [2022 NSF CSSI PI Meeting](https://cssi-pi-community.github.io/2022-meeting/) for "Towards a Sustainable Data and Software Cyberinfrastructure" at Alexandria, VA. 
![CSSI-ROCCI-Poster-2022](https://user-images.githubusercontent.com/5705572/178409498-e34c78e0-355f-416c-941b-7f3fa8a7e1f8.jpg)

- [The 2nd International Workshop on Big Data Reduction](https://iwbdr.github.io/iwbdr21/) held with 2021 IEEE Big Data conference.
![IWBDR-21](https://user-images.githubusercontent.com/5705572/178805606-164c6d0e-5f5e-4b2b-a3e7-97db833c6d94.png)

## Acknowledgement & Disclaimer

This material is based upon work supported by the National Science Foundation under Grants No. 2104023 and 2104024. Any opinions, findings, and conclusions or recommendations expressed in this material are those of the author(s) and do not necessarily reflect the views of the National Science Foundation.
