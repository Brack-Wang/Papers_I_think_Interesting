# Papers_I_think_Interesting

[StereoDiff: Stereo-Diffusion Synergy for Video Depth Estimation](https://arxiv.org/pdf/2506.20756)
- Stereo Matching + Diffusion

  

# 6/21
[Hunyuan3D 2.1: From Images to High-Fidelity 3D
Assets with Production-Ready PBR Material](https://arxiv.org/pdf/2506.15442)


[MCOO-SLAM: A Multi-Camera Omnidirectional Object SLAM System](https://arxiv.org/pdf/2506.15402)

[Particle-Grid Neural Dynamics for Learning
Deformable Object Models from RGB-D Videos](https://arxiv.org/pdf/2506.15680)

[Peering into the Unknown: Active View Selection
with Neural Uncertainty Maps for 3D Reconstruction](https://arxiv.org/pdf/2506.14856)


# 4/9
[D2USt3R: Enhancing 3D Reconstruction with 4D Pointmaps for Dynamic Scenes](https://arxiv.org/pdf/2504.06264)
- work directly related

[Flash Sculptor: Modular 3D Worlds from Objects](https://arxiv.org/pdf/2504.06178)
- A fun work working on edit 3D object

[3R-GS: Best Practice in Optimizing Camera Poses Along with 3DGS](https://arxiv.org/pdf/2504.04294)
- Focus on optimize camera pose, improve is not too much, but still value.

[BrainMRDiff: A Diffusion Model for Anatomically Consistent
Brain MRI Synthesis](https://arxiv.org/pdf/2504.04532)
- Considering brain structure to synthesis

# 4/1
[AnyCam: Learning to Recover Camera Poses and Intrinsics from Casual Videos](https://arxiv.org/pdf/2503.23282)
- Directly related, read in details

[Free 360 :
Layered Gaussian Splatting for Unbounded 360-Degree
View Synthesis from Extremely Sparse and Unposed Views](https://zju3dv.github.io/free360/)

[Zero-shot Domain Generalization of Foundational
Models for 3D Medical Image Segmentation:
An Experimental Study](https://arxiv.org/pdf/2503.22862)
- Survey on 3D segmentation on medical image based on foundation model

[LSNet: See Large, Focus Small](https://arxiv.org/pdf/2503.23135)
- A network layer following eye's imaging principle with rods and cones distribution.

[NeuralGS: Bridging Neural Fields and 3D Gaussian Splatting for
Compact 3D Representations](https://arxiv.org/pdf/2503.23162)

[Learning Bijective Surface Parameterization for Inferring Signed Distance
Functions from Sparse Point Clouds with Grid Deformation](https://arxiv.org/pdf/2503.23670)
- From point cloud to SDFs, its influencial task and could be the downstream task of imge to 3D.
- Work from professor [Yushen Liu](https://yushen-liu.github.io/index_cn.html), who focus on geometry construction.

[OpenDriveVLA: Towards End-to-end Autonomous Driving with
Large Vision Language Action Model](https://arxiv.org/pdf/2503.23463)
- End to end, vla, a good setting.is it the trend now?
- From the demo, the navigation is not stable enought.


# 3/24

[A Recipe for Generating 3D Worlds From a Single Image](https://arxiv.org/pdf/2503.16611)
- A pipeline from single image to 3D. A combination, but a good start point. Expecting one day one single image of real world to 3D.

[4D Gaussian Splatting SLAM](https://arxiv.org/pdf/2503.16710)
- The idea of seperate dynamic and static is aligned with mine. Using static scene to reconstruct, using keypoint to present dynamic.
- The visualization is good.
- The image of paper is not SVG and there is no camera trace visualization since its SLAM work.

[Instant Gaussian Stream: Fast and Generalizable Streaming of Dynamic Scene Reconstruction via Gaussian Splatting](https://arxiv.org/pdf/2503.16979)
- Using the anchor point to represent dynamic scene is similar like the above one. Might be useful but no more novel seems since this point.


[Pow3R: Empowering Unconstrained 3D Reconstruction with Camera and Scene Priors](https://arxiv.org/pdf/2503.17316)
- Directy related


# 3/21

[M3: 3D-SPATIAL MULTIMODAL MEMOR](https://arxiv.org/pdf/2503.16413)
- Directly related, need to read
- Complicated to decide impact, need discussion

[Dynamic Point Maps: A Versatile Representation for Dynamic 3D Reconstruction](https://arxiv.org/pdf/2503.16318)
- Directly related
- Add time dimenstion on DUst3r, output 2 pointmaps for each images. somewhat not quite new.

[OffsetOPT: Explicit Surface Reconstruction without Normal](https://arxiv.org/pdf/2503.15763)
- Another work for surface reconstruction

[Rapid patient-specific neural networks for intraoperative X-ray to volume registration](https://arxiv.org/pdf/2503.16309)
- X-ray Registration

[1000+ FPS 4D Gaussian Splatting for Dynamic Scene Renderin](https://arxiv.org/pdf/2503.16422)
- Fast

# 3/20
[DeepMesh: Auto-Regressive Artist-mesh Creation with Reinforcement Learning](https://arxiv.org/pdf/2503.15265)
- The work is amazing, targeting on point cloud to 3D mesh through 2 stages: course mesh creation and refine through RL.
- I wonder the domain range of this work
- Further work could continue on image to 3D mesh, or large scene 3D mesh.

[Learn Your Scales: Towards Scale-Consistent Generative Novel View Synthesis](https://arxiv.org/pdf/2503.15412)
- There are sacle ambigous problem in 3D tasks, foundation modles of DUST3R, VGGT normalize all information, 3D NVS like 3DGS also normalize. We may need to take a close look on scale problem instead of simply normalize.

[Fractal Generative Models](https://arxiv.org/list/cs.CV/recent)
- Divide and conquer to generate image with MAR, decrease the computation resource and enhance stability
- Could follow this track to synthesis high resolution 3D volume image by extending it to 3D.

[LEGION: Learning to Ground and Explain for Synthetic Image Detection](https://opendatalab.github.io/LEGION/)
- A synthesis dataset for the detection of synthesis data and improve the generation

[Learning-based 3D Reconstruction in Autonomous Driving: A Comprehensive Survey](https://arxiv.org/pdf/2503.14537)
- A survey

[World Models in Artificial Intelligence: Sensing, Learning, and Reasoning Like a Child](https://arxiv.org/pdf/2503.15168)
- Propose of building world model to empower AI with logic inference.

# 3/19

[Advances in 4D Generation: A Survey](https://arxiv.org/pdf/2503.14501)
- Good, a survey in 4D generation

[Impossible Videos](https://arxiv.org/pdf/2503.14378)
- Interseting task, showing impossible videos. Indicating the data imbalance in the visual generative models.


[3D Densification for Multi-Map Monocular VSLAM in Endoscopy](https://arxiv.org/pdf/2503.14346)
- The task I thought for MICCAI.



# 3/18

[Multimodal Chain-of-Thought Reasoning: A Comprehensive Survey](https://arxiv.org/pdf/2503.12605)
- Not familiar but seems like a huge topic with ambitous

[SatDepth: A Novel Dataset for Satellite Image Matching](https://arxiv.org/pdf/2503.12706)
- A dataset for Satellite Image Matching

[Deblur Gaussian Splatting SLAM](https://arxiv.org/pdf/2503.12572)
- Seems another track to do the RGB-SLAM, could take a look on how it estimate camera pose.
- Deblur image though 3DGS and SLAM

[VRsketch2Gaussian: 3D VR Sketch Guided 3D Object Generation with Gaussian Splatting](https://arxiv.org/pdf/2503.12383)
- From VR scratcg to 3D object, the task is novel and interesting.


[Point Cloud Based Scene Segmentation: A Survey](https://arxiv.org/pdf/2503.12595)
- A survey

# 3/17
[VGGT: Visual Geometry Grounded Transformer](https://arxiv.org/pdf/2503.11651)
- Foundation model for multi task of 3D. Good work!
- https://github.com/facebookresearch/vggt

[Seeing and Seeing Through the Glass:
Real and Synthetic Data for Multi-Layer Depth Estimation](https://arxiv.org/pdf/2503.11633)
-  Transparent object benchmark

[Direction-Aware Diagonal Autoregressive Image Generation](https://arxiv.org/pdf/2503.11129)

[Bring Your Rear Cameras for Egocentric 3D Human Pose Estimation](https://arxiv.org/pdf/2503.11652)
- Work good for AR VR headset

[NEURONS: Emulating the Human Visual Cortex Improves Fidelity and Interpretability in fMRI-to-Video Reconstruction](https://arxiv.org/pdf/2503.11167)
- Mainly because the task of fMRI signal from brain to video is interesting.

[COIN: Confidence Score-Guided Distillation for Annotation-Free Cell Segmentation](https://arxiv.org/pdf/2503.11439)
- Achieve the instance segmentation without gt, based on USS and SAM with distillation.


# 3/13

[Motion Blender Gaussian Splatting for Dynamic Reconstruction](https://arxiv.org/pdf/2503.09040)
- Motion based reconstruction for Dynamic Reconstruction
- Based on Shape of motion (wang qianqian), I had similar idea, will read in detail.

[Representing 3D Shapes With 64 Latent Vectors for 3D Diffusion Models](https://arxiv.org/pdf/2503.08737)
- It occurs to me that: 3D volume generation could use tri-plane, which is still underexplored in the medical imaging area.

[SDD-4DGS: Static-Dynamic Aware Decoupling in Gaussian Splatting for 4D Scene Reconstruction](https://arxiv.org/pdf/2503.09332)
- A 4DGS based on 3DGS mapping to improve depth estimation.
- A wired idea comes to me: is the 4D recosntruction really necessary? May be not, whats the downstream task and application? Besides, It has strong correlation with 3DGS and can't get it out as independent task. The novelty and influence may continue go down.

[Monte Carlo Diffusion for Generalizable Learning-Based RANSAC](https://arxiv.org/pdf/2503.09410)
- People have a bit more attention on RANSAC, which is a bit surprise to me. While it has the potential applicaiton on reconstrucion.


# 3/12 ranking

[Dynamic Scene Reconstruction: Recent Advance in Real-time Rendering and Streaming](https://arxiv.org/pdf/2503.08166)
- An review

[nnInteractive: Redefining 3D Promptable Segmentation](https://arxiv.org/pdf/2503.08373)
- Assit expert label medical data with diverse prompt. It's valuable.

[S3R-GS: Streamlining the Pipeline for Large-Scale Street Scene Reconstruction](https://arxiv.org/pdf/2503.08217)

[RayFlow: Instance-Aware Diffusion Acceleration via Adaptive Flow Trajectories](https://arxiv.org/pdf/2503.07699)

[Fixing the RANSAC Stopping Criterion](https://arxiv.org/pdf/2503.07829)
- Potentially used in long term localization

# 3/8-3/11
Busy days of ICCV submission and refilling.


# 3/7 ranking

[FluidNexus: 3D Fluid Reconstruction and Prediction from a Single Video](https://arxiv.org/pdf/2503.04720)
- Reconstructing and predicting 3D fluid appearance and velocity from a single video
- From single image to multi-view image, to 4D reconstruction, to prediction

[EgoLife: Towards Egocentric Life Assistan](https://arxiv.org/pdf/2503.03803)

[Task-Agnostic Attacks Against Vision Foundation Models](https://arxiv.org/pdf/2503.03842)

[Surgical Gaussian Surfels: Highly Accurate
Real-time Surgical Scene Rendering](https://arxiv.org/pdf/2503.04079)
- The work I planned to do. Curious how they did

[PLMP – Point-Line Minimal Problems for Projective SfM](https://arxiv.org/pdf/2503.04351)


[S2Gaussian: Sparse-View Super-Resolution 3D Gaussian Splatting](https://arxiv.org/pdf/2503.04314)

[Floxels: Fast Unsupervised Voxel Based Scene Flow Estimation](https://arxiv.org/pdf/2503.04718)
- Unsupervied method for scne flow estimation


# 3/4 ranking

[DIFIX3D+: Improving 3D Reconstructions with Single-Step Diffusion Models](https://arxiv.org/pdf/2503.01774)
- Reconstrution work should be assisted with the generative model, this work did it.


[CAT-3DGS: A CONTEXT-ADAPTIVE TRIPLANE APPROACH TO RATE-DISTORTION-OPTIMIZED 3DGS
COMPRESSION](https://arxiv.org/pdf/2503.00357)


[MUSt3R: Multi-view Network for Stereo 3D Reconstruction](https://arxiv.org/pdf/2503.01661)
- Following up work of dust3r

[FGS-SLAM: Fourier-based Gaussian Splatting for Real-time SLAM with
Sparse and Dense Map Fusion](https://arxiv.org/pdf/2503.01109)
- Fuse point clouds for slam

## 3/3 ranking


Works focus on train generation model with less resource
-[How far can we go with ImageNet for Text-to-Image generation?](https://arxiv.org/pdf/2502.21318)
-[Training-free and Adaptive Sparse Attention for Efficient Long Video Generation](https://arxiv.org/pdf/2502.21079)

[CADDreamer: CAD object Generation from Single-view Images](https://arxiv.org/pdf/2502.20732)


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

[No Parameters, No Problem: 3D Gaussian Splatting without Camera Intrinsics and Extrinsics](https://arxiv.org/pdf/2502.19800)
- Seems a dust3r(ViT from image to pointmap)+3DGS with some technique design.
- The name is good

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


