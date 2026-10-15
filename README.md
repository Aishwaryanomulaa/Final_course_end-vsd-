# VSDIAT Course Learning Summary

## Overview

This repository documents my learning journey and practical work during the VSDIAT course, covering RTL Design, Physical Design, VSDBabySoC implementation, and Static Timing Analysis (STA).

## 1. RTL Design

RTL (Register Transfer Level) describes digital hardware using Verilog.

- Learned the basics of RTL design and hardware description.
- Worked with Verilog modules and design concepts.
- Studied simulation and waveform-based verification.

**Repository:** [RTL Design Workshop](https://github.com/Aishwaryanomulaa/RTL_Design_Workshop)

## 2. Physical Design

Explored the RTL-to-GDS physical design flow using OpenROAD.

The major stages include:

1. Synthesis
2. Floorplanning
3. Placement
4. Clock Tree Synthesis (CTS)
5. Routing
6. Timing and design-rule checks

**Repository:** [Physical Design](https://github.com/Aishwaryanomulaa/Physical_Design)

## 3. VSDBabySoC Implementation

Worked with the VSDBabySoC design and OpenROAD flow configuration.

- Inspected design files and configuration settings.
- Examined floorplanning and macro placement.
- Reviewed placement and CTS outputs.
- Investigated routing logs and congestion reports.
- Used screenshots and reports to document implementation progress.

## 4. Static Timing Analysis (STA)

Performed Static Timing Analysis across SKY130 timing corners using OpenSTA for the VSDBabySoC design.

The analysis covered:

- Timing path reports
- Setup timing checks
- Slack analysis
- Worst Negative Slack (WNS)
- Total Negative Slack (TNS)
- Comparison of timing results across corners

The results showed that timing performance varies across corners, with both positive and negative slack values. Negative slack indicates timing violations that require further investigation.

## 5. Tools and Technologies

- Verilog
- OpenROAD
- OpenSTA
- VSDBabySoC
- SKY130 PDK
- Static Timing Analysis

## 6. Key Learnings

- Understanding RTL design and hardware implementation.
- Learning the stages of the RTL-to-GDS flow.
- Inspecting physical design outputs and reports.
- Understanding setup timing, slack, WNS, and TNS.
- Identifying implementation issues through logs and reports.
- Documenting results using screenshots and technical reports.

## 7. Video Presentation

My VSDIAT course learning journey and practical implementation work are presented in the video below.

**[Watch the VSD Course Presentation](https://github.com/Aishwaryanomulaa/Final_course_end-vsd-/blob/main/Final_course_video.mp4)**

The video covers RTL Design, Physical Design, VSDBabySoC implementation using OpenROAD, and Static Timing Analysis (STA) across SKY130 timing corners.

## Conclusion

This course provided practical exposure to RTL design, physical design, VSDBabySoC implementation, and Static Timing Analysis. It helped me understand the RTL-to-GDS workflow and the importance of timing analysis and implementation reports in VLSI design.
