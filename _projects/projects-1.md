---
title: "PROJECT 1: Bidirectional Soft Robotic Arm for Blood Clot (Thrombus) Removal - COMPLETED"

excerpt: "In the course of this project, I endeavored to conceptualize and prototype an innovative soft robotic arm (a diameter of 0.9 mm). Distinguished by its remarkable capacity for bidirectional flexion and spiral motion, this novel technological advancement holds substantial promise for application in procedures involving the removal of blood clots (thrombus)."

collection: projects
---
<div style="text-align: center;">
  <img src='/images/Project1_1.png' width='400' alt='Project1_1'>
</div>
<br>
<div class="excerpt-content">
  <p>
<strong style="color: orange;">Software:</strong> Solidworks, MATLAB, and CURA;<br>
<strong style="color: orange;">Hardware:</strong>
QPIDe Data Acquisition Device (Quanser),  Pressure Sensors 40PC250G2A (Honeywell), Linear Motors (Zaber X-LRQ-E Series), laser (IL-1000, Keyence), UltiMaker S3, Mark-10 Force Gauge, 3D Force Sensor (ATI Nano 17), and Electrosurgical Unit (Led Surtron 120, Stark Medical);<br> 
<strong style="color: orange;">Skills:</strong> Mechanical design, Prototyping, Mathematical Modeling (Soft Actuators), and Image Processing (MATLAB). 
 </p>
</div>
---
<strong style="color: orange;">Design and Working Principle - [PDF](https://drive.google.com/file/d/1UwA_GYwfIiBaUOyBB7S5KUIUzIJ7Q3UB/view?usp=sharing)</strong>

<div class="excerpt-content">
  <p>
Here, I used a hydraulic filament artificial muscle called <a href="https://ieeexplore.ieee.org/abstract/document/9300132" target="_blank"><strong>HFAM</strong></a>—including a silicon tube and a helical coil—accompanied by a constraint layer comprised of ultrathin-wall heat shrink (<strong>Fig. b</strong>). The muscle exhibits elongation under pressurization exceeding Pm; however, owing to the cut-slot constraint layer, this elongation transforms into a bending motion. Conversely, upon depressurization, the HFAM contracts, inducing a bidirectional bending motion in the soft robotic arm (SRA) (<strong>Fig. d</strong>). Moreover, an incremental increase in pressure results in the SRA bending out of its original plane, facilitated by the helical coil, ultimately forming a spiral shape—an inherent capability of this SRA. Additionally, a specifically designed and prototyped handle (<strong>Fig. c</strong>) facilitates the control of this micro SRA, rendering it a portable, disposable, compact, and lightweight medical device (<strong>Fig. a</strong>).
  </p>
</div>

<div style="text-align: center;">
  <img src='/images/Project1_2.png' width='500' alt='Project1_2' style='border-radius: 25px;'>
</div>
-----
<strong style="color: orange;">Demonstration and Validation</strong>
<div class="excerpt-content">
  <p>
To elucidate the capabilities of the SRA, a simulated blood vessel and thrombus were employed in the experimentation (<strong>Fig. a</strong>). The catheter underwent insertion into the phantom blood vessel and subsequent navigation towards the thrombus, ultimately penetrating it. After the SRA pierced through the thrombus, it started forming the spiral shape, then being pulled to complete the thrombus removal procedure (<strong>Fig. b</strong>). This procedure necessitated a meticulous examination of the response exhibited by the end-effector of the SRA. Consequently, an experimental investigation (<strong>Fig. c</strong>) was undertaken to assess this critical aspect. The obtained results indicate that the response latency of the end-effector is remarkably low, measuring at a minimum of 0.0482 seconds (<strong>Fig. d</strong>).
  </p>
</div>

<div style="text-align: center;">
  <img src='/images/Project1_3.png' width='500' alt='Project1_3' style='border-radius: 25px;'>
</div>
-----
<strong style="color: orange;">Media</strong>

<div style="text-align: center;">
  <video width="500" controls>
    <source src='/videos/ProjectM1.mp4' type='video/mp4'>
  </video>
</div>