# RoboHyperX

**Basic Info**. This repo collects curated academic papers, knowledge, and resources about robot learning.

- [Papers](#papers)
  - [Surveys](#Surveys)
  - [Benchmarks](#benchmarks)
  - [IL for Manipulation](#il-for-manipulation)
  - [RL for Manipulation](#rl-for-manipulation)
  - [Bimanual Manipulation](#bimanual-manipulation)
  - [World Model for Manipulation](#world-model-for-manipulation)
  - [Vision-Language-Action Model (VLA)](#vision-language-action-model-vla)
  - [Humanoid Loco-Manipulation](#humanoid-loco-manipulation-wbc)
  - [Humanoid Manipulation](#humanoid-manipulation)
  - [Humanoid VLA](#humanoid-vla)
  - [Legged Robot](#legged-robot)
  - [Wheel-Legged Robot](#wheel-legged-robot)
  - [Foundation Model](#foundation-model)
  - [Others](#others)
- [Workshops](#workshops)
  - [RSS 2025](#rss-2025)
  - [ICRA 2025](#icra-2025)
  - [IROS 2025](#iros-2025)
  - [RSS 2024](#rss-2024)
  - [RSS 2023](#rss-2023)
- [Pub-list](#conferences--journals)
- [Rankings](#rankings)
- [Deadline](#deadline)
- [Courses](#courses)
- [Blog](#blog)
- [Insights](#insights)
 
---
## Papers
<!-- (- [](), [](), []() ) -->

### Surveys
- [arXiv 2025.08](https://arxiv.org/abs/2508.13073), Large VLM-based Vision-Language-Action Models for Robotic Manipulation: A Survey
- [arXiv 2025.07](https://arxiv.org/abs/2404.19664), Towards Generalist Robot Learning from Internet Video: A Survey
- [arXiv 2025.07](https://arxiv.org/abs/2507.00917), A Survey: Learning Embodied Intelligence from
Physical Simulators and World Models, [github](https://github.com/NJU3DV-LoongGroup/Embodied-World-Models-Survey)
- [arXiv 2025.01](https://arxiv.org/abs/2501.02116), Humanoid Locomotion and Manipulation: Current Progress and Challenges in Control, Planning, and Learning
- [BIROB 2025.03](https://www.sciencedirect.com/science/article/pii/S266737972400055X), A survey on the visual perception of humanoid robot

### Benchmarks
- [arXiv 2023.10](https://arxiv.org/abs/2306.03310), LIBERO: Benchmarking Knowledge Transfer for Lifelong Robot Learning, [website](https://libero-project.github.io/main.html), [github](https://github.com/Lifelong-Robot-Learning/LIBERO)

### IL for Manipulation
- [arXiv 2025.07](https://arxiv.org/abs/2507.05331), A Careful Examination of Large Behavior Models for Multitask Dexterous Manipulation, [website](https://toyotaresearchinstitute.github.io/lbm1/)
- [arXiv 2024.05](https://arxiv.org/abs/2405.20321), ORION: Vision-based Manipulation from Single Human Video with Open-World Object Graphs, [website](https://ut-austin-rpl.github.io/ORION-release/)
- [arXiv 2024.10](https://arxiv.org/abs/2410.07864), RDT-1B: a Diffusion Foundation Model for Bimanual Manipulation, [website](https://rdt-robotics.github.io/rdt-robotics/), [github](https://github.com/thu-ml/RoboticsDiffusionTransformer)
- [arXiv 2024.10](https://arxiv.org/abs/2410.10803v2), Generalizable Humanoid Manipulation with Improved 3D Diffusion Policies, [website](https://humanoid-manipulation.github.io/), [github](https://github.com/YanjieZe/Improved-3D-Diffusion-Policy)
- [arXiv 2024.03](https://arxiv.org/abs/2403.03954), 3D Diffusion Policy: Generalizable Visuomotor Policy Learning via Simple 3D Representations, [website](https://3d-diffusion-policy.github.io/), [github](https://github.com/YanjieZe/3D-Diffusion-Policy)
- [arXiv 2023.10](https://arxiv.org/abs/2302.12422), MimicPlay: Long-Horizon Imitation Learning by Watching Human Play, [website](https://mimic-play.github.io/), [github](https://github.com/j96w/MimicPlay)
- [arXiv 2023.04](https://arxiv.org/abs/2304.13705), Learning Fine-Grained Bimanual Manipulation with Low-Cost Hardware, [website](https://tonyzhaozh.github.io/aloha/), [github](https://github.com/tonyzhaozh/act)
- [arXiv 2023.03](https://arxiv.org/abs/2303.04137v5), Diffusion Policy: Visuomotor Policy Learning via Action Diffusion, [website](https://diffusion-policy.cs.columbia.edu/), [github](https://github.com/real-stanford/diffusion_policy)

### RL for Manipulation
- [arXiv 2024.10](https://arxiv.org/abs/2410.21845), Precise and Dexterous Robotic Manipulation via Human-in-the-Loop Reinforcement Learning, [website](https://hil-serl.github.io/), [github](https://github.com/rail-berkeley/hil-serl)

### Bimanual Manipulation
- [TRO 2024.02](https://ieeexplore.ieee.org/document/10449470), Enabling Versatility and Dexterity of the Dual-Arm Manipulators: A General Framework toward Universal Cooperative Manipulation

### World Model for Manipulation
- [arXiv 2025.08](https://arxiv.org/abs/2509.00361), Generative Visual Foresight Meets Task-Agnostic Pose Estimation in Robotic Table-top Manipulation, [website](https://clearlab-sustech.github.io/gvf-tape/)
- [arXiv 2025.05](https://arxiv.org/abs/2505.12705), DreamGen: Unlocking Generalization in Robot Learning through Video World Models, [website](https://research.nvidia.com/labs/gear/dreamgen/), [github](https://github.com/nvidia/GR00T-dreams)
- [arXiv 2025.07](https://arxiv.org/abs/2507.01099), Geometry-aware 4D Video Generation for Robot Manipulation, [website](https://robot4dgen.github.io/), [github](https://github.com/lzylucy/4dgen)
- [arXiv 2025.07](https://arxiv.org/abs/2506.01943), Learning Video Generation for Robotic Manipulation with Collaborative Trajectory Control, [website](https://fuxiao0719.github.io/projects/robomaster/), [github](https://github.com/KwaiVGI/RoboMaster)
- [arXiv 2025.05](https://arxiv.org/abs/2505.14357), Vid2World: Crafting Video Diffusion Models to Interactive World Models, [website](https://knightnemo.github.io/vid2world/)
- [arXiv 2023.01](https://arxiv.org/abs/2306.11335), Surfer: Progressive Reasoning with World Models for Robotic Manipulation, [website](https://pzhren.github.io/Surfer/), [github](https://github.com/pzhren/Surfer)

### Vision-Language-Action Model (VLA)
- [arXiv 2025.08](https://arxiv.org/abs/2508.07917), MolmoAct: Action Reasoning Models that can Reason in Space, [website](https://allenai.org/blog/molmoact), [github](https://github.com/allenai/MolmoAct)
- [arXiv 2025.07](https://arxiv.org/abs/2507.04447), DreamVLA: A Vision-Language-Action Model Dreamed with Comprehensive World Knowledge, [website](https://zhangwenyao1.github.io/DreamVLA/), [github](https://github.com/Zhangwenyao1/DreamVLA)
- [arXiv 2025.06](https://arxiv.org/abs/2506.07961), BridgeVLA: Input-Output Alignment for Efficient 3D Manipulation Learning with Vision-Language Models, [website](https://bridgevla.github.io/home_page.html), [github](https://github.com/BridgeVLA/BridgeVLA)
- [arXiv 2025.05](https://arxiv.org/abs/2505.06111), UniVLA: Learning to Act Anywhere with Task-centric Latent Actions, [github](https://github.com/OpenDriveLab/UniVLA)
- [arXiv 2025.03](https://arxiv.org/abs/2503.08950), FP3: A 3D Foundation Policy for Robotic Manipulation, [website](https://3d-foundation-policy.github.io/), [github](https://github.com/horipse01/3d-foundation-policy)
- [arXiv 2025.03](https://arxiv.org/abs/2503.07511), PointVLA: Injecting the 3D World into Vision-Language-Action Models, [website](https://pointvla.github.io/)
- [arXiv 2025.01](https://arxiv.org/abs/2501.15830), SpatialVLA: Exploring Spatial Representations for Visual-Language-Action Models, [website](https://spatialvla.github.io/), [github](https://github.com/SpatialVLA/SpatialVLA)
- [arXiv 2024.10](https://arxiv.org/abs/2410.24164), π0: A Vision-Language-Action Flow Model for General Robot Control, [website](https://www.physicalintelligence.company/blog/pi0), [github](https://github.com/Physical-Intelligence/openpi)
- [arXiv 2024.06](https://arxiv.org/abs/2406.09246), OpenVLA: An Open-Source Vision-Language-Action Model, [website](https://openvla.github.io/), [github](https://github.com/openvla/openvla)

### Humanoid Loco-Manipulation (WBC)
- [arXiv 2025.06](https://arxiv.org/abs/2506.12851), KungfuBot: Physics-Based Humanoid Whole-Body Control for Learning Highly-Dynamic Skills, [website](https://kungfu-bot.github.io/), [github](https://github.com/TeleHuman/PBHC)
- [arXiv 2025.09](https://arxiv.org/abs/2509.16638), KungfuBot 2: Learning Versatile Motion Skills for Humanoid Whole-Body Control, [website](https://kungfubot2-humanoid.github.io/), [github](https://github.com/TeleHuman/PBHC)
- [arXiv 2025.07](https://www.arxiv.org/abs/2506.07876), Versatile Loco-Manipulation through Flexible Interlimb Coordination, [website](https://relic-locoman.rai-inst.com/)
- [arXiv 2025.09](https://arxiv.org/abs/2509.16757), HDMI: Learning Interactive Humanoid Whole-Body Control from Human Videos, [website](https://hdmi-humanoid.github.io/#/), [github](https://github.com/LeCAR-Lab/HDMI)
- [arXiv 2025.05](https://arxiv.org/abs/2505.03729), VideoMimic: Visual imitation enables contextual humanoid control, [website](https://www.videomimic.net/), [github](https://github.com/hongsukchoi/VideoMimic)
- [arXiv 2025.08](https://arxiv.org/abs/2508.21043), HITTER: A HumanoId Table TEnnis Robot via Hierarchical Planning and Learning, [website](https://humanoid-table-tennis.github.io/)
- [arXiv 2025.08](https://arxiv.org/abs/2508.08241), BeyondMimic: From Motion Tracking to Versatile Humanoid Control via Guided Diffusion, [website](https://beyondmimic.github.io/), [github](https://github.com/HybridRobotics/whole_body_tracking)
- [arXiv 2025.07](https://arxiv.org/abs/2507.06905), ULC: A Unified and Fine-Grained Controller for Humanoid Loco-Manipulation, [website](https://ulc-humanoid.github.io/)
- [arXiv 2025.05](https://arxiv.org/abs/2505.02833), TWIST: Teleoperated Whole-Body Imitation System, [website](https://yanjieze.com/TWIST/), [github](https://github.com/YanjieZe/TWIST)
- [arXiv 2025.05](https://arxiv.org/abs/2505.06776), FALCON: Learning Force-Adaptive Humanoid Loco-Manipulation, [website](https://lecar-lab.github.io/falcon-humanoid/), [github](https://github.com/LeCAR-Lab/FALCON/)
- [arXiv 2025.05](https://arxiv.org/abs/2505.07294), HuB: Learning Extreme Humanoid Balance, [website](https://hub-robot.github.io/)
- [arXiv 2025.05](https://arxiv.org/abs/2505.24198), Hold My Beer: Learning Gentle Humanoid Locomotion and End-Effector Stabilization Control, [website](https://lecar-lab.github.io/SoFTA/), [github](https://github.com/LeCAR-Lab/SoFTA)
- [arXiv 2025.02](https://arxiv.org/abs/2502.01143), ASAP: Aligning Simulation and Real-World Physics for Learning Agile Humanoid Whole-Body Skills, [website](https://agile.human2humanoid.com/), [github](https://github.com/LeCAR-Lab/ASAP)
- [arXiv 2025.02](https://arxiv.org/abs/2502.13013), HOMIE: Humanoid Loco-Manipulation with Isomorphic Exoskeleton Cockpit (RL), [website](https://homietele.github.io/), [github](https://github.com/InternRobotics/OpenHomie)

### Humanoid Manipulation
- [arXiv 2025.06](https://arxiv.org/abs/2506.05064), DemoSpeedup: Accelerating Visuomotor Policies via Entropy-Guided Demonstration Acceleration, [website](https://demospeedup.github.io/)
- [arXiv 2025.02](https://arxiv.org/abs/2502.13134), RHINO: Learning Real-Time Humanoid-Human-Object Interaction from Human Demonstrations, [website](https://humanoid-interaction.github.io/), [github](https://github.com/TimerChen/RHINO)
- [arXiv 2024.10](https://arxiv.org/abs/2410.11792), OKAMI: Teaching Humanoid Robots Manipulation Skills through Single Video Imitation, [website](https://ut-austin-rpl.github.io/OKAMI/), [github](https://github.com/UT-Austin-RPL/OKAMI)
- [arXiv 2024.10](https://arxiv.org/abs/2410.10803v2), Generalizable Humanoid Manipulation with Improved 3D Diffusion Policies, [website](https://humanoid-manipulation.github.io/), [github](https://github.com/YanjieZe/Improved-3D-Diffusion-Policy)

### Humanoid VLA
- [arXiv 2025.06](https://arxiv.org/abs/2506.13751), LeVERB: Humanoid Whole-Body Control with Latent Vision-Language Instruction, [website](https://ember-lab-berkeley.github.io/LeVERB-Website/)

### Legged Robot
- [arXiv 2025.06](https://arxiv.org/abs/2506.09588), Attention-based map encoding for learning generalized legged locomotion
- [arXiv 2025.05](https://arxiv.org/abs/2505.22974), Learning coordinated badminton skills for legged manipulators
- [arXiv 2024.01](https://arxiv.org/abs/2401.17583), Agile But Safe: Learning Collision-Free High-Speed Legged Locomotion, [website](https://agile-but-safe.github.io/), [github](https://github.com/LeCAR-Lab/ABS)
- [arXiv 2023.09](https://arxiv.org/abs/2309.15462), DTC: Deep Tracking Control
- [arXiv 2022.01](https://arxiv.org/abs/2201.08117), Learning robust perceptive locomotion for quadrupedal robots in the wild, [website](https://perceptive-loco.github.io/)
- [arXiv 2020.10](https://arxiv.org/abs/2010.11251), Learning Quadrupedal Locomotion over Challenging Terrain
- [arXiv 2019.01](https://arxiv.org/abs/1901.08652), Learning agile and dynamic motor skills for legged robots
- [arXiv 2019.09](https://arxiv.org/abs/1909.06586v1), Highly Dynamic Quadruped Locomotion via Whole-Body Impulse Control and Model Predictive Control
- [IROS 2018.10](https://ieeexplore.ieee.org/document/8594448), Dynamic Locomotion in the MIT Cheetah 3 Through Convex Model-Predictive Control
- [ICRA 2018.05](https://ieeexplore.ieee.org/abstract/document/8460904), Contact Model Fusion for Event-Based Locomotion in Unstructured Terrains

### Wheel-Legged Robot
- [arXiv 2024.05](https://arxiv.org/abs/2405.01792), Learning Robust Autonomous Navigation and Locomotion for Wheeled-Legged Robots

### Foundation Model
- [arXiv 2025.01](https://arxiv.org/abs/2501.12375), Video Depth Anything: Consistent Depth Estimation for Super-Long Videos, [website](https://videodepthanything.github.io/), [github](https://github.com/DepthAnything/Video-Depth-Anything)

### Others
- [arXiv 2023.12](https://arxiv.org/abs/2312.04393), PhysHOI: Physics-Based Imitation of Dynamic Human-Object Interaction, [website](https://wyhuai.github.io/physhoi-page/), [github](https://github.com/wyhuai/PhysHOI)

## Workshops
### RSS 2025
- [[RSS 2025] Benchmarking Robot Manipulation: Improving Interoperability and Modularity](https://www.robot-manipulation.org/events/workshops/rss-2025)
- [[RSS 2025] 3rd Workshop on Dexterous Manipulation: Learning and Control with Diverse Data](https://dex-manipulation.github.io/rss2025/)
- [[RSS 2025] Equivariant Systems: Theory and Applications in State Estimation, Artificial Intelligence and Control](https://equisystems.github.io/)
- [[RSS 2025] Gaussian Representations for Robot Autonomy: Challenges and Opportunities](https://sites.google.com/view/gmm-workshop-rss25)
- [[RSS 2025] 2nd Workshop on Generative Modeling Meets Human-Robot Interaction (GenAI-HRI)](https://sites.google.com/view/gai-hri)
- [[RSS 2025] Human-in-the-loop Robot Learning: Teaching, Correcting, and Adapting](https://hitl-robot-learning.github.io/)
- [[RSS 2025] Large Foundation Model for Interactive Robot Learning](https://lfmrss2025.weebly.com/)
- [[RSS 2025] Workshop on Learned Robot Representations (RoboReps)](https://rss25-roboreps.github.io/)
- [[RSS 2025] Navigating Contact Dynamics in Robotics: Bridging the Gap Between Modeling, Sensing, and Contact-aware Control](https://sites.google.com/colorado.edu/ws-contact-dynamics/home)
- [[RSS 2025] 2nd Workshop on Out-of-Distribution Generalization in Robotics: Towards Trustworthy AI-driven Autonomy](https://sites.google.com/stanford.edu/ood-workshop-rss-25/home)
- [[RSS 2025] Resilient Off-road Autonomous Robotics (ROAR)](https://off-roaders.github.io/off-road-workshop-2025/)
- [[RSS 2025] Workshop on Whole-body Control and Bimanual Manipulation: Applications in Humanoids and Beyond](https://wcbm-workshop.github.io/)
- [[RSS 2025] Workshop on Continual Robot Learning from Humans](https://continual-robot-learning-from-humans.github.io/)
- [[RSS 2025] EgoAct: 1st Workshop on Egocentric Perception and Action for Robot Learning](https://egoact.github.io/rss2025/)
- [[RSS 2025] Fast motion planning and control in the era of parallelism](https://sites.google.com/rice.edu/parallelized-planning-control/)
- [[RSS 2025] Human-Robot Contact and Manipulation (HRCM)](https://hrcm-workshop.github.io/2025/)
- [[RSS 2025] Mobile Manipulation: Emerging Opportunities & Contemporary Challenges](https://rss-moma-2025.github.io/)
- [[RSS 2025] R3: Reasoning for Robust Robot Manipulation in the Open World](https://sites.google.com/view/rss2025r3/home)
- [[RSS 2025] Reliable Robotics: Safety and Security in the Face of GenAI](https://sites.google.com/view/rss2025-reliable-robotics/home)
- [[RSS 2025] Resource Constrained Robotics](https://sites.google.com/view/rc4roboticsrss25)
- [[RSS 2025] Robot Planning in the Era of Foundation Models (FM4RoboPlan)](https://sites.google.com/brown.edu/fm4roboplan)
- [[RSS 2025] 2nd Workshop on Semantic Reasoning and Goal Understanding in Robotics (SemRob)](https://semrob.github.io/)
- [[RSS 2025] Space Robotics: Toward the Next Generation of Autonomous Missions](https://albee.github.io/space-robotics-rss/)
- [[RSS 2025] Structured World Models for Robotic Manipulation](https://swomo-rss.github.io/)
### ICRA 2025
- [[ICRA 2025] 7th Workshop on Long-Term Human Motion Prediction](https://motionpredictionicra2025.github.io/)
- [[ICRA 2025] Foundation Models and Neuro-Symbolic AI for Robotics](https://sairlab.org/icra25/)
- [[ICRA 2025] Human-Centered Robot Learning in the Era of Big Data and Large Models](https://human-cenetered-robot-learning-workshop.github.io/icra-2025/)
- [[ICRA 2025] Workshop on Field Robotics](https://norlab-ulaval.github.io/icra_workshop_field_robotics/)
- [[ICRA 2025] Towards Reliable and Trustworthy Embodied AI in Everyday Scenarios](https://sites.google.com/view/reliable-embodied-ai/home)
- [[ICRA 2025] Learning Meets Model-Based Methods for Contact-Rich Manipulation](https://contact-rich.github.io/)
- [[ICRA 2025] Nonverbal Cues for Human-Robot Cooperative Intelligence](https://nocworkshop.github.io/2025/)
- [[ICRA 2025] Towards Human Level Intelligence Vision and Tactile Sensing](https://shanluo.github.io/ViTacWorkshops/)
- [[ICRA 2025] Building a Common Humanoid Platform Infrastructure for AI-based Testing](https://www.daslhub.org/icra2025Workshop/)
- [[ICRA 2025] Beyond Pick and Place – Unifying Learning-Based and Model-Based Approaches for Contact-Rich Manipulation](https://sites.google.com/view/icra-2025-beyond-pick-place/home)
- [[ICRA 2025] Safely Leveraging Vision-Language Foundation Models in Robotics: Challenges and Opportunities](https://sites.google.com/stanford.edu/safe-vlm-icra/home)
- [[ICRA 2025] RoboLetics 2.0: Workshop on Athletic Robots and Dynamic Motor Skills](https://sites.google.com/view/roboletics2)
- [[ICRA 2025] Structured Learning for Efficient, Reliable, and Transparent Robots](https://sites.google.com/view/srl-icra-2025/home)
- [[ICRA 2025] 3rd Workshop on Multilateral Human-Interaction-Oriented Teleoperation](https://sites.google.com/view/icra-2025-workshop?usp=sharing)
- [[ICRA 2025] Language and Semantics of Task and Motion Planning](https://dyalab.mines.edu/2025/icra-workshop/)
- [[ICRA 2025] Reflections on Representations and Manipulating Deformable Objects](https://deformable-workshop.github.io/icra2025/)
- [[ICRA 2025] Beyond the Lab: Robust Planning and Control in Real World Scenarios](https://sites.google.com/view/robust-planning-icra2025-ws)
### IROS 2025
- [[IROS 2025] ROMADO: 5th workshop on RObotic MAnipulation of Deformable Objects: holistic approaches and challenges forward](https://romado-workshop.github.io/ROMADO2025.github.io/)
- [[IROS 2025] Perception and Planning for Mobile Manipulation in Changing Environments](https://autonomousrobots.nl/workshops/2025-iros)
- [[IROS 2025] Frontiers in Dynamic, Intelligent, and Adaptive Multi-Arm Manipulation](https://www.iit.it/web/hrii/iros2025-workshop-multi-arm)
- [[IROS 2025] Benchmarking via Competitions in Robotic Grasping and Manipulation – 2nd edition](https://sites.google.com/view/iros2025-bench-competitions/)
- [[IROS 2025] Advancing Active Perception: Bridging Sensing, Planning, and Interaction](https://activep-ws.github.io/)
- [[IROS 2025] Tactile Sensing Toward Robot Dexterity and Intelligence](https://sites.google.com/view/iros-2025-workshop-tactile)
- [[IROS 2025] Workshop on Multimodal Robot Learning in Physical Worlds (MRLPW)](https://internrobotics.shlab.org.cn/workshop/2025/)
- [[IROS 2025] LeaPRiDE: Learning, Planning, and Reasoning in Dynamic Environments](https://leapride.robot-learning.net/)
- [[IROS 2025] Building Safe Robots: A Holistic Integrated View on Safety from Modelling, Control & Implementation](https://building-safe-robots-workshop.github.io/)
- [[IROS 2025] Robotic Fine Manipulation: Integrating Tactile, Visual, and Intelligent Control](https://robofinemani.github.io/)
- [[IROS 2025] Intelligent Robotics: Harnessing Embodied Intelligence and Learning for Next-Generation Manipulation]()
- [[IROS 2025] Human-in-the-Loop Robot Learning in the Era of Foundation Models: Challenges and Opportunities](https://www.iit.it/web/hrii/iros2025-workshop)
- [[IROS 2025] Robot Learning From Human Teleoperation: Prospects and Challenges](https://sites.google.com/view/lfht-iros25-workshop-proposal/home)
- [[IROS 2025] 4th Sensorimotor-Augmented Teleoperation: Human-interaction-oriented Paradigm and Real-world Concerns](https://sites.google.com/view/iros-workshop-4th-sat-2025)
- [[IROS 2025] 4th Workshop on Mobile Manipulation and Embodied Intelligence: Towards Next-Gen Mobile Manipulation with Modularity, Reconfiguration, and Generalization (MOMA.v4)](https://mobile-manipulation.net/events/moma-iros25/)
- [[IROS 2025] Bimanual Manipulation: Advancing Human-Humanoid Interaction and Collaboration](https://sites.google.com/view/iros2025-ws-bi-mp)
- [[IROS 2025] Data-Enabled Learning and Control for Robotics](https://sites.google.com/view/iros-2025-learning-and-control/home)
- [[IROS 2025] SPACE- Semantic Planning of robotic Agents in Collaborative Environments](https://workshopspace.github.io/iros2025/)
- [[IROS 2025] 1st Workshop on Embodied AI and Robotics for Future Scientific Discovery](https://airobot4sci.github.io/)
- [[IROS 2025] Contact and Impact-aware Manipulation](https://cim-workshop.github.io/)
- [[IROS 2025] RoboGen: 3D World Generation for Robot Learning and Autonomous Systems](https://robogen-iros.github.io/)
- [[IROS 2025] Workshop on Generative AI for Robotics and Smart Manufacturing](https://iros-2025-ai4roboticsmanufacturing.github.io/)
- [[IROS 2025] The Future of Hybrid Mobility: Innovations in Wheeled-Legged Robots](https://www.wheeledleggedrobotics.com/)
- [[IROS 2025] The 2nd Workshop and Competition on Multi-Robot Perception and Navigation Challenges in Logistics and Inspection Tasks](https://www.panlogin.com/)
- [[IROS 2025] Human-aware Embodied AI](https://heai-iros25-workshop.github.io/)
- [[IROS 2025] 2nd Workshop on AI Meets Autonomy: Vision, Language, and Autonomous Systems](https://www.ai-meets-autonomy.com/)
- [[IROS 2025] Shared Autonomy and Sense of Agency: Balancing Control, Effort, and Experience in Human-Robot Interaction](https://sssa-teleoperation.github.io/workshop/)
- [[IROS 2025] Action and Interaction: Humans and Robots in Collaboration](https://sites.google.com/view/iros-2025-workshop-tbd/home)
- [[IROS 2025] RoDGE: Robotic Data Generation and Evaluation: Bridging Simulation and Real-World Deployment](https://rodge-iros25.github.io/)
- [[IROS 2025] Augmentative Human-Robot Interaction: From Human Augmentation to Human-Inspired Collaboration](https://sites.google.com/view/sensory-augmentation-iros2025/)
- [[IROS 2025] Advancements for Intelligent Robotics in 4D Scenes: Localization, Reconstruction, Rendering, and Generation](https://4drobotics-iros2025.github.io/)
### RSS 2024
- [[RSS 2024] 2nd Workshop on Dexterous Manipulation:Design, Perception and Control](https://dex-manipulation.github.io/rss2024)
- [[RSS 2024] Safety and Normative Behaviors in Human-Robot Interaction](https://sites.google.com/view/safe-hri/)
- [[RSS 2024] Data Generation for Robotics](https://sites.google.com/view/data-generation-for-robotics/home)
- [[RSS 2024] EARL: Embodiment-Aware Robot Learning (EARL)](https://sites.google.com/view/wearl)
- [[RSS 2024] GenAI-HRI: Generative modeling meets human-robot interaction](https://sites.google.com/view/gai-hri/home)
- [[RSS 2024] Learning for Assistive Robotics](https://sites.google.com/view/rss2024-assistive-robotics)
- [[RSS 2024] Open-Set Robot Perception in the Wild](https://open-set-robotics.github.io/)
- [[RSS 2024] Semantics for Robotics: From Environment Understanding and Reasoning to Safe Interaction](https://www.dynsyslab.org/rss24-workshop-on-semantics-for-robotics/)
- [[RSS 2024] Tutorial: Supervised Policy Learning for Real Robots](https://supervised-robot-learning.github.io/)
- [[RSS 2024] Geometric and Algebraic Structure in Robot Learning](https://sites.google.com/view/gas-rl-rss2024)
- [[RSS 2024] Social Intelligence in Humans and Robots](https://social-intelligence-human-ai.github.io/proposal.html)
- [[RSS 2024] GROUND: advancing GROup UNderstanding and robots' aDaptive behavior](https://ground-hri.github.io/workshop/)
- [[RSS 2024] Lifelong Robot Learning: Generalization, Adaptation, and Deployment with Large Models](https://sites.google.com/view/lifelong-robot-learning)
- [[RSS 2024] Navigation & Mobile Manipulation in Challenging and Cluttered Natural Environments](https://nature-bots.github.io/)
- [[RSS 2024] Robotic Tasks and How to Specify Them? — Task Specification for General-Purpose Intelligent Robots](https://sites.google.com/view/rss-taskspec)
- [[RSS 2024] Towards Safe Autonomy: Emerging Requirements, Definitions, and Methods](https://sites.google.com/view/rss2024-safe-autonomy/home)
- [[RSS 2024] Semantic Reasoning and Goal Understanding in Robotics (SemRob)](https://semrob.github.io/)
### RSS 2023
- [[RSS 2023] Learning Dexterous Manipulation](https://learn-dex-hand.github.io/rss2023/)
- [[RSS 2023] Articulate Robots: Utilizing Language for Robot Learning](https://sites.google.com/andrew.cmu.edu/rss-2023-articulate-robots/home)
- [[RSS 2023] Taking Mobile Manipulators into the Real World](https://jhavl.github.io/RealWorldManipulation/)
- [[RSS 2023] Toward Natural Motion Generation](https://toward-natural-motion-generation.github.io/rss2023/)
- [[RSS 2023] Towards Safe Autonomy: New Challenges and Trends in Robot Perception](https://sites.google.com/view/rss2023-safe-autonomy)
- [[RSS 2023] Datasets and Benchmarking Tools for Advancing and Evaluating Robotic Manufacturing](https://sites.google.com/view/rss-2023-nist-moad)
- [[RSS 2023] Interdisciplinary Exploration of Generalizable Manipulation Policy Learning: Paradigms and Debates](https://ai-workshops.github.io/interdisciplinary-exploration-of-gmpl/)
- [[RSS 2023] Robot Representations for Scene Understanding, Reasoning and Planning](https://mit-spark.github.io/robotRepresentations-RSS2023/)
- [[RSS 2023] Experiment-oriented Locomotion and Manipulation Research](https://rss-ws-2023-lm.github.io/)
- [[RSS 2023] Learning for Task and Motion Planning](https://zt-yang.github.io/rss23-l4tamp-workshop/)
- [[RSS 2023] Symmetries in Robot Learning](https://sites.google.com/view/rss23-sym)
- [[RSS 2023] Variable Impedance Learning and Control: From the Foundations to the Future Perspectives](https://sites.google.com/view/vic-ws-rss23/)


## Conferences & Journals

### Journals

#### Robotics Journals

- [Science Robotics](https://www.science.org/journal/scirobotics)
- [IEEE Transactions on Robotics (T-RO)](https://www.ieee-ras.org/publications/t-ro)
- [The International Journal of Robotics Research (IJRR)](https://journals.sagepub.com/home/ijr)
- [Journal of Field Robotics (JFR)](https://onlinelibrary.wiley.com/journal/15564967)
- [Autonomous Robots](https://www.springer.com/journal/10514)
- [IEEE Robotics and Automation Letters (RA-L)](https://www.ieee-ras.org/publications/ra-l)
- [Robotics and Autonomous Systems](https://www.sciencedirect.com/journal/robotics-and-autonomous-systems)
- [Advanced Intelligent Systems](https://onlinelibrary.wiley.com/journal/26404567)
- [Frontiers in Robotics and AI](https://www.frontiersin.org/journals/robotics-and-ai)

#### Computer Vision Journals

- [International Journal of Computer Vision (IJCV)](https://www.springer.com/journal/11263)
- [IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI)](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=34)
- [Computer Vision and Image Understanding (CVIU)](https://www.sciencedirect.com/journal/computer-vision-and-image-understanding)
- [Image and Vision Computing (IVC)](https://www.journals.elsevier.com/image-and-vision-computing)
- [Machine Vision and Applications](https://www.springer.com/journal/138)
- [Journal of Vision Research](https://www.journals.elsevier.com/vision-research)

#### Machine Learning / AI Journals

- [Journal of Machine Learning Research (JMLR)](https://www.jmlr.org/)
- [Machine Learning (Springer)](https://www.springer.com/journal/10994)
- [IEEE Transactions on Neural Networks and Learning Systems (TNNLS)](https://cis.ieee.org/publications/t-neural-networks-and-learning-systems)
- [Neural Computation (MIT Press)](https://direct.mit.edu/neco)
- [Artificial Intelligence (Elsevier)](https://www.sciencedirect.com/journal/artificial-intelligence)
- [AI Open](https://www.journals.elsevier.com/ai-open)
- [Nature Machine Intelligence](https://www.nature.com/natmachintell/)
- [Transactions of the Association for Computational Linguistics (TACL)](https://transacl.org/)
- [Foundations and Trends in Machine Learning](https://www.nowpublishers.com/Journal/MAL)

#### Interdisciplinary / Systems-Oriented Journals (CV+ML+Robotics)

- [IEEE Robotics and Automation Magazine (RAM)](https://www.ieee-ras.org/publications/ram)
- [ACM Transactions on Graphics (TOG)](https://tog.acm.org/)
- [IEEE Transactions on Image Processing (TIP)](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=83)
- [IEEE Transactions on Cybernetics](https://cis.ieee.org/publications/t-cybernetics)
- [Sensors (Robotics Section)](https://www.mdpi.com/journal/sensors/sections/robotics)

### Conferences

#### Robotics

- [Robotics: Science and Systems (RSS)](https://roboticsconference.org) 
- [IEEE International Conference on Robotics and Automation (ICRA)](https://www.ieee-ras.org/conferences-workshops/fully-sponsored/icra) 
- [IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)](https://www.ieee-ras.org/conferences-workshops/financially-co-sponsored/iros)
- [International Symposium of Robotics Research](http://ifrr.org/isrr)
- [International Symposium of Experimental Robotics](http://ifrr.org/iser)
- [Workshop on the Algorithmic Foundations of Robotics](http://ifrr.org/wafr)
- [Conference on Nonlinear Model Predictive Control](https://nmpc2024.org/)
- [ROSCon](https://roscon.ros.org/)

#### Computer Vision & Embodied Perception Conferences

- [CVPR (IEEE Conference on Computer Vision and Pattern Recognition)](https://cvpr.thecvf.com/)
- [ICCV (IEEE International Conference on Computer Vision)](https://iccv2023.thecvf.com/)
- [ECCV (European Conference on Computer Vision)](https://eccv2024.ecva.net/)

#### Machine Learning & AI

- [NeurIPS (Conference on Neural Information Processing Systems)](https://nips.cc/)
- [ICLR (International Conference on Learning Representations)](https://iclr.cc/)
- [ICML (International Conference on Machine Learning)](https://icml.cc/)
- [AAAI Conference on Artificial Intelligence](https://aaai.org/Conferences/)
- [ACL (Annual Meeting of the Association for Computational Linguistics)](https://aclweb.org/portal/)

### Seminars

- [视觉与学习青年学者研讨会（Vision And Learning SEminar, VALSE）](https://valser.org/)
- [北京智源大会（BAAI Conference）](https://www.baai.ac.cn/)
- [中国具身智能大会（China Embodied AI Conference, CEAI）](https://ceai.caai.cn/)


## Rankings

- [Roboranking: A Robotics Faculty Hub and University Ranking System](https://roboranking.org/)
- [A.I. Author Rankings by Publications](https://airankings.professor-x.de/)
- [A Normalized Professor Placement Guide to CS PhD Rankings](https://sethkarten.github.io/professor)

## Deadline
- [AI Conference Deadlines](https://aideadlin.es/)
- [CCF Recommendation Conference Deadline Countdowns](https://ccfddl.com/)

## Courses
- [CS4756 Robot Learning (Cornell)](https://www.cs.cornell.edu/courses/cs4756/2024fa/)
- [16-831 Introduction to Robot Learning (CMU)](https://16-831.github.io/spring25/)
- [16-745 Optimal Control and Reinforcement Learning (CMU)](https://optimalcontrol.ri.cmu.edu/)
- [Robotic Manipulation Perception, Planning, and Control (MIT)](https://manipulation.csail.mit.edu/index.html)
- [CS285 Deep Reinforcement Learning (UC Berkeley)](https://rail.eecs.berkeley.edu/deeprlcourse/)
- [CS 287 Advanced Robotics (UC Berkeley)](https://people.eecs.berkeley.edu/~pabbeel/cs287-fa15/)
- [CS229 Machine Learning (Stanford)](https://cs229.stanford.edu/)
- [CS391R: Robot Learning Perception, Decision Making, and General-Purpose Robot Autonomy](https://www.cs.utexas.edu/~yukez/cs391r_fall2020/index.html)
- [Model Predictive Control and Reinforcement Learning (Uni Freiburg)](https://www.syscop.de/teaching/ss2021/model-predictive-control-and-reinforcement-learning)
- [Imitation Learning for Robotics (UofT)](https://www.cs.toronto.edu/~florian/courses/imitation_learning/)

## Blog
- [IEEE Spectrum – Robotics](https://spectrum.ieee.org/topic/robotics)
- [Singularity Hub - Robotics](https://singularityhub.com/tag/robotics/)
- [NVIDIA Developer Blog – Robotics](https://developer.nvidia.com/blog/category/robotics)
- [New Atlas - Robotics](https://newatlas.com/robotics/)
- [Tech Xplore - Robotics News](https://techxplore.com/robotics-news/)
- [ScienceDaily - Robotics](https://www.sciencedaily.com/news/computers_math/robotics/)
- [Stanford AI Lab - Robotics Posts](https://ai.stanford.edu/blog/robotics/)
- [The Robot Report](https://www.therobotreport.com/)
- [TechCrunch - Robotics](https://techcrunch.com/category/robotics/)
- [MIT News - Robotics](https://news.mit.edu/topic/robotics)
- [机器之心](https://www.jiqizhixin.com/)
- [量子位](https://www.qbitai.com/)

## Insights
- [博士这五年 - 李沐](https://zhuanlan.zhihu.com/p/25099638)
- [博士第五年 - 杨硕](https://zhuanlan.zhihu.com/p/631748171)
- [The Ph.D. Grinding - Philip J. Guo](https://www.dropbox.com/scl/fi/g8mc1lniyf26opxtrqgna/pguo-PhD-grind.pdf?rlkey=mmj1sryb14hl8o4k9offkyj6u&e=1&dl=0)
- [Modest Advice - Stephen C. Stearns](https://stearnslab.yale.edu/modest-advice)
- [博士五年总结 - 田渊栋](https://yuandong-tian.com/blogs/five_year_summary_of_PhD.pdf)
- [Learning Research - Sida Peng](https://github.com/pengsida/learning_research)
- [TBD](http://www.kktim.cn/doku.php?id=graduate_handbook)
