# D-Robotics RDK S100 S100P Developer Kit (80TOPS/128TOPS)
![]([https://github.com/YahboomTechnology/RDK-S100-S100P/blob/main/RDK_S100(P).jpg])
# Introduction
RDK S100/S100P is a developer kit designed specifically for embodied intelligent robots. It employs humanoid-Inspired dual-brain architecture, integrating a high-performance CPU, an 80TOPS/128TOPS BPU (AI acceleration unit), and a real-time MCU to achieve integrated computing and control. Onboard multiple interface for easy startup, it significantly enhances the robot perception, decision-making, and control capabilities in complex scenarios through heterogeneous computing and dynamic task scheduling, helping developers quickly build intelligent robot applications.
# Features
* Integrates three core units: a CPU (6x Cortex-A78AE, 100K DMIPS), a BPU (new Nash architecture, 80 TOPS/128 TOPS), and an MCU (4x Cortex-R52, 6K+ DMIPS).

CPU handles real-time scheduling and low-latency tasks; 

BPU is optimized for CNN/Transformer, supporting 160+ ONNX operators to improve AI inference energy efficiency; 

MCU enables high-frame-rate joint control, forming a "brain-cerebellum" collaborative architecture that balances intelligence and real-time performance.

* Efficient model collaboration is achieved through a three-tiered hardware division of labor: 

CPU, BPU,MCU.Large models (vision/point cloud/LLM/VLM) are handled by the CPU and BPU for perception and decision-making. 

Small models (motion control) are executed in conjunction with the MCU and BPU, freeing up CPU resources.

Dynamic model switching across the perception-execution chain is supported, ensuring on-demand resource allocation in complex tasks. The MCU specializes in high real-time control, while the BPU assists in computation and reduces its workload.

* End-to-end millisecond-level response closed loop

Visually acquired data undergoes semantic detection (LLM/VLM) and state analysis via BPU+CPU; the motion control model generates instructions through BPU inference, and the MCU executes high-frame-rate joint closed-loop control.

Threechip collaboration achieves millisecond-level response from human commands to mechanical execution, adapting to dynamic scenario requirements.

* Full-interface design for flexible storage expansion

Provides a classic 40pin interface + dual M.2 Key expansion interfaces, supporting JTAG debugging, camera expansion, and MCU interfaces.

Equipped with 64GB eMMC storage, 4×USB 3.0 ports and dual Gigabit Ethernet ensure high-speed data transmission, and supports Type-C quick-connect. The layered interface design caters to both engineering debugging and modular expansion needs.

* Open-source algorithms cover multiple robot forms

Through 200+ open source algorithms and application examples, it quickly adapts to scenarios such as semi-humanoid/quadruped/humanoid/point-legged/bipedal robots and robotic arms (LeRobot), lowering the development threshold for multi-form robots and accelerating deployment from hardware to specific scenarios.

# More Details
[Click here](https://category.yahboom.net/products/rdk-s100-s100p)

# Please Contact Us
If you have any problem when using our robot after checking the tutorial, please contact us.

### WhatsApp:
+86 18682378128

### Technical support email: 
support@yahboom.com

