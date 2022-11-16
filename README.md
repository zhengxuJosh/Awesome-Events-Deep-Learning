<!--A curated list of resources for Image and Video Deblurring-->
<!-- PROJECT LOGO -->

<p align="center">
  <h2 align="center">Awesome-Deep-Learning-Technologies-in-Events</h2>
  <p align="center">A curated list of resources for deep learning with events camera.
    <br />
    <br />
    <br />
    <a href="https://github.com/yunfanLu/Awesome-Event-Guided-Enhancement/pulls/new">Suggest new item</a>
    <br />
    <a href="https://github.com/yunfanLu/Awesome-Event-Guided-Enhancement/issues/new">Report Bug</a>
  </p>
</p>

## Conference Time:
| conference | Submission deadline |
| ---------- | ------------------- |
| AAAI2023   | 2022/08/08          |
| CVPR2023   | 2022/11(TBD)        |

<h2>Table of contents</h2>

- [0. Event Imaging, Simulation, Representation and Dataset](#0-event-imaging-simulation-representation-and-dataset)
  - [0.1 Imaging](#01-imaging)
  - [0.1 Simulation](#01-simulation)
  - [0.2 Representation](#02-representation)
  - [0.3 Dataset](#03-dataset)
- [1. Low-Level Vision](#1-low-level-vision)
  - [1.0 Image / Video Reconstruction](#10-image--video-reconstruction)
  - [1.1 Super Resolution with Event](#11-super-resolution-with-event)
  - [1.2 Deblurring with Event](#12-deblurring-with-event)
  - [1.3 Video Interpolation with Event](#13-video-interpolation-with-event)
  - [1.4 Low-light Image Enhancement with Event](#14-low-light-image-enhancement-with-event)
  - [1.5 HDR Imaging with Event](#15-hdr-imaging-with-event)
  - [1.6 Denoising](#16-denoising)
  - [1.7 Super Resolution](#17-super-resolution)
  - [1.8 Deblur](#18-deblur)
  - [1.9 Calibrate](#19-calibrate)
  - [1.10 Optical Flow Estimation](#110-optical-flow-estimation)
  - [1.11 Motion Estimation](#111-motion-estimation)
  - [1.12 SAI](#112-sai)
- [2 High-Level](#2-high-level)
  - [2.1 Detection](#21-detection)
  - [2.2 Segmentation](#22-segmentation)
  - [2.3 Pose Estimation](#23-pose-estimation)
  - [2.4 Video Understanding](#24-video-understanding)
  - [2.5 Tracking](#25-tracking)
- [3 Three-D Vision with Event](#3-three-d-vision-with-event)
  - [3.1 NeRF with Events](#31-nerf-with-events)
  - [3.2 Reconstruction with Events](#32-reconstruction-with-events)
- [4. Compression](#4-compression)
- [4.1 Lossless](#41-lossless)

# 0. Event Imaging, Simulation, Representation and Dataset

## 0.1 Imaging 

## 0.1 Simulation



| Publication | Title                                                       | Highlight |
| ----------- | ----------------------------------------------------------- | --------- |
| ECCV 2020   | Reducing the Sim-to-Real Gap for Event Cameras              |           |
| CVPR 20202  | Video to Events: Recycling Video Datasets for Event Cameras |           |
## 0.2 Representation
| Publication | Title                                                      | Highlight |
| ----------- | ---------------------------------------------------------- | --------- |
| T-PAMA 2020 | Time-Ordered Recent Event (TORE) Volumes for Event Cameras |           |

## 0.3 Dataset

| Publication | Title                                                       | Highlight |
| ----------- | ----------------------------------------------------------- | --------- |
| CVPR 20202  | Video to Events: Recycling Video Datasets for Event Cameras |           |


# 1. Low-Level Vision 

## 1.0 Image / Video Reconstruction


| Publication | Title                                                                                                              | Highlight |
| ----------- | ------------------------------------------------------------------------------------------------------------------ | --------- |
| CVPR 2021   | Back to Event Basics: Self-Supervised Learning of Image Reconstruction for Event Cameras via Photometric Constancy |           |
| ECCV 2020   | Event Enhanced High-Quality Image Recovery                                                                         |           |
| WACV 2020   | Fast Image Reconstruction with an Event Camera                                                                     |           |
| T-PAMI 2020 | High Frame Rate Video Reconstruction Based on an Event Camera                                                      |           |
| T-PAMI 2019 | High Speed and High Dynamic Range Video with an Event Camera                                                       |           |

## 1.1 Super Resolution with Event

| Publication | Title                                                                                                | Highlight                         |
| ----------- | ---------------------------------------------------------------------------------------------------- | --------------------------------- |
| ICCV 2021   | EvIntSR-Net: Event Guided Multiple Latent Frames Reconstruction and Super-resolution                 | Latent frame reconstruction; MISR |
| ECCV 2020   | Event Enhanced High-Quality Image Recovery                                                           | eSL-Net; Sparse learning          |
| CVPR 2020   | Joint Filtering of Intensity Images and Neuromorphic Events for High-Resolution Noise-Robust Imaging | GEF; Joint filtering              |
| CVPR 2021   | Turning Frequency to Resolution: Video Super-resolution via Event Cameras                            | E-VSR; frequency                  |

## 1.2 Deblurring with Event
| Publication | Title                                                   | Highlight                |
| ----------- | ------------------------------------------------------- | ------------------------ |
| ECCV 2020   | Event Enhanced High-Quality Image Recovery              | eSL-Net; Sparse learning |
| ECCV 2022   | Event-guided Deblurring of Unknown Exposure Time Videos | ETES; Cross-modal        |

## 1.3 Video Interpolation with Event
| Publication | Title                                                                                               | Highlight                 |
| ----------- | --------------------------------------------------------------------------------------------------- | ------------------------- |
| CVPR 2022   | TimeReplayer: Unlocking the Potential of Event Cameras for Video Interpolation                      |                           |
| CVPR 2022   | E-CIR: Event-Enhanced Continuous Intensity Recovery                                                 |                           |
| CVPR 2022   | Time Lens++: Event-based Frame Interpolation with Parametric Non-linear Flow and Multi-scale Fusion | Dataset                   |
| CVPR 2022   | Unifying Motion Deblurring and Frame Interpolation with Events                                      |                           |
| ECCV 2022   | Video Interpolation by Event-driven Anisotropic Adjustment of Optical Flow                          |                           |
| ICCV 2021   | Training Weakly Supervised Video Frame Interpolation with Events                                    | Weakly Supervised         |
| CVPR 2021   | Time Lens: Event-based Video Frame Interpolation                                                    | First Work; Dataset       |
| CVPR 2021   | EFI-Net: Video Frame Interpolation from Fusion of Events and Frames                                 | Dataset; Open Dataset     |
| ECCV 2020   | Learning Event-Driven Video Deblurring and Interpolation                                            | Deblurring; Interpolation |
| ICCV-W 2019 | Event-driven Video Frame Synthesis                                                                  |                           |


## 1.4 Low-light Image Enhancement with Event
| Publication | Title                                   | Highlight |
| ----------- | --------------------------------------- | --------- |
| ECCV 2020   | Learning to See in the Dark with Events |           |

## 1.5 HDR Imaging with Event
| Publication | Title                                                                                                                            | Highlight                  |
| ----------- | -------------------------------------------------------------------------------------------------------------------------------- | -------------------------- |
| CVPR 2022   | Multi-Bracket High Dynamic Range Imaging With Event Cameras                                                                      |                            |
| ICCV 2021   | An Asynchronous Kalman Filter for Hybrid Event Cameras                                                                           |                            |
| CVPR 2019   | Event-based High Dynamic Range Image and Very High Frame Rate Video Generation using Conditional Generative Adversarial Networks | Conditional GAN            |
| TAPMI 2019  | High Speed and High Dynamic Range Video with an Event Camera                                                                     | Recurrent network          |
| CVPR 2021   | Learning to Reconstruct High Speed and High Dynamic Range Videos from Events                                                     | RCNN; Temporal consistency |

## 1.6 Denoising


## 1.7 Super Resolution
| Publication | Title                                                                                                                            | Highlight                              |
| ----------- | -------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------- |
| CVPR 2020   | EventSR: From Asynchronous Events to Image Reconstruction, Restoration, and Super-Resolution via End-to-End Adversarial Learning | EventSR; End2end; Adversarial learning |
| TAPMI 2020  | E2SRI: Learning to Super-Resolve Intensity Images from Events                                                                    | SR-Net; RCNN                           |



## 1.8 Deblur
| Publication | Title                                                               | Highlight |
| ----------- | ------------------------------------------------------------------- | --------- |
| T-CAI       | Robust motion compensation for event cameras with smooth constraint |           |


## 1.9 Calibrate

| Publication | Title                              | Highlight |
| ----------- | ---------------------------------- | --------- |
| CVPR-W 2021 | How To Calibrate Your Event Camera |           |


## 1.10 Optical Flow Estimation

| Publication | Title                                                                   | Highlight |
| ----------- | ----------------------------------------------------------------------- | --------- |
| ICCV 2020   | Single Image Optical Flow Estimation With an Event Camera               |           |
| CVPR 2016   | Simultaneous Optical Flow and Intensity Estimation From an Event Camera |           |

## 1.11 Motion Estimation


| Publication | Title                                                        | Highlight           |
| ----------- | ------------------------------------------------------------ | ------------------- |
| T-IRAL 2016 | Accurate Angular Velocity Estimation With an Event Camera    | velocity estimation |
| ICRA 2020   | EVDodgeNet: Deep Dynamic Obstacle Dodging with Event Cameras |                     |

## 1.12 SAI

| Publication | Title                                                        | Highlight |
| ----------- | ------------------------------------------------------------ | --------- |
| CVPR 2021   | Event-Based Synthetic Aperture Imaging With a Hybrid Network |           |

# 2 High-Level 

## 2.1 Detection
| Publication | Title                                                      | Highlight |
| ----------- | ---------------------------------------------------------- | --------- |
| NISP 2020   | Learning to Detect Objects with a 1 Megapixel Event Camera |           |

## 2.2 Segmentation

## 2.3 Pose Estimation

## 2.4 Video Understanding

## 2.5 Tracking
| Publication | Title                                                         | Highlight |
| ----------- | ------------------------------------------------------------- | --------- |
|             | Object tracking on event cameras with offline–online learning |           |


# 3 Three-D Vision with Event

## 3.1 NeRF with Events
| Publication | Title                                                               | Highlight |
| ----------- | ------------------------------------------------------------------- | --------- |
| Arxiv 2022  | EventNeRF: Neural Radiance Fields from a Single Colour Event Camera |           |

## 3.2 Reconstruction with Events


# 4. Compression

# 4.1 Lossless
| Publication | Title                                       | Highlight |
| ----------- | ------------------------------------------- | --------- |
| T-SPL 2020  | Lossless Compression of Event Camera Frames |           |