# Eye-in-Hand-Calibration
Eye-in-Hand Calibration of a manipulator robot arm using SLAM techniques

In this project, a self-calibration approach for eye-in hand robots using SLAM is considered. The goal is to calibrate the positioning of a robotic arm, with a camera mounted on the end-effector automatically using a SLAM-based method like Extended Kalman Filter (EKF). Given the camera intrinsic parameters and a set of feature markers in a work-space, the camera extrinsic parameters are approximated. An EKF based measurement model is deployed to effectively localize the camera and compute the camera to end-effector transformation. The proposed approach is tested on a UR5 manipulator with a depth camera mounted on the end-effector to validate our results.


![1](https://user-images.githubusercontent.com/92863991/212873345-50953a35-31e9-402b-b445-c5572354d226.png)
![2](https://user-images.githubusercontent.com/92863991/212873351-cff48a79-fe05-4292-8f51-cfc534fd5f12.png)

![sl4](https://user-images.githubusercontent.com/92863991/212874855-9168c7ce-9129-406a-9559-22ce920206c9.png)
![sl3](https://user-images.githubusercontent.com/92863991/212874859-e1859b4e-e101-4e75-9f89-293a1b467cc8.png)
![sl2](https://user-images.githubusercontent.com/92863991/212874860-40e620c9-a2be-4a63-8f8f-67721a93597e.png)
![slam1](https://user-images.githubusercontent.com/92863991/212874861-dc694906-dc41-43db-a32b-fb8778edbee9.png)
