---
layout: default
---

## About Me

I am an M.S. student specializing in robotics in the Department of Intelligence and Information at *Seoul National University*. I received my B.S. in Mechanical Engineering from *Seoul National University*.

My early research focused on **wearable robotics** and **glove design**. At the *SNU Biorobotics Laboratory*, I participated in research on a **wrist-anchoring mechanism** for wearable glove. At the *SNU Healthcare Robotics Laboratory*, I developed a **variable-stiffness haptic glove** designed to render different levels of compliance in virtual reality.

I later played a key role in the development of **METHEUS** at *IDeAOcean*, a startup spun out of the *IDeA Laboratory* at *Seoul National University*. METHEUS is an **autonomous linkage mechanism design software platform** recognized with a CES 2024 Innovation Award. My work focused on the algorithmic generation, analysis, and optimization of mechanical systems.

Building on my experience in robotic hands and linkage mechanism optimization, my master's research at the *SNU Dynamic Robotic Systems Laboratory* focuses on the **computational design of linkage-driven robotic fingers and hands**. I have led a first-author research project on a **structurally minimal 3-DoF closed-chain robotic finger** and have also contributed to **tendon-driven robotic hands** and **wearable glove systems**.

### Research Interests

- Computational design and synthesis of robotic mechanisms
- Robotic fingers and hands
- Linkage mechanism analysis and optimization
- Wearable robotics and haptic interfaces
- Hardware realization of computationally generated mechanisms

<hr class="section-divider">

## Robotic Hands

### Computational Design of Robotic Fingers and Hands

**SNU Dynamic Robotic Systems Laboratory**  
**Advisor: Prof. Jaeheung Park**  
**First-Author Research**  
*Under Review at IEEE Robotics and Automation Letters (RA-L)*

This research addresses the structural complexity of conventional 3-DoF linkage-driven robotic fingers through a topology-to-dimension computational design framework.

<img src="/portfolio/images/MinimalFinger1.png"
     alt="Computationally designed 3-DoF closed-chain robotic finger">

Instead of designing a finger as several decoupled anatomical modules, this work treats the entire robotic finger as one spatial closed-chain mechanism. The goal is to substantially reduce link-joint count while preserving useful 3-DoF fingertip motion and whole-hand grasp capability.

<img src="/portfolio/images/MinimalFinger2.png"
     alt="Computationally designed 3-DoF closed-chain robotic hand">

The main components of the research include:

- Enumerating admissible mechanism topologies that satisfy the required three degrees of freedom and structural constraints.
- Identifying a structurally minimal mechanism topology composed of the minimum number of links and joints.
- Performing multi-objective dimensional optimization using NSGA-II to maximize both the three-dimensional fingertip workspace and the workspace on the finger's desired symmetry plane.
- Converting the optimized linkage topology into a manufacturable robotic finger through the integrated design of actuators, joint structures, links, and mechanical interfaces.
- Implementing the control and electronic systems using ROS 2 and Dynamixel actuators.
- Experimentally evaluating the fabricated finger's motion repeatability and force capacity.
- Integrating four fingers into a complete robotic hand and demonstrating glove-based teleoperation.

<video autoplay muted loop playsinline preload="auto" controls>
  <source src="/portfolio/images/MinimalFinger.mp4" type="video/mp4">
  Your browser does not support embedded videos.
</video>

[Visit the Project Page](https://jae-hun-kim.github.io/minimal-finger/)

<hr class="subsection-divider">

### Tendon-Driven Robotic Fingers and Hands

**SNU Dynamic Robotic Systems Laboratory**  
**Advisor: Prof. Jaeheung Park**  
**Second-Author Research**  
*Under Review at Intelligent Service Robotics (ISR)*

I contributed to the development of a tendon-driven robotic finger and hand incorporating rolling-contact joints.

My contributions include:

- Assembly of 3D-printed finger modules using tendons, sheaths, and elastic ligaments
- Kinematic modeling between tendon displacement and finger configuration
- ROS 2 and Dynamixel-based control implementation
- Experimental validation of motion repeatability and force capacity
- Integration of multiple fingers into a teleoperated robotic hand

<video autoplay muted loop playsinline preload="auto" controls>
  <source src="/portfolio/images/TendonFinger.mp4" type="video/mp4">
  Your browser does not support embedded videos.
</video>

<hr class="section-divider">

## Computational Mechanism Design

### Autonomous Linkage Mechanism Design Software

**IDeAOcean**  
*Startup spun out of SNU IDeA Laboratory*

I played a key role in the development of algorithms for generating, analyzing, and optimizing linkage-based robotic mechanisms in both two-dimensional and three-dimensional design spaces.

The developed framework algorithmically generated mechanisms composed of various mechanical elements, evaluated their kinematic behavior, and optimized promising candidates according to user-defined objectives and constraints. Most of the algorithm development and numerical implementation were conducted in MATLAB.

<video autoplay muted loop playsinline preload="auto" controls>
  <source src="/portfolio/images/IDeAOcean.mp4" type="video/mp4">
  Your browser does not support embedded videos.
</video>

<hr class="section-divider">

## Wearable Robotics

### Wrist Anchoring System for Wearable Glove

**SNU Biorobotics Laboratory**  
**Advisor: Prof. Kyu-Jin Cho**  
**Undergraduate Research**

I participated in an undergraduate research project exploring a motor-cable wrist-anchoring mechanism for a wearable robotic glove system.

The project investigated a concept for automatically tightening and releasing the wrist interface using a motor-driven cable mechanism, with the aim of reducing the need for manual attachment and adjustment by the user.

<div class="two-image-row">
  <div>
    <img src="/portfolio/images/Biorobotics1.jpg"
         alt="Motor-cable wrist anchoring system for wearable glove 1">
  </div>

  <div>
    <img src="/portfolio/images/Biorobotics2.jpg"
         alt="Motor-cable wrist anchoring system for wearable glove 2">
  </div>
</div>

<hr class="subsection-divider">

### Variable-Stiffness Haptic Glove

**SNU Healthcare Robotics Laboratory**  
**Advisor: Prof. Amy Kyungwon Han**  
**Undergraduate Thesis**

I proposed and fabricated a variable-stiffness haptic glove based on electrostatic clutches. The glove was designed to provide haptic feedback not only for rigid virtual objects but also for soft objects with different levels of compliance.

Elastic bands and electrostatic clutches were arranged in a zigzag architecture along the fingers. By selectively activating the electrostatic clutches, the load paths between the elastic bands could be reconfigured into free, serial, parallel, and fully constrained states. This mechanism provided six discrete stiffness modes.

<img src="/portfolio/images/HealthcareRobotics.jpg"
     alt="Variable-stiffness haptic glove using electrostatic clutches">

<hr class="section-divider">
