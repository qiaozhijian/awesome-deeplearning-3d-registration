﻿# awesome-deeplearning-3d-registration

A curated list of papers about point cloud registration inspired by [awesome-point-cloud-registration](https://github.com/weiweisun2018/awesome-point-clouds-registration)

You will be very welcome to make Pull Request to current repository or [this](https://github.com/weiweisun2018/awesome-point-clouds-registration) (Recommanded) if you find the awesome paper/code/dataset.

## Global Registration
| Models   |Date| Publication| Paper | Code |
|----------|----|------------|------|---|
| 3DMatch | 2017 | CVPR | [3DMatch: Learning Local Geometric Descriptors from RGB-D Reconstructions](https://arxiv.org/abs/1603.08182) | [C/C++/MATLAB](https://github.com/andyzeng/3dmatch-toolbox) |
| 3DFeat-Net | 2018 | ECCV | [3DFeat-Net: Weakly Supervised Local 3D Features for Point Cloud Registration](https://arxiv.org/pdf/1807.09413.pdf) | [Python/C/MATLAB](https://github.com/yewzijian/3DFeatNet) |
| DCP | 2019 | ICCV | [Deep closest point: Learning representations for point cloud registration](https://arxiv.org/abs/1905.03304) | [Python](https://github.com/WangYueFt/dcp) |
| Choy et al.| 2019 | ICCV | [Fully Convolutional Geometric Features](https://node1.chrischoy.org/data/publications/fcgf/fcgf.pdf) | [Python](https://github.com/chrischoy/FCGF) |
| PointNetLK | 2019 | CVPR | [PointNetLK: Robust & Efficient Point Cloud Registration using PointNet](https://arxiv.org/pdf/1903.05711.pdf) | [Python](https://github.com/hmgoforth/PointNetLK) |
| Deng et al.  | 2019 | CVPR | [3D Local Features for Direct Pairwise Registration](https://openaccess.thecvf.com/content_CVPR_2019/html/Deng_3D_Local_Features_for_Direct_Pairwise_Registration_CVPR_2019_paper.html) | None |
| Lan et al.  | 2019 | CVPR | [Robust Point Cloud Based Reconstruction of Large-Scale Outdoor Scenes](https://arxiv.org/abs/1905.09634) | [Python/C++](https://github.com/ziquan111/RobustPCLReconstruction) |
| Federico  et al. | 2020 | IROS | [Segmentation-Based 4D Registration of Plants Point Clouds for Phenotyping](https://www.ipb.uni-bonn.de/wp-content/papercite-data/pdf/magistri2020iros.pdf) | None |
| VCR-Net | 2020 | IROS | [End-to-End  3D  Point  Cloud  Learning  for  Registration  Task  UsingVirtual  Correspondences](https://arxiv.org/pdf/2011.14579.pdf) | [Pytorch](https://github.com/qiaozhijian/VCR-Net) |
| D3Feat | 2020 | CVPR | [D3feat: Joint learning of dense detection and description of 3d local features](https://arxiv.org/abs/2003.03164) | [Python/C++](https://github.com/XuyangBai/D3Feat/) |
| GraphTER | 2020 | CVPR | [GraphTER: Unsupervised Learning of Graph Transformation Equivariant Representations via Auto-Encoding Node-wise Transformations](https://arxiv.org/pdf/1911.08142.pdf) | [Python](https://github.com/gyshgx868/graph-ter) |
| Gojcic et al.  | 2020 | CVPR | [Learning multiview 3D point cloud registration](https://arxiv.org/abs/2001.05119) | [Python](https://github.com/zgojcic/3D_multiview_reg) |
| RPM-Net | 2020 | CVPR | [RPM-Net: Robust Point Matching using Learned Features](https://arxiv.org/abs/2003.13479) | [Python](https://github.com/yewzijian/RPMNet) |
| 3DRegNet | 2020 | CVPR | [3DRegNet: A Deep Neural Network for 3D Point Registration](https://arxiv.org/pdf/1904.01701.pdf) | [Python](https://github.com/3DVisionISR/3DRegNet) |
| D3Feat | 2020 | CVPR | [D3Feat: Joint Learning of Dense Detection and Description of 3D Local Features](https://arxiv.org/abs/2003.03164) | [Python/C++](https://github.com/XuyangBai/D3Feat/) |
| Deep Global Registration | 2020 | CVPR | [Deep Global Registration](http://vladlen.info/publications/deep-global-registration/) | [Python](https://github.com/chrischoy/DeepGlobalRegistration) |
| PRNet | 2020 | NIPS | [PRNet: Self-Supervised Learning for Partial-to-Partial Registration](https://arxiv.org/abs/1910.12240) | [Python](https://github.com/WangYueFt/prnet) |
| IDAM | 2020 | ECCV | [Iterative Distance-Aware Similarity Matrix Convolution with Mutual-Supervised Point Elimination for Efficient Point Cloud Registration](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123690375.pdf) | [Python](https://github.com/jiahaowork/idam) |
| GraphTER | 2020 | arXiv | [GraphTER: Unsupervised Learning of Graph Transformation Equivariant Representations via Auto-Encoding Node-wise Transformations](https://arxiv.org/abs/1911.08142) | [Python](https://github.com/gyshgx868/graph-ter) |
| CMU | 2020 | 3DV | [Correspondence Matrices are Underrated](https://arxiv.org/pdf/2010.16085.pdf) | [Pytorch](https://github.com/tzodge/PCR-CMU) |
| SpinNet | 2021 | CVPR | [SpinNet: Learning a General Surface Descriptor for 3D Point Cloud Registration](https://arxiv.org/pdf/2011.12149v2.pdf) | [Pytorch](https://github.com/QingyongHu/SpinNet) |
| PointDSC | 2021 | CVPR | [PointDSC: Robust Point Cloud Registration using Deep Spatial Consistency](https://arxiv.org/pdf/2103.05465v1.pdf) | [python](https://github.com/XuyangBai/PointDSC) |
| PHASER | 2021 | CVPR | [PHASER: a Robust and Correspondence-free Global Pointcloud Registration](https://arxiv.org/pdf/2102.02767v1.pdf) | [python](https://github.com/ethz-asl/phaser) |
| RGM | 2021 | CVPR | [Robust Point Cloud Registration Framework Based on Deep Graph Matching](https://arxiv.org/pdf/2103.04256v1.pdf) | [python](https://github.com/fukexue/RGM) |
| PREDATOR | 2021 | CVPR | [PREDATOR: Registration of 3D Point Clouds with Low Overlap](https://arxiv.org/abs/2011.13005v3) | [python](https://github.com/prs-eth/OverlapPredator) |
| PointNetLK Revisited | 2021 | CVPR | [PointNetLK Revisited](https://arxiv.org/pdf/2008.09527v2.pdf) | [python](https://github.com/Lilac-Lee/PointNetLK_Revisited) |
| robot | 2021 | NIPS | [Accurate Point Cloud Registration with Robust Optimal Transport ](https://arxiv.org/pdf/2111.00648v1.pdf) | [python](https://github.com/uncbiag/shapmagn) |
| GeDi | 2022 | PAMI | [Generalisable and distinctive 3D local deep descriptors for point cloud registration](https://arxiv.org/pdf/2105.10382.pdf) | [python](https://github.com/fabiopoiesi/gedi) |
| SC2-PCR | 2022 | CVPR | [SC2-PCR: A Second Order Spatial Compatibility for Efficient and Robust Point Cloud Registration](https://arxiv.org/pdf/2203.14453v1.pdf) | [python](https://github.com/zhichen902/sc2-pcr) |


## Odometry in Autonomous Vehicle
| Models   |Date| Publication| Paper | Code |
|----------|----|------------|------|---|
| Gil Elba et al. | 2017 | CVPR | [3D Point Cloud Registration for Localization Using a Deep Neural Network Auto-Encoder](https://ieeexplore.ieee.org/document/8099748) | [python](https://github.com/gilbaz/LORAX) |
| Velas et al. | 2018 | ICARSC | [CNN for IMU Assisted Odometry Estimation using Velodyne LiDAR](https://arxiv.org/abs/1712.06352) | None |
| LocNet | 2018 | IV | [Locnet: Global localization in 3d point clouds for mobile vehicles](https://arxiv.org/abs/1712.02165) | [caffe](https://github.com/ZJUYH/LocNet_caffe) |
| Barsan et al. | 2018 | CoRL | [Learning to localize using a lidar intensity map](http://proceedings.mlr.press/v87/barsan18a/barsan18a.pdf) | None |
| Valente et al. | 2019 | IROS | [Deep sensor fusion for real-time odometry estimation](https://ieeexplore.ieee.org/document/8967803) | None |
| DeepPCO | 2019 | IROS | [DeepPCO: End-to-End Point Cloud Odometry through Deep Parallel Neural Network](https://arxiv.org/abs/1910.11088) | None |
| LO-Net | 2019 | CVPR | [LO-Net: Deep Real-time Lidar Odometry](https://arxiv.org/abs/1904.08242) | None |
| L3-Net| 2019 | CVPR | [L3-Net: Towards Learning Based LiDAR Localization for Autonomous Driving](https://ieeexplore.ieee.org/document/8954371/references) | None |
|DeepLO | 2019 | arXiv | [DeepLO: Geometry-Aware Deep LiDAR Odometry](https://arxiv.org/pdf/1902.10562.pdf) | None |
| DeepICP | 2019 | ICCV | [DeepICP: An End-to-End Deep Neural Network for 3D Point Cloud Registration](https://arxiv.org/pdf/1905.04153.pdf) | None |
| CAE-LO | 2020 | arXiv | [CAE-LO: LiDAR Odometry Leveraging Fully Unsupervised Convolutional Auto-Encoder for Interest Point Detection and Feature Description](https://arxiv.org/abs/2001.01354) | [Python/MATLAB](https://github.com/SRainGit/CAE-LO) |
| SelfVoxeLO | 2020 | arXiv | [SelfVoxeLO: Self-supervised LiDAR Odometry with Voxel-based Deep Neural Networks](https://arxiv.org/abs/2010.09343) | None |
| PointLoc | 2020 | arXiv | [PointLoc: Deep Pose Regressor for LiDAR Point Cloud Localization](https://arxiv.org/abs/2003.02392?context=cs.RO) | None |
| Li et al. | 2020 | arXiv | [DMLO: Deep Matching LiDAR Odometry](https://arxiv.org/pdf/2004.03796.pdf) | None |
|DeLORA| 2021 | ICRA | [Self-supervised Learning of LiDAR Odometry for Robotic Applications](https://arxiv.org/pdf/2011.05418.pdf) | [code](https://github.com/leggedrobotics/DeLORA) |
|PWCLO-Net| 2022 | CVPR | [PWCLO-Net: Deep LiDAR Odometry in 3D Point Clouds Using Hierarchical Embedding Mask Optimization](https://openaccess.thecvf.com/content/CVPR2021/papers/Wang_PWCLO-Net_Deep_LiDAR_Odometry_in_3D_Point_Clouds_Using_Hierarchical_CVPR_2021_paper.pdf) | [code](https://github.com/IRMVLab/PWCLONet) |
|RSLO| 2022 | R-AL | [Robust Self-supervised LiDAR Odometry via Representative Structure Discovery and 3D Inherent Error Modeling](https://arxiv.org/pdf/2202.13353.pdf) | [code](https://github.com/DecaYale/RSLO) |


