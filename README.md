# GeoDrive: 3D Geometry-Informed Driving World Model with Precise Action Control

**GeoDrive: 3D Geometry-Informed Driving World Model with Precise Action Control**<br>

Abstract: Recent advancements in world models have revolutionized dynamic environment simulation, allowing systems to foresee future states and assess potential actions. In autonomous driving, these capabilities help vehicles anticipate the behavior of other road users, perform risk-aware planning, accelerate training in simulation, and adapt to novel scenarios, thereby enhancing safety and reliability. Current approaches exhibit deficiencies in maintaining robust 3D geometric consistency or accumulating artifacts during occlusion handling, both critical for reliable safety assessment in autonomous navigation tasks. To address this, we introduce GeoDrive, which explicitly integrates robust 3D geometry conditions into driving world models to enhance spatial understanding and action controllability. Specifically, we first extract a 3D representation from the input frame and then obtain its 2D rendering based on the user-specified ego-car trajectory. To enable dynamic modeling, we propose a dynamic editing module during training to enhance the renderings by editing the positions of the vehicles. Extensive experiments demonstrate that our method significantly outperforms existing models in both action accuracy and 3D spatial awareness, leading to more realistic, adaptable, and reliable scene modeling for safer autonomous driving. Additionally, our model can generalize to novel trajectories and offers interactive scene editing capabilities, such as object editing and object trajectory control.

**Anthony Chen<sup>1,2\*</sup>**, **Wenzhao Zheng*<sup>3\*</sup>**, **Yida Wang<sup>2\*</sup>**, **Xueyang Zhang<sup>2</sup>**, **Kun Zhan<sup>2</sup>**, **Peng Jia<sup>2</sup>**, **Kurt Keutzer<sup>3</sup>**, **Shanghang Zhang<sup>1†</sup>**  
<sup>1</sup>Peking University  <sup>2</sup>Li Auto Inc.  <sup>3</sup>UC Berkeley  
<br>
\* indicates equal contribution  
† corresponding author  


**[Paper](https://arxiv.org/abs/2505.22421)**

[![Watch the video](https://img.youtube.com/vi/LECkvCff6v0/0.jpg)](https://www.youtube.com/watch?v=LECkvCff6v0)

## TODO List

- **[2025-05-30]** ✅ Release [paper](https://arxiv.org/abs/2505.22421)
- [ ] Release inference code
- [ ] Release model checkpoints


## Citation
```
@misc{chen2025geodrive3dgeometryinformeddriving,
      title={GeoDrive: 3D Geometry-Informed Driving World Model with Precise Action Control}, 
      author={Anthony Chen and Wenzhao Zheng and Yida Wang and Xueyang Zhang and Kun Zhan and Peng Jia and Kurt Keutzer and Shanghang Zhang},
      year={2025},
      eprint={2505.22421},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2505.22421}, 
}
```
