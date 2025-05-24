---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<span class='anchor' id='about-me'></span>

I am currently a postdoctoral scholar at the [UCLA Mobility Lab](https://mobility-lab.seas.ucla.edu/), working under the guidance of Prof. Jiaqi Ma. Previously, I was a research intern at the [NVIDIA Research Autonomous Vehicle Group](https://research.nvidia.com/labs/avg/) and a visiting student researcher at UC Berkeley in the [Mechanical Systems Control (MSC) Lab](https://msc.berkeley.edu/). I earned my Ph.D. from Nanyang Technological University (NTU), where I conducted research in the [Automated Driving and Human-Machine System (AutoMan) Lab](https://lvchen.wixsite.com/automan) under the supervision of Prof. Chen Lyu.

My research focuses on the intersection of robotics, mobility, and artificial intelligence (AI). I aim to develop algorithms and techniques that enable machines/robots to interact with humans naturally and make intelligent decisions. My research interests include deep learning, reinforcement learning, and generative AI, applied to areas such as perception, prediction, decision-making, simulation in autonomous driving, and human-machine interaction. My work has led to the publication of over 30 papers in top AI, ITS, and robotics journals and conferences. 

# 🔥 News
- *2025.01*: &nbsp;🎉🎉 Our paper on generative driving policy and reinforcement learning fine-tuning has been accepted by ICRA!
- *2024.12*: &nbsp;🎉🎉 Our paper on hybrid prediction integrated planning for autonomous driving has been accepted by TPAMI!
- *2024.09*: &nbsp;🎉🎉 Our NAVSIM paper on end-to-end driving benchmark has been accepted at NeurIPS 2024 Datasets and Benchmarks Track!
- *2024.07*: &nbsp;🎉🎉 Our ITSC invited session on [Learning-powered and Knowledge-driven Autonomous Driving](https://sites.google.com/view/itsc-lpad-2) has received 11 paper submissions, all of which were accepted. Congratulations to all the authors! Looking forward to seeing you in Edmonton, Canada!
- *2024.06*: &nbsp;🎉🎉 Our team secured first place in the Waymo Open Dataset Occupancy Flow Challenge and second place in the Sim Agents Challenge! Check out our technical reports on the [Waymo challenge website](https://waymo.com/open/challenges/) and [CVPR 2024 Workshop on Autonomous Driving](https://cvpr2024.wad.vision/).
- *2024.05*: &nbsp;🎉🎉 Our paper on online belief prediction and POMDP planning has been accepted by RAL!
- *2024.01*: &nbsp;🎉🎉 Our paper on joint prediction and planning for tree policy has been accepted by ICRA! See you in Yokohama, Japan!
- *2023.11*: &nbsp; I was invited by zdjszx.com to give a public lecture on "Scalable, Learnable, and Interactive Decision-making for Autonomous Driving". The recorded version of the lecture (in Chinese) is available for viewing on [bilibili](https://www.bilibili.com/video/BV1Mz4y1c7BS/?share_source=copy_web&vd_source=d38ad63504821012428c34311a1df246).
- *2023.10*: &nbsp;🎉🎉 Our paper on brain-inspired reinforcement learning for safe autonomous driving has been accepted by TPAMI!
- *2023.09*: &nbsp;🎉🎉 We won the best paper runner-up award in ITSC 2023!
- *2023.09*: &nbsp;🎉🎉 Our paper on human-guided reinforcement learning for robot navigation has been accepted by TPAMI!
- *2023.08*: &nbsp;🎉🎉 Our GameFormer paper has been accepted by ICCV as **Oral presentation**!

# 📝 Publications
## Highlights
<div class='paper-box'><div class='paper-box-image'><img src='images/gendrive.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**Gen-Drive: Enhancing Diffusion Generative Driving Policies with Reward Modeling and Reinforcement Learning Fine-tuning**

Zhiyu Huang, Xinshuo Weng, Maximilian Igl, Yuxiao Chen, Yulong Cao, Boris Ivanovic, Marco Pavone, Chen Lv

**IEEE International Conference on Robotics and Automation (ICRA), 2025**

[**Paper**](https://arxiv.org/abs/2410.05582) \| [**Project**](https://mczhi.github.io/GenDrive/)

- We introduce the Gen-Drive framework, which shifts from the traditional prediction and deterministic planning framework to a generation-then-evaluation planning paradigm. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><img src='images/vbd.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**Versatile Behavior Diffusion for Generalized Traffic Simulation**

Zhiyu Huang, Zixu Zhang, Ameya Vaidya, Yuxiao Chen, Chen Lv, Jaime Fernández Fisac

**arXiv, 2024**

[**Paper**](https://arxiv.org/abs/2404.02524) \| [**Project**](https://sites.google.com/view/versatile-behavior-diffusion) \| [![](https://img.shields.io/github/stars/SafeRoboticsLab/VBD?style=social&label=Code Stars)](https://github.com/SafeRoboticsLab/VBD)

-  We propose VBD, a novel traffic scenario generation framework that utilizes diffusion generative models to predict scene-consistent and controllable multi-agent interactions in closed-loop settings.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><img src='images/pomdp.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**Learning Online Belief Prediction for Efficient POMDP Planning in Autonomous Driving**

Zhiyu Huang, Chen Tang, Chen Lv, Masayoshi Tomizuka, Wei Zhan

**IEEE Robotics and Automation Letters, 2024**

[**Paper**](https://arxiv.org/abs/2401.15315)

-  We propose an online belief-update-based behavior prediction model and an efficient planner for POMDPs. We develop a Transformer-based prediction model, enhanced with a recurrent neural memory model, to dynamically update latent belief state and infer the intentions of other agents.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><img src='images/DTPP.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**DTPP: Differentiable Joint Conditional Prediction and Cost Evaluation for Tree Policy Planning in Autonomous Driving**

Zhiyu Huang, Peter Karkus, Boris Ivanovic, Yuxiao Chen, Marco Pavone, Chen Lv

**IEEE International Conference on Robotics and Automation (ICRA), 2024**

[**Paper**](https://arxiv.org/abs/2310.05885) \| [![](https://img.shields.io/github/stars/MCZhi/DTPP?style=social&label=Code Stars)](https://github.com/MCZhi/DTPP)

-  We employ a tree-structured policy planner and propose a differentiable joint training framework for both ego-conditioned prediction and cost evaluation models, resulting in a direct improvement of the final planning performance.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><img src='images/thesis.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**Learning-enabled Decision-making for Autonomous Driving: Framework and Methodology**

**PhD Thesis, 2024**

[**Thesis**](https://dr.ntu.edu.sg/handle/10356/172842)

-  This thesis presents a comprehensive framework and a series of learning-based methodologies for decision-making in AVs, with the objective of improving the scalability, adaptability, and alignment of their decision-making systems.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><img src='images/gameformer.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">  
  
**GameFormer: Game-theoretic Modeling and Learning of Transformer-based Interactive Prediction and Planning for Autonomous Driving**

Zhiyu Huang, Haochen Liu, Chen Lv

**IEEE/CVF International Conference on Computer Vision (ICCV), 2023**

**Oral presentation (top 3%)**

[**Paper**](https://arxiv.org/abs/2303.05760) \| [**Project**](https://mczhi.github.io/GameFormer/) \| [![](https://img.shields.io/github/stars/MCZhi/GameFormer?style=social&label=Code Stars)](https://github.com/MCZhi/GameFormer) \| **GameFormer Planner** [![](https://img.shields.io/github/stars/MCZhi/GameFormer-Planner?style=social&label=Code Stars)](https://github.com/MCZhi/GameFormer-Planner) 

-  We address the interaction prediction problem by formulating it with hierarchical game theory and implementing it with TransFormer networks.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><img src='images/IADM.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">  
  
**Learning Interaction-aware Motion Prediction Model for Decision-making in Autonomous Driving**

Zhiyu Huang, Haochen Liu, Jingda Wu, Wenhui Huang, Chen Lv

**IEEE International Conference on Intelligent Transportation Systems (ITSC), 2023** 

[**Best Paper Runner-up Award**](https://2023.ieee-itsc.org/best-paper-awards/)

[**Paper**](https://arxiv.org/abs/2302.03939) \| [![](https://img.shields.io/github/stars/MCZhi/Predictive-Decision?style=social&label=Code Stars)](https://github.com/MCZhi/Predictive-Decision)

-  We propose an interaction-aware motion prediction model that is able to predict other agents' future trajectories according to the ego agent's future plans, i.e., their reactions to the ego's actions.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><img src='images/CMPIRL.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**Conditional Predictive Behavior Planning with Inverse Reinforcement Learning for Human-like Autonomous Driving**

Zhiyu Huang, Haochen Liu, Jingda Wu, Chen Lv

**IEEE Transactions on Intelligent Transportation Systems, 2023**

[**Paper**](https://arxiv.org/abs/2212.08787)

- Distinguished from existing learning-based methods that directly output decisions, we introduce a predictive behavior planning framework that learns to predict and evaluate from human driving data. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><img src='images/DIPP.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">  
  
**Differentiable Integrated Motion Prediction and Planning with Learnable Cost Function for Autonomous Driving**

Zhiyu Huang, Haochen Liu, Jingda Wu, Chen Lv

**IEEE Transactions on Neural Networks and Learning Systems, 2023** 

[**Paper**](https://arxiv.org/abs/2207.10422) \| [**Project**](https://mczhi.github.io/DIPP/) \| [![](https://img.shields.io/github/stars/MCZhi/DIPP?style=social&label=Code Stars)](https://github.com/MCZhi/DIPP)

-  We propose an end-to-end differentiable framework that integrates prediction and planning modules and is able to learn the cost function from data.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><img src='images/prediction.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**Multi-modal Motion Prediction with Transformer-based Neural Network for Autonomous Driving**

Zhiyu Huang, Xiaoyu Mo, Chen Lv

**IEEE International Conference on Robotics and Automation (ICRA), 2022**

[**Paper**](https://arxiv.org/abs/2109.06446)

-  We propose a neural prediction framework based on the Transformer structure to model the relationship among the interacting agents and extract the attention of the target agent on the map waypoints.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><img src='images/ExpertDRL.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**Efficient Deep Reinforcement Learning with Imitative Expert Priors for Autonomous Driving**

Zhiyu Huang, Jingda Wu, Chen Lv

**IEEE Transactions on Neural Networks and Learning Systems, 2022**

[**Paper**](https://arxiv.org/abs/2103.10690) \|  [**Project**](https://mczhi.github.io/Expert-Prior-RL/) \| [![](https://img.shields.io/github/stars/MCZhi/Expert-Prior-RL?style=social&label=Code Stars)](https://github.com/MCZhi/Expert-Prior-RL)

-  We propose a novel framework to incorporate human prior knowledge in DRL, in order to improve the sample efficiency and save the effort of designing sophisticated reward functions.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><img src='images/IRL.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**Driving Behavior Modeling using Naturalistic Human Driving Data with Inverse Reinforcement Learning** 

Zhiyu Huang, Jingda Wu, Chen Lv

**IEEE Transactions on Intelligent Transportation Systems, 2021**

[**Paper**](https://arxiv.org/abs/2010.03118) \| [![](https://img.shields.io/github/stars/MCZhi/Driving-IRL-NGSIM?style=social&label=Code Stars)](https://github.com/MCZhi/Driving-IRL-NGSIM)

- We propose a structural assumption about internal reward function-based human driving behavior and employ sampling-based maximum entropy inverse reinforcement learning (IRL) algorithm to infer the reward function parameters from naturalistic human driving data.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><img src='images/multimodal.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**Multi-modal sensor fusion-based deep neural network for end-to-end autonomous driving with scene understanding** 

Zhiyu Huang, Chen Lv, Yang Xing, Jingda Wu

**IEEE Sensors Journal, 2020**

[**Paper**](https://arxiv.org/abs/2005.09202)

- We propose a novel deep neural network-based system for end-to-end autonomous driving, consisting of multimodal sensor fusion, scene understanding, and conditional driving policy modules. 
</div>
</div>

## All Publications
### Journal
- [Hybrid-Prediction Integrated Planning for Autonomous Driving](https://ieeexplore.ieee.org/abstract/document/10833731), Haochen Liu, **Zhiyu Huang**, Wenhui Huang, Haohan Yang, Xiaoyu Mo, Chen Lv, **IEEE Transactions on Pattern Analysis and Machine Intelligence, 2025** [![](https://img.shields.io/github/stars/georgeliu233/HPP?style=social&label=Code Stars)](https://github.com/georgeliu233/HPP)

- [Safety-Aware Human-in-the-Loop Reinforcement Learning With Shared Control for Autonomous Driving](https://ieeexplore.ieee.org/abstract/document/10596046), Wenhui Huang, Haochen Liu, **Zhiyu Huang**, Chen Lv, **IEEE Transactions on Intelligent Transportation Systems** [![](https://img.shields.io/github/stars/OscarHuangWind/Safe-Human-in-the-Loop-RL?style=social&label=Code Stars)](https://github.com/OscarHuangWind/Safe-Human-in-the-Loop-RL)

- [Augmenting Reinforcement Learning with Transformer-based Scene Representation Learning for Decision-making of Autonomous Driving](https://arxiv.org/abs/2208.12263), Haochen Liu, **Zhiyu Huang**, Xiaoyu Mo, Chen Lv, **IEEE Transactions on Intelligent Vehicles, 2024** [![](https://img.shields.io/github/stars/georgeliu233/Scene-Rep-Transformer?style=social&label=Code Stars)](https://github.com/georgeliu233/Scene-Rep-Transformer) 

- [Transformer-Based Traffic-Aware Predictive Energy Management of a Fuel Cell Electric Vehicle](https://ieeexplore.ieee.org/abstract/document/10409570), Jingda Wu, **Zhiyu Huang**, Chen Lv, **IEEE Transactions on Vehicular Technology, 2024**

- [Map-Adaptive Multimodal Trajectory Prediction via Intention-Aware Unimodal Trajectory Predictors](https://ieeexplore.ieee.org/abstract/document/10323217/), Xiaoyu Mo, Haochen Liu, **Zhiyu Huang**, Xiuxian Li, Chen Lv,  **IEEE Transactions on Intelligent Transportation Systems, 2023**

- [Fear-Neuro-Inspired Reinforcement Learning for Safe Autonomous Driving](https://ieeexplore.ieee.org/document/10273631), Xiangkun He, Jingda Wu, **Zhiyu Huang**, Zhongxu Hu, Jun Wang, Alberto Sangiovanni-Vincentelli, Chen Lv, **IEEE Transactions on Pattern Analysis and Machine Intelligence, 2023**

- [Human-Guided Reinforcement Learning with Sim-to-Real Transfer for Autonomous Navigation](https://ieeexplore.ieee.org/document/10250993), Jingda Wu, Yanxin Zhou, Haohan Yang, **Zhiyu Huang**, Chen Lv, **IEEE Transactions on Pattern Analysis and Machine Intelligence, 2023** [![](https://img.shields.io/github/stars/wujingda/Multi-Hug-RL?style=social&label=Code Stars)](https://github.com/wujingda/Multi-Hug-RL)

- [Uncertainty-Aware Model-Based Reinforcement Learning with Application to Autonomous Driving](https://arxiv.org/abs/2106.12194), Jingda Wu, **Zhiyu Huang**, Chen Lv, **IEEE Transactions on Intelligent Vehicles, 2022**

- [Prioritized Experience-based Reinforcement Learning With Human Guidance for Autonomous Driving](https://arxiv.org/abs/2109.12516), Jingda Wu, **Zhiyu Huang**, Wenhui Huang, Chen Lv, **IEEE Transactions on Neural Networks and Learning Systems, 2022** [![](https://img.shields.io/github/stars/wujingda/Prioritized-Human-in-the-loop-End-to-end-Autonomous-Driving?style=social&label=Code Stars)](https://github.com/wujingda/Prioritized-Human-in-the-loop-End-to-end-Autonomous-Driving)

- [Towards Human-in-the-loop AI: Enhancing Deep Reinforcement Learning via Real-time Human Guidance for Autonomous Driving](https://www.sciencedirect.com/science/article/pii/S2095809922004878), Jingda Wu, **Zhiyu Huang**, Zhongxu Hu, Chen Lv, **Engineering, 2022** [![](https://img.shields.io/github/stars/wujingda/Human-in-the-loop-Deep-Reinforcement-Learning?style=social&label=Code Stars)](https://github.com/wujingda/Human-in-the-loop-Deep-Reinforcement-Learning)

- [Multi-Agent Trajectory Prediction With Heterogeneous Edge-Enhanced Graph Attention Network](https://ieeexplore.ieee.org/abstract/document/9700483), Xiaoyu Mo, **Zhiyu Huang**, Yang Xing, Chen Lv, **IEEE Transactions on Intelligent Transportation Systems, 2022** [![](https://img.shields.io/github/stars/Xiaoyu006/MATP-with-HEAT?style=social&label=Code Stars)](https://github.com/Xiaoyu006/MATP-with-HEAT)

- [Personalized Trajectory Planning and Control of Lane-Change Maneuvers for Autonomous Driving](https://ieeexplore.ieee.org/abstract/document/9419761/), Chao Huang, Hailong Huang, Peng Hang, Hongbo Gao, Jingda Wu, **Zhiyu Huang**, Chen Lv, **IEEE Transactions on Vehicular Technology, 2021**

### Conference
- [NAVSIM: Data-Driven Non-Reactive Autonomous Vehicle Simulation and Benchmarking](https://arxiv.org/abs/2406.15349), Daniel Dauner, Marcel Hallgarten, Tianyu Li, Xinshuo Weng, **Zhiyu Huang**, Zetong Yang, Hongyang Li, Igor Gilitschenski, Boris Ivanovic, Marco Pavone, Andreas Geiger, Kashyap Chitta, **Advances in Neural Information Processing Systems (NeurIPS) Track on Datasets and Benchmarks, 2024** [![](https://img.shields.io/github/stars/autonomousvision/navsim?style=social&label=Code Stars)](https://github.com/autonomousvision/navsim)

- [Scalable Traffic Simulation for Autonomous Driving via Multi-Agent Goal Assignment and Autoregressive Goal-Directed Planning](https://ieeexplore.ieee.org/abstract/document/10588681/), Xiaoyu Mo, Haochen Liu, **Zhiyu Huang**, Jianwu Fang, Jianru Xue, Chen Lv, **IEEE Intelligent Vehicles Symposium (IV), 2024**

- [Occupancy Prediction-Guided Neural Planner for Autonomous Driving](https://arxiv.org/abs/2305.03303), Haochen Liu, **Zhiyu Huang**, Chen Lv, **IEEE International Conference on Intelligent Transportation Systems (ITSC), 2023** [![](https://img.shields.io/github/stars/georgeliu233/OPGP?style=social&label=Code Stars)](https://github.com/georgeliu233/OPGP)

- [Multi-modal Hierarchical Transformer for Occupancy Flow Field Prediction in Autonomous Driving](https://arxiv.org/abs/2208.00394), Haochen Liu, **Zhiyu Huang**, Chen Lv, **IEEE International Conference on Robotics and Automation (ICRA), 2023** [![](https://img.shields.io/github/stars/georgeliu233/STrajNet?style=social&label=Code Stars)](https://github.com/georgeliu233/STrajNet)

- [Stochastic Multimodal Interaction Prediction for Urban Driving](https://ieeexplore.ieee.org/abstract/document/9922298), Xiaoyu Mo, **Zhiyu Huang**, Chen Lv, **IEEE International Conference on Intelligent Transportation Systems (ITSC), 2022**

- [ReCoAt: A Deep Learning-based Framework for Multi-Modal Motion Prediction in Autonomous Driving Application](https://arxiv.org/abs/2207.00726), **Zhiyu Huang**, Xiaoyu Mo, Chen Lv, **IEEE International Conference on Intelligent Transportation Systems (ITSC), 2022**

- [Improved Deep Reinforcement Learning with Expert Demonstrations for Urban Autonomous Driving](https://arxiv.org/abs/2102.09243), Haochen Liu, **Zhiyu Huang**, Jingda Wu, Chen Lv, **IEEE Intelligent Vehicles Symposium (IV), 2022**

- [Digital Twin-enabled Reinforcement Learning for End-to-end Autonomous Driving](https://ieeexplore.ieee.org/abstract/document/9540179), Jingda Wu, **Zhiyu Huang**, Peng Hang, Chao Huang, Niels De Boer, Chen Lv, **IEEE International Conference on Digital Twins and Parallel Intelligence (DTPI), 2021**

- [Multi-scale driver behaviors reasoning system for intelligent vehicles based on a joint deep learning framework](https://ieeexplore.ieee.org/abstract/document/9283004), Yang Xing, Zhongxu Hu, **Zhiyu Huang**, Chen Lv, Dongpu Cao, Efstathios Velenis, **IEEE International Conference on Systems, Man, and Cybernetics (SMC), 2020**

### Preprint
- [V2XPnP: Vehicle-to-Everything Spatio-Temporal Fusion for Multi-Agent Perception and Prediction](https://arxiv.org/abs/2412.01812), Zewei Zhou, **Zhiyu Huang**, Bolei Zhou, Jiaqi Ma, **arXiv, 2024** [![](https://img.shields.io/github/stars/Zewei-Zhou/V2XPnP?style=social&label=Code Stars)](https://github.com/Zewei-Zhou/V2XPnP)

# 🎖 Honors and Awards
- *2025.05* NTU MAE Best PhD Thesis Award
- *2025.01* U.S. DOT Intersection Safety Challenge Tire 1 Winner
- *2024.08* IEEE ITS Best Dissertation Award Finalist
- *2024.07* Best Paper Award, [RSS 2024 workshop for Autonomous Vehicles Across Scale ](https://vindulamj.github.io/rss24-avas-workshop/)
- *2024.06* [1st Place Winner, Waymo Open Dataset Occupancy Flow Challenge](http://cvpr2024.wad.vision/), CVPR Workshop on Autonomous Driving
- *2024.06* [2rd Place Winner, Waymo Open Dataset Sim Agents Challenge](http://cvpr2024.wad.vision/), CVPR Workshop on Autonomous Driving
- *2023.09* Best Paper Runner-up Award, ITSC 2023
- *2023.06* [Innovation Award, nuPlan Planning Challenge](https://opendrivelab.com/AD23Challenge.html#nuplan_planning), CVPR Workshop on End-to-End Autonomous Driving \| [\[video\]](https://youtu.be/ZwhXilQKULY?t=1204)
- *2023.06* [3rd Place Winner, Waymo Open Dataset Motion Prediction Challenge](http://cvpr2023.wad.vision/), CVPR Workshop on Autonomous Driving
- *2022.12* [3rd Place Winner, Most Innovative Award, Driving SMARTS Competition](https://smarts-project.github.io/archive/2022_nips_driving_smarts/competition/), NeurIPS Competition Track \| [\[slides\]](https://smarts-project.github.io/assets/docs/aid_driving_smarts.pdf)
- *2022.06* [2nd Place Winner, Waymo Open Dataset Occupancy and Flow Prediction Challenge](http://cvpr2022.wad.vision/), CVPR Workshop on Autonomous Driving
- *2022.03* [2nd Place Winner, IEEE VTS Motor Vehicles Challenge](https://oraprdnt.uqtr.uquebec.ca/pls/public/gscw031?owa_no_site=6851), VPPC
- *2021.06* [1st Place Winner, Waymo Open Dataset Interaction Prediction Challenge](http://cvpr2021.wad.vision/), CVPR Workshop on Autonomous Driving \| [\[video\]](https://youtu.be/sjXI_FKYw4Y?t=2546)
- *2021.06* [2nd Place Winner, Waymo Open Dataset Motion Prediction Challenge](http://cvpr2021.wad.vision/), CVPR Workshop on Autonomous Driving
- *2019.06* Outstanding Graduate (Top 1%)
- *2018.10* National Scholarship (Top 1%)
- *2017.10* National Scholarship (Top 1%)

# 📖 Education
- *2019 - 2024*, Doctor of Philosophy, Robotics and Intelligent Systems, Nanyang Technological University, Singapore 
- *2015 - 2019*, Bachelor of Engineering, Vehicle Engineering, Chongqing University, Chongqing, China

# 📚 Academic Services
## Program Committee
- Lead organizer of Special Session on [learning-powered prediction and decision-making](https://sites.google.com/view/itsc-lpad) at ITSC, 2023
- Lead organizer of Invited Session on [learning-powered and knowledge-driven autonomous driving](https://sites.google.com/view/itsc-lpad-2) at ITSC, 2024

## Associate Editor
- [OJ-ITS – IEEE Open Journal of Intelligent Transportation Systems](https://ieee-itss.org/pub/oj-its/board/)

## Journal Reviewer
- IEEE Transactions on Intelligent Transportation Systems 
- IEEE Transactions on Neural Networks and Learning Systems
- IEEE Transactions on Intelligent Vehicles 
- IEEE Transactions on Cybernetics
- IEEE Robotics and Automation Letters
- Transportation Research Part C: Emerging Technologies
- Engineering Applications of Artificial Intelligence
- Artificial Intelligence Review 

## Conference Reviewer
- IEEE International Conference on Robotics and Automation (ICRA) 2022 -- 2025
- IEEE Intelligent Transportation Systems Conference (ITSC) 2022 -- 2025
- IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS) 2023 -- 2025
- European Conference on Computer Vision (ECCV) 2024
- Conference on Robot Learning (CoRL) 2024
- IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR) 2025
- IEEE/CVF International Conference on Computer Vision (ICCV) 2025
- Conference on Neural Information Processing Systems 2025
