# Stevens-VLP16-Dataset

This dataset is captured using a Velodyne VLP-16, which is mounted on an UGV - Clearpath Jackal, on Stevens Institute of Technology campus. The VLP-16 rotation rate is set to 10Hz. This data-set features over 20K scans and many loop-closures. The TF transform in the bags is provided by [LeGO-LOAM](https://github.com/RobustFieldAutonomyLab/LeGO-LOAM) (without enabling the loop-cloure function, pure lidar odometry). 

## UGV Platform

![](/pics/jackal.png)

## Topics in bag

![](/pics/tf.png)

[## Location](https://www.google.com/maps/place/Stevens+Institute+of+Technology/@40.7448183,-74.0278369,17z/data=!3m1!4b1!4m5!3m4!1s0x89c259de94dced4f:0xd4c9d146086e72ae!8m2!3d40.7448183!4d-74.0256482)

[![](/pics/google-earth.png)](https://www.google.com/maps/place/Stevens+Institute+of+Technology/@40.7448183,-74.0278369,17z/data=!3m1!4b1!4m5!3m4!1s0x89c259de94dced4f:0xd4c9d146086e72ae!8m2!3d40.7448183!4d-74.0256482)

## Point cloud map

![](/pics/point-cloud.png)

[## Download](https://drive.google.com/drive/folders/1dIsonWdZNBGiUiGh2H6dWJKoJ1k8_A2j?usp=sharing)

[![](/pics/google-drive.png)](https://drive.google.com/drive/folders/1dIsonWdZNBGiUiGh2H6dWJKoJ1k8_A2j?usp=sharing)

## Trajectory demo

![](/pics/demo.gif)

## Cite *LeGO-LOAM*

Thank you for citing our *LeGO-LOAM* paper if you use any of this data: 
```
@inproceedings{legoloam2018,
  title={LeGO-LOAM: Lightweight and Ground-Optimized Lidar Odometry and Mapping on Variable Terrain},
  author={Tixiao Shan and Brendan Englot},
  booktitle={IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)},
  pages={4758-4765},
  year={2018},
  organization={IEEE}
}
```
