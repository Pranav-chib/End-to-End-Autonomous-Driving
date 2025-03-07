
# <p align=center>`End-to-End Autonomous Driving`<br>
end-to-end autonomous driving is a promising paradigm as it
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

# <p align=center>Recent Advancements in End-to-End Autonomous Driving using Deep Learning: A Survey <a href="https://medium.com/@pranavs_chib/end-to-end-autonomous-driving-using-deep-learning-8a94ecb3bb6b">
  <a href="https://medium.com/@pranavs_chib/end-to-end-autonomous-driving-using-deep-learning-8a94ecb3bb6b"> <img align="left" alt="JJ's Medium" src="https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white" />
</a>
<a href="https://ieeexplore.ieee.org/document/10258330">	![IEEE](https://a11ybadges.com/badge?logo=ieee) 
</a>
<a href="http://arxiv.org/abs/2307.04370">
  <img align="left" alt="JJ's Medium" src="https://img.shields.io/badge/arXiv-2307.04370-b31b1b.svg" />
</a>

Authors: [Pranav Singh Chib](https://github.com/Pranav-chib), [Pravendra Singh](https://scholar.google.com/citations?user=YwDTxJMAAAAJ&hl=en)</p>
Modular architecture is a widely used approach in autonomous driving systems, which divides the driving pipeline into discrete sub-tasks. This architecture relies on individual sensors and algorithms to process data and generate control outputs. In contrast, the End-to-End autonomous driving approach streamlines the system, improving efficiency and robustness by directly mapping sensory input to control outputs. The benefits of End-to-End autonomous driving have garnered significant attention in the research community. 

This repo contains a curated list of resources on End-to-End Autonomous Driving, arranged chronologically. We regularly update it with the latest papers and their corresponding open-source implementations.

## Table of Contents

- [LEARNING APPROACHES](#LEARNING-APPROACHES)
- [EXPLAINABILITY](#EXPLAINABILITY)
- [EVALUATION](#EVALUATION)
- [SAFETY](#SAFETY)
- [LARGE LANGUAGE MODELS IN AUTONOMOUS DRIVING](#Large-Language-Models-in-autonomous-driving)
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

# Large Language Models in autonomous driving
<center>
The following repository contain a curated list of resources on 3D LLM-based autonomous driving research papers with their corresponding open-source implementations.
  
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Pranav-chib/3D-LLM-Autonomous-Driving)



1. [2D LLM driving Agents](#2D-LLM-Driving-Agents)
2. [3D Perception based LLM driving Agents](#3D-Perception-based-LLM-Driving-Agents)

<hr />

# 2D LLM driving Agents

[**Mtd-gpt: A multi-task
decision-making gpt model for autonomous driving at unsignalized in-
tersections**](https://arxiv.org/abs/2307.16118) [ITSC-2023]<br> Jiaqi Liu, Peng Hang, Xiao Qi, Jianqiang Wang, Jian Sun <br>

- LLM Arch: [GPT 2](https://huggingface.co/openai-community/gpt2)

- Task: Perception, Planning, Decision Making

- Metrics: RLHF, GPT Score

- Datasets: [Expert Dataset](https://github.com/Farama-Foundation/HighwayEnv)


[**GPT-Driver: Learning to Drive with GPT**](https://arxiv.org/abs/2307.16118) [NeurIPS-2023 Workshop]<br> Jiageng Mao, Yuxi Qian, Junjie Ye, Hang Zhao, Yue Wang <br>
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/PointsCoder/GPT-Driver)


- LLM Arch: [GPT-3.5](https://platform.openai.com/docs/models)

- Task: Planning 

- Metrics: Avg. L2 and Collision Rate

- Datasets: [nuScenes](https://www.nuscenes.org/nuscenes)


[**Drivegpt4: Interpretable end-to-end autonomous driving via
large language mode**](https://arxiv.org/abs/2310.01412) [RAL-2024]<br> Zhenhua Xu, Yujia Zhang, Enze Xie, Zhen Zhao, Yong Guo, Kwan-Yee. K. Wong, Zhenguo Li, Hengshuang Zhao <br>
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://drive.google.com/drive/folders/1PsGL7ZxMMz1ZPDS5dZSjzjfPjuPHxVL5?usp=sharing) 

- LLM Arch: [Llama 2](https://www.llama.com/llama2/), [CLIP](https://github.com/openai/CLIP)

- Task: Planning, Control

- Metrics: BLEU4, METEOR, ChatGPT score, RMSE, CIDEr

- Datasets: [BDD-X](https://github.com/JinkyuKimUCB/BDD-X-dataset)



[**Drive as You Speak: Enabling Human-Like Interaction with Large Language Models in Autonomous Vehicles**](https://openaccess.thecvf.com/content/WACV2024W/LLVM-AD/papers/Cui_Drive_As_You_Speak_Enabling_Human-Like_Interaction_With_Large_Language_WACVW_2024_paper.pdf) [WACV-2024 Workshop]<br> Can Cui, Yunsheng Ma, Xu Cao, Wenqian Ye, Ziran Wang <br>

- LLM Arch: [GPT4](https://platform.openai.com/docs/models)

- Task: Motion Planning
  
- Metrics: GPT Score



[**Drive Like a Human: Rethinking Autonomous Driving with Large Language Models**](https://arxiv.org/abs/2307.07162) [WACV-2024 Workshop]<br> Daocheng Fu, Xin Li, Licheng Wen, Min Dou, Pinlong Cai, Botian Shi, Yu Qiao <br>
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/PJLab-ADG/DriveLikeAHuman) 

- LLM Arch: [GPT-3.5](https://platform.openai.com/docs/models)
  
- Task: Planning, Control

- Datasets: [HighwayEnv](https://github.com/Farama-Foundation/HighwayEnv)


[**Driving with LLMs: Fusing Object-Level Vector Modality for Explainable Autonomous Driving**](https://browse.arxiv.org/abs/2310.01957) [ICRA-2024]  <br>Long Chen, Oleg Sinavski, Jan Hünermann, Alice Karnsund, Andrew James Willmott, Danny Birch, Daniel Maund, Jamie Shotton <br>
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/wayveai/Driving-with-LLMs/tree/main/data)

- LLM Arch: [GPT-3.5](https://platform.openai.com/docs/models)
  
- Task: Perception, Planning
  
- Metrics: MAE, GPT Grading

- Datasets: [Driving QA](https://github.com/wayveai/Driving-with-LLMs/tree/main/data)




[**LANGUAGEMPC: LARGE LANGUAGE MODELS AS DECISION MAKERS FOR AUTONOMOUS DRIVING**](https://arxiv.org/pdf/2310.03026) [arXiv-2023]  <br>Hao Sha, Yao Mu, Yuxuan Jiang, Li Chen, Chenfeng Xu, Ping Luo, Shengbo Eben Li, Masayoshi Tomizuka, Wei Zhan, Mingyu Ding <br>
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://sites.google.com/view/llm-mpc)

- LLM Arch: [GPT-3.5](https://platform.openai.com/docs/models)
  
- Task: Planning, Control
  
- Metrics: Observation matrix, Weight matrix, Action bias, Collision Rate, Inefficiency, Time
  
- Datasets: [IdSim](https://github.com/liuyuqi123/ComplexUrbanScenarios)



[**A language agent for autonomous driving**](https://openreview.net/forum?id=UPE6WYE8vg#discussion) [COLM-2024]  <br>Jiageng Mao, Jiageng_Mao1, Junjie Ye, Yuxi Qian, Marco Pavone, Yue Wang<br>
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/USC-GVL/Agent-Driver)

- LLM Arch: [GPT-3.5](https://platform.openai.com/docs/models)
  
- Task: Perception, Prediction, Planning
  
- Metrics: Avg. L2, Collision Rate
  
- Datasets: [nuScenes](https://www.nuscenes.org/nuscenes)


[**“Asynchronous Large Language Model Enhanced Planner for Autonomous Driving**](https://arxiv.org/abs/2406.14556) [ECCV-2024]  <br>Yuan Chen, Zi-han Ding, Ziqin Wang, Yan Wang, Lijun Zhang, Si Liu<br>
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/memberRE/AsyncDriver)

- LLM Arch: [Llama2-13B](https://huggingface.co/meta-llama/Llama-2-13b)
  
- Task: Planning
  
- Metrics: Driving direction compliance, Ego comfortable, Ego progress along the expert route, No ego at-fault collisions, Speed limit compliance, Time to collision 
  
- Datasets: [nuPlan](https://www.nuscenes.org/nuplan)


# 3D Perception based LLM Driving Agents


[**Omnidrive: A holistic llm-agent framework
for autonomous driving with 3d perception, reasoning and planninge**](https://arxiv.org/abs/2405.01533) [arXiv-2024]<br> Shihao Wang, Zhiding Yu, Xiaohui Jiang, Shiyi Lan, Min Shi, Nadine Chang, Jan Kautz, Ying Li, Jose M. Alvarez <br>
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/NVlabs/OmniDrive) 

- LLM Arch: [GPT4](https://platform.openai.com/docs/models), [EVA-02-L](https://github.com/baaivision/EVA) 

- Task: 3D perception, VQA

- Metrics: CR, IR, METEOR, ROUGE and CIDEr

- Datasets: [OmniDrive](https://github.com/NVlabs/OmniDrive/tree/main), [nuScenes](https://www.nuscenes.org/nuscenes)


[**Is a 3D-Tokenized LLM the Key to Reliable Autonomous Driving?**](https://arxiv.org/abs/2405.18361) [arXiv-2024]<br> Yifan Bai, Dongming Wu, Yingfei Liu, Fan Jia, Weixin Mao, Ziheng Zhang, Yucheng Zhao, Jianbing Shen, Xing Wei, Tiancai Wang, Xiangyu Zhang <br>

- LLM Arch: [Vicuna](https://lmsys.org/blog/2023-03-30-vicuna/), [StreamPETR](https://github.com/exiawsh/StreamPETR), [TopoMLP](https://github.com/wudongming97/TopoMLP)

- Task: 3D perception

- Metrics: Avg. L2 and Collision Rate

- Datasets: [nuScenes](https://www.nuscenes.org/nuscenes)



[**DME-Driver: Integrating Human Decision Logic and 3D Scene Perception in Autonomous Driving**](https://arxiv.org/abs/2401.03641) [arXiv-2024]<br> Wencheng Han, Dongqian Guo, Cheng-Zhong Xu, Jianbing Shen <br>


- LLM Arch: [GPT4](https://platform.openai.com/docs/models), [LLaVA](https://llava-vl.github.io/blog/2024-01-30-llava-next/)

- Task: Perception, Planning

- Metrics: Avg. L2 and Collision Rate

- Datasets: [Human-Driver Behavior and Decision-Making](https://arxiv.org/abs/2401.03641)



[**Talk2bev: Language-enhanced bird’s-eye view maps for autonomous driving**](https://arxiv.org/abs/2310.02251) [ICRA-2024]<br> Tushar Choudhary, Vikrant Dewangan, Shivam Chandhok, Shubham Priyadarshan, Anushka Jain, Arun K. Singh, Siddharth Srivastava, Krishna Murthy Jatavallabhula, K. Madhava Krishna <br>
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://llmbev.github.io/talk2bev/) 


- LLM Arch: [Vicuna](https://lmsys.org/blog/2023-03-30-vicuna/), [Flan5XXL](https://huggingface.co/google/flan-t5-xxl)

- Task: Perception, Planning

- Metrics: Accuracy on MCQ, Jaccard Index, Distance Error

- Datasets: [nuScenes](https://www.nuscenes.org/nuscenes)


[**DriveLM: Driving with Graph Visual Question Answering**](https://arxiv.org/abs/2312.14150) [ECCV-2024]<br> Chonghao Sima, Katrin Renz, Kashyap Chitta, Li Chen, Hanxue Zhang, Chengen Xie, Jens Beißwenger, Ping Luo, Andreas Geiger, Hongyang Li <br>
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/OpenDriveLab/DriveLM) 


- LLM Arch: [Vicuna-13B](https://lmsys.org/blog/2023-03-30-vicuna/)

- Task: Graph VQA, Perception, Prediction, Planning

- Metrics: GPTScore, Meteor, BLEU1, CIDEr, ROUGE, Classification accuracy

- Datasets:  [DriveLM-nuScenes](https://github.com/OpenDriveLab/DriveLM), [DriveLM-CARLA](https://github.com/OpenDriveLab/DriveLM)




[**LLMI3D: MLLM-based 3D Perception from a Single 2D Image**](https://arxiv.org/abs/2408.07422) [arXiv-2025]<br> Fan Yang, Sicheng Zhao, Yanhao Zhang, Hui Chen, Haonan Lu, Jungong Han, Guiguang Ding Li <br>


- LLM Arch: [GPT4](https://platform.openai.com/docs/models)

- Task: Perception, Reasoning.

- Metrics:  Acc@0.25, Acc@0.5 (IoU thresholds of 25% and 50%), DepthError, LengthError, WidthError, and HeightError.

- Datasets:  [IG3D](https://arxiv.org/abs/2408.07422)

 
## Dataset
  
| Dataset  |   Reasoning    |   Outlook | Size     | 
|:---------:|:-------------:|:------:|:--------------------------------------------:|
| [BDD-X 2018](https://github.com/JinkyuKimUCB/explainable-deep-driving)  | Description | Planning Description & Justification    | 8M frames, 20k text strings   
| [HAD HRI Advice 2019](https://usa.honda-ri.com/had)   | Advice | Goal-oriented & stimulus-driven advice | 5,675 video clips, 45k text strings  
| [Talk2Car 2019](https://github.com/talk2car/Talk2Car)  | Description |  Goal Point Description | 30k frames, 10k text strings 
| [DRAMA 2022](https://usa.honda-ri.com/drama)  | Description |  QA + Captions | 18k frames, 100k text strings 
| [nuScenes-QA 2023](https://arxiv.org/abs/2305.14836)   |  QA |  Perception Result     | 30k frames, 460k QA pairs
| [DriveLM-2023](https://github.com/OpenDriveLab/DriveLM) |  QA + Scene Description | Perception, Prediction and Planning with Logic | 30k frames, 600k QA pairs 

</center>


<hr />

# Citation

If you find the listing and survey useful for your work, please cite the paper:

```

@ARTICLE{10258330,
  author={Chib, Pranav Singh and Singh, Pravendra},
  journal={IEEE Transactions on Intelligent Vehicles}, 
  title={Recent Advancements in End-to-End Autonomous Driving Using Deep Learning: A Survey}, 
  year={2024},
  volume={9},
  number={1},
  pages={103-118},
  keywords={Autonomous vehicles;Pipelines;Navigation;Task analysis;Surveys;Laser radar;Computer architecture;Autonomous driving;end-to-end driving;intelligent transportation system;deep learning},
  doi={10.1109/TIV.2023.3318070}}


```
[🔼 Back to top](#Table-of-Contents)
