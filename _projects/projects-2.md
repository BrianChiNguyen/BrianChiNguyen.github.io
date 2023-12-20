---
title: "PROJECT 2: Omnidirectional Soft Robotic Arm for Vascular Intervention Surgery (VIS) - COMPLETED"

excerpt: "In this project, my objective was to design and prototype an novel omnidirectional soft robotic arm (SRA)--a diameter of 3.0 mm. This distinctive SRA incorporates three degrees-of-freedom (DOFs) and exhibits considerable potential for versatile applications in the realm of VIS, particularly in procedures such as cardiac ablation. Additionally, I devised a stabilizing mechanism and implemented a soft force sensor as integral supporting components for the SRA. The utilization of soft robotics in the design of this device serves to not only augment safety and flexibility but also to address challenges such as force loss and hysteresis friction that are inherent in traditional cable-driven catheters. The adoption of soft robotics technology thus contributes significantly to overcoming these limitations, enhancing the overall efficacy of the proposed soft robotic arm in the context of medical procedures."

collection: projects
---
<div style="text-align: center;">
  <img src='/images/J3.png' width='400' alt='J3'>
</div>
<br>
<div class="excerpt-content">
  <p>
<strong style="color: orange;">Software:</strong> Solidworks, MATLAB, and CURA;<br>
<strong style="color: orange;">Hardware:</strong>
QPIDe Data Acquisition Device (Quanser), Magnetic Tracking System (trakSTAR - TRACKLAB), Pressure Sensors 40PC250G2A (Honeywell), Linear Motors (Zaber X-LRQ-E Series), Load Cell – LSB200 (FUTEK), and Electrosurgical Unit (Led Surtron 120, Stark Medical);<br> 
<strong style="color: orange;">Skills:</strong> Mechanical design, Prototyping, Mathematical Modeling (Soft Actuators), and Image Processing. 
 </p>
</div>
---
<strong style="color: orange;">Design and Working Principle - [PDF](https://drive.google.com/file/d/1zYttcikO3ERVIetWi9fbCQRN9AwHLr6Z/view?usp=drive_link)</strong>

<div class="excerpt-content">
  <p>
For protyping this SRA, I used three <a href="https://ieeexplore.ieee.org/abstract/document/9300132" target="_blank"><strong>HFAMs</strong></a> being arranged 120 degrees apart and contrained by a layer comprised of ultrathin-wall heat shrink (<strong>Fig. A</strong>), thereby endowing  the system with three degrees of freedom (3-DOFs). This SRA's working principle is elegantly straightforward: any deviation in pressure among the HFAMs results in the bending of the SRA, while uniform pressures across all HFAMs induce elongation. The inherent flexibility of the SRA facilitates its navigation into intricate chambers and corners (<strong>Fig. B</strong>). Through the formulation of a mathematical model, the operational workspace of the SRA was elucidated, which is a set of concentric spheres with increasing radii and partially missing bottom areas (<strong>Fig. C-D</strong>). This workspace was then validated by the use of a magnetic tracking system.
  </p>
</div>

<div style="text-align: center;">
  <img src='/images/Project2_2.png' width='500' alt='Project2_2' style='border-radius: 25px;'>
</div>
-----
<strong style="color: orange;">Demonstration and Validation</strong>
<div class="excerpt-content">
  <p>
I conducted an experiment to validate the feasibility of the SRA performing the prevailing cardiac ablation in the heart's right atrium (RA). A phantom model representing the inferior vena cava (IVC) and RA was employed, incorporating a small porcine tissue specimen (<strong>Fig. A</strong>). The procedure involved the insertion of the SRA into the IVC, with the stabilizing mechanism activated upon the SRA's tip reaching the RA, thereby ensuring tip stability (<strong>Fig. B-C</strong>). Subsequently, the ablation procedure was carried out prior to the retraction of the SRA from the simulated cardiac environment (<strong>Fig. D</strong>).
  </p>
</div>

<div style="text-align: center;">
  <img src='/images/Project2_3.png' width='500' alt='Project2_3' style='border-radius: 25px;'>
</div>
-----
<strong style="color: orange;">Media</strong>

<div style="text-align: center;">
  <video width="500" controls>
    <source src='/videos/ProjectM2.mp4' type='video/mp4'>
  </video>
</div>