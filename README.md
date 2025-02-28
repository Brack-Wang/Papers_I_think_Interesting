# Papers_I_think_Interesting


## 2/28 ranking

[Do computer vision foundation models learn the low-level characteristics of the human visual system?](https://arxiv.org/pdf/2502.20256)
- Interesting work analysing the Vision Foundation models and human visual.
- Some conclusion below
  

| Term                           | Explanation  | Research Findings  |
|--------------------------------|-------------|-------------------|
| **Contrast Detection Differences** | Computer vision models have lower sensitivity to low-contrast details and show irregular responses across different spatial frequencies. | Computer vision models are less sensitive to low contrast detection and are not as stable as human vision. |
| **Contrast Masking Similarity** | In complex backgrounds, the visibility of target objects decreases, and both human and computer vision exhibit similar behavior. | The masking characteristics of DINOv2 and OpenCLIP are closely aligned with human vision. |
| **Contrast Constancy** | The human visual system maintains stable contrast perception under different lighting conditions and object sizes, while computer vision models are less stable in low-frequency regions. | DINOv2 and OpenCLIP perform well in high-frequency regions, but overall still differ from human vision. |


[Ready-to-React: Online Reaction Policy for Two-Character Interaction Generation](https://zju3dv.github.io/ready_to_react/)
- Generate reaction of boxing, the demo is fun.
- Based on diffusion model with masked autoencoder, considering the past history to predict.

## 2/27 ranking

[Does 3D Gaussian Splatting Need Accurate Volumetric Rendering?](https://arxiv.org/pdf/2502.19318)
- Good story, good mathmatics. Claiming 3DGS is efficient but overall approximate while volumetric rendering is accurate.
- Volume rendering on 3DGS again. Guess it code bsed on 3DGS, introducing the Extinction Coefficient of NeRF inside.
- Wait for read in detail.

[Distill Any Depth: Distillation Creates a Stronger Monocular Depth Estimator](https://arxiv.org/pdf/2502.19204)
- Distillation consider global and local depth, achieving result simiar and a bit better than DepthAnything2.
- Wondering efficiency and the implementation Simplicity.

[EVER: Exact Volumetric Ellipsoid Rendering for Real-time View Synthesis](https://arxiv.org/abs/2410.01804)
- Considering the geometry length inside the GS using volume representation. Similar idea with our X-Field(we think from property of X-Ray not volmue, but achieve similar thought). A trend of utilizing volume is surged. It will soon achieve the ideal SOTA.
- The demo result seems to reconstruct large scene quickly, wondering the memory comsuption.

[EMT: A Visual Multi-Task Benchmark Dataset for Autonomous Driving in the Arab Gulf Region](https://arxiv.org/pdf/2502.19260)
- Datsset contains over 30,000 frames from a dash-camera perspective, along with 570,000 annotated bounding boxes, covering approximately 150 kilometers of driving routes.
- The EMT dataset supports three primary tasks: tracking, trajectory forecasting and intention prediction.
- Potentially used for test tracking.

**other**

[rendernet](https://rendernet.ai/)
- Given image and music create movie, changing dress, the demo looks good and attracting. But I do not want to pay for trying.


**Opinions**

Current Trend: AI models for images/videos mostly use diffusion, while text models prefer autoregression.
```
Information Structure:
- Text is a sequence where each word depends on the previous one, making autoregression more natural.
- Images/videos have spatial and temporal patterns, which diffusion models handle well by refining details step by step.

Noise and Perception:
- Humans see images holistically, so diffusion can gradually remove noise to restore details.
- Text errors are discrete (e.g., typos, grammar issues), making noise removal less effective.

```


## 2/26 ranking
CVPR25 not published last night, waiting for it.

[UNIGS: UNIFIED LANGUAGE-IMAGE-3D PRETRAINING WITH GAUSSIAN SPLATTING](https://arxiv.org/pdf/2502.17860)
- People trend to combine pretrain VLM with the 3DGS to achieve multiple tasks.

[Synthesizing Consistent Novel Views via 3D Epipolar Attention without Re-Training](https://arxiv.org/pdf/2502.18219)
- Introduce the epipolor plain to improve the consistency of 3D generation without finetune. In other word, it shows introducing geometry information for the pretrain model could improve performance.

[SynthRAD2025 Grand Challenge dataset: generating synthetic CTs for radiotherapy](https://arxiv.org/pdf/2502.17609)
- The dataset comprises 2362 cases, including 890 MRI-CT pairs and 1472 CBCT-CT pairs.
- If they are 3D volume, its a big dataset in medical images.



## 2/25 ranking
[GRAPH-GUIDED SCENE RECONSTRUCTION FROM IMAGES WITH 3D GAUSSIAN SPLATTING](https://arxiv.org/pdf/2502.17377)
- Optimization of 3DGS on large scene. The design of the selection of the camera pose based on graph is interesting.
- The usage of Octree is not new, but the idea of volume rendering become trend on this filed.

[DICEPTION: A Generalist Diffusion Model for Visual Perceptual Tasks](https://arxiv.org/pdf/2502.17157)
- It claim to do multi-task including depth estimation, segmentation as a foundation model. With finetune on 1% dataset, it could achieve good performance on OOD data.
- Wait for the code publish.

[DIS-CO: Discovering Copyrighted Content in VLMs Training Data](https://arxiv.org/pdf/2502.17358)
- Detect whether synthesis content of VLM infringe copyright of testing data.

[CAR-LOAM: Color-Assisted Robust LiDAR Odometry and Mapping](https://arxiv.org/pdf/2502.17249)
- Lidar based SLAM is longlasting and mature task.
- It occur to me that the dust3r representation is a kind of lidar（Flash Lidar， Solid-State Lidar， Directed Lidar）. Could inspired by lidar SLAM methods.


