# awesome-simulator

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
![GitHub last commit](https://img.shields.io/github/last-commit/SCP-CN-001/awesome-simulator?style=flat?cacheSeconds=86400))

A curated list of free and open-source simulators for robotics and autonomous driving research.

This repository aims to highlight simulators that are truly practical and valuable for researchers, following the philosophy that "Awesome is awesome", only the most recommended tools are featured in the Awesome Simulators section.

At the same time, we recognize and respect the efforts of developers working on emerging or less mature simulators. Therefore, additional sections are included to catalog all known simulators in this domain.

[Awesome robotics simulators](#awesome-robotics-simulators)

[Awesome driving simulators](#awesome-driving-simulators)

[Other robotics simulators](#other-robotics-simulators)

[Other driving simulators](#other-driving-simulators)

[Survey about simulators](#survey-about-simulators)

[Citation](#citation)

[How to Contribute](#how-to-contribute)

## Awesome robotics simulators

- **MuJoCo**: A physics engine for model-based control." `IROS 2012`. [[paper](https://ieeexplore.ieee.org/abstract/document/6386109)] [[code](https://github.com/google-deepmind/mujoco)] [[doc](https://mujoco.readthedocs.io/en/stable/overview.html)]

    ![GitHub last commit](https://img.shields.io/github/last-commit/google-deepmind/mujoco?cacheSeconds=86400)
    ![GitHub Tag](https://img.shields.io/github/v/tag/google-deepmind/mujoco?color=%236e8b74?cacheSeconds=86400)
    ![GitHub Repo stars](https://img.shields.io/github/stars/google-deepmind/mujoco?style=flat?cacheSeconds=86400)

- **Webots**: Professional Mobile Robot Simulation [[paper](https://arxiv.org/abs/cs/0412052)] [[code](https://github.com/cyberbotics/webots)] [[doc](https://cyberbotics.com/)]

    ![GitHub last commit](https://img.shields.io/github/last-commit/cyberbotics/webots?cacheSeconds=86400)
    ![GitHub Tag](https://img.shields.io/github/v/tag/cyberbotics/webots?color=%236e8b74?cacheSeconds=86400)
    ![GitHub Repo stars](https://img.shields.io/github/stars/cyberbotics/webots?style=flat?cacheSeconds=86400)

- **Isaac Sim** [[code](https://github.com/isaac-sim/IsaacSim)] [[doc](https://docs.isaacsim.omniverse.nvidia.com/latest/index.html)]

    ![GitHub last commit](https://img.shields.io/github/last-commit/isaac-sim/isaacsim?cacheSeconds=86400)
    ![GitHub Tag](https://img.shields.io/github/v/tag/isaac-sim/isaacsim?color=%236e8b74?cacheSeconds=86400)
    ![GitHub Repo stars](https://img.shields.io/github/stars/isaac-sim/isaacsim?style=flat?cacheSeconds=86400)

- **Gazebo**: Design and Use Paradigms for Gazebo, An Open-source Multi-robot Simulator `IROS 2004` [[paper](https://ieeexplore.ieee.org/abstract/document/1389727)] [[code](https://github.com/gazebosim/gz-sim)] [[doc](https://gazebosim.org/docs/)]

    ![GitHub last commit](https://img.shields.io/github/last-commit/gazebosim/gz-sim?cacheSeconds=86400)
    ![GitHub Tag](https://img.shields.io/github/v/tag/gazebosim/gz-sim?color=%236e8b74?cacheSeconds=86400)
    ![GitHub Repo stars](https://img.shields.io/github/stars/gazebosim/gz-sim?style=flat?cacheSeconds=86400)

- **PyBullet**: real-time collision detection and multi-physics simulation for VR, games, visual effects, robotics, machine learning [[code](https://github.com/bulletphysics/bullet3)] [[doc](https://pybullet.org/wordpress/index.php/forum-2/)]

    ![GitHub last commit](https://img.shields.io/github/last-commit/bulletphysics/bullet3?cacheSeconds=86400)
    ![GitHub Tag](https://img.shields.io/github/v/tag/bulletphysics/bullet3?color=%236e8b74?cacheSeconds=86400)
    ![GitHub Repo stars](https://img.shields.io/github/stars/bulletphysics/bullet3?style=flat?cacheSeconds=86400)

## Awesome driving simulators

- **CARLA**: An Open Urban Driving Simulator `CoRL 2017` [[paper](https://proceedings.mlr.press/v78/dosovitskiy17a.html)] [[code](GitHub - carla-simulator/carla: Open-source simulator for autonomous driving research.)]  [[doc](https://carla.readthedocs.io/en/latest/)]

    Minimal requirements: 8GB RAM, 600GB disk space, Ubuntu 16.04+, Python 3.6+

    ![GitHub last commit](https://img.shields.io/github/last-commit/carla-simulator/carla?cacheSeconds=86400)
    ![GitHub Tag](https://img.shields.io/github/v/tag/carla-simulator/carla?color=%236e8b74?cacheSeconds=86400)
    ![GitHub Repo stars](https://img.shields.io/github/stars/carla-simulator/carla?style=flat?cacheSeconds=86400)

- **HighwayEnv**: An Environment for Autonomous Driving Decision-Making [[code](https://github.com/Farama-Foundation/HighwayEnv)] [[doc](https://highway-env.farama.org/)]

    ![GitHub last commit](https://img.shields.io/github/last-commit/Farama-Foundation/highwayenv)
    ![GitHub Tag](https://img.shields.io/github/v/tag/Farama-Foundation/highwayenv?color=%236e8b74)
    ![GitHub Repo stars](https://img.shields.io/github/stars/Farama-Foundation/highwayenv?style=flat)

- **SUMO**: Simulation of Urban Mobility: an Overview `SIMUL 2011` [[paper](https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=685ee67cdfbbb8c9d6c5163849c0399ed4936149)] [[code](https://github.com/eclipse-sumo/sumo)] [[doc](https://sumo.dlr.de/docs/index.html)]

    Minimal requirements: 8GB RAM, a 4-core processor

    ![GitHub last commit](https://img.shields.io/github/last-commit/eclipse-sumo/sumo?cacheSeconds=86400)
    ![GitHub Tag](https://img.shields.io/github/v/tag/eclipse-sumo/sumo?color=%236e8b74?cacheSeconds=86400)
    ![GitHub Repo stars](https://img.shields.io/github/stars/eclipse-sumo/sumo?style=flat?cacheSeconds=86400)

- **MetaDrive**: Composing Diverse Driving Scenarios for Generalizable Reinforcement Learning `T-PAMI` [[paper](https://ieeexplore.ieee.org/abstract/document/9829243)] [[code](https://github.com/metadriverse/metadrive)] [[doc](https://metadrive-simulator.readthedocs.io/en/latest/)]

    ![GitHub last commit](https://img.shields.io/github/last-commit/metadriverse/metadrive?cacheSeconds=86400)
    ![GitHub Tag](https://img.shields.io/github/v/tag/metadriverse/metadrive?color=%236e8b74?cacheSeconds=86400)
    ![GitHub Repo stars](https://img.shields.io/github/stars/metadriverse/metadrive?style=flat?cacheSeconds=86400)

- **Waymax**: An Accelerated, Data-Driven Simulator for Large-Scale Autonomous Driving Research `NeurIPS 2023` [[paper](https://proceedings.neurips.cc/paper_files/paper/2023/hash/1838feeb71c4b4ea524d0df2f7074245-Abstract-Datasets_and_Benchmarks.html)] [[code](https://github.com/waymo-research/waymax)] [[doc](https://waymo-research.github.io/waymax/docs/)]

    ![GitHub last commit](https://img.shields.io/github/last-commit/waymo-research/waymax?cacheSeconds=86400)
    ![GitHub Repo stars](https://img.shields.io/github/stars/waymo-research/waymax?style=flat?cacheSeconds=86400)

## Other robotics simulators

- OpenRAVE: Open Robotics Automation Virtual Environment: An environment for testing, developing, and deploying robotics motion planning algorithms. [[paper](https://www.ri.cmu.edu/pub_files/pub4/diankov_rosen_2008_2/diankov_rosen_2008_2.pdf)] [[code](https://github.com/rdiankov/openrave)] [[doc](https://www.openrave.org/docs/latest_stable/)]

    ![GitHub last commit](https://img.shields.io/github/last-commit/rdiankov/openrave?cacheSeconds=86400)
    ![GitHub Tag](https://img.shields.io/github/v/tag/rdiankov/openrave?color=%236e8b74?cacheSeconds=86400)
    ![GitHub Repo stars](https://img.shields.io/github/stars/rdiankov/openrave?style=flat?cacheSeconds=86400)

## Other driving simulators

> This section is sorted by the initial release date. Simulators whose **core components** haven’t been updated in over a year will be moved from the *Awesome* section to here.

### 2025

### 2024

- **Vista**: A Generalizable Driving World Model with High Fidelity and Versatile Controllability `NeurIPS 2024` [[paper](https://arxiv.org/abs/2405.17398)] [[code](GitHub - OpenDriveLab/Vista: [NeurIPS 2024] A Generalizable World Model for Autonomous Driving)] [[website](https://opendrivelab.com/Vista/)]

    ![GitHub last commit](https://img.shields.io/github/last-commit/OpenDriveLab/vista?cacheSeconds=86400)
    ![GitHub Repo stars](https://img.shields.io/github/stars/opendrivelab/vista?style=flat?cacheSeconds=86400)


- **Tactics2D**: A Highly Modular and Extensible Simulator for Driving Decision-Making `T-IV` [[paper](https://ieeexplore.ieee.org/abstract/document/10561544)] [[code](GitHub - WoodOxen/tactics2d: Tactics2D: A Reinforcement Learning Environment Library with Generative)] [[doc](https://tactics2d.readthedocs.io/en/latest/)]

    ![GitHub last commit](https://img.shields.io/github/last-commit/woodoxen/tactics2d?cacheSeconds=86400)
    ![GitHub Tag](https://img.shields.io/github/v/tag/woodoxen/tactics2d?color=%236e8b74?cacheSeconds=86400)
    ![GitHub Repo stars](https://img.shields.io/github/stars/woodoxen/tactics2d?style=flat?cacheSeconds=86400)

### 2023

- **LimSim**: A Long-Term Interactive Multi-Scenario Traffic Simulator `ITSC 2023` [[paper](https://ieeexplore.ieee.org/abstract/document/10422219)] [[code](https://github.com/PJLab-ADG/LimSim/tree/master)] [[doc](https://pjlab-adg.github.io/LimSim/)]

    ![GitHub last commit](https://img.shields.io/github/last-commit/PJLab-ADG/limsim?cacheSeconds=86400)
    ![GitHub Repo stars](https://img.shields.io/github/stars/PJLab-ADG/limsim?style=flat?cacheSeconds=86400)

- **BITS**: Bi-level Imitation for Traffic Simulation `ICRA 2023` [[paper](https://ieeexplore.ieee.org/abstract/document/10161167)] [[code](https://github.com/NVlabs/traffic-behavior-simulation)]

    ![GitHub last commit](https://img.shields.io/github/last-commit/NVlabs/traffic-behavior-simulation?cacheSeconds=86400)
    ![GitHub Repo stars](https://img.shields.io/github/stars/nvlabs/traffic-behavior-simulation?style=flat?cacheSeconds=86400)

### 2022

- **InterSim**: Interactive Traffic Simulation via Explicit Relation Modeling `IROS 2022` [[paper](https://ieeexplore.ieee.org/abstract/document/9982008)] [[code](https://github.com/Tsinghua-MARS-Lab/InterSim)]

    ![GitHub last commit](https://img.shields.io/github/last-commit/Tsinghua-MARS-Lab/intersim?cacheSeconds=86400)
    ![GitHub Repo stars](https://img.shields.io/github/stars/Tsinghua-MARS-Lab/intersim?style=flat?cacheSeconds=86400)

- **Nocturne**: A Scalable Driving Benchmark for Bringing Multi-agent Learning One Step Closer to the Real World `NeurIPS 2022` [[paper](https://proceedings.neurips.cc/paper_files/paper/2022/hash/191e9e721a2748a860714fb23aaf7c5d-Abstract-Datasets_and_Benchmarks.html)] [[code](https://github.com/facebookresearch/nocturne)] [[doc](https://github.com/facebookresearch/nocturne/tree/main/docs)]

    ![GitHub last commit](https://img.shields.io/github/last-commit/facebookresearch/nocturne?cacheSeconds=86400)
    ![GitHub Repo stars](https://img.shields.io/github/stars/facebookresearch/nocturne?style=flat?cacheSeconds=86400)

### 2021

- **NuPlan**: A Closed-loop ML-based Planning Benchmark for Autonomous Vehicles `Arxiv 2021.06` [[paper](https://arxiv.org/abs/2106.11810)] [[code](https://github.com/motional/nuplan-devkit)] [[doc](https://nuplan-devkit.readthedocs.io/en/latest/)]

    ![GitHub last commit](https://img.shields.io/github/last-commit/motional/nuplan-devkit?cacheSeconds=86400)
    ![GitHub Tag](https://img.shields.io/github/v/tag/motional/nuplan-devkit?color=%236e8b74?cacheSeconds=86400)
    ![GitHub Repo stars](https://img.shields.io/github/stars/motional/nuplan-devkit?style=flat?cacheSeconds=86400)

- **L2R** (Learn-To-Race): A Multimodal Control Environment for Autonomous Racing `ICCV 2021` [[paper](https://openaccess.thecvf.com/content/ICCV2021/html/Herman_Learn-To-Race_A_Multimodal_Control_Environment_for_Autonomous_Racing_ICCV_2021_paper.html)] [[code](https://github.com/learn-to-race/l2r)] [[doc](https://learn-to-race.readthedocs.io/en/latest/)]

    ![GitHub last commit](https://img.shields.io/github/last-commit/learn-to-race/l2r?cacheSeconds=86400)
    ![GitHub Tag](https://img.shields.io/github/v/tag/learn-to-race/l2r?color=%236e8b74?cacheSeconds=86400)
    ![GitHub Repo stars](https://img.shields.io/github/stars/learn-to-race/l2r?style=flat?cacheSeconds=86400)

- **DI-drive**: Decision Intelligence Platform for Autonomous Driving simulation [[code](https://github.com/opendilab/DI-drive)] [[doc](https://opendilab.github.io/DI-drive/)]

    ![GitHub last commit](https://img.shields.io/github/last-commit/opendilab/di-drive?cacheSeconds=86400)
    ![GitHub Tag](https://img.shields.io/github/v/tag/opendilab/DI-drive?color=%236e8b74?cacheSeconds=86400)
    ![GitHub Repo stars](https://img.shields.io/github/stars/opendilab/di-drive?style=flat?cacheSeconds=86400)

### 2020

- **SMARTS**: An Open-source Scalable Multi-agent RL Training School for Autonomous Driving `CoRL 2020`[[paper](https://proceedings.mlr.press/v155/zhou21a.html)] [[code](https://github.com/huawei-noah/SMARTS)] [[doc](https://smarts.readthedocs.io/en/latest/)]

    ![GitHub last commit](https://img.shields.io/github/last-commit/huawei-noah/smarts?cacheSeconds=86400)
    ![GitHub Tag](https://img.shields.io/github/v/tag/huawei-noah/smarts?color=%236e8b74?cacheSeconds=86400)
    ![GitHub Repo stars](https://img.shields.io/github/stars/huawei-noah/smarts?style=flat?cacheSeconds=86400)

- **SUMMIT**: A Simulator for Urban Driving in Massive Mixed Traffic `ICRA 2020` [[paper](https://ieeexplore.ieee.org/abstract/document/9197228)] [[code](https://github.com/AdaCompNUS/summit)] [[doc](https://adacompnus.github.io/summit-docs/)]

    ![GitHub last commit](https://img.shields.io/github/last-commit/AdaCompNUS/summit?cacheSeconds=86400)
    ![GitHub Tag](https://img.shields.io/github/v/tag/AdaCompNUS/summit?color=%236e8b74?cacheSeconds=86400)
    ![GitHub Repo stars](https://img.shields.io/github/stars/AdaCompNUS/summit?style=flat?cacheSeconds=86400)

- **LGSVL**: A High Fidelity Simulator for Autonomous Driving `ITSC 2020` [[paper](https://ieeexplore.ieee.org/abstract/document/9294422)] [[code](https://github.com/lgsvl/simulator)] [[doc](https://www.svlsimulator.com/docs)]

    ![GitHub last commit](https://img.shields.io/github/last-commit/lgsvl/simulator?cacheSeconds=86400)
    ![GitHub Tag](https://img.shields.io/github/v/tag/lgsvl/simulator?color=%236e8b74?cacheSeconds=86400)
    ![GitHub Repo stars](https://img.shields.io/github/stars/lgsvl/simulator?style=flat?cacheSeconds=86400)

- **BARK**: Open Behavior Benchmarking in Multi-Agent Environments `IROS 2020` [[paper](https://ieeexplore.ieee.org/abstract/document/9341222/)] [[code](https://github.com/bark-simulator/bark)] [[website](https://bark-simulator.github.io/)]

    ![GitHub last commit](https://img.shields.io/github/last-commit/bark-simulator/bark?cacheSeconds=86400)
    ![GitHub Tag](https://img.shields.io/github/v/tag/bark-simulator/bark?color=%236e8b74?cacheSeconds=86400)
    ![GitHub Repo stars](https://img.shields.io/github/stars/bark-simulator/bark?style=flat?cacheSeconds=86400)

### 2019

- **CityFlow**: A Multi-Agent Reinforcement Learning Environment for Large Scale City Traffic Scenario `WWW 2019` [[paper](https://dl.acm.org/doi/abs/10.1145/3308558.3314139)] [[code](https://github.com/cityflow-project/CityFlow)] [[doc](https://cityflow.readthedocs.io/en/latest/)]

    ![GitHub last commit](https://img.shields.io/github/last-commit/cityflow-project/cityflow?cacheSeconds=86400)
    ![GitHub Repo stars](https://img.shields.io/github/stars/cityflow-project/cityflow?style=flat?cacheSeconds=86400)

- **MACAD**: Multi-agent Connected Autonomous Driving using Deep Reinforcement Learning `IJCNN 2019` [[paper](https://ieeexplore.ieee.org/abstract/document/9207663)] [[code](https://github.com/praveen-palanisamy/macad-gym)] [[doc](https://github.com/praveen-palanisamy/macad-gym?tab=readme-ov-file#getting-started)]

    ![GitHub last commit](https://img.shields.io/github/last-commit/praveen-palanisamy/macad-gym?cacheSeconds=86400)
    ![GitHub Tag](https://img.shields.io/github/v/tag/praveen-palanisamy/macad-gym?color=%236e8b74?cacheSeconds=86400)
    ![GitHub Repo stars](https://img.shields.io/github/stars/praveen-palanisamy/macad-gym?style=flat?cacheSeconds=86400)

- **AirSim**: High-Fidelity Visual and Physical Simulation for Autonomous Vehicles `SPAR` [[paper](https://link.springer.com/chapter/10.1007/978-3-319-67361-5_40)] [[code](https://github.com/microsoft/AirSim)] [[doc](https://airsim-fork.readthedocs.io/en/docs/)]

    ![GitHub last commit](https://img.shields.io/github/last-commit/microsoft/airsim?cacheSeconds=86400)
    ![GitHub Tag](https://img.shields.io/github/v/tag/microsoft/airsim?color=%236e8b74?cacheSeconds=86400)
    ![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/airsim?style=flat?cacheSeconds=86400)

### 2018

### 2017

- **CommonRoad**: Composable Benchmarks for Motion Planning on Roads `IV 2017` [[paper](https://ieeexplore.ieee.org/abstract/document/7995802)] [[code](https://github.com/CommonRoad)] [[doc](https://commonroad.in.tum.de/)]

    ![GitHub last commit](https://img.shields.io/github/last-commit/commonroad/commonroad-scenario-designer?cacheSeconds=86400)
    ![GitHub Tag](https://img.shields.io/github/v/tag/commonroad/commonroad-scenario-designer?color=%236e8b74?cacheSeconds=86400)
    ![GitHub Repo stars](https://img.shields.io/github/stars/commonroad/commonroad-scenario-designer?style=flat?cacheSeconds=86400)

- **Flow**: A Modular Learning Framework for Mixed Autonomy Traffic `Arxiv 2017.10` [[paper](https://arxiv.org/abs/1710.05465)] [[code](https://github.com/flow-project/flow)] [[doc](https://flow.readthedocs.io/en/latest/)]

    ![GitHub last commit](https://img.shields.io/github/last-commit/flow-project/flow?cacheSeconds=86400)
    ![GitHub Tag](https://img.shields.io/github/v/tag/flow-project/flow?color=%236e8b74?cacheSeconds=86400)
    ![GitHub Repo stars](https://img.shields.io/github/stars/flow-project/flow?style=flat?cacheSeconds=86400)

- **DeepDrive** [[code](https://github.com/deepdrive/deepdrive)] [[website](https://deepdrive.io/)]

    ![GitHub last commit](https://img.shields.io/github/last-commit/deepdrive/deepdrive?cacheSeconds=86400)
    ![GitHub Tag](https://img.shields.io/github/v/tag/deepdrive/deepdrive?color=%236e8b74?cacheSeconds=86400)
    ![GitHub Repo stars](https://img.shields.io/github/stars/deepdrive/deepdrive?style=flat?cacheSeconds=86400)

### 2016

- **Udacity** [[code](https://github.com/udacity/self-driving-car-sim)]

    ![GitHub last commit](https://img.shields.io/github/last-commit/udacity/self-driving-car-sim?cacheSeconds=86400)
    ![GitHub Tag](https://img.shields.io/github/v/tag/udacity/self-driving-car-sim?color=%236e8b74?cacheSeconds=86400)
    ![GitHub Repo stars](https://img.shields.io/github/stars/udacity/self-driving-car-sim?style=flat?cacheSeconds=86400)

### 2011

- **VDrift** [[code](https://github.com/VDrift/vdrift/)] [[doc](http://vdrift.net/)]

    ![GitHub Repo stars](https://img.shields.io/github/stars/vdrift/vdrift?style=flat?cacheSeconds=86400)
    ![GitHub Tag](https://img.shields.io/github/v/tag/vdrift/vdrift?color=%236e8b74?cacheSeconds=86400)
    ![GitHub Repo stars](https://img.shields.io/github/stars/vdrift/vdrift?style=flat?cacheSeconds=86400)

### 2000

- **Torcs**: The Open Racing Car Simulator [[paper](https://www.cse.chalmers.se/~chrdimi/papers/torcs.pdf)] [[code](https://sourceforge.net/projects/torcs/files/)]

    last commit: April 2025, tag: 1.3.8

## Survey about simulators

Li, Yueyuan, et al. "Choose your simulator wisely: A review on open-source simulators for autonomous driving." *IEEE Transactions on Intelligent Vehicles* 9.5 (2024): 4861-4876.

Chen, Di, et al. "Data-driven traffic simulation: A comprehensive review." IEEE Transactions on Intelligent Vehicles 9.4 (2024): 4730-4748.

Zhou, Jixiang, et al. "A survey on autonomous driving system simulators." *2022 IEEE International Symposium on Software Reliability Engineering Workshops (ISSREW)*. IEEE, 2022.

Kaur, Prabhjot, et al. "A survey on simulators for testing self-driving cars." *2021 Fourth International Conference on Connected and Autonomous Driving (MetroCAD)*. IEEE, 2021.

Holen, Martin, Kristian Knausgård, and Morten Goodwin. "An evaluation of autonomous car simulators and their applicability for supervised and reinforcement learning." *International Conference on Intelligent Technologies and Applications*. Cham: Springer International Publishing, 2021.

Bruck, Lucas, Bruce Haycock, and Ali Emadi. "A review of driving simulation technology and applications." *IEEE Open Journal of Vehicular Technology 2* (2020): 1-16.

Afzal, Afsoon, et al. "A study on the challenges of using robotics simulators for testing." *arXiv preprint arXiv:2004.07368* (2020).

Chao, Qianwen, et al. "A survey on visual traffic simulation: Models, evaluations, and applications in autonomous driving." *Computer Graphics Forum*. Vol. 39. No. 1. 2020.

## Citation

If you find the list about driving simulators helpful for your work, please cite

```latex
@article{li2024choose,
  title={Choose your simulator wisely: A review on open-source simulators for autonomous driving},
  author={Li, Yueyuan and Yuan, Wei and Zhang, Songan and Yan, Weihao and Shen, Qiyuan and Wang, Chunxiang and Yang, Ming},
  journal={IEEE Transactions on Intelligent Vehicles},
  year={2024},
  publisher={IEEE}
}
```

## How to Contribute

You’re welcome to suggest simulators that meet the following criteria for inclusion in this repository:

- Designed for robotics or autonomous driving tasks
- Open-source
