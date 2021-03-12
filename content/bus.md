+++
title="Autonomous Bus Project"
slug="bus"
+++

{{< figure src="/img/projects/nus_city_sim.png" title="" width="500px" caption="Simulation of bus in Gazebo." class="img_center">}}


I was the lead of the perception team for the Autonomous Bus project. This project was funded by the Land Transport Agency of Singapore (LTA) in collaboration with ST Engineering and A\*STAR. Our team developed and implemented the software stack which detects, classifies, tracks, and predicts trajectories of dynamic obstacles for a self-driving bus. My main contributions are as follows:
+ I developed the Robotic Operating System (ROS) sensor drivers for the embedded system on-board the bus.
+ Using the Gazebo simulator, I developed the simulation of the autonomous bus.
+ I wrote a custom plugin for the cost map for object detection.
+ To track multiple detected objects across time, I implemented and tuned a Kalman filter-based tracker.
+ I developed several methods for online future trajectory prediction of dynamic obstacles.
+ I also headed the development of the Singapore Autonomous Bus (SGAB) dataset which can be downloaded [here](https://arc.nus.edu.sg/project/2020/10/abcd/).

Additionally, my Master's thesis is also done under this project. The thesis was entitled “Trajectory Prediction of Dynamic Obstacles for Autonomous Vehicles” and can be downloaded [here](https://scholarbank.nus.edu.sg/handle/10635/173720). The following is the contributions of my thesis:
+ Three methods for online trajectory prediction for deployment on an autonomous vehicle were studied and implemented.
+ The deep learning method with the Autoencoder model using Gated Recurrent Units (GRUs) performed the best.


Active years: 2017-2021