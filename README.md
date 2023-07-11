
# <p align=center> This repository supplements our survey on <br> [End-to-End Autonomous Driving](http://arxiv.org/abs/2307.04370).
End-to-End autonomous driving is a promising paradigm as it
circumvents the drawbacks associated with modular systems,
such as their overwhelming complexity and propensity for error
propagation. Autonomous driving transcends conventional traffic
patterns by proactively recognizing critical events in advance,
ensuring passengers’ safety and providing them with comfortable
transportation, particularly in highly stochastic and variable
traffic settings.

Authors: [Pranav Singh Chib](https://github.com/Pranav-chib), [Pravendra Singh](https://scholar.google.com/citations?user=YwDTxJMAAAAJ&hl=en)
</p>

<p align="center">
<img src="/Learning3_Methods.gif" width="500" height="500"/>
<p>

<hr />

# <p align=center>`Recent Advancements in End-to-End Autonomous Driving using Deep Learning: A Survey`</p>
Modular architecture is a widely used approach in autonomous driving systems, which divides the driving pipeline into discrete sub-tasks. This architecture relies on individual sensors and algorithms to process data and generate control outputs. In contrast, the End-to-End autonomous driving approach streamlines the system, improving efficiency and robustness by directly mapping sensory input to control outputs. The benefits of End-to-End autonomous driving have garnered significant attention in the research community. 

This repo contains a curated list of resources on End-to-End Autonomous Driving, arranged chronologically. We regularly update it with the latest papers and their corresponding open-source implementations.



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
[arXiv2023] <br> Bernhard Jaeger, Kashyap Chitta, Andreas Geiger<br>
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/autonomousvision/carla_garage)

[**Scaling Self-Supervised End-to-End Driving with Multi-View Attention Learning**](https://arxiv.org/abs/2302.03198)
[arxiv2023] <br> Yi Xiao, Felipe Codevilla, Diego Porres, Antonio M. Lopez<br>

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




<hr />

# Citation

If you find the listing and survey useful for your work, please cite the paper:

```
@misc{chib2023recent,
    title={Recent Advancements in End-to-End Autonomous Driving using Deep Learning: A Survey},
    author={Pranav Singh Chib and Pravendra Singh},
    year={2023},
    eprint={2307.04370},
    archivePrefix={arXiv},
    primaryClass={cs.RO}
}

```
