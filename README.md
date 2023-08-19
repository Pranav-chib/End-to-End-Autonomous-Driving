
# <p align=center>`End-to-End Autonomous Driving`<br>
End-to-End autonomous driving is a promising paradigm as it
circumvents the drawbacks associated with modular systems,
such as their overwhelming complexity and propensity for error
propagation. Autonomous driving transcends conventional traffic
patterns by proactively recognizing critical events in advance,
ensuring passengers’ safety and providing them with comfortable
transportation, particularly in highly stochastic and variable
traffic settings.

</p>

<p align="center">
<img src="/Learning3_Methods.gif" width="500" height="500"/>
<p>

<hr />

# <p align=center>[Recent Advancements in End-to-End Autonomous Driving using Deep Learning: A Survey](http://arxiv.org/abs/2307.04370)
Authors: [Pranav Singh Chib](https://github.com/Pranav-chib), [Pravendra Singh](https://scholar.google.com/citations?user=YwDTxJMAAAAJ&hl=en)</p>
Modular architecture is a widely used approach in autonomous driving systems, which divides the driving pipeline into discrete sub-tasks. This architecture relies on individual sensors and algorithms to process data and generate control outputs. In contrast, the End-to-End autonomous driving approach streamlines the system, improving efficiency and robustness by directly mapping sensory input to control outputs. The benefits of End-to-End autonomous driving have garnered significant attention in the research community. 

This repo contains a curated list of resources on End-to-End Autonomous Driving, arranged chronologically. We regularly update it with the latest papers and their corresponding open-source implementations.

## Table of Contents

- [LEARNING APPROACHES](#LEARNING-APPROACHES)
- [EXPLAINABILITY](#EXPLAINABILITY)
- [EVALUATION](#EVALUATION)
- [SAFETY](#SAFETY)
- [CITATION](#Citation)

<hr />

# LEARNING APPROACHES
The following are the different learning approaches of End-to-End Driving

- [Imitation learning](#Imitation-learning)<br>
- [Behavioural cloning](#Behavioural-cloning)<br>
- [Reinforcement learning](#Reinforcement-learning)<br>
- [Multi-task learning](#Multi-task-learning)<br>
- [Knowledge Distillation](#Knowledge-Distillation)<br>
- [Other Learning](#Other-Learning)

## Imitation learning

[**Think Twice before Driving: Towards Scalable Decoders for End-to-End Autonomous Driving.**](https://arxiv.org/abs/2305.0624) [CVPR2023] <br> Xiaosong Jia, Penghao Wu, Li Chen, Jiangwei Xie, Conghui He, Junchi Yan, Hongyang Li <br>
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/OpenDriveLab/ThinkTwice)


[**Policy Pre-training for Autonomous Driving via Self-supervised Geometric Modeling**](https://openreview.net/forum?id=X5SUR7g2vVw)
[ICLR2023] <br> Penghao Wu, Li Chen, Hongyang Li, Xiaosong Jia, Junchi Yan, Yu Qiao <br>

[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/OpenDriveLab/PPGeo)

[**Hidden Biases of End-to-End Driving Models**](https://arxiv.org/abs/2306.07957) 
[ICCV2023] <br> Bernhard Jaeger, Kashyap Chitta, Andreas Geiger<br>
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/autonomousvision/carla_garage)

[**Scaling Vision-based End-to-End Autonomous Driving with Multi-View Attention Learning**](https://arxiv.org/abs/2302.03198)
[IROS 2023] <br> Yi Xiao, Felipe Codevilla, Diego Porres, Antonio M. Lopez<br>

[**Learning from All Vehicles**](http://arxiv.org/pdf/1709.04622v4)
[CVPR2022] <br> Dian Chen, Philipp Krähenbühl <br>
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/dotchen/LAV.git)

[**PlanT: Explainable Planning Transformers via Object-Level Representations**](https://arxiv.org/abs/2210.14222)
[CoRL2022] <br> Katrin Renz, Kashyap Chitta, Otniel-Bogdan Mercea, A. Sophia Koepke, Zeynep Akata, Andreas Geiger<br>
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/autonomousvision/plant)


[**Multi-Modal Fusion Transformer for End-to-End Autonomous Driving**](https://arxiv.org/abs/2104.09224)
[CVPR2021] <br> Aditya Prakash, Kashyap Chitta, Andreas Geiger<br>
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/autonomousvision/transfuser.git)

[**Learning by Watching**](https://arxiv.org/abs/2106.05966)
[CVPR2021] <br> Jimuyang Zhang, Eshed Ohn-Bar <br>

[**End-to-End Urban Driving by Imitating a Reinforcement Learning Coach**](https://arxiv.org/abs/2108.08265)
[ICCV2021] <br> Zhejun Zhang, Alexander Liniger, Dengxin Dai, Fisher Yu, Luc Van Gool <br>
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/zhejz/carla-roach.git)

[**Learning by Cheating**](http://arxiv.org/pdf/2107.00123v1)
[CoRL2020] <br> Dian Chen, Brady Zhou, Vladlen Koltun, Philipp Krähenbühl <br> 
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/dotchen/LearningByCheating.git)

[**SAM: Squeeze-and-Mimic Networks for Conditional Visual Driving Policy Learning**](https://arxiv.org/abs/1912.02973)
[[CoRL2020]] <br> Albert Zhao, Tong He, Yitao Liang, Haibin Huang, Guy Van den Broeck, Stefano Soatto <br>
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/twsq/sam-driving.git)

[**Urban Driving with Conditional Imitation Learning**](http://arxiv.org/pdf/1912.00177v2)
[ICRA2020] <br> Jeffrey Hawke, Richard Shen, Corina Gurau, Siddharth Sharma, Daniele Reda, Nikolay Nikolov, Przemyslaw Mazur, Sean Micklethwaite, Nicolas Griffiths, Amar Shah, Alex Kendall <br> 


[**Multimodal End-to-End Autonomous Driving**](https://ieeexplore.ieee.org/abstract/document/9165167) 
[TITS2020] <br> Yi Xiao, Felipe Codevilla, Akhil Gurram, Onay Urfalioglu, Antonio M. López <br>

[**Learning to Drive from Simulation without Real World Labels**](https://arxiv.org/abs/1812.03823)
[ICRA2019] <br> Alex Bewley, Jessica Rigley, Yuxuan Liu, Jeffrey Hawke, Richard Shen, Vinh-Dieu Lam, Alex Kendall <br>



## Behavioural cloning

 [**TransFuser: Imitation with Transformer-Based Sensor Fusion for Autonomous Driving**](https://arxiv.org/abs/2205.15997)
 [TPAMI2022] <br> Kashyap Chitta, Aditya Prakash, Bernhard Jaeger, Zehao Yu, Katrin Renz, Andreas Geiger<br>
 [![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/autonomousvision/transfuser.git)

[**Trajectory-guided Control Prediction for End-to-end Autonomous Driving: A Simple yet Strong Baseline**](https://arxiv.org/abs/2206.08129) 
[NeurIPS2022] <br>Penghao Wu, Xiaosong Jia, Li Chen, Junchi Yan, Hongyang Li, Yu Qiao<br>
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/OpenDriveLab/TCP)


[**KING: Generating Safety-Critical Driving Scenarios for Robust Imitation via Kinematics Gradients**](https://arxiv.org/abs/2204.13683)
[ECCV2022] <br> Niklas Hanselmann, Katrin Renz, Kashyap Chitta, Apratim Bhattacharyya, Andreas Geiger <br>
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/autonomousvision/transfuser.git)


[**Learning to Drive by Watching YouTube Videos: Action-Conditioned Contrastive Policy Pretraining**](https://arxiv.org/abs/2204.02393) [ECCV2022] <br> Qihang Zhang, Zhenghao Peng, Bolei Zhou <br>
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/metadriverse/ACO)

[**NEAT: Neural Attention Fields for End-to-End Autonomous Driving**](https://arxiv.org/abs/2109.04456)
[ICCV2021] <br> Kashyap Chitta, Aditya Prakash, Andreas Geiger <br>
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/autonomousvision/neat.git)

[**Learning Situational Driving**](http://arxiv.org/pdf/1811.07868v2) 
[CVPR2020] <br> Eshed Ohn-Bar, Aditya Prakash, Aseem Behl, Kashyap Chitta, Andreas Geiger <br>

[**Exploring the Limitations of Behavior Cloning for Autonomous Driving**](https://arxiv.org/abs/1904.08980) 
[ICCV2019] <br> Felipe Codevilla, Eder Santana, Antonio M. López, Adrien Gaidon <br>
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/felipecode/coiltraine.git)

## Reinforcement learning

[**Efficient Learning of Safe Driving Policy via Human-AI Copilot Optimization**](https://arxiv.org/abs/2202.10341#:~:text=HACO%20can%20train%20agents%20to,baselines%20with%20a%20large%20margin.)
[ICLR2022] <br> Quanyi Li, Zhenghao Peng, Bolei Zhou <br>
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/decisionforce/HACO)

[**End-to-End Urban Driving by Imitating a Reinforcement Learning Coach**](https://arxiv.org/abs/2108.08265)
[ICCV2021] <br> Zhejun Zhang, Alexander Liniger, Dengxin Dai, Fisher Yu, Luc Van Gool <br>
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/zhejz/carla-roach.git)
    
[**Learning To Drive From a World on Rails**](http://arxiv.org/pdf/2105.00636v3)
[ICCV2021]<br> Dian Chen, Vladlen Koltun, Philipp Krähenbühl <br>
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/dotchen/WorldOnRails.git)

[**End-to-End Model-Free Reinforcement Learning for Urban Driving Using Implicit Affordances**](https://openaccess.thecvf.com/content_CVPR_2020/html/Toromanoff_End-to-End_Model-Free_Reinforcement_Learning_for_Urban_Driving_Using_Implicit_Affordances_CVPR_2020_paper.html)
[CVPR2020] <br> Marin Toromanoff, Emilie Wirbel, Fabien Moutarde<br>

[**Learning to drive in a day**](https://arxiv.org/abs/1807.00412) 
[ICRA2019] <br> Alex Kendall, Jeffrey Hawke, David Janz, Przemyslaw Mazur, Daniele Reda, John-Mark Allen, Vinh-Dieu Lam, Alex Bewley, Amar Shah<br>
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/r7vme/learning-to-drive-in-a-day)

## Multi-task learning

[**Planning-oriented Autonomous Driving**](https://arxiv.org/abs/2212.10156) :trophy:Best Paper
[CVPR2023]  <br> Yihan Hu, Jiazhi Yang, Li Chen, Keyu Li, Chonghao Sima, Xizhou Zhu, Siqi Chai, Senyao Du, Tianwei Lin, Wenhai Wang, Lewei Lu, Xiaosong Jia, Qiang Liu, Jifeng Dai, Yu Qiao, Hongyang Li <br>
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/OpenDriveLab/UniAD)

[**ReasonNet: End-to-End Driving with Temporal and Global Reasoning**](https://arxiv.org/abs/2305.10507)
[CVPR2023] <br> Hao Shao, Letian Wang, Ruobing Chen, Steven L. Waslander, Hongsheng Li, Yu Liu<br>

[**Coaching a Teachable Student**](https://openaccess.thecvf.com/content/CVPR2023/html/Zhang_Coaching_a_Teachable_Student_CVPR_2023_paper.html)
[CVPR2023] <br> Jimuyang Zhang, Zanming Huang, Eshed Ohn-Bar <br>

[**Think Twice before Driving: Towards Scalable Decoders for End-to-End Autonomous Driving.**](https://arxiv.org/abs/2305.0624) [CVPR2023] <br> Xiaosong Jia, Penghao Wu, Li Chen, Jiangwei Xie, Conghui He, Junchi Yan, Hongyang Li <br>
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/OpenDriveLab/ThinkTwice)

[**Safety-Enhanced Autonomous Driving Using Interpretable Sensor Fusion Transformer**](https://arxiv.org/abs/2207.14024)
[CoRL2022] <br> Hao Shao, Letian Wang, RuoBing Chen, Hongsheng Li, Yu Liu<br>
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/opendilab/InterFuser)

[**SAM: Squeeze-and-Mimic Networks for Conditional Visual Driving Policy Learning**](https://arxiv.org/abs/1912.02973)
[[CoRL2020]] <br> Albert Zhao, Tong He, Yitao Liang, Haibin Huang, Guy Van den Broeck, Stefano Soatto <br>
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/twsq/sam-driving.git)

[**Urban Driving with Conditional Imitation Learning**](http://arxiv.org/pdf/1912.00177v2)
[ICRA2020] <br> Jeffrey Hawke, Richard Shen, Corina Gurau, Siddharth Sharma, Daniele Reda, Nikolay Nikolov, Przemyslaw Mazur, Sean Micklethwaite, Nicolas Griffiths, Amar Shah, Alex Kendall <br> 

## Knowledge Distillation

[**Learning from All Vehicles**](http://arxiv.org/pdf/1709.04622v4)
[CVPR2022] <br> Dian Chen, Philipp Krähenbühl <br>
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/dotchen/LAV.git)

[**End-to-End Urban Driving by Imitating a Reinforcement Learning Coach**](https://arxiv.org/abs/2108.08265)
[ICCV2021] <br> Zhejun Zhang, Alexander Liniger, Dengxin Dai, Fisher Yu, Luc Van Gool <br>
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/zhejz/carla-roach.git)

[**Learning To Drive From a World on Rails**](http://arxiv.org/pdf/2105.00636v3)
[ICCV2021]<br> Dian Chen, Vladlen Koltun, Philipp Krähenbühl <br>
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/dotchen/WorldOnRails.git)

[**Learning by Cheating**](http://arxiv.org/pdf/2107.00123v1)
[CoRL2020] <br> Dian Chen, Brady Zhou, Vladlen Koltun, Philipp Krähenbühl <br> 
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/dotchen/LearningByCheating.git)

[**SAM: Squeeze-and-Mimic Networks for Conditional Visual Driving Policy Learning**](https://arxiv.org/abs/1912.02973)
[[CoRL2020]] <br> Albert Zhao, Tong He, Yitao Liang, Haibin Huang, Guy Van den Broeck, Stefano Soatto <br>
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/twsq/sam-driving.git)

 ## Other Learning

[**ST-P3: End-to-end Vision-based Autonomous Driving via Spatial-Temporal Feature Learning**](https://arxiv.org/abs/2207.07601)
[ECCV2022] <br> Shengchao Hu, Li Chen, Penghao Wu, Hongyang Li, Junchi Yan, Dacheng Tao<br>
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/OpenDriveLab/ST-P3)

[🔼 Back to top](#Table-of-Contents)
<hr />
 
# EXPLAINABILITY
- [Post-hoc saliency methods]()

- [Counterfactual explanation]()


## Post-hoc saliency methods

## Attention

[**Planning-oriented Autonomous Driving**](https://arxiv.org/abs/2212.10156) :trophy:Best Paper
[CVPR2023]  <br> Yihan Hu, Jiazhi Yang, Li Chen, Keyu Li, Chonghao Sima, Xizhou Zhu, Siqi Chai, Senyao Du, Tianwei Lin, Wenhai Wang, Lewei Lu, Xiaosong Jia, Qiang Liu, Jifeng Dai, Yu Qiao, Hongyang Li <br>
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/OpenDriveLab/UniAD)

[**Policy Pre-training for Autonomous Driving via Self-supervised Geometric Modeling**](https://openreview.net/forum?id=X5SUR7g2vVw)
[ICLR2023] <br> Penghao Wu, Li Chen, Hongyang Li, Xiaosong Jia, Junchi Yan, Yu Qiao <br>

[**Scaling Vision-based End-to-End Autonomous Driving with Multi-View Attention Learning**](https://arxiv.org/abs/2302.03198)
[IROS 2023] <br> Yi Xiao, Felipe Codevilla, Diego Porres, Antonio M. Lopez<br>

 [**TransFuser: Imitation with Transformer-Based Sensor Fusion for Autonomous Driving**](https://arxiv.org/abs/2205.15997)
 [TPAMI2022] <br> Kashyap Chitta, Aditya Prakash, Bernhard Jaeger, Zehao Yu, Katrin Renz, Andreas Geiger<br>
 [![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/autonomousvision/transfuser.git)

[**PlanT: Explainable Planning Transformers via Object-Level Representations**](https://arxiv.org/abs/2210.14222)
[CoRL2022] <br> Katrin Renz, Kashyap Chitta, Otniel-Bogdan Mercea, A. Sophia Koepke, Zeynep Akata, Andreas Geiger<br>
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/autonomousvision/plant)

[**Multi-Modal Fusion Transformer for End-to-End Autonomous Driving**](https://arxiv.org/abs/2104.09224)
[CVPR2021] <br> Aditya Prakash, Kashyap Chitta, Andreas Geiger<br>
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/autonomousvision/transfuser.git)

[**NEAT: Neural Attention Fields for End-to-End Autonomous Driving**](https://arxiv.org/abs/2109.04456)
[ICCV2021] <br> Kashyap Chitta, Aditya Prakash, Andreas Geiger <br>
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/autonomousvision/neat.git)
 
## Semantic representation and Auxiliary output

[**Learning from All Vehicles**](http://arxiv.org/pdf/1709.04622v4)
[CVPR2022] <br> Dian Chen, Philipp Krähenbühl <br>
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/dotchen/LAV.git)

 [**TransFuser: Imitation with Transformer-Based Sensor Fusion for Autonomous Driving**](https://arxiv.org/abs/2205.15997)
 [TPAMI2022] <br> Kashyap Chitta, Aditya Prakash, Bernhard Jaeger, Zehao Yu, Katrin Renz, Andreas Geiger<br>
 [![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/autonomousvision/transfuser.git)

[**ST-P3: End-to-end Vision-based Autonomous Driving via Spatial-Temporal Feature Learning**](https://arxiv.org/abs/2207.07601)
[ECCV2022] <br> Shengchao Hu, Li Chen, Penghao Wu, Hongyang Li, Junchi Yan, Dacheng Tao<br>
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/OpenDriveLab/ST-P3)




## Counterfactual explanation


## Attention 

[**Planning-oriented Autonomous Driving**](https://arxiv.org/abs/2212.10156) :trophy:Best Paper
[CVPR2023]  <br> Yihan Hu, Jiazhi Yang, Li Chen, Keyu Li, Chonghao Sima, Xizhou Zhu, Siqi Chai, Senyao Du, Tianwei Lin, Wenhai Wang, Lewei Lu, Xiaosong Jia, Qiang Liu, Jifeng Dai, Yu Qiao, Hongyang Li <br>
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/OpenDriveLab/UniAD)


[**Safety-Enhanced Autonomous Driving Using Interpretable Sensor Fusion Transformer**](https://arxiv.org/abs/2207.14024)
[CoRL2022] <br> Hao Shao, Letian Wang, RuoBing Chen, Hongsheng Li, Yu Liu<br>
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/opendilab/InterFuser)

[**PlanT: Explainable Planning Transformers via Object-Level Representations**](https://arxiv.org/abs/2210.14222)
[CoRL2022] <br> Katrin Renz, Kashyap Chitta, Otniel-Bogdan Mercea, A. Sophia Koepke, Zeynep Akata, Andreas Geiger<br>
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/autonomousvision/plant)

[**NEAT: Neural Attention Fields for End-to-End Autonomous Driving**](https://arxiv.org/abs/2109.04456)
[ICCV2021] <br> Kashyap Chitta, Aditya Prakash, Andreas Geiger <br>
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/autonomousvision/neat.git)

## Semantic representation and Auxiliary output

 
[**Hidden Biases of End-to-End Driving Models**](https://arxiv.org/abs/2306.07957) 
[arXiv2023] <br> Bernhard Jaeger, Kashyap Chitta, Andreas Geiger<br>
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/autonomousvision/carla_garage)
 
 [**TransFuser: Imitation with Transformer-Based Sensor Fusion for Autonomous Driving**](https://arxiv.org/abs/2205.15997)
 [TPAMI2022] <br> Kashyap Chitta, Aditya Prakash, Bernhard Jaeger, Zehao Yu, Katrin Renz, Andreas Geiger<br>
 [![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/autonomousvision/transfuser.git)

 [**Safety-Enhanced Autonomous Driving Using Interpretable Sensor Fusion Transformer**](https://arxiv.org/abs/2207.14024)
[CoRL2022] <br> Hao Shao, Letian Wang, RuoBing Chen, Hongsheng Li, Yu Liu<br>
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/opendilab/InterFuser)

[**Learning Situational Driving**](http://arxiv.org/pdf/1811.07868v2) 
[CVPR2020] <br> Eshed Ohn-Bar, Aditya Prakash, Aseem Behl, Kashyap Chitta, Andreas Geiger <br>



[🔼 Back to top](#Table-of-Contents)
<hr />

# EVALUATION


## Open Loop

- [**nuScenes**](https://www.nuscenes.org/nuscenes) 

- [**KITTI**](https://www.cvlibs.net/datasets/kitti/)

- [**Argoverse 1 & 2**](https://www.argoverse.org/av2.html)


## Close Loop

- [**CARLA**](https://leaderboard.carla.org/)
  
- [**nuPlan**](https://www.nuscenes.org/nuplan?externalData=all&mapData=all&modalities=Any)

<hr />

##  <p align=center>[**CARLA LEADERBOARD 1.0 UNTIL AUGUST 2023**](https://leaderboard.carla.org/)

| Rank  |                     Submission                    |   DS  |   RC  |   IP  |       CP       |  CV  |   CL  |  RLI  |  SSI |   OI  |  RD  |    AB    |  Type (E/M) |
|:-----:|:-------------------------------------------------:|:-----:|:-----:|:-----:|:--------------:|:----:|:-----:|:-----:|:----:|:-----:|:----:|:--------:|:-----------:|
|       |                                                   |   \%  |   \%  | [0,1] | infractions/km |      |       |       |      |       |      |          | End/Modular |
|   1   |        [**ReasonNet: End-to-End Driving with Temporal and Global Reasoning**](https://arxiv.org/abs/2305.10507)       | 79.95 | 89.89 |  0.89 |      0.02      | 0.13 |  0.01 |  0.08 | 0.00 |  0.04 | 0.00 |   0.33   |      E      |
|   2   |         [**Safety-Enhanced Autonomous Driving Using Interpretable Sensor Fusion Transformer**](https://arxiv.org/abs/2207.14024)       | 76.18 | 88.23 |  0.84 |      0.04      | 0.37 |  0.14 |  0.22 | 0.00 |  0.13 | 0.00 |   0.43   |      E      |
|   3   |          [**Trajectory-guided Control Prediction for End-to-end Autonomous Driving: A Simple yet Strong Baseline**](https://arxiv.org/abs/2206.08129)        | 75.14 | 85.63 |  0.87 |      0.00      | 0.32 |  0.00 |  0.09 | 0.00 |  0.04 | 0.00 |   0.54   |      E      |
|   4   |                       [**Hidden Biases of End-to-End Driving Models**](https://arxiv.org/abs/2306.07957)                         | 66.32 | 78.57 |  0.84 |      0.00      | 0.50 |  0.00 |  0.01 | 0.00 |  0.12 | 0.00 |   0.71   |      E      |
|   5   |         [**Learning from All Vehicles**](http://arxiv.org/pdf/1709.04622v4)       | 61.85 | 94.46 |  0.64 |      0.04      | 0.70 |  0.02 |  0.17 | 0.00 |  0.25 | 0.09 |   0.10   |      E      |
|   6   |      [**TransFuser: Imitation with Transformer-Based Sensor Fusion for Autonomous Driving**](https://arxiv.org/abs/2205.15997)   | 61.18 | 86.69 |  0.71 |      0.04      | 0.81 |  0.01 |  0.05 | 0.00 |  0.23 | 0.00 |   0.43   |      E      |
|   7   | [**Latent TransFuser**](https://arxiv.org/abs/2205.15997)| 45.20 | 66.31 |  0.72 |      0.02      | 1.11 |  0.02 |  0.05 | 0.00 |  0.16 | 0.00 |   1.82   |      E      |
|   8   |          [**GRIAD**](https://arxiv.org/abs/2111.08575)         | 36.79 | 61.85 |  0.60 |      0.00      | 2.77 |  0.41 |  0.48 | 0.00 |  1.39 | 1.11 |   0.84   |      E      |
|   9   |    [**TransFuser+**](https://arxiv.org/abs/2205.15997)    | 34.58 | 69.84 |  0.56 |      0.04      | 0.70 |  0.03 |  0.75 | 0.00 |  0.18 | 0.00 |   2.41   |      E      |
|   10   |   [**Learning To Drive From a World on Rails**](http://arxiv.org/pdf/2105.00636v3)  | 31.37 | 57.65 |  0.56 |      0.61      | 1.35 |  1.02 |  0.79 | 0.00 |  0.96 | 1.69 |   0.47   |      E      |
|  11   |         [**End-to-End Model-Free Reinforcement Learning for Urban Driving Using Implicit Affordances**](https://openaccess.thecvf.com/content_CVPR_2020/html/Toromanoff_End-to-End_Model-Free_Reinforcement_Learning_for_Urban_Driving_Using_Implicit_Affordances_CVPR_2020_paper.html)        | 24.98 | 46.97 |  0.52 |      0.00      | 2.33 |  2.47 |  0.55 | 0.00 |  1.82 | 1.44 |   0.94   |      E      |
|   12  |          [**NEAT: Neural Attention Fields for End-to-End Autonomous Driving**](https://arxiv.org/abs/2109.04456)          | 21.83 | 41.71 |  0.65 |      0.04      | 0.74 |  0.62 |  0.70 | 0.00 |  2.68 | 0.00 |   5.22   |      E      |


# SAFETY

- [Training on Critical Scenarios](#Training-on-Critical-Scenarios)
- [Safety Constraints Integration](#Safety-Constraints-Integration)
- [Additional Safety Modules](#Additional-Safety-Modules)

##  Training on Critical Scenarios 
unprotected turnings at intersections, pedestrians emerging from occluded regions, aggressive lane-changing, and other safety heuristics.

[**KING: Generating Safety-Critical Driving Scenarios for Robust Imitation via Kinematics Gradients**](https://arxiv.org/abs/2204.13683)
[ECCV2022] <br> Niklas Hanselmann, Katrin Renz, Kashyap Chitta, Apratim Bhattacharyya, Andreas Geiger <br>
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/autonomousvision/transfuser.git)

[**Learning from All Vehicles**](http://arxiv.org/pdf/1709.04622v4)
[CVPR2022] <br> Dian Chen, Philipp Krähenbühl <br>
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/dotchen/LAV.git)

[**Multi-Modal Fusion Transformer for End-to-End Autonomous Driving**](https://arxiv.org/abs/2104.09224)
[CVPR2021] <br> Aditya Prakash, Kashyap Chitta, Andreas Geiger<br>
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/autonomousvision/transfuser.git)


## Safety Constraints Integration 
safety cost function, avoiding unsafe maneuvers and collision avoidance strategies.


[**Think Twice before Driving: Towards Scalable Decoders for End-to-End Autonomous Driving.**](https://arxiv.org/abs/2305.0624) [CVPR2023] <br> Xiaosong Jia, Penghao Wu, Li Chen, Jiangwei Xie, Conghui He, Junchi Yan, Hongyang Li <br>
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/OpenDriveLab/ThinkTwice)


[**Policy Pre-training for Autonomous Driving via Self-supervised Geometric Modeling**](https://openreview.net/forum?id=X5SUR7g2vVw)
[ICLR2023] <br> Penghao Wu, Li Chen, Hongyang Li, Xiaosong Jia, Junchi Yan, Yu Qiao <br>

 [**TransFuser: Imitation with Transformer-Based Sensor Fusion for Autonomous Driving**](https://arxiv.org/abs/2205.15997)
 [TPAMI2022] <br> Kashyap Chitta, Aditya Prakash, Bernhard Jaeger, Zehao Yu, Katrin Renz, Andreas Geiger<br>
 [![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/autonomousvision/transfuser.git)


[**Efficient Learning of Safe Driving Policy via Human-AI Copilot Optimization**](https://arxiv.org/abs/2202.10341#:~:text=HACO%20can%20train%20agents%20to,baselines%20with%20a%20large%20margin.)
[ICLR2022] <br> Quanyi Li, Zhenghao Peng, Bolei Zhou <br>
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/decisionforce/HACO)

[**Safety-Enhanced Autonomous Driving Using Interpretable Sensor Fusion Transformer**](https://arxiv.org/abs/2207.14024)
[CoRL2022] <br> Hao Shao, Letian Wang, RuoBing Chen, Hongsheng Li, Yu Liu<br>
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/opendilab/InterFuser)

[**ST-P3: End-to-end Vision-based Autonomous Driving via Spatial-Temporal Feature Learning**](https://arxiv.org/abs/2207.07601)
[ECCV2022] <br> Shengchao Hu, Li Chen, Penghao Wu, Hongyang Li, Junchi Yan, Dacheng Tao<br>
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/OpenDriveLab/ST-P3)

[**Learning To Drive From a World on Rails**](http://arxiv.org/pdf/2105.00636v3)
[ICCV2021]<br> Dian Chen, Vladlen Koltun, Philipp Krähenbühl <br>
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/dotchen/WorldOnRails.git)

[**SAM: Squeeze-and-Mimic Networks for Conditional Visual Driving Policy Learning**](https://arxiv.org/abs/1912.02973)
[[CoRL2020]] <br> Albert Zhao, Tong He, Yitao Liang, Haibin Huang, Guy Van den Broeck, Stefano Soatto <br>
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/twsq/sam-driving.git)

## Additional Safety Modules 
Preventing deviations from safe operation.

[**Planning-oriented Autonomous Driving**](https://arxiv.org/abs/2212.10156) :trophy:Best Paper
[CVPR2023]  <br> Yihan Hu, Jiazhi Yang, Li Chen, Keyu Li, Chonghao Sima, Xizhou Zhu, Siqi Chai, Senyao Du, Tianwei Lin, Wenhai Wang, Lewei Lu, Xiaosong Jia, Qiang Liu, Jifeng Dai, Yu Qiao, Hongyang Li <br>
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/OpenDriveLab/UniAD)

[**PlanT: Explainable Planning Transformers via Object-Level Representations**](https://arxiv.org/abs/2210.14222)
[CoRL2022] <br> Katrin Renz, Kashyap Chitta, Otniel-Bogdan Mercea, A. Sophia Koepke, Zeynep Akata, Andreas Geiger<br>
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/autonomousvision/plant)

[**Trajectory-guided Control Prediction for End-to-end Autonomous Driving: A Simple yet Strong Baseline**](https://arxiv.org/abs/2206.08129) 
[NeurIPS2022] <br>Penghao Wu, Xiaosong Jia, Li Chen, Junchi Yan, Hongyang Li, Yu Qiao<br>
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/OpenDriveLab/TCP)



<hr />

# Citation

If you find the listing and survey useful for your work, please cite the paper:

```

@article{chib2023recent,
    title={Recent Advancements in End-to-End Autonomous Driving using Deep Learning: A Survey},
    author={Pranav Singh Chib and Pravendra Singh},
    year={2023},
    eprint={2307.04370},
    archivePrefix={arXiv},
    primaryClass={cs.RO}
}

```
[🔼 Back to top](#Table-of-Contents)
