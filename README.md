# Mime-Bot-using-Human-Pose-Estimation
* Details of the project are given in the [Report](https://github.com/pi-sharan/Mime-Bot-using-Human-Pose-Estimation/blob/main/Report%20Human%20Pose%20Est.pdf)

# Work and Simulation :
* We implemented the paper [CVPR '16](https://arxiv.org/pdf/1602.00134.pdf) with minor changes in architecture to increase the FPS we were getting.
* Final Result - 
![](https://github.com/pi-sharan/Mime-Bot-using-Human-Pose-Estimation/blob/main/humanoid_control.gif)

## Requirements:
* Python 3.6 or higher
* PyBullet
* posenet
* tensorflow
* numpy
* OpenCV

Notice How the Bot is simulated in 2D environment only. With estimation of pose in 3D [See This](https://github.com/pi-sharan/Mime-Bot-using-Human-Pose-Estimation/tree/main/3d%20Pose%20Est%20(Low%20FPS)) the highest achieved fps was 5, so we had to implement 2D Est due to hardware limitations.

Download the repository and run the [Final.py](https://github.com/pi-sharan/Mime-Bot-using-Human-Pose-Estimation/blob/main/Final.py) file to see the final implementation of the project.
