# Awesome-Reinforcement-Learning-Autonomous-Racing

## Top Reinforcement Learning Autonomous Racing Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on RL Training Environments, Autonomous Racing Simulators & Self-Hosted Platforms*  

**Last updated: October 2026**



This repository tracks notable **commercial RL autonomous racing platforms** and **open-source projects** that train, test, and deploy reinforcement learning agents for autonomous driving and racing — from 1/18th scale cars to full-scale race cars and high-fidelity simulators.



**Examples** include AWS DeepRacer, Wayve, Applied Intuition, CARLA, Cognata, Donkey Car, Gym Retro, Unity ML-Agents, Foretellix, and AirSim (the category leaders).



**Open-source emphasis**: RL autonomous racing is one of the strongest open-source domains. **AWS DeepRacer** open-sources its simulator and training tools, **Donkey Car** provides a complete DIY platform, **CARLA** delivers the leading autonomous driving simulator, and **Unity ML-Agents** enables general RL training. **F1TENTH** and **RoboRacer** standardize 1/10th scale racing, while **BeamNG.tech**, **AirSim**, and **Gazebo** provide physics simulation. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[AWS DeepRacer](https://aws.amazon.com/deepracer/)**  

  **AWS's 1/18th scale autonomous racing platform** — train RL models in simulation and deploy to physical cars . **DeepRacer League** for competitive racing . **Best for learning RL with a physical car** .



- **[Wayve](https://wayve.ai/)**  

  **End-to-end deep learning for autonomous driving** — not open-source but industry-leading . **Best for understanding production AV AI** .



- **[Applied Intuition](https://www.appliedintuition.com/)**  

  **Simulation and validation platform for autonomous vehicles** — high-fidelity sensor models and scenario generation . **Best for enterprise AV development** .



- **[CARLA Cloud](https://carla.org/)**  

  **Cloud-hosted CARLA simulator** — managed infrastructure for scalable scenario execution . **Best for large-scale simulation** .



- **[Cognata](https://www.cognata.com/)**  

  **AI-driven simulation for ADAS and AV validation** — realistic 3D environments and sensor simulation . **Best for enterprise validation** .



- **[Donkey Car Cloud](https://www.donkeycar.com/)**  

  **Managed Donkey Car platform** — see Open-Source section for the core project.



- **[Unity ML-Agents](https://unity.com/products/machine-learning-agents)**  

  **Unity's RL toolkit** — train agents in Unity environments . **Best for game-like RL environments** .



- **[Foretellix](https://www.fortellix.com/)**  

  **Coverage-driven verification for autonomous systems** — measurable safety metrics . **Best for AV verification** .



- **[AirSim Cloud](https://microsoft.github.io/AirSim/)**  

  **Microsoft's simulation platform** — see Open-Source section for the core project.



## Open-Source GitHub Projects



### Autonomous Racing Platforms



- **[AWS DeepRacer](https://github.com/aws-deepracer)**  

  **The most accessible RL autonomous racing platform**, Apache-2.0 licensed . **1/18th scale car with camera, compute, and AWS integration** . **Simulator for training RL models** — track environments with reward functions . **DeepRacer League** for competitive racing . **The de facto entry point for RL racing** . **Best for learning RL with a physical car** .



- **[Donkey Car](https://github.com/autorope/donkeycar)**  

  **Open-source DIY self-driving car platform**, MIT licensed with **3,000+ GitHub stars** . **1/16th to 1/10th scale cars** with Raspberry Pi, camera, and motor controller . **Behavioral cloning and RL support** . **The most popular DIY autonomous racing platform** . **Best for hobbyists and educators** .



- **[F1TENTH](https://github.com/f1tenth)**  

  **1/10th scale autonomous racing platform**, MIT licensed . **Standardized hardware and software stack** — used in university courses and competitions . **ROS2-based with simulation and physical cars** . **The academic standard for autonomous racing** . **Best for university research and education** .



- **[RoboRacer](https://github.com/roboracer)**  

  **1/10th scale autonomous racing** (formerly F1TENTH) . **Standardized platform with simulation and physical cars** . **Best for autonomous racing competitions** .



- **[DeepRacer Simulator](https://github.com/aws-deepracer/aws-deepracer-simapp)**  

  **Open-source DeepRacer simulator** — train RL models locally . **Docker-based with Gazebo** . **Best for DeepRacer training** .



### Autonomous Driving Simulators



- **[CARLA](https://github.com/carla-simulator/carla)**  

  **The leading open-source autonomous driving simulator**, MIT licensed with **14,000+ GitHub stars** . **Unreal Engine-based with realistic urban environments** . **Configurable sensor suites (LiDAR, cameras, radar, GNSS, IMU)** . **Python/C++ APIs with ROS bridge** . **Scenario runner for reproducible testing** . **The de facto standard for AV research** . **Best for autonomous driving RL** .



- **[AirSim](https://github.com/microsoft/AirSim)**  

  **Microsoft's simulation platform for drones and cars**, MIT licensed with **16,000+ GitHub stars** . **Unreal Engine and Unity-based** . **ROS and CyberRT integration** . **Best for drone and car RL** .



- **[BeamNG.tech](https://github.com/BeamNG/beamngpy)**  

  **Soft-body physics simulation for autonomous vehicles**, open-source Python library . **Realistic vehicle dynamics** . **Best for vehicle dynamics research** .



- **[Gazebo](https://github.com/gazebosim/gz-sim)**  

  **Open-source robotics simulator**, Apache-2.0 licensed . **ROS integration** . **Best for general robotics simulation** .



- **[SUMO](https://github.com/eclipse-sumo/sumo)**  

  **Microscopic traffic simulation**, EPL-2.0 licensed . **Large network simulation** . **Best for traffic-level simulation** .



- **[LGSVL Simulator](https://github.com/lgsvl/simulator)**  

  **Unity-based autonomous vehicle simulator**, Apache-2.0 licensed . **ROS and CyberRT integration** . **Best for AV simulation** .



### RL Training Frameworks



- **[Unity ML-Agents](https://github.com/Unity-Technologies/ml-agents)**  

  **Unity's RL toolkit**, Apache-2.0 licensed with **16,000+ GitHub stars** . **Train agents in Unity environments** . **Supports PPO, SAC, and other algorithms** . **Best for game-like RL environments** .



- **[Gym Retro](https://github.com/openai/retro)**  

  **OpenAI's retro game RL environment**, MIT licensed . **Train agents on classic games** . **Best for general RL research** .



- **[Stable Baselines3](https://github.com/DLR-RM/stable-baselines3)**  

  **Reliable RL implementations in PyTorch**, MIT licensed with **8,000+ GitHub stars** . **PPO, A2C, DQN, SAC, TD3** . **Best for RL algorithm implementation** .



- **[Ray RLlib](https://github.com/ray-project/ray)**  

  **Distributed RL library**, Apache-2.0 licensed . **Scalable RL training** . **Best for large-scale RL** .



- **[CleanRL](https://github.com/vwxyzjn/cleanrl)**  

  **Single-file RL implementations**, MIT licensed . **Research-friendly RL** . **Best for RL research** .



- **[Tianshou](https://github.com/thu-ml/tianshou)**  

  **PyTorch-based RL library**, MIT licensed . **Modular RL framework** . **Best for RL research** .



### Additional Strong Open-Source Options



- **AutoRally** — 1/5th scale autonomous racing platform from Georgia Tech .

- **MIT Racecar** — MIT's 1/10th scale autonomous racing platform .

- **OpenPodcar** — Open-source autonomous vehicle platform .

- **DeepRacer-for-Cloud** — Cloud-based DeepRacer training .

- **RoBorregos** — Autonomous racing platform from Tec de Monterrey .

- **Autoware** — Open-source autonomous driving stack .

- **Apollo** — Baidu's open autonomous driving platform .

- **Pylot** — Modular autonomous driving platform .

- **ROS2** — Robot Operating System for autonomous systems .

- **CARLA ROS Bridge** — ROS/ROS2 bridge for CARLA .



**Frameworks for building custom RL autonomous racing solutions**: Combine **AWS DeepRacer** for the most accessible physical RL racing platform . Use **F1TENTH** or **RoboRacer** for standardized 1/10th scale racing with ROS2 . Deploy **CARLA** for high-fidelity autonomous driving simulation . Choose **Donkey Car** for DIY autonomous racing with behavioral cloning . Integrate **Unity ML-Agents** for game-like RL environments . Use **Stable Baselines3** or **Ray RLlib** for RL algorithm implementation . Note that true commercial autonomous racing with full-scale vehicles, production-grade simulators, and enterprise validation (Applied Intuition, Cognata, Foretellix) remains primarily commercial territory; open-source stacks provide strong racing platforms, simulators, and RL frameworks that require integration for complete autonomous racing development.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Autonomous racing platforms involve physical vehicles that can cause injury or property damage. **Follow all safety guidelines** — test in controlled environments, use emergency stop mechanisms, and comply with local regulations.

- **RL training requires significant compute** — CARLA and high-fidelity simulators need GPU resources. DeepRacer training can run on AWS or locally with Docker .

- **Sim-to-real transfer is challenging** — models trained in simulation may not transfer directly to physical cars. Plan for fine-tuning and domain randomization .

- **Open-source racing platforms vary in maturity** — AWS DeepRacer and Donkey Car are production-ready; F1TENTH is the academic standard . Evaluate before committing.

- The open-source ecosystem provides strong racing platforms, simulators, and RL frameworks, but **full-scale vehicles, production-grade simulators, and enterprise validation** remain primarily commercial offerings.



---



**Made for RL researchers, autonomous racing enthusiasts, and robotics engineers.**  

Let's make reinforcement learning autonomous racing more open, transparent, and accessible.
