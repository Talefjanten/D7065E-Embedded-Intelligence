AI Driven Control and Optimization System (Arrowhead Framework in Papyrus)

This project models an AI driven industrial control and optimization system using Papyrus (SysML) and the Arrowhead Framework.
The goal was to design a three level cascaded control architecture, combining traditional PID control with AI based supervision and global coordination to optimize an industrial ore handling process.

Modeled the system architecture in Papyrus using SysD, SysDD, SD, and IDD blocks.


What I Built
--------------------------------------------------
Designed a three level control hierarchy:

1. Local PID controllers for real time regulation

2. A Local AI Supervisor that adapts PID behavior

3. Global AI Coordinator that optimizes overall system performance

Defined communication and service interactions using the Arrowhead Framework (Service Registry, Authorization, and Orchestration).


What I Learned:
--------------------------------------------------
How service oriented automation supports scalability and interoperability.

The value of model driven engineering for system of systems (SoS) design.


Tools & References
--------------------------------------------------
Papyrus (Eclipse) – SysML modeling
Arrowhead Framework – SOA-based architecture for automation
“IoT Automation: Arrowhead Framework” by Jerker Delsing (CRC Press)
SysML / UML

Future work
--------------------------------------------------
1. Integrate predictive maintenance using AI models trained on sensor data.

2. Add reinforcement learning for realtime optimization of energy usage and throughput.

3. Develop a human machine interface (HMI) for visualization and manual overrides.

4. Expand the system into a multi cloud AI coordination network for full scale ore processing including conveyors, crushers, and magnetic separators creating an end to end intelligent control pipeline.

5. Extend the structured SysD / SysDD / SD / IDD modeling approach, currently demonstrated on the Power Sensor, to all subsystems 
  (motors, feeders, AI modules, and controllers). This would make the overall system model more consistent, scalable, and reusable.

6. Explore data logging and analytics for long term performance tracking and continuous learning.
