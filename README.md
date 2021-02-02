# Stevens-VLP16-Dataset

This dataset is captured using a Velodyne VLP-16, which is mounted on an UGV - Clearpath Jackal, on Stevens Institute of Technology campus. The VLP-16 rotation rate is set to 10Hz. This data-set features over 20K scans and many loop-closures. The TF transform in the bags is provided by [LeGO-LOAM](https://github.com/RobustFieldAutonomyLab/LeGO-LOAM) (without enabling the loop-cloure function, pure lidar odometry). The whole mapping process is also recorded in videos.

## UGV Platform

![](/pics/jackal.png)

## TF in the bags

![](/pics/tf.png)

## Topics in the bags

```
/tf # not needed for running LeGO-LOAM, do not publish it when test with LeGO-LOAM
/imu/data # not aligned with VLP-16, only offers initial transformation guess, not necessary for running LeGO-LOAM
/velodyne_points
```

## Location

https://www.google.com/maps/place/Stevens+Institute+of+Technology/@40.7448183,-74.0278369,17z/data=!3m1!4b1!4m5!3m4!1s0x89c259de94dced4f:0xd4c9d146086e72ae!8m2!3d40.7448183!4d-74.0256482

[![](/pics/google-earth.png)](https://www.google.com/maps/place/Stevens+Institute+of+Technology/@40.7448183,-74.0278369,17z/data=!3m1!4b1!4m5!3m4!1s0x89c259de94dced4f:0xd4c9d146086e72ae!8m2!3d40.7448183!4d-74.0256482)

## Point cloud map

![](/pics/point-cloud.png)

## Download

https://drive.google.com/drive/folders/16p5UPUCZ1uK0U4XE-hJKjazTsRghEMJa?usp=sharing

## Cite

Thank you for citing our paper if you use any of this data: 

```
@inproceedings{traversability2018,
  title={Bayesian Generalized Kernel Inference for Terrain Traversability Mapping},
  author={Shan, Tixiao and Wang, Jinkun and Englot, Brendan and Doherty, Kevin},
  booktitle={In Proceedings of the 2nd Annual Conference on Robot Learning},
  year={2018}
}
```

```
@inproceedings{legoloam2018,
  title={LeGO-LOAM: Lightweight and Ground-Optimized Lidar Odometry and Mapping on Variable Terrain},
  author={Shan, Tixiao and Englot, Brendan},
  booktitle={IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)},
  pages={4758-4765},
  year={2018},
  organization={IEEE}
}
```
