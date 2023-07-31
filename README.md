<h1 align="center">TESCO Scheduler</h1>
<div align="center">

## Abstract
Fog computing is one of the most widely used paradigms for analyzing and computing the data locally, instead of sending data to remote cloud servers. The main objective of fog computing is to lower the latency of services compared to cloud systems while also reducing the requirement of network bandwidth across computing devices. But as in a fog environment, more data is processed locally, fog nodes usually receive more requests daily, leading to system contention and processing overload. To tackle this, the state-of-the-art relies on machine learning coupled with simulations to forecast processing loads and limit the chances of node contention. However, prior work performs a single simulation to test whether a resource management decision, such as task placement, is optimal or not. This usually ignores the stochastic aspects in the environment or the noise in simulations. To resolve this, we proposed a novel approach called TESCO to perform simulations to test multiple candidate scheduling decisions and decide the optimal one. We demonstrate that TESCO outperforms state-of-the-art scheduler (COSCO) that uses single simulations with low overheads

## Quick Start Guide
To run the Multi_Simulation/Single_Simulation  technique , install required packages using
''
python3 install.py
''
To run the code with the required scheduler, modify line 107 of `main.py` to one of the several options Single_Simulation, Multiple_Simulation
''
scheduler = Multiple_Simulation()
''
To run the simulator, use the following command
python3 main.py


## Cite this work
S. Iftikhar et al., "TESCO: Multiple Simulations based AI-augmented Fog computing for QoS Optimization," 2022 IEEE Smartworld, Ubiquitous Intelligence & Computing, Scalable Computing & Communications, Digital Twin, Privacy Computing, Metaverse, Autonomous & Trusted Vehicles (SmartWorld/UIC/ScalCom/DigitalTwin/PriComp/Meta), Haikou, China, 2022, pp. 2092-2099, doi: 10.1109/SmartWorld-UIC-ATC-ScalCom-DigitalTwin-PriComp-Metaverse56740.2022.00302.


