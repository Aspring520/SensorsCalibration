# SensorsCalibration toolbox v0.1

## Introduction

Sensor calibration is the foundation block of any autonomous system and its constituent sensors and must be performed correctly before sensor fusion may be implemented. Precise calibrations are vital for further processing steps, such as sensor fusion and implementation of algorithms for obstacle detection, localization and mapping, and control. Further, sensor fusion is one of the essential tasks in AD applications that fuses information obtained from multiple sensors to reduce the uncertainties compared to when sensors are used individually. To solve the problem of sensor calibration for autonomous vehicles, we provide a sensors calibration toolbox. The calibration toolbox can be used to calibrate sensors such as IMU, Lidar, Camera, and Radar.

### AD
The calibration tools included in the calibration toolbox are as follows:

| calibration sensor |calibration type| calibration method | mannual calibration | auto calibration | link |
| :--------------: |:--------------:| :------------: | :--------------: | :------------: | :------------: |
| camera intrinsice| intrinsic |  target-based  |             |  &#10004;  ||
| imu heading      | extrinsic |  target-less   |             |  &#10004;  ||
| lidar2imu        | extrinsic |  target-less   |   &#10004;  |  &#10004;  ||
| lidar2camera     | extrinsic |  target-less   |   &#10004;  |  &#10004;  ||
| lidar2lidar      | extrinsic |  target-less   |   &#10004;  |  &#10004;  ||
| radar2camera     | extrinsic |  target-less   |   &#10004;  |            ||
| radar2lidar      | extrinsic |  target-less   |   &#10004;  |            ||


### ADAS
At the same time, the calibration toolbox also provides some factory calibration tools. These tools can be used for end of line Calibration. 

| calibration board type  | calibration sensor | calibration board pattern | remove opencv | auto calibration | link |
| :--------------: |:--------------:| :------------: | :--------------: | :------------: | :------------: |
| chessboard   | camera |    |       &#10004;      |  &#10004;       ||
| circle board      | camera |     |       &#10004;     |  &#10004;  ||
| vertical board        | camera |     |   &#10004;  |  &#10004;     || 
| aruco marker board     | camera |    |   &#10004;  |  &#10004;     ||
| apriltag board      | camera |     |   &#10004;  |  &#10004;       ||
| round hole board      | camera and lidar |  |   &#10004;  |      &#10004;      ||

## Related paper
Related paper available on arxiv:  
[OpenCalib: A calibration toolbox for different application scenarios](http://arxiv.org)

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


<!-- LICENSE -->
## License

`SensorsCalibration` is released under the [Apache 2.0 license](LICENSE).


## Contact
If you have questions about this repo, please contact Yan Guohang (`yanguohang@pjlab.org.cn`).