## Title: Integrated Multi-Platform Automation System for Industrial Assembly and ASRS

This project focuses on the integration of multiple programming and automation platforms and creating an industrial-grade automation system.

The assembly line resembles an industrial assembly line that assembles a product. The assembly line comprises 4 stages, namely:
1) Components intake
2) Assembly
3) ASRS (Automatic Storage and Retrieval System)

These stages further have sub-stages.
1) Components intake:
   a) Visual inspection of components
   b) Separation of defective components
   c) Pick and place component to the next stage

2) Assembly:
   a) Rotation of the component into the right orientation
   b) Pinning
   c) Pick and place of the pinned component into the pressing machine
   d) Pressing
   e) Transfer of the assembled part to ASRS

3) ASRS:
   a) Picking the assembly from the conveyor
   b) Placing the assembly on the desired rack

Components Used:
1) 6 DOF Cobots x 3 (For pick and place operations)
2) Pneumatic actuators
3) Camera for Computer Vision (For Defective product identification)
4) Multiple sensors
5) Controllers:
   1) Beckhoff Ethercat PLC
   2) Raspberry Pi 4
   3) Nvidia Jetson Nano
