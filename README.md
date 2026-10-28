# Five-Finger Tendon-Driven Robotic Hand

### Independent Robotics Research Project | 20-Week Development Plan

**Status:** In Development  
**Focus:** Robotics, Embedded Systems, Feedback Control, Experimental Research

## Project Overview

This project investigates the design, implementation, and experimental evaluation of contact-feedback control strategies for a low-cost, five-finger tendon-driven robotic hand.

The project builds upon an existing open-source mechanical platform while independently developing the sensing, embedded control, data acquisition, and experimental evaluation systems.

The primary objective is to investigate whether fingertip contact feedback can improve grasp retention and reduce unnecessary contact loading compared with conventional fixed-position control.

## Research Objectives

1. Integrate five fingertip force-sensitive resistors (FSRs) into a five-finger robotic hand.
2. Develop an embedded control architecture using Arduino/C++ and Python.
3. Implement three grasp-control strategies:
   - **M0 — Fixed Closure:** Open-loop position-based grasping.
   - **M1 — Contact Stop:** Threshold-based contact detection and independent finger stopping.
   - **M2 — Contact Maintenance:** Closed-loop contact-feedback control using bounded proportional adjustments.
4. Evaluate grasp retention, contact-signal behavior, response time, and robustness under controlled experimental conditions.
5. Develop a reproducible experimental workflow with documented hardware, firmware, datasets, and statistical analysis.

## Technical Stack

- **Programming:** Python, C++ / Arduino
- **Hardware:** 3D-printed tendon-driven robotic hand, servo motors, FSR sensors, PCA9685
- **Embedded Systems:** Serial communication, analog sensor acquisition, actuator control
- **Control Systems:** Open-loop control, threshold-based control, proportional feedback control
- **Data Analysis:** NumPy, pandas, Matplotlib, SciPy
- **Version Control:** Git and GitHub

## Research Methodology

The study will compare M0, M1, and M2 using the same robotic platform under standardized experimental conditions.

Performance will be evaluated using grasp-retention success rates, fingertip contact-sensor measurements, grasping time, and failure-mode analysis.

Experimental parameters and testing protocols will be established before final data collection to support reproducibility and reduce experimental bias.

## Development Roadmap

| Phase | Weeks | Focus |
|---|---|---|
| I | 1–4 | Open-source platform verification, hardware preparation, and single-finger testing |
| II | 5–9 | Sensor integration, data acquisition, and five-finger system assembly |
| III | 10–13 | Implementation and validation of M0, M1, and M2 |
| IV | 14–16 | Experimental design and controlled grasp testing |
| V | 17–18 | Statistical analysis and performance evaluation |
| VI | 19–20 | Research report, reproducibility verification, and final demonstration |

## Research Handbook

The complete 20-week independent research and learning plan is available below.

**[View the Academic Research Handbook (PDF)](docs/Solo_Five_Finger_Robotic_Hand_Academic_20_Week_Handbook.pdf)**

The handbook outlines weekly learning objectives, hardware integration tasks, control-system development, experimental methodology, and expected research deliverables.

## Expected Deliverables

- Functional five-finger robotic hand with contact sensing
- Independently developed grasp-control algorithms
- Embedded firmware and Python data acquisition tools
- Experimental datasets and reproducible analysis scripts
- Academic-style technical research report
- Demonstration video and technical documentation

## Open-Source Hardware Attribution

The mechanical platform is based on the [JulianLee-07/Robotic-Hand](https://github.com/JulianLee-07/Robotic-Hand) repository.

Original mechanical design and associated source materials are credited to their respective creator. Any reuse or redistribution of source files will be subject to confirmation of the applicable licensing permissions.

This project's intended independent contributions focus on sensor integration, feedback-control development, experimental methodology, and performance analysis.

## Research Status

This project is currently in the development stage. Experimental results and performance claims will be published only after testing and validation.