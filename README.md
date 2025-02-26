# Papers_I_think_Interesting

## 2/256 ranking
CVPR25 not published last night, waiting for it.

[UNIGS: UNIFIED LANGUAGE-IMAGE-3D PRETRAINING WITH GAUSSIAN SPLATTING](https://arxiv.org/pdf/2502.17860)
- People trend to combine pretrain VLM with the 3DGS to achieve multiple tasks.

[Synthesizing Consistent Novel Views via 3D Epipolar Attention without Re-Training](https://arxiv.org/pdf/2502.18219)
- Introduce the epipolor plain to improve the consistency of 3D generation without finetune. In other word, it shows introducing geometry information for the pretrain model could improve performance.

[SynthRAD2025 Grand Challenge dataset: generating synthetic CTs for radiotherapy](https://arxiv.org/pdf/2502.17609)
- The dataset comprises 2362 cases, including 890 MRI-CT pairs and 1472 CBCT-CT pairs.
- If they are 3D volume, its a big dataset in medical images.


[HRR: Hierarchical Retrospection Refinement for Generated Image Detection](https://arxiv.org/pdf/2502.17862)
- Generation based method for detection
- As researcher, we need to choose an area which we could continue to explore for years, with impactful, with large work. In 2018 people are crazy on object detection, now YOLO is v11 now and believed detection is not a complex task now. Thanks all works on it.

[Self-Supervised Data Generation for Precision Agriculture: Blending Simulated Environments with Real Imagery](https://arxiv.org/pdf/2502.18320)
- It's new to me that agriculture also has the scarcity in labelled data. The proposed method do not have too much novelty. But it occurs me that many area in real life are scarcity in labelled data, from biology, to agriculture.


## 2/25 ranking
[GRAPH-GUIDED SCENE RECONSTRUCTION FROM IMAGES WITH 3D GAUSSIAN SPLATTING](https://arxiv.org/pdf/2502.17377)
- Optimization of 3DGS on large scene. The design of the selection of the camera pose based on graph is interesting.
- The usage of Octree is not new, but the idea of volume rendering become trend on this filed.

[DICEPTION: A Generalist Diffusion Model for Visual Perceptual Tasks](https://arxiv.org/pdf/2502.17157)
- It claim to do multi-task including depth estimation, segmentation as a foundation model. With finetune on 1% dataset, it could achieve good performance on OOD data.
- Wait for the code publish.

[DIS-CO: Discovering Copyrighted Content in VLMs Training Data](https://arxiv.org/pdf/2502.17358)
- Detect whether synthesis content of VLM infringe copyright of testing data.

[TOWARDS HIERARCHICAL RECTIFIED FLOW](https://arxiv.org/pdf/2502.17436)
- A method for efficiently training generative model.
- Research in a theoretical way on 2D general images.

[CAR-LOAM: Color-Assisted Robust LiDAR Odometry and Mapping](https://arxiv.org/pdf/2502.17249)
- Lidar based SLAM is longlasting and mature task.
- It occur to me that the dust3r representation is a kind of lidar（Flash Lidar， Solid-State Lidar， Directed Lidar）. Could inspired by lidar SLAM methods.

[RELICT: A Replica Detection Framework for Medical Image Generation](https://arxiv.org/pdf/2502.17360)
- As the person did medical generation, I do not like this task. But It values, protecting patients' privacy is one of reason why synthesis data required.

[Improving Monocular Visual-Inertial Initialization with Structureless Visual-Inertial Bundle Adjustment](https://arxiv.org/pdf/2502.16598)
- Monocular Visual + inertial odometry for localization, usually no odometry in 3D tasks but could be saved.
