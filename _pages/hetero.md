---
layout: archive
title: "2D Heterogeneous Coverage"
permalink: /research/hetero
author_profile: true
---

<p align="center"><img src="../images/hetero_setup.png" alt="Logo" style="width:50%"></p>

<p align="justify"> 
During my work in the Biorobotics Lab, I proposed a generic toolbox to automate the calibration process. I have noticed that the manual collection of calibration photo samples is a tedious procedure,  while most calibration toolboxes available only solve parameters for users after photo sample collection is finished. Therefore, I designed a calibration toolbox to automatically take photo samples using robot arms and remove the burden of sample collection from humans. When implementing, I have employed the idea of polymorphism to generalize different types of calibration motion into similar structures such that the toolbox will not only support but also optimize its motion for various types of calibration. When used, the toolbox will take in multiple parameters, e.g., the number of photo samples, and generate a motion plan for the robot arm to execute and collect samples. The toolbox has been released in <a href="https://github.com/Flowerst-0416/UR_arm_camera_calibration">here</a> and I hope this work will help other researchers with their calibration process as well.
</p>

<p align="center">
<img src="../images/hetero_decomposition.png" alt="Logo" style="width:30%">
<img src="../images/hetero.gif" alt="Logo" style="width:30%">
<img src="../images/hetero_legends.png" alt="Logo" style="width:55%">
</p>






