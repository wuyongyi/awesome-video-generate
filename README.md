# awesome-video-generate-since-2022
A curated list of awesome Video generate resources and projects since 2022(gpt-3 droped in 2022)

# Video Diffusion
A curated list of recent diffusion models for video generation, editing, restoration, understanding, nerf, etc.



## Table of Contents <!-- omit in toc -->
- [Open-source Toolboxes and Foundation Models](#open-source-toolboxes-and-foundation-models)
- [Evaluation Benchmarks and Metrics](#evaluation-benchmarks-and-metrics)
- [Video Generation](#video-generation)
- [Controllable Video Generation](#controllable-video-generation)
- [Motion Customization](#motion-customization)
- [Long Video / Film Generation](#long-video--film-generation)
- [Video Generation with Physical Prior / 3D](#video-generation-with-physical-prior--3d)
- [Video Editing](#video-editing)
- [Long-form Video Generation and Completion](#long-form-video-generation-and-completion)
- [Human or Subject Motion](#human-or-subject-motion)
- [AI Safety for Video Generation](#AI-Safety-for-Video-Generation)
- [Video Enhancement and Restoration](#video-enhancement-and-restoration)
- [Audio Synthesis for Video](#audio-synthesis-for-video)
- [Human Feedback for Video Generation](#human-feedback-for-video-generation)
- [Policy Learning with Video Generation](#policy-learning-with-video-generation)
- [3D / NeRF](#3d--nerf)
- [World Model](#world-model)
- [Video Understanding](#video-understanding)
- [Healthcare and Biology](#healthcare-and-biology)

### Open-source Toolboxes and Foundation Models 

+ [Open-Sora-Plan](https://github.com/PKU-YuanGroup/Open-Sora-Plan)  
  [![Star](https://img.shields.io/github/stars/PKU-YuanGroup/Open-Sora-Plan.svg?style=social&label=Star)](https://github.com/PKU-YuanGroup/Open-Sora-Plan)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://github.com/PKU-YuanGroup/Open-Sora-Plan/blob/main/docs/Report-v1.0.0.md)

+ [Open-Sora](https://github.com/hpcaitech/Open-Sora)  
  [![Star](https://img.shields.io/github/stars/hpcaitech/Open-Sora.svg?style=social&label=Star)](https://github.com/hpcaitech/Open-Sora)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://github.com/hpcaitech/Open-Sora/blob/main/docs/zh_CN/README.md)

+ [Stable Video Diffusion](https://github.com/Stability-AI/generative-models)  
  [![Star](https://img.shields.io/github/stars/Stability-AI/generative-models.svg?style=social&label=Star)](https://github.com/Stability-AI/generative-models)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://stability.ai/news/stable-video-diffusion-open-ai-video-model) 

+ [Show-1](https://github.com/showlab/Show-1)  
  [![Star](https://img.shields.io/github/stars/showlab/Show-1.svg?style=social&label=Star)](https://github.com/showlab/Show-1)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://showlab.github.io/Show-1/) 

+ [Hotshot-XL (text-to-GIF)](https://huggingface.co/cerspense/zeroscope_v2_576w)  
  [![Star](https://img.shields.io/github/stars/hotshotco/Hotshot-XL.svg?style=social&label=Star)](https://github.com/hotshotco/Hotshot-XL)

+ [zeroscope_v2](https://huggingface.co/cerspense/zeroscope_v2_576w)  
  [![Website](https://img.shields.io/badge/576w-9cf)](https://huggingface.co/cerspense/zeroscope_v2_576w) 
  [![Website](https://img.shields.io/badge/XL-9cf)](https://huggingface.co/cerspense/zeroscope_v2_XL) 

+ [I2VGen-XL (image-to-video / video-to-video)](https://modelscope.cn/models/damo/Image-to-Video/summary)  
  [![Website](https://img.shields.io/badge/Website(I2V)-9cf)](https://modelscope.cn/models/damo/Image-to-Video/summary) 
  [![Website](https://img.shields.io/badge/Website(V2V)-9cf)](https://modelscope.cn/models/damo/Video-to-Video/summary) 

+ [text-to-video-synthesis-colab](https://github.com/camenduru/text-to-video-synthesis-colab)  
  [![Star](https://img.shields.io/github/stars/camenduru/text-to-video-synthesis-colab.svg?style=social&label=Star)](https://github.com/camenduru/text-to-video-synthesis-colab)

+ [VideoCrafter: A Toolkit for Text-to-Video Generation and Editing](https://github.com/VideoCrafter/VideoCrafter)  
  [![Star](https://img.shields.io/github/stars/VideoCrafter/VideoCrafter.svg?style=social&label=Star)](https://github.com/VideoCrafter/VideoCrafter)

+ [ModelScope (Text-to-video synthesis)](https://modelscope.cn/models/damo/text-to-video-synthesis/summary)  
  [![Star](https://img.shields.io/github/stars/modelscope/modelscope.svg?style=social&label=Star)](https://github.com/modelscope/modelscope)

+ [Diffusers (Text-to-video synthesis)](https://huggingface.co/docs/diffusers/main/en/api/pipelines/text_to_video#texttovideo-synthesis)  
  [![Star](https://img.shields.io/github/stars/huggingface/diffusers.svg?style=social&label=Star)](https://github.com/huggingface/diffusers)

### Evaluation Benchmarks and Metrics
+ [Frechet Video Motion Distance: A Metric for Evaluating Motion Consistency in Videos](https://arxiv.org/pdf/2407.16124) (Jun., 2024)  
  [![Star](https://img.shields.io/github/stars/DSL-Lab/FVMD-frechet-video-motion-distance.svg?style=social&label=Star)](https://github.com/DSL-Lab/FVMD-frechet-video-motion-distance)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2407.16124)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://pypi.org/project/fvmd/1.0.0/)
  
+ [T2V-CompBench: A Comprehensive Benchmark for Compositional Text-to-video Generation](https://arxiv.org/abs/2407.14505) (Jun., 2024)  
  [![Star](https://img.shields.io/github/stars/KaiyueSun98/T2V-CompBench.svg?style=social&label=Star)](https://github.com/KaiyueSun98/T2V-CompBench)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.14505)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://t2v-compbench.github.io/)
  
+ [ChronoMagic-Bench: A Benchmark for Metamorphic Evaluation of Text-to-Time-lapse Video Generation](https://arxiv.org/abs/2406.18522) (Jun., 2024)  
  [![Star](https://img.shields.io/github/stars/PKU-YuanGroup/ChronoMagic-Bench.svg?style=social&label=Star)](https://github.com/PKU-YuanGroup/ChronoMagic-Bench)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.18522)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://pku-yuangroup.github.io/ChronoMagic-Bench/)

+ [PEEKABOO: Interactive Video Generation via Masked-Diffusion](https://arxiv.org/abs/2312.07509) (CVPR, 2024)  
  [![Star](https://img.shields.io/github/stars/microsoft/Peekaboo.svg?style=social&label=Star)](https://github.com/microsoft/Peekaboo)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.07509)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://jinga-lala.github.io/projects/Peekaboo/)

+ [T2VScore: Towards A Better Metric for Text-to-Video Generation](https://arxiv.org/abs/2401.07781) (Jan., 2024)      
  [![Star](https://img.shields.io/github/stars/showlab/T2VScore.svg?style=social&label=Star)](https://github.com/showlab/T2VScore)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.07781)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://showlab.github.io/T2VScore/)

+ [StoryBench: A Multifaceted Benchmark for Continuous Story Visualization](https://arxiv.org/abs/2308.11606) (NeurIPS, 2023)      
  [![Star](https://img.shields.io/github/stars/google/storybench.svg?style=social&label=Star)](https://github.com/google/storybench)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.11606)

+ [VBench: Comprehensive Benchmark Suite for Video Generative Models](https://arxiv.org/abs/2311.17982) (Nov., 2023)      
  [![Star](https://img.shields.io/github/stars/Vchitect/VBench.svg?style=social&label=Star)](https://github.com/Vchitect/VBench?tab=readme-ov-file)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.17982)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://vchitect.github.io/VBench-project/) 

+ [FETV: A Benchmark for Fine-Grained Evaluation of Open-Domain Text-to-Video Generation](https://arxiv.org/abs/2311.01813) (Nov., 2023)      
  [![Star](https://img.shields.io/github/stars/llyx97/FETV.svg?style=social&label=Star)](https://github.com/llyx97/FETV)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.01813)

+ [EvalCrafter: Benchmarking and Evaluating Large Video Generation Models](https://arxiv.org/abs/2310.11440) (Oct., 2023)      
  [![Star](https://img.shields.io/github/stars/EvalCrafter/EvalCrafter.svg?style=social&label=Star)](https://github.com/EvalCrafter/EvalCrafter)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.11440)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://evalcrafter.github.io/) 
  [![Dataset](https://img.shields.io/badge/Dataset-e97451)](https://huggingface.co/datasets/RaphaelLiu/EvalCrafter_T2V_Dataset) 

+ [Evaluation of Text-to-Video Generation Models: A Dynamics Perspective](https://arxiv.org/pdf/2407.01094) (Jul., 2024)      
  [![Star](https://img.shields.io/github/stars/MingXiangL/DEVIL.svg?style=social&label=Star)](https://github.com/MingXiangL/DEVIL)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2407.01094)

+ [VidProM: A Million-scale Real Prompt-Gallery Dataset for Text-to-Video Diffusion Models](https://arxiv.org/abs/2403.06098) (May., 2024)      
  [![Star](https://img.shields.io/github/stars/WangWenhao0716/VidProM.svg?style=social&label=Star)](https://github.com/WangWenhao0716/VidProM)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.06098)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://github.com/WangWenhao0716/VidProM) 
  [![Dataset](https://img.shields.io/badge/Dataset-e97451)](https://vidprom.github.io/) 
  
+ [Panda-70M: Captioning 70M Videos with Multiple Cross-Modality Teachers](https://arxiv.org/abs/2402.19479) (CVPR, 2024)      
  [![Star](https://img.shields.io/github/stars/snap-research/Panda-70M.svg?style=social&label=Star)](https://github.com/snap-research/Panda-70M)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.19479)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://github.com/snap-research/Panda-70M) 
  [![Dataset](https://img.shields.io/badge/Dataset-e97451)](https://snap-research.github.io/Panda-70M/) 

### Video Generation 


+ [Real-Time Video Generation with Pyramid Attention Broadcast](https://arxiv.org/abs/2408.12588) (Aug., 2024)      
  [![Star](https://img.shields.io/github/stars/NUS-HPC-AI-Lab/VideoSys.svg?style=social&label=Star)](https://github.com/NUS-HPC-AI-Lab/VideoSys)
  [![paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.12588)

+ [xGen-VideoSyn-1: High-fidelity Text-to-Video Synthesis with Compressed Representations](https://arxiv.org/abs/2408.12590) (Aug., 2024)      
  [![Star](https://img.shields.io/github/stars/SalesforceAIResearch/xgen-videosyn.svg?style=social&label=Star)](https://github.com/SalesforceAIResearch/xgen-videosyn)
  [![paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.12590)


+ [CogVideoX: Text-to-video generation](https://github.com/THUDM/CogVideo/blob/main/resources/CogVideoX.pdf) (Aug., 2024)      
  [![Star](https://img.shields.io/github/stars/THUDM/CogVideo.svg?style=social&label=Star)](https://github.com/THUDM/CogVideo)
  [![paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://github.com/THUDM/CogVideo/blob/main/resources/CogVideoX.pdf)

+ [FreeLong: Training-Free Long Video Generation with SpectralBlend Temporal Attention](https://arxiv.org/abs/2407.19918) (Aug., 2024)      
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.19918)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://yulu.net.cn/freelong/)
  
+ [VEnhancer: Generative Space-Time Enhancement for Video Generation](https://arxiv.org/abs/2407.07667) (Jul., 2024)      
  [![Star](https://img.shields.io/github/stars/Vchitect/VEnhancer.svg?style=social&label=Star)](https://github.com/Vchitect/VEnhancer)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.07667)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://vchitect.github.io/VEnhancer-project/)

+ [Live2Diff: Live Stream Translation via Uni-directional Attention in Video Diffusion Models](https://arxiv.org/abs/2407.08701) (Jul., 2024)      
  [![Star](https://img.shields.io/github/stars/open-mmlab/Live2Diff.svg?style=social&label=Star)](https://github.com/open-mmlab/Live2Diff)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.08701)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://live2diff.github.io/)

+ [Video Diffusion Alignment via Reward Gradient](https://arxiv.org/abs/2407.08737) (Jul., 2024)      
  [![Star](https://img.shields.io/github/stars/mihirp1998/VADER.svg?style=social&label=Star)](https://github.com/mihirp1998/VADER)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.08737)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://vader-vid.github.io/)

+ [ExVideo: Extending Video Diffusion Models via Parameter-Efficient Post-Tuning](https://arxiv.org/abs/2406.14130) (Jun., 2024)      
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.14130)

+ [MimicMotion: High-Quality Human Motion Video Generation with Confidence-aware Pose Guidance](https://arxiv.org/abs/2406.19680) (Jul., 2024)      
  [![Star](https://img.shields.io/github/stars/Tencent/MimicMotion.svg?style=social&label=Star)](https://github.com/Tencent/MimicMotion)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.19680)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://tencent.github.io/MimicMotion/)

+ [Identifying and Solving Conditional Image Leakage in Image-to-Video Diffusion Model](https://arxiv.org/abs/2406.15735) (Jun., 2024)   
  [![Star](https://img.shields.io/github/stars/thu-ml/cond-image-leakage.svg?style=social&label=Star)](https://github.com/thu-ml/cond-image-leakage/tree/main?tab=readme-ov-file)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.15735)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://cond-image-leak.github.io/)

+ [Video-Infinity: Distributed Long Video Generation](https://arxiv.org/abs/2406.16260) (Jun., 2024)      
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.16260)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://video-infinity.tanzhenxiong.com/)

+ [MotionBooth: Motion-Aware Customized Text-to-Video Generation](https://arxiv.org/abs/2406.17758) (Jun., 2024)      
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.17758)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://jianzongwu.github.io/projects/motionbooth/)

+ [Text-Animator: Controllable Visual Text Video Generation](https://arxiv.org/abs/2406.17777) (Jun., 2024)      
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.17777)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://laulampaul.github.io/text-animator.html)

+ [UniAnimate: Taming Unified Video Diffusion Models for Consistent Human Image Animation](https://arxiv.org/abs/2406.01188) (Jun., 2024)      
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.01188)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://unianimate.github.io/)

+ [T2V-Turbo: Breaking the Quality Bottleneck of Video Consistency Model with Mixed Reward Feedback](https://arxiv.org/abs/2405.18750) (May, 2024)      
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.18750)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://t2v-turbo.github.io/)

+ [Collaborative Video Diffusion: Consistent Multi-video Generation with Camera Control](https://arxiv.org/abs/2405.17414) (May, 2024)      
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.17414)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://collaborativevideodiffusion.github.io/)

+ [Human4DiT: Free-view Human Video Generation with 4D Diffusion Transformer](https://arxiv.org/abs/2405.17405) (May, 2024)      
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.17405)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://human4dit.github.io/)

+ [FIFO-Diffusion: Generating Infinite Videos from Text without Training](https://arxiv.org/abs/2405.11473) (May, 2024)      
  [![Star](https://img.shields.io/github/stars/jjihwan/FIFO-Diffusion_public.svg?style=social&label=Star)](https://github.com/jjihwan/FIFO-Diffusion_public)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.11473)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://jjihwan.github.io/projects/FIFO-Diffusion)

+ [Vidu: a Highly Consistent, Dynamic and Skilled Text-to-Video Generator with Diffusion Models](https://arxiv.org/abs/2405.04233) (May, 2024)      
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.04233)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://www.shengshu-ai.com/vidu)

+ [Lumina-T2X: Transforming Text into Any Modality, Resolution, and Duration via Flow-based Large Diffusion Transformers](https://arxiv.org/abs/2405.05945) (May, 2024)      
  [![Star](https://img.shields.io/github/stars/Alpha-VLLM/Lumina-T2X.svg?style=social&label=Star)](https://github.com/Alpha-VLLM/Lumina-T2X)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.05945)

+ [StoryDiffusion: Consistent Self-Attention for Long-Range Image and Video Generation](https://arxiv.org/abs/2405.01434) (May, 2024)      
  [![Star](https://img.shields.io/github/stars/HVision-NKU/StoryDiffusion.svg?style=social&label=Star)](https://github.com/HVision-NKU/StoryDiffusion)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.01434)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://storydiffusion.github.io/)

+ [TI2V-Zero: Zero-Shot Image Conditioning for Text-to-Video Diffusion Models](https://arxiv.org/abs/2404.16306) (CVPR 2024)      
  [![Star](https://img.shields.io/github/stars/merlresearch/TI2V-Zero.svg?style=social&label=Star)](https://github.com/merlresearch/TI2V-Zero)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.16306)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://merl.com/research/highlights/TI2V-Zero)

+ [ID-Animator: Zero-Shot Identity-Preserving Human Video Generation](https://arxiv.org/abs/2404.15275) (Apr., 2024)  
  [![Star](https://img.shields.io/github/stars/ID-Animator/ID-Animator.svg?style=social&label=Star)](https://github.com/ID-Animator/ID-Animator) 
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.15275)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://id-animator.github.io/)

+ [AnimateZoo: Zero-shot Video Generation of Cross-Species Animation via Subject Alignment](https://arxiv.org/abs/2404.04946) (Apr., 2024)  
  [![Star](https://img.shields.io/github/stars/JustinXu0/AnimateZoo.svg?style=social&label=Star)](https://github.com/JustinXu0/AnimateZoo) 
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.04946)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://justinxu0.github.io/AnimateZoo/)

+ [MagicTime: Time-lapse Video Generation Models as Metamorphic Simulators](https://arxiv.org/abs/2404.05014) (Apr., 2024)      
  [![Star](https://img.shields.io/github/stars/PKU-YuanGroup/MagicTime.svg?style=social&label=Star)](https://github.com/PKU-YuanGroup/MagicTime)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.05014)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://pku-yuangroup.github.io/MagicTime/) 
  [![Dataset](https://img.shields.io/badge/Dataset-e97451)](https://drive.google.com/drive/folders/1WsomdkmSp3ql3ImcNsmzFuSQ9Qukuyr8?usp=sharing) 

+ [TRIP: Temporal Residual Learning with Image Noise Prior for Image-to-Video Diffusion Models](https://arxiv.org/abs/2403.17005) (CVPR 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.17005)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://trip-i2v.github.io/TRIP/)

+ [VSTAR: Generative Temporal Nursing for Longer Dynamic Video Synthesis](https://arxiv.org/abs/2403.13501) (Mar., 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.13501)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://yumengli007.github.io/VSTAR/)

+ [StreamingT2V: Consistent, Dynamic, and Extendable Long Video Generation from Text](https://arxiv.org/abs/2403.14773) (Mar., 2024)  
  [![Star](https://img.shields.io/github/stars/Picsart-AI-Research/StreamingT2V.svg?style=social&label=Star)](https://github.com/Picsart-AI-Research/StreamingT2V)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.14773)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://streamingt2v.github.io/)

+ [Intention-driven Ego-to-Exo Video Generation](https://arxiv.org/abs/2403.09194) (Mar., 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.09194)

+ [VideoElevator: Elevating Video Generation Quality with Versatile Text-to-Image Diffusion Models](https://arxiv.org/abs/2403.05438) (Mar., 2024)  
  [![Star](https://img.shields.io/github/stars/YBYBZhang/VideoElevator.svg?style=social&label=Star)](https://github.com/YBYBZhang/VideoElevator)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.05438)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://videoelevator.github.io/)

+ [Snap Video: Scaled Spatiotemporal Transformers for Text-to-Video Synthesis](https://arxiv.org/abs/2402.14797) (Feb., 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.14797)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://snap-research.github.io/snapvideo/)

+ [One-Shot Motion Customization of Text-to-Video Diffusion Models](https://arxiv.org/abs/2402.14780) (Feb., 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.14780)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://anonymous-314.github.io/)

+ [Magic-Me: Identity-Specific Video Customized Diffusion](https://arxiv.org/abs/2402.09368) (Feb., 2024)  
  [![Star](https://img.shields.io/github/stars/Zhen-Dong/Magic-Me.svg?style=social&label=Star)](https://github.com/Zhen-Dong/Magic-Me)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.09368)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://magic-me-webpage.github.io/)

+ [ConsistI2V: Enhancing Visual Consistency for Image-to-Video Generation](https://arxiv.org/abs/2402.04324) (Feb., 2024)  
  [![Star](https://img.shields.io/github/stars/TIGER-AI-Lab/ConsistI2V.svg?style=social&label=Star)](https://github.com/TIGER-AI-Lab/ConsistI2V)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.04324)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://tiger-ai-lab.github.io/ConsistI2V/)

+ [Direct-a-Video: Customized Video Generation with User-Directed Camera Movement and Object Motion](https://arxiv.org/abs/2402.03162) (Feb., 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.03162)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://direct-a-video.github.io/)

+ [Video-LaVIT: Unified Video-Language Pre-training with Decoupled Visual-Motional Tokenization](https://arxiv.org/abs/2402.03161) (Feb., 2024)  
  [![Star](https://img.shields.io/github/stars/jy0205/LaVIT.svg?style=social&label=Star)](https://github.com/jy0205/LaVIT)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.03161)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://video-lavit.github.io/)

+ [Boximator: Generating Rich and Controllable Motions for Video Synthesis](https://arxiv.org/abs/2402.01566) (Feb., 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.01566)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://boximator.github.io/)

+ [Lumiere: A Space-Time Diffusion Model for Video Generation](https://arxiv.org/abs/2401.12945) (Jan., 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.12945)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://lumiere-video.github.io/)

+ [ActAnywhere: Subject-Aware Video Background Generation](https://arxiv.org/abs/2401.10822) (Jan., 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.10822)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://actanywhere.github.io/)

+ [WorldDreamer: Towards General World Models for Video Generation via Predicting Masked Tokens](https://arxiv.org/abs/2401.09985) (Jan., 2024)  
  [![Star](https://img.shields.io/github/stars/JeffWang987/WorldDreamer.svg?style=social&label=Star)](https://github.com/JeffWang987/WorldDreamer)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.09985)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://world-dreamer.github.io/)

+ [CustomVideo: Customizing Text-to-Video Generation with Multiple Subjects](https://arxiv.org/abs/2401.09962) (Jan., 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.09962)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://kyfafyd.wang/projects/customvideo/)

+ [UniVG: Towards UNIfied-modal Video Generation](https://arxiv.org/abs/2401.09084) (Jan., 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.09084)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://univg-baidu.github.io/)

+ [VideoCrafter2: Overcoming Data Limitations for High-Quality Video Diffusion Models](https://arxiv.org/abs/2401.09047) (Jan., 2024)  
  [![Star](https://img.shields.io/github/stars/AILab-CVC/VideoCrafter.svg?style=social&label=Star)](https://github.com/AILab-CVC/VideoCrafter)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.09047)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://ailab-cvc.github.io/videocrafter2/)

+ [360DVD: Controllable Panorama Video Generation with 360-Degree Video Diffusion Model](https://arxiv.org/abs/2401.06578) (Jan., 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.06578)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://akaneqwq.github.io/360DVD/)

+ [RAVEN: Rethinking Adversarial Video Generation with Efficient Tri-plane Networks](https://arxiv.org/abs/2401.06035) (Jan., 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.06035)

+ [Latte: Latent Diffusion Transformer for Video Generation](https://arxiv.org/abs/2401.03048) (Jan., 2024)  
  [![Star](https://img.shields.io/github/stars/Vchitect/Latte.svg?style=social&label=Star)](https://github.com/Vchitect/Latte)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.03048)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://maxin-cn.github.io/latte_project/)

+ [MagicVideo-V2: Multi-Stage High-Aesthetic Video Generation](https://arxiv.org/abs/2401.04468) (Jan., 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.04468)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://magicvideov2.github.io/)

+ [VideoDrafter: Content-Consistent Multi-Scene Video Generation with LLM](https://arxiv.org/abs/2401.01256) (Jan., 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.01256)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://videodrafter.github.io/)

+ [FlashVideo: A Framework for Swift Inference in Text-to-Video Generation](https://arxiv.org/abs/2401.00869) (Dec., 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.00869)

+ [I2V-Adapter: A General Image-to-Video Adapter for Video Diffusion Models](https://arxiv.org/abs/2312.16693) (Dec., 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.16693)

+ [A Recipe for Scaling up Text-to-Video Generation with Text-free Videos](https://arxiv.org/abs/2312.15770) (Dec., 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.15770)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://tf-t2v.github.io/)

+ [PIA: Your Personalized Image Animator via Plug-and-Play Modules in Text-to-Image Models](https://arxiv.org/abs/2312.13964) (Dec., 2023)  
  [![Star](https://img.shields.io/github/stars/open-mmlab/PIA.svg?style=social&label=Star)](https://github.com/open-mmlab/PIA)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.13964)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://pi-animator.github.io/)

+ [VideoPoet: A Large Language Model for Zero-Shot Video Generation](https://arxiv.org/abs/2312.14125) (Dec., 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.14125)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://sites.research.google/videopoet/)

+ [InstructVideo: Instructing Video Diffusion Models with Human Feedback](https://arxiv.org/abs/2312.12490) (Dec., 2023)  
  [![Star](https://img.shields.io/github/stars/damo-vilab/i2vgen-xl.svg?style=social&label=Star)](https://github.com/damo-vilab/i2vgen-xl/blob/main/doc/InstructVideo.md)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.12490)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://instructvideo.github.io/)

+ [VideoLCM: Video Latent Consistency Model](https://arxiv.org/abs/2312.09109) (Dec., 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.09109)

+ [PEEKABOO: Interactive Video Generation via Masked-Diffusion](https://arxiv.org/abs/2312.07509) (Dec., 2023)  
  [![Star](https://img.shields.io/github/stars/microsoft/Peekaboo.svg?style=social&label=Star)](https://github.com/microsoft/Peekaboo)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.07509)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://jinga-lala.github.io/projects/Peekaboo/)

+ [FreeInit: Bridging Initialization Gap in Video Diffusion Models](https://arxiv.org/abs/2312.07537) (Dec., 2023)  
  [![Star](https://img.shields.io/github/stars/TianxingWu/FreeInit.svg?style=social&label=Star)](https://github.com/TianxingWu/FreeInit)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.07537)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://tianxingwu.github.io/pages/FreeInit/)

+ [Photorealistic Video Generation with Diffusion Models](https://arxiv.org/abs/2312.06662) (Dec., 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.06662)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://walt-video-diffusion.github.io/)

+ [Upscale-A-Video: Temporal-Consistent Diffusion Model for Real-World Video Super-Resolution](https://arxiv.org/abs/2312.06640) (Dec., 2023)  
  [![Star](https://img.shields.io/github/stars/sczhou/Upscale-A-Video.svg?style=social&label=Star)](https://github.com/sczhou/Upscale-A-Video)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.06640)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://shangchenzhou.com/projects/upscale-a-video/)

+ [DreaMoving: A Human Video Generation Framework based on Diffusion Models](https://arxiv.org/abs/2312.05107) (Dec., 2023)  
  [![Star](https://img.shields.io/github/stars/dreamoving/dreamoving-project.svg?style=social&label=Star)](https://github.com/dreamoving/dreamoving-project)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.05107)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://dreamoving.github.io/dreamoving/)

+ [MotionCrafter: One-Shot Motion Customization of Diffusion Models](https://arxiv.org/abs/2312.05288) (Dec., 2023)  
  [![Star](https://img.shields.io/github/stars/zyxElsa/MotionCrafter.svg?style=social&label=Star)](https://github.com/zyxElsa/MotionCrafter)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.05288)

+ [AnimateZero: Video Diffusion Models are Zero-Shot Image Animators](https://arxiv.org/abs/2312.03793) (Dec., 2023)  
  [![Star](https://img.shields.io/github/stars/vvictoryuki/AnimateZero.svg?style=social&label=Star)](https://github.com/vvictoryuki/AnimateZero)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.03793)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://vvictoryuki.github.io/animatezero.github.io/)

+ [AVID: Any-Length Video Inpainting with Diffusion Model](https://arxiv.org/abs/2312.03816) (Dec., 2023)  
  [![Star](https://img.shields.io/github/stars/zhang-zx/AVID.svg?style=social&label=Star)](https://github.com/zhang-zx/AVID)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.03816)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://zhang-zx.github.io/AVID/)

+ [MTVG : Multi-text Video Generation with Text-to-Video Models](https://arxiv.org/abs/2312.04086) (Dec., 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.04086)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://kuai-lab.github.io/mtvg-page)

+ [DreamVideo: Composing Your Dream Videos with Customized Subject and Motion](https://arxiv.org/abs/2312.04433) (Dec., 2023)  
  [![Star](https://img.shields.io/github/stars/damo-vilab/i2vgen-xl.svg?style=social&label=Star)](https://github.com/damo-vilab/i2vgen-xl)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.04433)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://dreamvideo-t2v.github.io/)

+ [Hierarchical Spatio-temporal Decoupling for Text-to-Video Generation](https://arxiv.org/abs/2312.04483) (Dec., 2023)  
  [![Star](https://img.shields.io/github/stars/damo-vilab/i2vgen-xl.svg?style=social&label=Star)](https://github.com/damo-vilab/i2vgen-xl)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.04483)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://higen-t2v.github.io/)

+ [GenTron: Delving Deep into Diffusion Transformers for Image and Video Generation](https://arxiv.org/abs/2312.04557) (CVPR 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.04557)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://www.shoufachen.com/gentron_website/)

+ [GenDeF: Learning Generative Deformation Field for Video Generation](https://arxiv.org/abs/2312.04561) (Dec., 2023)  
  [![Star](https://img.shields.io/github/stars/aim-uofa/GenDeF.svg?style=social&label=Star)](https://github.com/aim-uofa/GenDeF)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.04561)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://aim-uofa.github.io/GenDeF/)

+ [F3-Pruning: A Training-Free and Generalized Pruning Strategy towards Faster and Finer Text-to-Video Synthesis](https://arxiv.org/abs/2312.03459) (Dec., 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.03459)

+ [DreamVideo: High-Fidelity Image-to-Video Generation with Image Retention and Text Guidance](https://arxiv.org/abs/2312.03018) (Dec., 2023)  
  [![Star](https://img.shields.io/github/stars/anonymous0769/DreamVideo.svg?style=social&label=Star)](https://github.com/anonymous0769/DreamVideo)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.03018)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://anonymous0769.github.io/DreamVideo/)

+ [LivePhoto: Real Image Animation with Text-guided Motion Control](https://arxiv.org/abs/2312.02928) (Dec., 2023)  
  [![Star](https://img.shields.io/github/stars/XavierCHEN34/LivePhoto.svg?style=social&label=Star)](https://github.com/XavierCHEN34/LivePhoto)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.02928)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://xavierchen34.github.io/LivePhoto-Page/)

+ [Fine-grained Controllable Video Generation via Object Appearance and Context](https://arxiv.org/abs/2312.02919) (Dec., 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.02919)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://hhsinping.github.io/factor/)

+ [VideoBooth: Diffusion-based Video Generation with Image Prompts](https://arxiv.org/abs/2312.00777) (Dec., 2023)  
  [![Star](https://img.shields.io/github/stars/Vchitect/VideoBooth.svg?style=social&label=Star)](https://github.com/Vchitect/VideoBooth)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.00777)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://vchitect.github.io/VideoBooth-project/)

+ [StyleCrafter: Enhancing Stylized Text-to-Video Generation with Style Adapter](https://arxiv.org/abs/2312.00330) (Dec., 2023)  
  [![Star](https://img.shields.io/github/stars/GongyeLiu/StyleCrafter.svg?style=social&label=Star)](https://github.com/GongyeLiu/StyleCrafter)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.00330)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://gongyeliu.github.io/StyleCrafter.github.io/)

+ [MicroCinema: A Divide-and-Conquer Approach for Text-to-Video Generation](https://arxiv.org/abs/2311.18829) (Nov., 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.18829)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://wangyanhui666.github.io/MicroCinema.github.io/)

+ [ART•V: Auto-Regressive Text-to-Video Generation with Diffusion Models](https://arxiv.org/abs/2311.18834) (Nov., 2023)  
  [![Star](https://img.shields.io/github/stars/WarranWeng/ART.V.svg?style=social&label=Star)](https://github.com/WarranWeng/ART.V)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.18834)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://warranweng.github.io/art.v/)

+ [Smooth Video Synthesis with Noise Constraints on Diffusion Models for One-shot Video Tuning](https://arxiv.org/abs/2311.17536) (Nov., 2023)  
  [![Star](https://img.shields.io/github/stars/SPengLiang/SmoothVideo.svg?style=social&label=Star)](https://github.com/SPengLiang/SmoothVideo)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.17536)

+ [VideoAssembler: Identity-Consistent Video Generation with Reference Entities using Diffusion Model](https://arxiv.org/abs/2311.17338) (Nov., 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.17338)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://videoassembler.github.io/videoassembler/)

+ [MotionZero:Exploiting Motion Priors for Zero-shot Text-to-Video Generation](https://arxiv.org/abs/2311.16635) (Nov., 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.16635)

+ [MagicAnimate: Temporally Consistent Human Image Animation using Diffusion Model](https://arxiv.org/abs/2311.16498) (Nov., 2023)  
  [![Star](https://img.shields.io/github/stars/magic-research/magic-animate.svg?style=social&label=Star)](https://github.com/magic-research/magic-animate)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.16498)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://showlab.github.io/magicanimate)

+ [FlowZero: Zero-Shot Text-to-Video Synthesis with LLM-Driven Dynamic Scene Syntax](https://arxiv.org/abs/2311.15813) (Nov., 2023)  
  [![Star](https://img.shields.io/github/stars/aniki-ly/FlowZero.svg?style=social&label=Star)](https://github.com/aniki-ly/FlowZero)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.15813)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://flowzero-video.github.io/)

+ [Sketch Video Synthesis](https://arxiv.org/abs/2311.15306) (Nov., 2023)  
  [![Star](https://img.shields.io/github/stars/yudianzheng/SketchVideo.svg?style=social&label=Star)](https://github.com/yudianzheng/SketchVideo)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.15306)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://sketchvideo.github.io/)

+ [Stable Video Diffusion: Scaling Latent Video Diffusion Models to Large Datasets](https://arxiv.org/abs/2311.15127) (Nov., 2023)  
  [![Star](https://img.shields.io/github/stars/Stability-AI/generative-models.svg?style=social&label=Star)](https://github.com/Stability-AI/generative-models)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.15127)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://stability.ai/news/stable-video-diffusion-open-ai-video-model)

+ [Decouple Content and Motion for Conditional Image-to-Video Generation](https://arxiv.org/abs/2311.14294) (Nov., 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.14294)

+ [FusionFrames: Efficient Architectural Aspects for Text-to-Video Generation Pipeline](https://arxiv.org/abs/2311.13073) (Nov., 2023)  
  [![Star](https://img.shields.io/github/stars/ai-forever/KandinskyVideo.svg?style=social&label=Star)](https://github.com/ai-forever/KandinskyVideo)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.13073)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://ai-forever.github.io/kandinsky-video/)

+ [Fine-Grained Open Domain Image Animation with Motion Guidance](https://arxiv.org/abs/2311.12886) (Nov., 2023)
  [![Star](https://img.shields.io/github/stars/alibaba/animate-anything.svg?style=social&label=Star)](https://github.com/alibaba/animate-anything)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.12886)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://animationai.github.io/AnimateAnything/)

+ [GPT4Motion: Scripting Physical Motions in Text-to-Video Generation via Blender-Oriented GPT Planning](https://arxiv.org/abs/2311.12631) (Nov., 2023)  
  [![Star](https://img.shields.io/github/stars/jiaxilv/GPT4Motion.svg?style=social&label=Star)](https://github.com/jiaxilv/GPT4Motion)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.12631)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://gpt4motion.github.io/)

+ [MagicDance: Realistic Human Dance Video Generation with Motions & Facial Expressions Transfer](https://arxiv.org/abs/2311.12052) (Nov., 2023)  
  [![Star](https://img.shields.io/github/stars/Boese0601/MagicDance.svg?style=social&label=Star)](https://github.com/Boese0601/MagicDance)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.12052)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://boese0601.github.io/magicdance/)

+ [MoVideo: Motion-Aware Video Generation with Diffusion Models](https://arxiv.org/abs/2311.11325) (Nov., 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.11325)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://jingyunliang.github.io/MoVideo/)

+ [Make Pixels Dance: High-Dynamic Video Generation](https://arxiv.org/abs/2311.10982) (Nov., 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.10982)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://makepixelsdance.github.io/)

+ [Emu Video: Factorizing Text-to-Video Generation by Explicit Image Conditioning](https://arxiv.org/abs/2311.10709) (Nov., 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.10709)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://emu-video.metademolab.com/)
  
+ [Optimal Noise pursuit for Augmenting Text-to-Video Generation](https://arxiv.org/abs/2311.00949) (Nov., 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.00949)

+ [VideoDreamer: Customized Multi-Subject Text-to-Video Generation with Disen-Mix Finetuning](https://arxiv.org/abs/2311.00990) (Nov., 2023)  
  [![Star](https://img.shields.io/github/stars/videodreamer23/videodreamer23.github.io.svg?style=social&label=Star)](https://github.com/videodreamer23/videodreamer23.github.io)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.00990)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://videodreamer23.github.io/)

+ [SEINE: Short-to-Long Video Diffusion Model for Generative Transition and Prediction](https://arxiv.org/abs/2310.20700) (Oct., 2023)  
  [![Star](https://img.shields.io/github/stars/Vchitect/SEINE.svg?style=social&label=Star)](https://github.com/Vchitect/SEINE)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.20700)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://vchitect.github.io/SEINE-project/)

+ [FreeNoise: Tuning-Free Longer Video Diffusion Via Noise Rescheduling](https://arxiv.org/abs/2310.15169) (Oct., 2023)  
  [![Star](https://img.shields.io/github/stars/arthur-qiu/LongerCrafter.svg?style=social&label=Star)](https://github.com/arthur-qiu/LongerCrafter)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.15169)
  [![Website](https://img.shields.io/badge/Website-9cf)](http://haonanqiu.com/projects/FreeNoise.html)

+ [DynamiCrafter: Animating Open-domain Images with Video Diffusion Priors](https://arxiv.org/abs/2310.12190) (Oct., 2023)  
  [![Star](https://img.shields.io/github/stars/Doubiiu/DynamiCrafter.svg?style=social&label=Star)](https://github.com/Doubiiu/DynamiCrafter)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.12190)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://doubiiu.github.io/projects/DynamiCrafter/)
  
+ [LAMP: Learn A Motion Pattern for Few-Shot-Based Video Generation](https://arxiv.org/abs/2310.10769) (Oct., 2023)  
  [![Star](https://img.shields.io/github/stars/RQ-Wu/LAMP.svg?style=social&label=Star)](https://github.com/RQ-Wu/LAMP)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.10769)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://rq-wu.github.io/projects/LAMP/) 

+ [Show-1: Marrying Pixel and Latent Diffusion Models for Text-to-Video Generation](https://arxiv.org/abs/2309.15818) (Sep., 2023)  
  [![Star](https://img.shields.io/github/stars/showlab/Show-1.svg?style=social&label=Star)](https://github.com/showlab/Show-1)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.15818)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://showlab.github.io/Show-1/) 

+ [MotionDirector: Motion Customization of Text-to-Video Diffusion Models](https://arxiv.org/abs/2310.08465) (Sep., 2023)  
  [![Star](https://img.shields.io/github/stars/showlab/MotionDirector.svg?style=social&label=Star)](https://github.com/showlab/MotionDirector)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.08465)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://showlab.github.io/MotionDirector/)

+ [LAVIE: High-Quality Video Generation with Cascaded Latent Diffusion Models](https://arxiv.org/abs/2309.15103) (Sep., 2023)  
  [![Star](https://img.shields.io/github/stars/Vchitect/LaVie.svg?style=social&label=Star)](https://github.com/Vchitect/LaVie)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.15103)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://vchitect.github.io/LaVie-project/) 

+ [Diverse and Aligned Audio-to-Video Generation via Text-to-Video Model Adaptation](https://arxiv.org/abs/2309.16429) (Sep., 2023)  
  [![Star](https://img.shields.io/github/stars/guyyariv/TempoTokens.svg?style=social&label=Star)](https://github.com/guyyariv/TempoTokens)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.16429)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://pages.cs.huji.ac.il/adiyoss-lab/TempoTokens/) 

+ [Free-Bloom: Zero-Shot Text-to-Video Generator with LLM Director and LDM Animator](https://arxiv.org/abs/2309.14494) (Sep., 2023)  
  [![Star](https://img.shields.io/github/stars/SooLab/Free-Bloom.svg?style=social&label=Star)](https://github.com/SooLab/Free-Bloom)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.14494)

+ [Hierarchical Masked 3D Diffusion Model for Video Outpainting](https://arxiv.org/abs/2309.02119) (Sep., 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.02119)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://fanfanda.github.io/M3DDM/) 

+ [Reuse and Diffuse: Iterative Denoising for Text-to-Video Generation](https://arxiv.org/abs/2309.03549) (Sep., 2023)  
  [![Star](https://img.shields.io/github/stars/anonymous0x233/ReuseAndDiffuse.svg?style=social&label=Star)](https://github.com/anonymous0x233/ReuseAndDiffuse)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.03549)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://anonymous0x233.github.io/ReuseAndDiffuse/) 

+ [VideoGen: A Reference-Guided Latent Diffusion Approach for High Definition Text-to-Video Generation](https://arxiv.org/abs/2309.00398) (Sep., 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.00398)

+ [MagicAvatar: Multimodal Avatar Generation and Animation](https://arxiv.org/abs/2308.14748) (Aug., 2023)  
  [![Star](https://img.shields.io/github/stars/magic-research/magic-avatar.svg?style=social&label=Star)](https://github.com/magic-research/magic-avatar)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.14748)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://magic-avatar.github.io/) 

+ [Empowering Dynamics-aware Text-to-Video Diffusion with Large Language Models](https://arxiv.org/abs/2308.13812) (Aug., 2023)  
  [![Star](https://img.shields.io/github/stars/scofield7419/Dysen.svg?style=social&label=Star)](https://github.com/scofield7419/Dysen)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.13812)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://haofei.vip/Dysen-VDM/) 

+ [SimDA: Simple Diffusion Adapter for Efficient Video Generation](https://arxiv.org/abs/2308.09710) (Aug., 2023)  
  [![Star](https://img.shields.io/github/stars/ChenHsing/SimDA.svg?style=social&label=Star)](https://github.com/ChenHsing/SimDA)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.09710)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://chenhsing.github.io/SimDA/) 

+ [ModelScope Text-to-Video Technical Report](https://arxiv.org/abs/2308.06571) (Aug., 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.06571)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://modelscope.cn/models/damo/text-to-video-synthesis/summary) 

+ [Dual-Stream Diffusion Net for Text-to-Video Generation](https://arxiv.org/abs/2308.08316) (Aug., 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.08316)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://anonymous.4open.science/r/Private-C3E8) 

+ [InternVid: A Large-scale Video-Text Dataset for Multimodal Understanding and Generation](https://arxiv.org/abs/2307.06942) (Jul., 2023)  
  [![Star](https://img.shields.io/github/stars/OpenGVLab/InternVideo.svg?style=social&label=Star)](https://github.com/OpenGVLab/InternVideo/tree/main/Data/InternVid)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2307.06942)

+ [Animate-A-Story: Storytelling with Retrieval-Augmented Video Generation](https://arxiv.org/abs/2307.06940) (Jul., 2023)  
  [![Star](https://img.shields.io/github/stars/VideoCrafter/Animate-A-Story.svg?style=social&label=Star)](https://github.com/VideoCrafter/Animate-A-Story)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2307.06940)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://videocrafter.github.io/Animate-A-Story/) 

+ [AnimateDiff: Animate Your Personalized Text-to-Image Diffusion Models without Specific Tuning](https://arxiv.org/abs/2307.04725) (Jul., 2023)  
  [![Star](https://img.shields.io/github/stars/guoyww/animatediff.svg?style=social&label=Star)](https://github.com/guoyww/animatediff/)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2307.04725)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://animatediff.github.io/) 

+ [DisCo: Disentangled Control for Referring Human Dance Generation in Real World](https://arxiv.org/abs/2307.000400) (Jul., 2023)  
  [![Star](https://img.shields.io/github/stars/Wangt-CN/DisCo.svg?style=social&label=Star)](https://github.com/Wangt-CN/DisCo)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2307.00040)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://disco-dance.github.io/) 

+ [Learn the Force We Can: Enabling Sparse Motion Control in Multi-Object Video Generation](https://arxiv.org/abs/2306.03988) (Jun., 2023)                                       
  [![Star](https://img.shields.io/github/stars/araachie/yoda.svg?style=social&label=Star)](https://github.com/araachie/yoda) 
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.03988)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://araachie.github.io/yoda/) 

+ [VideoComposer: Compositional Video Synthesis with Motion Controllability](https://arxiv.org/abs/2306.02018) (Jun., 2023)  
  [![Star](https://img.shields.io/github/stars/damo-vilab/videocomposer.svg?style=social&label=Star)](https://github.com/damo-vilab/videocomposer)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.02018)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://videocomposer.github.io/) 

+ [Probabilistic Adaptation of Text-to-Video Models](https://arxiv.org/abs/2306.01872) (Jun., 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.01872)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://video-adapter.github.io/video-adapter/) 

+ [Make-Your-Video: Customized Video Generation Using Textual and Structural Guidance](https://arxiv.org/abs/2306.00943) (Jun., 2023)  
  [![Star](https://img.shields.io/github/stars/VideoCrafter/Make-Your-Video.svg?style=social&label=Star)](https://github.com/VideoCrafter/Make-Your-Video)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.00943)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://doubiiu.github.io/projects/Make-Your-Video/) 

+ [Gen-L-Video: Multi-Text to Long Video Generation via Temporal Co-Denoising](https://arxiv.org/abs/2305.18264) (May, 2023)  
  [![Star](https://img.shields.io/github/stars/G-U-N/Gen-L-Video.svg?style=social&label=Star)](https://github.com/G-U-N/Gen-L-Video)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.18264)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://g-u-n.github.io/projects/gen-long-video/index.html) 

+ [Cinematic Mindscapes: High-quality Video Reconstruction from Brain Activity](https://arxiv.org/abs/2305.11675) (May, 2023)  
  [![Star](https://img.shields.io/github/stars/jqin4749/MindVideo.svg?style=social&label=Star)](https://github.com/jqin4749/MindVideo)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.11675) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://mind-video.com/)

+ [Any-to-Any Generation via Composable Diffusion](https://arxiv.org/abs/2305.11846) (May, 2023)  
  [![Star](https://img.shields.io/github/stars/microsoft/i-Code.svg?style=social&label=Star)](https://github.com/microsoft/i-Code/tree/main/i-Code-V3)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.11846) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://codi-gen.github.io/)

+ [VideoFactory: Swap Attention in Spatiotemporal Diffusions for Text-to-Video Generation](https://arxiv.org/abs/2305.10874) (May, 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.10874) 

+ [Preserve Your Own Correlation: A Noise Prior for Video Diffusion Models](https://arxiv.org/abs/2305.10474) (May, 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.10474) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://research.nvidia.com/labs/dir/pyoco/)

+ [LaMD: Latent Motion Diffusion for Video Generation](https://arxiv.org/abs/2304.11603) (Apr., 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.11603) 

+ [Align your Latents: High-Resolution Video Synthesis with Latent Diffusion Models](https://arxiv.org/abs/2304.08818) (CVPR 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.08818) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://research.nvidia.com/labs/toronto-ai/VideoLDM/)

+ [Text2Performer: Text-Driven Human Video Generation](https://arxiv.org/abs/2304.08483) (Apr., 2023)  
  [![Star](https://img.shields.io/github/stars/yumingj/Text2Performer.svg?style=social&label=Star)](https://github.com/yumingj/Text2Performer)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.08483) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://yumingj.github.io/projects/Text2Performer)

+ [Generative Disco: Text-to-Video Generation for Music Visualization](https://arxiv.org/abs/2304.08551) (Apr., 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.08551) 

+ [Latent-Shift: Latent Diffusion with Temporal Shift](https://arxiv.org/abs/2304.08477) (Apr., 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.08477) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://latent-shift.github.io/) 
  
+ [DreamPose: Fashion Image-to-Video Synthesis via Stable Diffusion](https://arxiv.org/abs/2304.06025) (Apr., 2023)  
  [![Star](https://img.shields.io/github/stars/johannakarras/DreamPose.svg?style=social&label=Star)](https://github.com/johannakarras/DreamPose)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.06025) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://grail.cs.washington.edu/projects/dreampose/)

+ [Follow Your Pose: Pose-Guided Text-to-Video Generation using Pose-Free Videos](https://arxiv.org/abs/2304.01186) (Apr., 2023)  
  [![Star](https://img.shields.io/github/stars/mayuelala/FollowYourPose.svg?style=social&label=Star)](https://github.com/mayuelala/FollowYourPose)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.01186) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://follow-your-pose.github.io/) 

+ [Physics-Driven Diffusion Models for Impact Sound Synthesis from Videos](https://arxiv.org/abs/2303.16897) (CVPR 2023)  
  [![Star](https://img.shields.io/github/stars/sukun1045/video-physics-sound-diffusion.svg?style=social&label=Star)](https://github.com/sukun1045/video-physics-sound-diffusion) 
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.16897) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://sukun1045.github.io/video-physics-sound-diffusion/) 

+ [Seer: Language Instructed Video Prediction with Latent Diffusion Models](https://arxiv.org/abs/2303.14897) (Mar., 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.14897) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://seervideodiffusion.github.io/) 

+ [Text2video-Zero: Text-to-Image Diffusion Models Are Zero-Shot Video Generators](https://arxiv.org/abs/2303.13439) (Mar., 2023)   
  [![Star](https://img.shields.io/github/stars/Picsart-AI-Research/Text2Video-Zero.svg?style=social&label=Star)](https://github.com/Picsart-AI-Research/Text2Video-Zero) 
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.13439) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://text2video-zero.github.io/) 

+ [Conditional Image-to-Video Generation with Latent Flow Diffusion Models](https://arxiv.org/abs/2303.13744) (CVPR 2023)   
  [![Star](https://img.shields.io/github/stars/nihaomiao/CVPR23_LFDM.svg?style=social&label=Star)](https://github.com/nihaomiao/CVPR23_LFDM) 
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.13744)

+ [Decomposed Diffusion Models for High-Quality Video Generation](https://arxiv.org/abs/2303.08320) (CVPR 2023)   
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.08320) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://modelscope.cn/models/damo/text-to-video-synthesis/summary) 

+ [Video Probabilistic Diffusion Models in Projected Latent Space](https://arxiv.org/abs/2302.07685) (CVPR 2023)   
  [![Star](https://img.shields.io/github/stars/sihyun-yu/PVDM.svg?style=social&label=Star)](https://github.com/sihyun-yu/PVDM) 
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2302.07685) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://sihyun.me/PVDM/) 

+ [Learning 3D Photography Videos via Self-supervised Diffusion on Single Images](https://arxiv.org/abs/2302.10781) (Feb., 2023)   
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2302.10781)

+ [Structure and Content-Guided Video Synthesis With Diffusion Models](https://arxiv.org/abs/2302.03011) (Feb., 2023)   
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2302.03011) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://research.runwayml.com/gen2) 

+ [Tune-A-Video: One-Shot Tuning of Image Diffusion Models for Text-to-Video Generation](https://arxiv.org/abs/2212.11565) (ICCV 2023)   
  [![Star](https://img.shields.io/github/stars/showlab/Tune-A-Video?style=social)](https://github.com/showlab/Tune-A-Video) 
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2212.11565) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://tuneavideo.github.io/) 

+ [Mm-Diffusion: Learning Multi-Modal Diffusion Models for Joint Audio and Video Generation](https://arxiv.org/abs/2212.09478) (CVPR 2023)   
  [![Star](https://img.shields.io/github/stars/researchmm/MM-Diffusion.svg?style=social&label=Star)](https://github.com/researchmm/MM-Diffusion) 
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2212.09478)

+ [Magvit: Masked Generative Video Transformer](https://arxiv.org/abs/2212.05199) (Dec., 2022)    
  [![Star](https://img.shields.io/github/stars/MAGVIT/magvit.svg?style=social&label=Star)](https://github.com/MAGVIT/magvit) 
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2212.05199) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://magvit.cs.cmu.edu/) 

+ [VIDM: Video Implicit Diffusion Models](https://arxiv.org/abs/2212.00235) (AAAI 2023)   
  [![Star](https://img.shields.io/github/stars/MKFMIKU/VIDM.svg?style=social&label=Star)](https://github.com/MKFMIKU/VIDM) 
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2212.00235) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://kfmei.page/vidm/) 

+ [Efficient Video Prediction via Sparsely Conditioned Flow Matching](https://arxiv.org/abs/2211.14575) (Nov., 2022)   
  [![Star](https://img.shields.io/github/stars/araachie/river.svg?style=social&label=Star)](https://github.com/araachie/river) 
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2211.14575) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://araachie.github.io/river/)

+ [Latent Video Diffusion Models for High-Fidelity Video Generation With Arbitrary Lengths](https://arxiv.org/abs/2211.13221) (Nov., 2022)   
  [![Star](https://img.shields.io/github/stars/YingqingHe/LVDM.svg?style=social&label=Star)](https://github.com/YingqingHe/LVDM) 
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2211.13221) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://yingqinghe.github.io/LVDM/)

+ [SinFusion: Training Diffusion Models on a Single Image or Video](https://arxiv.org/abs/2211.11743) (Nov., 2022)   
  [![Star](https://img.shields.io/github/stars/YingqingHe/LVDM.svg?style=social&label=Star)](https://github.com/yanivnik/sinfusion-code) 
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2211.11743) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://yanivnik.github.io/sinfusion/)

+ [MagicVideo: Efficient Video Generation With Latent Diffusion Models](https://arxiv.org/abs/2211.11018) (Nov., 2022)   
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2211.11018) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://magicvideo.github.io/#)

+ [Imagen Video: High Definition Video Generation With Diffusion Models](https://arxiv.org/abs/2210.02303) (Oct., 2022)   
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2210.02303) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://imagen.research.google/video/)

+ [Make-A-Video: Text-to-Video Generation without Text-Video Data](https://openreview.net/forum?id=nJfylDvgzlq) (ICLR 2023)   
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://openreview.net/forum?id=nJfylDvgzlq) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://makeavideo.studio)

+ [Diffusion Models for Video Prediction and Infilling](https://arxiv.org/abs/2206.07696) (TMLR 2022)   
  [![Star](https://img.shields.io/github/stars/Tobi-r9/RaMViD.svg?style=social&label=Star)](https://github.com/Tobi-r9/RaMViD) 
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2206.07696) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://sites.google.com/view/video-diffusion-prediction)

+ [McVd: Masked Conditional Video Diffusion for Prediction, Generation, and Interpolation](https://arxiv.org/abs/2205.09853) (NeurIPS 2022)   
  [![Star](https://img.shields.io/github/stars/Tobi-r9/RaMViD.svg?style=social&label=Star)](https://github.com/voletiv/mcvd-pytorch)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2205.09853) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://mask-cond-video-diffusion.github.io)

+ [Video Diffusion Models](https://arxiv.org/abs/2204.03458) (Apr., 2022)   
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2204.03458) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://video-diffusion.github.io/)

+ [Diffusion Probabilistic Modeling for Video Generation](https://arxiv.org/abs/2203.09481) (Mar., 2022)   
  [![Star](https://img.shields.io/github/stars/buggyyang/RVD.svg?style=social&label=Star)](https://github.com/buggyyang/RVD) 
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2203.09481)

### Controllable Video Generation
+ [Animate Your Motion: Turning Still Images into Dynamic Videos](https://arxiv.org/abs/2403.10179)(Mar., 2023|ECCV 2024)    
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.10179)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://mingxiao-li.github.io/smcd/)

+ [EasyControl: Transfer ControlNet to Video Diffusion for Controllable Generation and Interpolation](https://arxiv.org/abs/2408.13005) (Aug., 2024)      
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.13005)

+ [ControlNeXt: Powerful and Efficient Control for Image and Video Generation](https://arxiv.org/pdf/2408.06070) (Aug., 2024)      
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2408.06070)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://pbihao.github.io/projects/controlnext/index.html)
  [![Star](https://img.shields.io/github/stars/dvlab-research/ControlNeXt.svg?style=social&label=Star)](https://github.com/dvlab-research/ControlNeXt)
  


+ [TrackGo: A Flexible and Efficient Method for Controllable Video Generation](https://arxiv.org/abs/2408.11475) (Aug., 2024)      
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.11475)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://zhtjtcz.github.io/TrackGo-Page/#)



+ [Puppet-Master: Scaling Interactive Video Generation as a Motion Prior for Part-Level Dynamics](https://arxiv.org/abs/2408.04631) (Aug., 2024)      
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.04631)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://vgg-puppetmaster.github.io/)

+ [Sketch2Scene: Automatic Generation of Interactive 3D Game Scenes from User's Casual Sketches](https://arxiv.org/abs/2408.04567) (Aug., 2024)      
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.04567)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://xrvisionlabs.github.io/Sketch2Scene/)

+ [Expressive Whole-Body 3D Gaussian Avatar) (Aug., 2024)      
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.21686)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://mks0601.github.io/ExAvatar/)
  
  

+ [HumanVid: Demystifying Training Data for Camera-controllable Human Image Animation](https://arxiv.org/pdf/2407.17438) (Jul., 2024)      
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2407.17438)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://humanvid.github.io/#)
  [![Star](https://img.shields.io/github/stars/zhenzhiwang/HumanVid.svg?style=social&label=Star)](https://github.com/zhenzhiwang/HumanVid)
  
+ [Cinemo: Consistent and Controllable Image Animation with Motion Diffusion Models](https://arxiv.org/abs/2407.15642) (Jul., 2024)      
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.15642)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://maxin-cn.github.io/cinemo_project/)
  [![Star](https://img.shields.io/github/stars/maxin-cn/Cinemo.svg?style=social&label=Star)](https://github.com/maxin-cn/Cinemo)


+ [VD3D: Taming Large Video Diffusion Transformers for 3D Camera Control](https://arxiv.org/abs/2407.12781) (Jul., 2024)      
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.12781)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://snap-research.github.io/vd3d/)

+ [Still-Moving: Customized Video Generation without Customized Video Data](https://arxiv.org/abs/2407.08674) (Jul., 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.08674)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://still-moving.github.io/)

+ [LivePortrait: Efficient Portrait Animation with Stitching and Retargeting Control](https://arxiv.org/abs/2407.03168) (Jul., 2024)  
  [![Star](https://img.shields.io/github/stars/KwaiVGI/LivePortrait.svg?style=social&label=Star)](https://github.com/KwaiVGI/LivePortrait)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.03168)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://github.com/KwaiVGI/LivePortrait)

+ [Image Conductor: Precision Control for Interactive Video Synthesis](https://arxiv.org/pdf/2406.15339) (Jun., 2024)  
  [![Star](https://img.shields.io/github/stars/liyaowei-stu/ImageConductor.svg?style=social&label=Star)](https://github.com/liyaowei-stu/ImageConductor)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2406.15339)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://liyaowei-stu.github.io/project/ImageConductor/)

+ [MimicMotion: High-Quality Human Motion Video Generation with Confidence-aware Pose Guidance](https://arxiv.org/abs/2406.19680) (Jun., 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.19680)

+ [FreeTraj: Tuning-Free Trajectory Control in Video Diffusion Models](https://arxiv.org/abs/2406.16863) (Jun., 2024)  
  [![Star](https://img.shields.io/github/stars/arthur-qiu/FreeTraj.svg?style=social&label=Star)](https://github.com/arthur-qiu/FreeTraj)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.16863)
  [![Website](https://img.shields.io/badge/Website-9cf)](http://haonanqiu.com/projects/FreeTraj.html)

+ [MOFA-Video: Controllable Image Animation via Generative Motion Field Adaptions in Frozen Image-to-Video Diffusion Model](https://arxiv.org/abs/2405.20222) (Jun., 2024)      
  [![Star](https://img.shields.io/github/stars/MyNiuuu/MOFA-Video.svg?style=social&label=Star)](https://github.com/MyNiuuu/MOFA-Video)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.20222)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://myniuuu.github.io/MOFA_Video/)

+ [Champ: Controllable and Consistent Human Image Animation with 3D Parametric Guidance](https://arxiv.org/abs/2403.14781) (Mar., 2024)  
  [![Star](https://img.shields.io/github/stars/fudan-generative-vision/champ.svg?style=social&label=Star)](https://github.com/fudan-generative-vision/champ)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.14781)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://fudan-generative-vision.github.io/champ/)

+ [TrailBlazer: Trajectory Control for Diffusion-Based Video Generation](https://arxiv.org/abs/2401.00896) (Jan., 2024)  
  [![Star](https://img.shields.io/github/stars/hohonu-vicml/Trailblazer.svg?style=social&label=Star)](https://github.com/hohonu-vicml/Trailblazer)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.00896)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://hohonu-vicml.github.io/Trailblazer.Page/)

+ [Motion-Zero: Zero-Shot Moving Object Control Framework for Diffusion-Based Video Generation](https://arxiv.org/abs/2401.10150) (Jan., 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.10150)

+ [Moonshot: Towards Controllable Video Generation and Editing with Multimodal Conditions](https://arxiv.org/abs/2401.01827) (Jan., 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.01827)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://showlab.github.io/Moonshot/)

+ [MotionCtrl: A Unified and Flexible Motion Controller for Video Generation](https://arxiv.org/abs/2312.03641) (Dec., 2023)  
  [![Star](https://img.shields.io/github/stars/TencentARC/MotionCtrl.svg?style=social&label=Star)](https://github.com/TencentARC/MotionCtrl)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.03641)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://wzhouxiff.github.io/projects/MotionCtrl/)

+ [Animate Anyone: Consistent and Controllable Image-to-Video Synthesis for Character Animation](https://arxiv.org/abs/2311.17117) (Nov., 2023)  
  [![Star](https://img.shields.io/github/stars/HumanAIGC/AnimateAnyone.svg?style=social&label=Star)](https://github.com/HumanAIGC/AnimateAnyone)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.17117)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://humanaigc.github.io/animate-anyone/)

+ [SparseCtrl: Adding Sparse Controls to Text-to-Video Diffusion Models](https://arxiv.org/abs/2311.16933) (Nov., 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.16933)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://guoyww.github.io/projects/SparseCtrl/)

+ [Control-A-Video: Controllable Text-to-Video Generation with Diffusion Models](https://arxiv.org/abs/2305.13840) (May, 2023)  
  [![Star](https://img.shields.io/github/stars/Weifeng-Chen/control-a-video.svg?style=social&label=Star)](https://github.com/Weifeng-Chen/control-a-video)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.13840)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://controlavideo.github.io/) 

+ [Motion-Conditioned Diffusion Model for Controllable Video Synthesis](https://arxiv.org/abs/2304.14404) (Apr., 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.14404) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://tsaishien-chen.github.io/MCDiff/)

+ [ControlVideo: Training-free Controllable Text-to-Video Generation](https://arxiv.org/abs/2305.13077) (May, 2023)  
  [![Star](https://img.shields.io/github/stars/YBYBZhang/ControlVideo.svg?style=social&label=Star)](https://github.com/YBYBZhang/ControlVideo)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.13077) 
  
+ [DragNUWA: Fine-grained Control in Video Generation by Integrating Text, Image, and Trajectory](https://arxiv.org/abs/2308.08089) (Aug., 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.08089)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://www.microsoft.com/en-us/research/project/dragnuwa/) 

+ [DragAnything: Motion Control for Anything using Entity Representation](https://arxiv.org/abs/2403.07420) (Mar., 2024)  
  [![Star](https://img.shields.io/github/stars/showlab/DragAnything.svg?style=social&label=Star)](https://github.com/showlab/DragAnything)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.07420)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://weijiawu.github.io/draganything_page/)

+ [CameraCtrl: Enabling Camera Control for Video Diffusion Models](https://arxiv.org/abs/2404.02101) (Apr., 2024)  
  [![Star](https://img.shields.io/github/stars/hehao13/CameraCtrl.svg?style=social&label=Star)](https://github.com/hehao13/CameraCtrl) 
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.02101)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://hehao13.github.io/projects-CameraCtrl/)

+ [Training-free Camera Control for Video Generation](https://arxiv.org/pdf/2406.10126) (Jun., 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2406.10126)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://lifedecoder.github.io/CamTrol/)

+ [Customizing Motion in Text-to-Video Diffusion Models](https://arxiv.org/abs/2312.04966) (Dec., 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.04966)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://joaanna.github.io/customizing_motion/)

+ [MotionClone: Training-Free Motion Cloning for Controllable Video Generation](https://arxiv.org/abs/2406.05338) (Jun., 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.05338)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://bujiazi.github.io/motionclone.github.io/)

+ [Tora: Trajectory-oriented Diffusion Transformer for Video Generation](https://arxiv.org/abs/2407.21705) (Jul., 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.21705)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://ali-videoai.github.io/tora_video/)

### Motion Customization

+ [MotionDirector: Motion Customization of Text-to-Video Diffusion Models](https://arxiv.org/abs/2310.08465) (Sep., 2023 | ECCV 2024)  
  [![Star](https://img.shields.io/github/stars/showlab/MotionDirector.svg?style=social&label=Star)](https://github.com/showlab/MotionDirector)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.08465)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://showlab.github.io/MotionDirector/)
  
+ [LAMP: Learn A Motion Pattern for Few-Shot-Based Video Generation](https://arxiv.org/abs/2310.10769) (Oct., 2023 | CVPR 2024)  
  [![Star](https://img.shields.io/github/stars/RQ-Wu/LAMP.svg?style=social&label=Star)](https://github.com/RQ-Wu/LAMP)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.10769)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://rq-wu.github.io/projects/LAMP/)
  
+ [Vmc: Video motion customization using temporal attention adaption for text-to-video diffusion models](https://arxiv.org/abs/2312.00845) (Dec., 2023 | CVPR 2024)  
  [![Star](https://img.shields.io/github/stars/HyeonHo99/Video-Motion-Customization.svg?style=social&label=Star)](https://github.com/HyeonHo99/Video-Motion-Customization)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.00845)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://video-motion-customization.github.io/)
  
+ [DreamVideo: Composing Your Dream Videos with Customized Subject and Motion](https://arxiv.org/abs/2312.04433) (Dec., 2023 | CVPR 2024)  
  [![Star](https://img.shields.io/github/stars/ali-vilab/VGen.svg?style=social&label=Star)](https://github.com/ali-vilab/VGen)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.04433)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://dreamvideo-t2v.github.io/)

+ [MotionCtrl: A Unified and Flexible Motion Controller for Video Generation](https://arxiv.org/abs/2312.03641) (Dec., 2023 | SIGGRAPH 2024)  
  [![Star](https://img.shields.io/github/stars/TencentARC/MotionCtrl.svg?style=social&label=Star)](https://github.com/TencentARC/MotionCtrl)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.03641)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://wzhouxiff.github.io/projects/MotionCtrl/)

+ [Customizing Motion in Text-to-Video Diffusion Models](https://arxiv.org/abs/2312.04966) (Dec., 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.04966)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://joaanna.github.io/customizing_motion/)

+ [Direct-a-Video: Customized Video Generation with User-Directed Camera Movement and Object Motion](https://arxiv.org/abs/2402.03162) (Feb., 2024)  
  [![Star](https://img.shields.io/github/stars/ysy31415/direct_a_video.svg?style=social&label=Star)](https://github.com/ysy31415/direct_a_video)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.03162)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://direct-a-video.github.io/)

+ [Customize-A-Video: One-Shot Motion Customization of Text-to-Video Diffusion Models](https://arxiv.org/abs/2402.14780) (Feb., 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.14780)

+ [DreamMotion: Space-Time Self-Similar Score Distillation for Zero-Shot Video Editing](https://arxiv.org/abs/2403.12002) (Mar., 2024 | ECCV 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.12002)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://hyeonho99.github.io/dreammotion/)

+ [DragAnything: Motion Control for Anything using Entity Representation](https://arxiv.org/abs/2403.07420) (Mar., 2024 | ECCV 2024)

  [![Star](https://img.shields.io/github/stars/EnVision-Research/MotionInversion.svg?style=social&label=Star)](https://github.com/EnVision-Research/MotionInversion)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.07420)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://weijiawu.github.io/draganything_page/)

+ [Spectral Motion Alignment for Video Motion Transfer using Diffusion Models](https://arxiv.org/abs/2403.15249) (Mar., 2024)  
  [![Star](https://img.shields.io/github/stars/geonyeong-park/Spectral-Motion-Alignment.svg?style=social&label=Star)](https://github.com/geonyeong-park/Spectral-Motion-Alignment)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.15249)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://geonyeong-park.github.io/spectral-motion-alignment/)

+ [Motion Inversion for Video Customization](https://arxiv.org/abs/2403.20193) (Mar., 2024)  
  [![Star](https://img.shields.io/github/stars/EnVision-Research/MotionInversion.svg?style=social&label=Star)](https://github.com/EnVision-Research/MotionInversion)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.20193)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://wileewang.github.io/MotionInversion/)

+ [Edit-Your-Motion: Space-Time Diffusion Decoupling Learning for Video Motion Editing](https://arxiv.org/abs/2405.04496) (Mar., 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.04496)

+ [Video Diffusion Models are Training-free Motion Interpreter and Controller](https://arxiv.org/abs/2405.14864) (May., 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.14864)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://xizaoqu.github.io/moft/)

+ [Collaborative Video Diffusion: Consistent Multi-video Generation with Camera Control](https://arxiv.org/abs/2405.17414) (May., 2024)  
  [![Star](https://img.shields.io/github/stars/CollaborativeVideoDiffusion/CVD.svg?style=social&label=Star)](https://github.com/CollaborativeVideoDiffusion/CVD)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.17414)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://collaborativevideodiffusion.github.io/)

+ [MotionClone: Training-Free Motion Cloning for Controllable Video Generation](https://arxiv.org/abs/2406.05338) (Jun., 2024)  
  [![Star](https://img.shields.io/github/stars/Bujiazi/MotionClone.svg?style=social&label=Star)](https://github.com/Bujiazi/MotionClone/)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.05338)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://bujiazi.github.io/motionclone.github.io/)

+ [FreeTraj: Tuning-Free Trajectory Control in Video Diffusion Models](https://arxiv.org/abs/2406.16863) (Jun., 2024)  
  [![Star](https://img.shields.io/github/stars/arthur-qiu/FreeTraj.svg?style=social&label=Star)](https://github.com/arthur-qiu/FreeTraj)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.16863)
  [![Website](https://img.shields.io/badge/Website-9cf)](http://haonanqiu.com/projects/FreeTraj.html)

+ [Zero-Shot Controllable Image-to-Video Animation via Motion Decomposition](https://www.amazon.science/publications/zero-shot-controllable-image-to-video-animation-via-motion-decomposition) (Jul., 2024 | ACM MM 2024)  

+ [Tora: Trajectory-oriented Diffusion Transformer for Video Generation](https://arxiv.org/abs/2407.21705) (Jul., 2024)  
  [![Star](https://img.shields.io/github/stars/arthur-qiu/FreeTraj.svg?style=social&label=Star)](https://github.com/arthur-qiu/FreeTraj)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.21705)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://ali-videoai.github.io/tora_video/)

+ [Reenact Anything: Semantic Video Motion Transfer Using Motion-Textual Inversion](https://arxiv.org/abs/2408.00458) (Aug., 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.00458)

  
### Long Video / Film Generation

+ [CinePreGen: Camera Controllable Video Previsualization via Engine-powered Diffusion](https://arxiv.org/pdf/2408.17424) (Aug., 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2408.17424)


+ [DreamCinema: Cinematic Transfer with Free Camera and 3D Character](https://arxiv.org/abs/2408.12601) (Aug., 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.12601)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://liuff19.github.io/DreamCinema/)
  [![Star](https://img.shields.io/github/stars/chen-wl20/DreamCinema?tab=readme-ov-file.svg?style=social&label=Star)](https://github.com/chen-wl20/DreamCinema?tab=readme-ov-file)


+ [SkyScript-100M: 1,000,000,000 Pairs of Scripts and Shooting Scripts for Short Drama](https://arxiv.org/pdf/2408.09333) (Aug., 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2408.09333)
  [![Star](https://img.shields.io/github/stars/vaew/SkyScript-100M.svg?style=social&label=Star)](https://github.com/vaew/SkyScript-100M)

+ [Anim-Director: A Large Multimodal Model Powered Agent for Controllable Animation Video Generation](https://arxiv.org/abs/2408.09787) (Aug., 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.09787)
  [![Star](https://img.shields.io/github/stars/HITsz-TMG/Anim-Director.svg?style=social&label=Star)](https://github.com/HITsz-TMG/Anim-Director)
  
+ [Kubrick: Multimodal Agent Collaborations for Synthetic Video Generation](https://arxiv.org/pdf/2408.10453) (Aug., 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2408.10453)


+ [DreamFactory: Pioneering Multi-Scene Long Video Generation with a Multi-Agent Framework](https://arxiv.org/abs/2408.11788) (Jul, 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.11788)


+ [MovieDreamer: Hierarchical Generation for Coherent Long Visual Sequence](https://arxiv.org/abs/2407.16655) (Jul, 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.16655)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://aim-uofa.github.io/MovieDreamer/)
  [![Star](https://img.shields.io/github/stars/aim-uofa/MovieDreamer.svg?style=social&label=Star)](https://github.com/aim-uofa/MovieDreamer)
  
+ [AutoAD-Zero: A Training-Free Framework for Zero-Shot Audio Description](https://arxiv.org/abs/2407.15850) (Jul, 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.15850)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://www.robots.ox.ac.uk/~vgg/research/autoad-zero/)
  [![Star](https://img.shields.io/github/stars/Jyxarthur/AutoAD-Zero.svg?style=social&label=Star)](https://github.com/Jyxarthur/AutoAD-Zero)



+ [AesopAgent: Agent-driven Evolutionary System on Story-to-Video Production](https://arxiv.org/abs/2403.07952) (Jul, 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.07952)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://aesopai.github.io/)

+ [TheaterGen: Character Management with LLM for Consistent Multi-turn Image Generation](https://arxiv.org/abs/2404.18919) (Jul, 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.18919)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://howe140.github.io/theatergen.io/)
  [![Star](https://img.shields.io/github/stars/donahowe/Theatergen.svg?style=social&label=Star)](https://github.com/donahowe/Theatergen)

+ [AutoStudio: Crafting Consistent Subjects in Multi-turn Interactive Image Generation](https://github.com/donahowe/AutoStudio) (Jul, 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.01388)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://github.com/donahowe/AutoStudio)
  [![Star](https://img.shields.io/github/stars/donahowe/AutoStudio.svg?style=social&label=Star)](https://github.com/donahowe/AutoStudio)

+ [DreamStory: Open-Domain Story Visualization by LLM-Guided Multi-Subject Consistent Diffusion](https://arxiv.org/abs/2407.12899) (Jul, 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.12899)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://dream-xyz.github.io/dreamstory)

+ [VideoDirectorGPT: Consistent Multi-scene Video Generation via LLM-Guided Planning](https://arxiv.org/abs/2309.15091) (Jul, 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.15091)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://videodirectorgpt.github.io/)
  [![Star](https://img.shields.io/github/stars/HL-hanlin/VideoDirectorGPT.svg?style=social&label=Star)](https://github.com/HL-hanlin/VideoDirectorGPT)

### Video Generation with Physical Prior / 3D

+ [StereoCrafter: Diffusion-based Generation of Long and High-fidelity Stereoscopic 3D from Monocular Videos](https://arxiv.org/pdf/2409.07447) (Oct, 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2409.07447)
  [![Website](https://img.shields.io/badge/Website-9cf)](http://stereocrafter.github.io/)


+ [ViewCrafter: Taming Video Diffusion Models for High-fidelity Novel View Synthesis](https://arxiv.org/abs/2409.02048) (Sep, 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.02048)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://drexubery.github.io/ViewCrafter/)
  [![Star](https://img.shields.io/github/stars/Drexubery/ViewCrafter.svg?style=social&label=Star)](https://github.com/Drexubery/ViewCrafter)

+ [Compositional 3D-aware Video Generation with LLM Director](https://www.microsoft.com/en-us/research/project/compositional-3d-aware-video-generation/) (Aug, 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2409.00558)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://www.microsoft.com/en-us/research/project/compositional-3d-aware-video-generation/)
  
+ [IDOL: Unified Dual-Modal Latent Diffusion for Human-Centric Joint Video-Depth Generation](https://arxiv.org/abs/2407.10937) (Jul, 2024)  
  [![Star](https://img.shields.io/github/stars/yhZhai/idol.svg?style=social&label=Star)](https://github.com/yhZhai/idol)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.16823)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://arxiv.org/abs/2407.10937)
  
+ [PhysDreamer: Physics-Based Interaction with 3D Objects via Video Generation](https://arxiv.org/abs/2404.13026) (ECCV 2024)  
  [![Star](https://img.shields.io/github/stars/a1600012888/PhysDreamer.svg?style=social&label=Star)](https://github.com/a1600012888/PhysDreamer)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.13026)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://physdreamer.github.io/)

### Video Editing 

+ [Unified Editing of Panorama, 3D Scenes, and Videos Through Disentangled Self-Attention Injection](https://arxiv.org/abs/2405.16823) (May, 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.16823)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://unifyediting.github.io/)

+ [I2VEdit: First-Frame-Guided Video Editing via Image-to-Video Diffusion Models](https://arxiv.org/abs/2405.16537) (May, 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.16537)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://i2vedit.github.io/)

+ [Looking Backward: Streaming Video-to-Video Translation with Feature Banks](https://arxiv.org/abs/2405.15757) (May, 2024)  
  [![Star](https://img.shields.io/github/stars/Jeff-LiangF/streamv2v.svg?style=social&label=Star)](https://github.com/Jeff-LiangF/streamv2v)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.15757)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://jeff-liangf.github.io/projects/streamv2v/)

+ [ReVideo: Remake a Video with Motion and Content Control](https://arxiv.org/abs/2405.13865) (May, 2024)  
  [![Star](https://img.shields.io/github/stars/MC-E/ReVideo.svg?style=social&label=Star)](https://github.com/MC-E/ReVideo)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.13865)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://mc-e.github.io/project/ReVideo/)

+ [Slicedit: Zero-Shot Video Editing With Text-to-Image Diffusion Models Using Spatio-Temporal Slices](https://arxiv.org/abs/2405.12211) (May, 2024)  
  [![Star](https://img.shields.io/github/stars/fallenshock/Slicedit.svg?style=social&label=Star)](https://github.com/fallenshock/Slicedit)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.12211)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://matankleiner.github.io/slicedit/)

+ [ViViD: Video Virtual Try-on using Diffusion Models](https://arxiv.org/abs/2405.11794) (May, 2024)  
  [![Star](https://img.shields.io/github/stars/BecauseImBatman0/ViViD.svg?style=social&label=Star)](https://github.com/BecauseImBatman0/ViViD)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.11794)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://becauseimbatman0.github.io/ViViD)

+ [Edit-Your-Motion: Space-Time Diffusion Decoupling Learning for Video Motion Editing](https://arxiv.org/abs/2405.04496) (May, 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.04496)

+ [GenVideo: One-shot target-image and shape aware video editing using T2I diffusion models](https://arxiv.org/abs/2404.12541) (Apr., 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.12541)

+ [EVA: Zero-shot Accurate Attributes and Multi-Object Video Editing](https://arxiv.org/abs/2403.16111) (Mar., 2024)  
  [![Star](https://img.shields.io/github/stars/knightyxp/EVA_Video_Edit.svg?style=social&label=Star)](https://github.com/knightyxp/EVA_Video_Edit)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.16111)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://knightyxp.github.io/EVA/)

+ [Spectral Motion Alignment for Video Motion Transfer using Diffusion Models](https://arxiv.org/abs/2403.15249) (Mar., 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.15249)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://geonyeong-park.github.io/spectral-motion-alignment/)

+ [AnyV2V: A Tuning-Free Framework For Any Video-to-Video Editing Tasks](https://arxiv.org/abs/2403.14468) (Mar., 2024)  
  [![Star](https://img.shields.io/github/stars/TIGER-AI-Lab/AnyV2V.svg?style=social&label=Star)](https://github.com/TIGER-AI-Lab/AnyV2V)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.14468)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://tiger-ai-lab.github.io/AnyV2V/)

+ [CoCoCo: Improving Text-Guided Video Inpainting for Better Consistency, Controllability and Compatibility](https://arxiv.org/abs/2403.12035) (Mar., 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.12035)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://cococozibojia.github.io/)
  [![Star](https://img.shields.io/github/stars/zibojia/COCOCO.svg?style=social&label=Star)](https://github.com/zibojia/COCOCO)

+ [DreamMotion: Space-Time Self-Similarity Score Distillation for Zero-Shot Video Editing](https://arxiv.org/abs/2403.12002) (Mar., 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.12002)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://hyeonho99.github.io/dreammotion/)

+ [Video Editing via Factorized Diffusion Distillation](https://arxiv.org/abs/2403.09334) (Mar., 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.09334)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://fdd-video-edit.github.io/)

+ [FastVideoEdit: Leveraging Consistency Models for Efficient Text-to-Video Editing](https://arxiv.org/abs/2403.06269) (Mar., 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.06269)

+ [UniEdit: A Unified Tuning-Free Framework for Video Motion and Appearance Editing](https://arxiv.org/abs/2402.13185) (Feb., 2024)  
  [![Star](https://img.shields.io/github/stars/JianhongBai/UniEdit.svg?style=social&label=Star)](https://github.com/JianhongBai/UniEdit)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.13185)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://jianhongbai.github.io/UniEdit/)
  
+ [Object-Centric Diffusion for Efficient Video Editing](https://arxiv.org/abs/2401.05735) (Jan., 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.05735)

+ [VASE: Object-Centric Shape and Appearance Manipulation of Real Videos](https://arxiv.org/abs/2401.02473) (Jan., 2024)  
  [![Star](https://img.shields.io/github/stars/helia95/VASE.svg?style=social&label=Star)](https://github.com/helia95/VASE)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.02473)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://helia95.github.io/vase-website/)

+ [FlowVid: Taming Imperfect Optical Flows for Consistent Video-to-Video Synthesis](https://arxiv.org/abs/2312.17681) (Dec., 2023)  
  [![Star](https://img.shields.io/github/stars/Jeff-LiangF/FlowVid.svg?style=social&label=Star)](https://github.com/Jeff-LiangF/FlowVid)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.17681)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://jeff-liangf.github.io/projects/flowvid/)

+ [Fairy: Fast Parallelized Instruction-Guided Video-to-Video Synthesis](https://arxiv.org/abs/2312.13834) (Dec., 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.13834)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://fairy-video2video.github.io/)

+ [RealCraft: Attention Control as A Solution for Zero-shot Long Video Editing](https://arxiv.org/abs/2312.12635) (Dec., 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.12635)

+ [MaskINT: Video Editing via Interpolative Non-autoregressive Masked Transformers](https://arxiv.org/abs/2312.12468) (Dec., 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.12468)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://maskint.github.io/)

+ [VidToMe: Video Token Merging for Zero-Shot Video Editing](https://arxiv.org/abs/2312.10656) (Dec., 2023)  
  [![Star](https://img.shields.io/github/stars/lixirui142/VidToMe.svg?style=social&label=Star)](https://github.com/lixirui142/VidToMe)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.10656)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://vidtome-diffusion.github.io/)

+ [A Video is Worth 256 Bases: Spatial-Temporal Expectation-Maximization Inversion for Zero-Shot Video Editing](https://arxiv.org/abs/2312.05856) (Dec., 2023)  
  [![Star](https://img.shields.io/github/stars/STEM-Inv/stem-inv.svg?style=social&label=Star)](https://github.com/STEM-Inv/stem-inv)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.05856)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://stem-inv.github.io/page/)

+ [Neutral Editing Framework for Diffusion-based Video Editing](https://arxiv.org/abs/2312.06708) (Dec., 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.06708)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://neuedit.github.io/)
  
+ [DiffusionAtlas: High-Fidelity Consistent Diffusion Video Editing](https://arxiv.org/abs/2312.03772) (Dec., 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.03772)

+ [RAVE: Randomized Noise Shuffling for Fast and Consistent Video Editing with Diffusion Models](https://arxiv.org/abs/2312.04524) (Dec., 2023)  
  [![Star](https://img.shields.io/github/stars/rehg-lab/RAVE.svg?style=social&label=Star)](https://github.com/rehg-lab/RAVE)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.04524)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://rave-video.github.io/)

+ [SAVE: Protagonist Diversification with Structure Agnostic Video Editing](https://arxiv.org/abs/2312.02503) (Dec., 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.02503)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://ldynx.github.io/SAVE/)

+ [MagicStick: Controllable Video Editing via Control Handle Transformations](https://arxiv.org/abs/2312.03047) (Dec., 2023)  
  [![Star](https://img.shields.io/github/stars/mayuelala/MagicStick.svg?style=social&label=Star)](https://github.com/mayuelala/MagicStick)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.03047)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://magic-stick-edit.github.io/)

+ [VideoSwap: Customized Video Subject Swapping with Interactive Semantic Point Correspondence](https://arxiv.org/abs/2312.02087) (CVPR 2024)  
  [![Star](https://img.shields.io/github/stars/showlab/VideoSwap.svg?style=social&label=Star)](https://github.com/showlab/VideoSwap)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.02087)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://videoswap.github.io/)

+ [DragVideo: Interactive Drag-style Video Editing](https://arxiv.org/abs/2312.02216) (Dec., 2023)  
  [![Star](https://img.shields.io/github/stars/RickySkywalker/DragVideo-Official.svg?style=social&label=Star)](https://github.com/RickySkywalker/DragVideo-Official)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.02216)

+ [Drag-A-Video: Non-rigid Video Editing with Point-based Interaction](https://arxiv.org/abs/2312.02936) (Dec., 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.02936)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://drag-a-video.github.io/)

+ [BIVDiff: A Training-Free Framework for General-Purpose Video Synthesis via Bridging Image and Video Diffusion Models](https://arxiv.org/abs/2312.02813) (Dec., 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.02813)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://bivdiff.github.io/)

+ [VMC: Video Motion Customization using Temporal Attention Adaption for Text-to-Video Diffusion Models](https://arxiv.org/abs/2312.00845) (CVPR 2024)  
  [![Star](https://img.shields.io/github/stars/HyeonHo99/Video-Motion-Customization.svg?style=social&label=Star)](https://github.com/HyeonHo99/Video-Motion-Customization)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.00845)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://video-motion-customization.github.io)

+ [FLATTEN: optical FLow-guided ATTENtion for consistent text-to-video editing](https://arxiv.org/abs/2310.05922) (ICLR 2024)  
  [![Star](https://img.shields.io/github/stars/yrcong/flatten.svg?style=social&label=Star)](https://github.com/yrcong/flatten)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.05922)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://flatten-video-editing.github.io)

+ [MotionEditor: Editing Video Motion via Content-Aware Diffusion](https://arxiv.org/abs/2311.18830) (Nov., 2023)  
  [![Star](https://img.shields.io/github/stars/Francis-Rings/MotionEditor.svg?style=social&label=Star)](https://github.com/Francis-Rings/MotionEditor)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.18830)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://francis-rings.github.io/MotionEditor/)

+ [Motion-Conditioned Image Animation for Video Editing](https://arxiv.org/abs/2311.18827) (Nov., 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.18827) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://facebookresearch.github.io/MoCA/)

+ [Space-Time Diffusion Features for Zero-Shot Text-Driven Motion Transfer](https://arxiv.org/abs/2311.17009) (CVPR 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.17009) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://diffusion-motion-transfer.github.io/)

+ [Cut-and-Paste: Subject-Driven Video Editing with Attention Control](https://arxiv.org/abs/2311.11697) (Nov., 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.11697)

+ [LatentWarp: Consistent Diffusion Latents for Zero-Shot Video-to-Video Translation](https://arxiv.org/abs/2311.00353) (Nov., 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.00353) 
  
+ [Fuse Your Latents: Video Editing with Multi-source Latent Diffusion Models](https://arxiv.org/abs/2310.16400) (Oct., 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.16400) 

+ [DynVideo-E: Harnessing Dynamic NeRF for Large-Scale Motion- and View-Change Human-Centric Video Editing](https://arxiv.org/abs/2310.10624) (Oct., 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.10624) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://showlab.github.io/DynVideo-E/)

+ [Ground-A-Video: Zero-shot Grounded Video Editing using Text-to-image Diffusion Models](https://arxiv.org/abs/2310.01107) (ICLR 2024)  
  [![Star](https://img.shields.io/github/stars/Ground-A-Video/Ground-A-Video.svg?style=social&label=Star)](https://github.com/Ground-A-Video/Ground-A-Video) 
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.01107) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://ground-a-video.github.io/)

+ [CCEdit: Creative and Controllable Video Editing via Diffusion Models](https://arxiv.org/abs/2309.16496) (Sep., 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.16496)

+ [MagicProp: Diffusion-based Video Editing via Motion-aware Appearance Propagation](https://arxiv.org/abs/2309.00908) (Sep., 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.00908)

+ [MagicEdit: High-Fidelity and Temporally Coherent Video Editing](https://arxiv.org/abs/2308.14749) (Aug., 2023)  
  [![Star](https://img.shields.io/github/stars/magic-research/magic-edit.svg?style=social&label=Star)](https://github.com/magic-research/magic-edit)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.14749)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://magic-edit.github.io/) 

+ [StableVideo: Text-driven Consistency-aware Diffusion Video Editing](https://arxiv.org/abs/2308.09592) (ICCV 2023)  
  [![Star](https://img.shields.io/github/stars/rese1f/StableVideo.svg?style=social&label=Star)](https://github.com/rese1f/StableVideo)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.09592)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://rese1f.github.io/StableVideo/) 

+ [CoDeF: Content Deformation Fields for Temporally Consistent Video Processing](https://arxiv.org/abs/2308.07926) (CVPR 2024)  
  [![Star](https://img.shields.io/github/stars/qiuyu96/CoDeF.svg?style=social&label=Star)](https://github.com/qiuyu96/CoDeF)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.07926)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://qiuyu96.github.io/CoDeF/) 

+ [TokenFlow: Consistent Diffusion Features for Consistent Video Editing](https://arxiv.org/abs/2307.10373) (ICLR 2024)   
  [![Star](https://img.shields.io/github/stars/omerbt/TokenFlow.svg?style=social&label=Star)](https://github.com/omerbt/TokenFlow) 
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2307.10373) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://diffusion-tokenflow.github.io/)

+ [INVE: Interactive Neural Video Editing](https://arxiv.org/abs/2307.07663) (Jul., 2023)   
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2307.07663) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://gabriel-huang.github.io/inve/)  

+ [VidEdit: Zero-Shot and Spatially Aware Text-Driven Video Editing](https://arxiv.org/abs//2306.08707) (Jun., 2023)   
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs//2306.08707) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://videdit.github.io/) 

+ [Rerender A Video: Zero-Shot Text-Guided Video-to-Video Translation](https://arxiv.org/abs/2306.07954) (SIGGRAPH Asia 2023)                                       
  [![Star](https://img.shields.io/github/stars/williamyang1991/Rerender_A_Video.svg?style=social&label=Star)](https://github.com/williamyang1991/Rerender_A_Video) 
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.07954)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://www.mmlab-ntu.com/project/rerender/) 

+ [ControlVideo: Adding Conditional Control for One Shot Text-to-Video Editing](https://arxiv.org/abs/2305.17098) (May, 2023)   
  [![Star](https://img.shields.io/github/stars/thu-ml/controlvideo.svg?style=social&label=Star)](https://github.com/thu-ml/controlvideo) 
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.17098) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://ml.cs.tsinghua.edu.cn/controlvideo/) 

+ [Make-A-Protagonist: Generic Video Editing with An Ensemble of Experts](https://arxiv.org/abs/2305.08850) (May, 2023)   
  [![Star](https://img.shields.io/github/stars/Make-A-Protagonist/Make-A-Protagonist.svg?style=social&label=Star)](https://github.com/Make-A-Protagonist/Make-A-Protagonist) 
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.08850) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://make-a-protagonist.github.io/) 

+ [Soundini: Sound-Guided Diffusion for Natural Video Editing](https://arxiv.org/abs/2304.06818) (Apr., 2023)   
  [![Star](https://img.shields.io/github/stars/kuai-lab/soundini-official.svg?style=social&label=Star)](https://github.com/kuai-lab/soundini-official) 
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.06818) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://kuai-lab.github.io/soundini-gallery/) 

+ [Zero-Shot Video Editing Using Off-the-Shelf Image Diffusion Models](https://arxiv.org/abs/2303.17599) (Mar., 2023)   
  [![Star](https://img.shields.io/github/stars/baaivision/vid2vid-zero.svg?style=social&label=Star)](https://github.com/baaivision/vid2vid-zero) 
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.17599) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://huggingface.co/spaces/BAAI/vid2vid-zero) 

+ [Edit-A-Video: Single Video Editing with Object-Aware Consistency](https://arxiv.org/abs/2303.17599) (Mar., 2023)   
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.07945) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://edit-a-video.github.io/) 

+ [FateZero: Fusing Attentions for Zero-shot Text-based Video Editing](https://arxiv.org/abs/2303.09535) (Mar., 2023)   
  [![Star](https://img.shields.io/github/stars/ChenyangQiQi/FateZero.svg?style=social&label=Star)](https://github.com/ChenyangQiQi/FateZero) 
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.09535) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://fate-zero-edit.github.io/)

+ [Pix2video: Video Editing Using Image Diffusion](https://arxiv.org/abs/2303.12688) (Mar., 2023)   
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.12688) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://duyguceylan.github.io/pix2video.github.io/) 

+ [Video-P2P: Video Editing with Cross-attention Control](https://arxiv.org/abs/2303.04761) (Mar., 2023)   
  [![Star](https://img.shields.io/github/stars/ShaoTengLiu/Video-P2P.svg?style=social&label=Star)](https://github.com/ShaoTengLiu/Video-P2P) 
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.04761) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://video-p2p.github.io/)

+ [Dreamix: Video Diffusion Models Are General Video Editors](https://arxiv.org/abs/2302.01329) (Feb., 2023)   
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2302.01329) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://dreamix-video-editing.github.io/) 

+ [Shape-Aware Text-Driven Layered Video Editing](https://arxiv.org/abs/2301.13173) (Jan., 2023)    
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2301.13173) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://text-video-edit.github.io/)   

+ [Speech Driven Video Editing via an Audio-Conditioned Diffusion Model](https://arxiv.org/abs/2301.04474) (Jan., 2023)   
  [![Star](https://img.shields.io/github/stars/DanBigioi/DiffusionVideoEditing.svg?style=social&label=Star)](https://github.com/DanBigioi/DiffusionVideoEditing) 
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2301.04474) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://danbigioi.github.io/DiffusionVideoEditing/) 

+ [Diffusion Video Autoencoders: Toward Temporally Consistent Face Video Editing via Disentangled Video Encoding](https://arxiv.org/abs/2212.02802) (CVPR 2023)  
  [![Star](https://img.shields.io/github/stars/man805/Diffusion-Video-Autoencoders.svg?style=social&label=Star)](https://github.com/man805/Diffusion-Video-Autoencoders) 
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2212.02802) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://diff-video-ae.github.io/) 


### Long-form Video Generation and Completion

+ [Streetscapes: Large-scale Consistent Street View Generation Using Autoregressive Video Diffusion](https://arxiv.org/pdf/2407.13759) (Jul., 2024)   
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2407.13759) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://boyangdeng.com/streetscapes/)
  
+ [MCVD: Masked Conditional Video Diffusion for Prediction, Generation, and Interpolation](https://arxiv.org/abs/2205.09853) (NeurIPS 2022)   
  [![Star](https://img.shields.io/github/stars/voletiv/mcvd-pytorch.svg?style=social&label=Star)](https://github.com/voletiv/mcvd-pytorch) 
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2205.09853) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://mask-cond-video-diffusion.github.io)

+ [NUWA-XL: Diffusion over Diffusion for eXtremely Long Video Generation](https://arxiv.org/abs/2303.12346) (Mar., 2023)   
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.12346) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://msra-nuwa.azurewebsites.net/#/)

+ [Flexible Diffusion Modeling of Long Videos](https://arxiv.org/abs/2205.11495) (May, 2022)   
  [![Star](https://img.shields.io/github/stars/plai-group/flexible-video-diffusion-modeling.svg?style=social&label=Star)](https://github.com/plai-group/flexible-video-diffusion-modeling) 
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2205.11495) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://fdmolv.github.io/)


### Human or Subject Motion 

+ [A Comprehensive Survey on Human Video Generation: Challenges, Methods, and Insights](https://arxiv.org/abs/2407.08428) (Jul., 2024)   
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.08428) 
  
+ [OccFusion: Rendering Occluded Humans with Generative Diffusion Priors](https://arxiv.org/pdf/2406.08801) (Jul., 2024)   
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2407.00316) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://cs.stanford.edu/~xtiange/projects/occfusion/)

+ [EchoMimic: Lifelike Audio-Driven Portrait Animations through Editable Landmark Conditions](https://arxiv.org/abs/2407.08136) (Jul., 2024)   
  [![Star](https://img.shields.io/github/stars/BadToBest/EchoMimic?style=social)](https://github.com/BadToBest/EchoMimic) 
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2407.08136) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://badtobest.github.io/echomimic.html)
  
+ [Hallo: Hierarchical Audio-Driven Visual Synthesis for Portrait Image Animation](https://arxiv.org/pdf/2406.08801) (Jun., 2024)   
  [![Star](https://img.shields.io/github/stars/fudan-generative-vision/hallo?style=social)](https://github.com/fudan-generative-vision/hallo) 
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2406.08801) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://fudan-generative-vision.github.io/hallo/#/)

+ [DiffSHEG: A Diffusion-Based Approach for Real-Time Speech-driven Holistic 3D Expression and Gesture Generation](https://arxiv.org/abs/2401.04747) (CVPR 2024)   
  [![Star](https://img.shields.io/github/stars/JeremyCJM/DiffSHEG.svg?style=social&label=Star)](https://github.com/JeremyCJM/DiffSHEG) 
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.04747) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://jeremycjm.github.io/proj/DiffSHEG/)

+ [Avatars Grow Legs: Generating Smooth Human Motion from Sparse Tracking Inputs with Diffusion Model](https://arxiv.org/abs/2304.08577) (CVPR 2023)   
  [![Star](https://img.shields.io/github/stars/facebookresearch/AGRoL.svg?style=social&label=Star)](https://github.com/facebookresearch/AGRoL) 
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.08577) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://dulucas.github.io/agrol/)

+ [InterGen: Diffusion-based Multi-human Motion Generation under Complex Interactions](https://arxiv.org/abs/2304.05684) (Apr., 2023)   
  [![Star](https://img.shields.io/github/stars/tr3e/InterGen.svg?style=social&label=Star)](https://github.com/tr3e/InterGen) 
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.05684) 

+ [ReMoDiffuse: Retrieval-Augmented Motion Diffusion Model](https://arxiv.org/abs/2304.01116) (Apr., 2023)   
  [![Star](https://img.shields.io/github/stars/mingyuan-zhang/ReMoDiffuse.svg?style=social&label=Star)](https://github.com/mingyuan-zhang/ReMoDiffuse) 
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.01116) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://mingyuan-zhang.github.io/projects/ReMoDiffuse.html)

+ [Human Motion Diffusion as a Generative Prior](https://arxiv.org/abs/2303.01418) (Mar., 2023)   
  [![Star](https://img.shields.io/github/stars/priorMDM/priorMDM.svg?style=social&label=Star)](https://github.com/priorMDM/priorMDM) 
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.01418) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://priormdm.github.io/priorMDM-page/)

+ [Can We Use Diffusion Probabilistic Models for 3d Motion Prediction?](https://arxiv.org/abs/2302.14503) (Feb., 2023)    
  [![Star](https://img.shields.io/github/stars/cotton-ahn/diffusion-motion-prediction.svg?style=social&label=Star)](https://github.com/cotton-ahn/diffusion-motion-prediction) 
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2302.14503) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://sites.google.com/view/diffusion-motion-prediction)

+ [Single Motion Diffusion](https://arxiv.org/abs/2302.05905) (Feb., 2023)   
  [![Star](https://img.shields.io/github/stars/SinMDM/SinMDM.svg?style=social&label=Star)](https://github.com/SinMDM/SinMDM) 
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2302.05905) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://sinmdm.github.io/SinMDM-page/)

+ [HumanMAC: Masked Motion Completion for Human Motion Prediction](https://arxiv.org/abs/2302.03665) (Feb., 2023)   
  [![Star](https://img.shields.io/github/stars/LinghaoChan/HumanMAC.svg?style=social&label=Star)](https://github.com/LinghaoChan/HumanMAC) 
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2302.03665) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://lhchen.top/Human-MAC/)

+ [DiffMotion: Speech-Driven Gesture Synthesis Using Denoising Diffusion Model](https://arxiv.org/abs/2301.10047) (Jan., 2023)   
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2301.10047) 

+ [Modiff: Action-Conditioned 3d Motion Generation With Denoising Diffusion Probabilistic Models](https://arxiv.org/abs/2301.03949) (Jan., 2023)     
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2301.03949) 


+ [Executing Your Commands via Motion Diffusion in Latent Space](https://arxiv.org/abs/2212.04048) (CVPR 2023)   
  [![Star](https://img.shields.io/github/stars/ChenFengYe/motion-latent-diffusion.svg?style=social&label=Star)](https://github.com/ChenFengYe/motion-latent-diffusion) 
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2212.04048) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://chenxin.tech/mld/)

+ [Pretrained Diffusion Models for Unified Human Motion Synthesis](https://arxiv.org/abs/2212.02837) (Dec., 2022)    
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2212.02837) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://ofa-sys.github.io/MoFusion/)
  
+ [PhysDiff: Physics-Guided Human Motion Diffusion Model](https://arxiv.org/abs/2212.02500) (Dec., 2022)   
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2212.02500) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://nvlabs.github.io/PhysDiff/)

+ [BeLFusion: Latent Diffusion for Behavior-Driven Human Motion Prediction](https://arxiv.org/abs/2211.14304) (Dec., 2022)     
  [![Star](https://img.shields.io/github/stars/BarqueroGerman/BeLFusion.svg?style=social&label=Star)](https://github.com/BarqueroGerman/BeLFusion) 
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2211.14304) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://barquerogerman.github.io/BeLFusion/)
  
+ [Listen, Denoise, Action! Audio-Driven Motion Synthesis With Diffusion Models](https://arxiv.org/abs/2211.09707) (Nov. 2022)   
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2211.09707) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://www.speech.kth.se/research/listen-denoise-action/)
  
+ [Diffusion Motion: Generate Text-Guided 3d Human Motion by Diffusion Model](https://arxiv.org/abs/2210.12315) (ICASSP 2023)   
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2210.12315) 
  
+ [Human Joint Kinematics Diffusion-Refinement for Stochastic Motion Prediction](https://arxiv.org/abs/2210.05976) (Oct., 2022)   
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2210.05976) 

+ [Human Motion Diffusion Model](https://arxiv.org/abs/2209.14916) (ICLR 2023)   
  [![Star](https://img.shields.io/github/stars/GuyTevet/motion-diffusion-model.svg?style=social&label=Star)](https://github.com/GuyTevet/motion-diffusion-model) 
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2209.14916) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://guytevet.github.io/mdm-page/)

+ [FLAME: Free-form Language-based Motion Synthesis & Editing](https://arxiv.org/abs/2209.00349) (AAAI 2023)   
  [![Star](https://img.shields.io/github/stars/kakaobrain/flame.svg?style=social&label=Star)](https://github.com/kakaobrain/flame) 
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2209.00349) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://kakaobrain.github.io/flame/)

+ [MotionDiffuse: Text-Driven Human Motion Generation with Diffusion Model](https://arxiv.org/abs/2208.15001) (Aug., 2022)   
  [![Star](https://img.shields.io/github/stars/mingyuan-zhang/MotionDiffuse.svg?style=social&label=Star)](https://github.com/mingyuan-zhang/MotionDiffuse) 
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2208.15001) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://mingyuan-zhang.github.io/projects/MotionDiffuse.html)

+ [Stochastic Trajectory Prediction via Motion Indeterminacy Diffusion](https://arxiv.org/abs/2203.13777) (CVPR 2022)   
  [![Star](https://img.shields.io/github/stars/gutianpei/MID.svg?style=social&label=Star)](https://github.com/gutianpei/MID) 
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2203.13777) 

### AI Safety for Video Generation
+ [What Matters in Detecting AI-Generated Videos like Sora?](https://arxiv.org/abs/2406.19568) (Jun., 2024)   
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.19568) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://justin-crchang.github.io/3DCNNDetection.github.io/)


### Video Enhancement and Restoration

+ [Disentangled Motion Modeling for Video Frame Interpolation](https://arxiv.org/abs/2406.17256) (Jun, 2024)   
  [![Star](https://img.shields.io/github/stars/JHLew/MoMo.svg?style=social&label=Star)](https://github.com/JHLew/MoMo)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.17256)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://github.com/JHLew/MoMo)

+ [DiffIR2VR-Zero: Zero-Shot Video Restoration with Diffusion-based Image Restoration Models](https://arxiv.org/abs/2407.01519) (Jul., 2024)   
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.01519)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://jimmycv07.github.io/DiffIR2VR_web/)

+ [LDMVFI: Video Frame Interpolation with Latent Diffusion Models](https://arxiv.org/abs/2303.09508) (Mar., 2023)   
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.09508)

+ [CaDM: Codec-aware Diffusion Modeling for Neural-enhanced Video Streaming](https://arxiv.org/abs/2211.08428) (Nov., 2022)   
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2211.08428)

### Audio Synthesis for Video

+ [VMAs: Video-to-Music Generation via Semantic Alignment in Web Music Videos](https://www.arxiv.org/abs/2409.07450) (Oct., 2024)   
  [![Website](https://img.shields.io/badge/Website-9cf)](https://genjib.github.io/project_page/VMAs/index.html)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://www.arxiv.org/abs/2409.07450)



+ [STA-V2A: Video-to-Audio Generation with Semantic and Temporal Alignment](https://arxiv.org/pdf/2409.08601) (Oct., 2024)   
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2409.08601)
  [![Star](https://img.shields.io/github/stars/yannqi/Draw-an-Audio-Code.svg?style=social&label=Star)](https://github.com/y-ren16/STAV2A)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://y-ren16.github.io/STAV2A/)



+ [Draw an Audio: Leveraging Multi-Instruction for Video-to-Audio Synthesis](https://arxiv.org/pdf/2409.06135) (Sep., 2024)   
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2409.06135)
  [![Star](https://img.shields.io/github/stars/yannqi/Draw-an-Audio-Code.svg?style=social&label=Star)](https://github.com/yannqi/Draw-an-Audio-Code)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://yannqi.github.io/Draw-an-Audio/)


+ [Mini-Omni: Language Models Can Hear, Talk While Thinking in Streaming](https://arxiv.org/abs/2408.16725) (Jul., 2024)   
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.16725)
  [![Star](https://img.shields.io/github/stars/gpt-omni/mini-omni.svg?style=social&label=Star)](https://github.com/gpt-omni/mini-omni)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://github.com/gpt-omni/mini-omni)
      


+ [Speech To Speech: an effort for an open-sourced and modular GPT4-o](https://github.com/huggingface/speech-to-speech) (Aug., 2024)   
  [![Star](https://img.shields.io/github/stars/huggingface/speech-to-speech.svg?style=social&label=Star)](https://github.com/huggingface/speech-to-speech)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://github.com/huggingface/speech-to-speech)
      

+ [Masked Generative Video-to-Audio Transformers with Enhanced Synchronicity](https://arxiv.org/abs/2407.10387) (Jul., 2024)   
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.10387)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://maskvat.github.io/)

+ [Video-to-Audio Generation with Hidden Alignment](https://arxiv.org/abs/2407.07464) (Jul., 2024)   
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.07464)
  [![Star](https://img.shields.io/github/stars/ariesssxu/vta-ldm.svg?style=social&label=Star)](https://github.com/ariesssxu/vta-ldm)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://sites.google.com/view/vta-ldm)
  
+ [Read, Watch and Scream! Sound Generation from Text and Video](https://arxiv.org/abs/2407.05551) (Jul., 2024)   
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.05551)
  [![Star](https://img.shields.io/github/stars/naver-ai/rewas.svg?style=social&label=Star)](https://github.com/naver-ai/rewas)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://naver-ai.github.io/rewas/)

+ [FoleyCrafter: Bring Silent Videos to Life with Lifelike and Synchronized Sounds](https://arxiv.org/abs/2407.01494) (July, 2024)   
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.01494)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://foleycrafter.github.io/)

+ [Network Bending of Diffusion Models for Audio-Visual Generation](https://arxiv.org/abs/2406.19589) (CVPR, 2024)   
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.19589)
  [![Star](https://img.shields.io/github/stars/dzluke/DAFX2024.svg?style=social&label=Star)](https://github.com/dzluke/DAFX2024)

### Human Feedback for Video Generation

+ [VIDEOSCORE: Building Automatic Metrics to Simulate Fine-grained Human Feedback for Video Generation](https://arxiv.org/pdf/2406.15252) (July, 2024)   
  [![Star](https://img.shields.io/github/stars/TIGER-AI-Lab/VideoScore.svg?style=social&label=Star)](https://github.com/TIGER-AI-Lab/VideoScore/)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.15252)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://tiger-ai-lab.github.io/VideoScore/)

### Policy Learning with Video Generation


+ [GR-MG: Leveraging Partially Annotated Data via Multi-Modal Goal Conditioned Policy](https://arxiv.org/abs/2408.14368) (July, 2024)   
  [![Star](https://img.shields.io/github/stars/bytedance/GR-MG/tree/main.svg?style=social&label=Star)](https://github.com/bytedance/GR-MG/tree/main)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.14368)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://gr-mg.github.io/)

+ [Any-point Trajectory Modeling for Policy Learning](https://arxiv.org/abs/2401.00025) (July, 2024)   
  [![Star](https://img.shields.io/github/stars/Large-Trajectory-Model/ATM.svg?style=social&label=Star)](https://github.com/Large-Trajectory-Model/ATM)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.00025)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://xingyu-lin.github.io/atm/)

+ [This&That: Language-Gesture Controlled Video Generation for Robot Planning](https://arxiv.org/abs/2407.05530) (Jun, 2024)   
  [![Star](https://img.shields.io/github/stars/cfeng16/this-and-that.svg?style=social&label=Star)](https://github.com/cfeng16/this-and-that)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.05530)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://cfeng16.github.io/this-and-that/)

+ [Dreamitate: Real-World Visuomotor Policy Learning via Video Generation](https://arxiv.org/abs/2406.16862) (Jun, 2024)   
  [![Star](https://img.shields.io/github/stars/cvlab-columbia/dreamitate.svg?style=social&label=Star)](https://github.com/cvlab-columbia/dreamitate)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.16862)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://dreamitate.cs.columbia.edu/)

### 3D / NeRF


+ [Hi3D: Pursuing High-Resolution Image-to-3D Generation with Video Diffusion Models](https://arxiv.org/pdf/2409.07452) (Oct., 2024)   
  [![Star](https://img.shields.io/github/stars/liuff19/ReconX.svg?style=social&label=Star)](https://github.com/yanghb22-fdu/Hi3D-Official)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2409.07452)


+ [ReconX: Reconstruct Any Scene from Sparse Views with Video Diffusion Model](https://arxiv.org/abs/2408.16767) (Aug., 2024)   
  [![Star](https://img.shields.io/github/stars/liuff19/ReconX.svg?style=social&label=Star)](https://github.com/liuff19/ReconX)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.16767)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://liuff19.github.io/ReconX/)

+ [SV4D: Dynamic 3D Content Generation with Multi-Frame and Multi-View Consistency](https://arxiv.org/abs/2407.17470) (Jul., 2024)   
  [![Star](https://img.shields.io/github/stars/Stability-AI/generative-models.svg?style=social&label=Star)](https://github.com/Stability-AI/generative-models)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.13764)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://sv4d.github.io/)
  
+ [Shape of Motion: 4D Reconstruction from a Single Video](https://arxiv.org/abs/2407.13764) (Jul., 2024)   
  [![Star](https://img.shields.io/github/stars/vye16/shape-of-motion.svg?style=social&label=Star)](https://github.com/vye16/shape-of-motion/)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.13764)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://shape-of-motion.github.io/)

+ [WonderWorld: Interactive 3D Scene Generation from a Single Image](https://arxiv.org/abs/2406.09394) (Jun., 2024)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.09394)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://wonderworld-2024.github.io/)

+ [WonderJourney: Going from Anywhere to Everywhere](https://arxiv.org/pdf/2312.03884) (CVPR 2024)  
  [![Star](https://img.shields.io/github/stars/KovenYu/WonderJourney.svg?style=social&label=Star)](https://github.com/KovenYu/WonderJourney)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2312.03884)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://kovenyu.com/wonderjourney/)

+ [MultiDiff: Consistent Novel View Synthesis from a Single Image](https://sirwyver.github.io/MultiDiff/static/assets/MultiDiff.pdf) (CVPR, 2024)   
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://sirwyver.github.io/MultiDiff/static/assets/MultiDiff.pdf)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://sirwyver.github.io/MultiDiff/)

+ [Vivid-ZOO: Multi-View Video Generation with Diffusion Model](https://arxiv.org/pdf/2406.08659v1) (Jun, 2024)   
  [![Star](https://img.shields.io/github/stars/Lakonik/SSDNeRF.svg?style=social&label=Star)](https://github.com/hi-zhengcheng/vividzoo)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2406.08659v1)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://hi-zhengcheng.github.io/vividzoo/)

+ [Director3D: Real-world Camera Trajectory and 3D Scene Generation from Text](https://arxiv.org/pdf/2406.17601) (June, 2024)   
  [![Star](https://img.shields.io/github/stars/imlixinyang/director3d.svg?style=social&label=Star)](https://github.com/imlixinyang/director3d)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2406.17601)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://imlixinyang.github.io/director3d-page/)
  
+ [YouDream: Generating Anatomically Controllable Consistent Text-to-3D Animals](https://arxiv.org/abs/2406.16273v1) (June, 2024)   
  [![Star](https://img.shields.io/github/stars/YouDream3D/YouDream.svg?style=social&label=Star)](https://github.com/YouDream3D/YouDream/)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.16273v1)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://youdream3d.github.io/)

+ [Text2NeRF: Text-Driven 3D Scene Generation with Neural Radiance Fields](https://arxiv.org/abs/2305.11588) (May, 2023)   
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.11588)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://eckertzhang.github.io/Text2NeRF.github.io/)

+ [RoomDreamer: Text-Driven 3D Indoor Scene Synthesis with Coherent Geometry and Texture](https://arxiv.org/abs/2305.11337) (May, 2023)   
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.11337)

+ [NeuralField-LDM: Scene Generation with Hierarchical Latent Diffusion Models](https://arxiv.org/abs/2304.09787) (CVPR 2023)   
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.09787)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://research.nvidia.com/labs/toronto-ai/NFLDM/)

+ [Single-Stage Diffusion NeRF: A Unified Approach to 3D Generation and Reconstruction](https://arxiv.org/abs/2304.06714) (Apr., 2023)  
  [![Star](https://img.shields.io/github/stars/Lakonik/SSDNeRF.svg?style=social&label=Star)](https://github.com/Lakonik/SSDNeRF) 
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.06714)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://lakonik.github.io/ssdnerf/)

+ [Instruct-NeRF2NeRF: Editing 3D Scenes with Instructions](https://arxiv.org/abs/2303.12789) (Mar., 2023)  
  [![Star](https://img.shields.io/github/stars/ayaanzhaque/instruct-nerf2nerf.svg?style=social&label=Star)](https://github.com/ayaanzhaque/instruct-nerf2nerf) 
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.12789)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://instruct-nerf2nerf.github.io/)

+ [DiffusioNeRF: Regularizing Neural Radiance Fields with Denoising Diffusion Models](https://arxiv.org/abs/2302.12231) (Feb., 2023)  
  [![Star](https://img.shields.io/github/stars/nianticlabs/diffusionerf.svg?style=social&label=Star)](https://github.com/nianticlabs/diffusionerf) 
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2302.12231)

+ [NerfDiff: Single-image View Synthesis with NeRF-guided Distillation from 3D-aware Diffusion](https://arxiv.org/abs/2302.10109) (Feb., 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2302.10109)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://jiataogu.me/nerfdiff/)

+ [DiffRF: Rendering-guided 3D Radiance Field Diffusion](https://arxiv.org/abs/2212.01206) (CVPR 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2212.01206)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://sirwyver.github.io/DiffRF/)


### World Model

+ [Digital Life Project: Autonomous 3D Characters with Social Intelligence](https://arxiv.org/abs/2312.04547) (CVPR 2024)  
  [![Star](https://img.shields.io/github/stars/caizhongang/Digital_Life_Project.svg?style=social&label=Star)](https://github.com/caizhongang/Digital_Life_Project) 
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.04547)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://digital-life-project.com/)

+ [3D-VLA: A 3D Vision-Language-Action Generative World Model](https://arxiv.org/abs/2403.09631) (ICML 2024)  
  [![Star](https://img.shields.io/github/stars/UMass-Foundation-Model/3D-VLA.svg?style=social&label=Star)](https://github.com/UMass-Foundation-Model/3D-VLA) 
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.09631)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://vis-www.cs.umass.edu/3dvla/)



### Video Understanding

+ [Exploring Diffusion Models for Unsupervised Video Anomaly Detection](https://arxiv.org/abs/2304.05841) (Apr., 2023)   
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.05841)

+ [PDPP:Projected Diffusion for Procedure Planning in Instructional Videos](https://arxiv.org/abs/2303.14676) (CVPR 2023)   
  [![Star](https://img.shields.io/github/stars/MCG-NJU/PDPP.svg?style=social&label=Star)](https://github.com/MCG-NJU/PDPP) 
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.14676)

+ [DiffTAD: Temporal Action Detection with Proposal Denoising Diffusion](https://arxiv.org/abs/2303.14863) (Mar., 2023)     
  [![Star](https://img.shields.io/github/stars/sauradip/DiffusionTAD.svg?style=social&label=Star)](https://github.com/sauradip/DiffusionTAD) 
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.14863)

+ [Diffusion Action Segmentation](https://arxiv.org/abs/2303.17959) (ICCV 2023)   
  [![Star](https://img.shields.io/github/stars/Finspire13/DiffAct.svg?style=social&label=Star)](https://github.com/Finspire13/DiffAct) 
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)]([https://arxiv.org/abs/2303.09867](https://arxiv.org/abs/2303.17959))
  [![Website](https://img.shields.io/badge/Website-9cf)](https://daochang.site/DiffAct-Project-Page/)

+ [DiffusionRet: Generative Text-Video Retrieval with Diffusion Model](https://arxiv.org/abs/2303.09867) (ICCV 2023)   
  [![Star](https://img.shields.io/github/stars/jpthu17/DiffusionRet.svg?style=social&label=Star)](https://github.com/jpthu17/DiffusionRet) 
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.09867)

+ [Refined Semantic Enhancement Towards Frequency Diffusion for Video Captioning](https://arxiv.org/abs/2211.15076) (Nov., 2022)   
  [![Star](https://img.shields.io/github/stars/lzp870/RSFD.svg?style=social&label=Star)](https://github.com/lzp870/RSFD) 
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2211.15076)

+ [A Generalist Framework for Panoptic Segmentation of Images and Videos](https://arxiv.org/abs/2210.06366) (Oct., 2022)   
  [![Star](https://img.shields.io/github/stars/google-research/pix2seq.svg?style=social&label=Star)](https://github.com/google-research/pix2seq) 
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2210.06366)


### Healthcare and Biology

+ [Annealed Score-Based Diffusion Model for Mr Motion Artifact Reduction](https://arxiv.org/abs/2301.03027) (Jan., 2023)  
  [![arxiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2301.03027) 

+ [Feature-Conditioned Cascaded Video Diffusion Models for Precise Echocardiogram Synthesis](https://arxiv.org/abs/2303.12644) (Mar., 2023)   
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.12644)

+ [Neural Cell Video Synthesis via Optical-Flow Diffusion](https://arxiv.org/abs/2212.03250) (Dec., 2022)   
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2212.03250)

# Text-To-Video 

## Table of Contents

- [Awesome-Text-To-Video ](#awesome-text-to-video-)
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
  - [Text To Video Generators](#text-to-video-generators)
    - [DeepBrain AI](#deepbrain-ai)
    - [Runway AI](#runway-ai)
    - [Kaiber AI](#kaiber-ai)
    - [Stable Diffusion Videos](#stable-diffusion-videos)
    - [Deforum Stable Diffusion](#deforum-stable-diffusion)
    - [Make-A-Video](#make-a-video)
    - [VEED.io](#veedio)
    - [Lumen5](#lumen5)
    - [Designs.AI](#designsai)
    - [Synthesia.io](#synthesiaio)
    - [InVideo.io](#invideoio)
    - [GliaCloud](#gliacloud)
    - [Synths Video](#synths-video)
    - [Pictory](#pictory)
    - [Designs.ai](#designsai-1)
    - [Wisecut](#wisecut)
    - [Fliki AI](#fliki-ai)
  - [Text to Video Papers](#text-to-video-papers)
    - [2023](#2023)
    - [2022](#2022)
  - [Contributing](#contributing)
  - [License](#license)



## Text To Video Generators

### [DeepBrain AI](https://www.deepbrain.io/)

<div align="center">
<img src="https://mpost.io/wp-content/uploads/image-90-39-1024x613.jpg" width="600px"></img>
</div>

What I want to recommend most among AI video generators is [DeepBrain’s AI Studios,](https://www.deepbrain.io/) which has a hyperrealistic Avatar. It has superior quality among the AI video SaaS. You can simply produce a video by typing a script. Creating AI video is much easier because it has a chroma key function and a ppt to video function. You can try making it for free.

- Select your AI presenter first (AI Studios provides more than 12 avatars for your AI films; it supports 80+ TTS languages and native AI avatars).
- Enter your AI video script. It also has a function called ChatGPT, so it can automatically generate scripts.
- Create your AI video and then download, stream, or translate it.

The use of the best AI video generators has revolutionized the way businesses create marketing content

### [Runway AI](https://runwayml.com/)

Runway AI is an innovative set of resources for video editors that taps into the potential of AI. It comes equipped with a variety of powerful features, such as:

- **Green screen tools:** The background can be edited out of any video.
- **Erase and replace:** Choose any frame from a movie (such as a tossed ball in a game of catch) and have Runway swap it out with anything else.
- **Infinite image:** Create a picture using AI and then use it to fill up more space than it would in the original.

Video editors will find these AI tools revolutionary. Even a novice may use it to execute complex video editing tasks in a matter of seconds. Nevertheless, Runway AI has even more in store. The Gen-1 and [Gen-2](https://dataconomy.com/blog/2023/03/21/what-is-runway-ai-gen-2-text-to-video-ai/) enhancements are a quantum leap forward for video editing.

It is one of the best AI video generators for using artificial intelligence’s cutting edge tech. You can try it for free by clicking [here](https://runwayml.com/).

### [Kaiber AI](https://www.kaiber.ai/)

Kaiser AI is a platform that allows you to generate high-quality videos using artificial intelligence. They produce AI videos for artists like Linkin Park, Kid Cudi, and Mike Shinoda, and more.

You can choose from a variety of templates, customize the characters, backgrounds, and dialogues, and let Kaiber AI video do the rest. You can also upload your own scripts and voiceovers, and Kaiber AI video will match them with the best visuals and animations.

![Are you looking for the best AI video generators? We explained the most popular in 2023, like Synthesia, Kaiber, Runway, and more. Keep reading!](https://dataconomy.com/wp-content/uploads/2023/04/Best-AI-video-generators-2.jpg)

It is one of the best AI video generators in the market. If you want to learn more about Kaiber AI and see some examples of what you can create with it, visit their [website](https://www.kaiber.ai/). You can also sign up for a free trial and start creating your own videos in minutes. It is one of the best AI video generators for engaging videos.

### [Stable Diffusion Videos](https://replicate.com/nateraw/stable-diffusion-videos)

<div align="center">
<img src="https://mpost.io/wp-content/uploads/image-51-32-1024x611.jpg" width="600px"></img>
</div>


[Stable Diffusion Videos](https://replicate.com/nateraw/stable-diffusion-videos) is a free online text-to-video AI generator to make videos from prompts. It is a text-to-video AI generator that uses the Stable Diffusion algorithm to generate videos from text prompts. It is a free online text-to-video AI generator to make videos from prompts. It is a text-to-video AI generator that uses the Stable Diffusion algorithm to generate videos from text prompts.

### [Deforum Stable Diffusion](https://replicate.com/deforum/deforum_stable_diffusion)

<div align="center">
<img src="https://mpost.io/wp-content/uploads/image-51-33-1024x589.jpg" width="600px"></img>
</div>

Another one text-to-video AI generator [Deforum](https://replicate.com/deforum/deforum_stable_diffusion) generates animations by constructing frames that take their forefathers into consideration. Using Deforum SD, it is now simpler than ever to produce coherent films and animations from Stable Diffusion outputs.
### [Make-A-Video](https://makeavideo.studio/)

<div align="center">
<img src="https://mpost.io/wp-content/uploads/image-51-31-1024x619.jpg" width="600px"></img>
</div>

[Make-A-Video](https://makeavideo.studio/) a new AI text-t-video generator from Meta makes amusing short films with just a few phrases.

The research, which was created to enable text-to-video generation, is based on recent developments in text-to-image generating technology. In addition to text, photographs and other videos can also be used to make movies. Although a time axis has been added, this is still the same diffusion.

Using images and descriptions, the system learns how the world appears and how it is typically described. Unlabeled movies are also used to help students comprehend how the world operates.

With just a few words or lines of text, you may use this information to create funny, original videos that will help you bring your imagination to life.

### [VEED.io](https://www.veed.io/)

<div align="center">
<img src="https://mpost.io/wp-content/uploads/image-51-30-1024x551.jpg" width="600px"></img>
</div>


With the help of [VEED.io](https://www.veed.io/)‘s robust A.I. technology and user-friendly interface, you can quickly produce great videos online. It can be used as a video editor to chop, crop, add subtitles, and more, or to convert any text into videos.

Here’s how it functions:

- Choose a stock video or upload your own
- You can edit the video by adding text, photos, etc.
- Download and export the movie



### [Lumen5](https://lumen5.com/)


<div align="center">
<img src="https://mpost.io/wp-content/uploads/image-51-29-1024x606.jpg" width="600px"></img>
</div>

A fantastic online tool for producing AI films is [Lumen5](https://lumen5.com/). For the purpose of producing quality video material, more than 800,000 users use Lumen5. The best thing about it is how simple it is to use and how little expertise in video editing is required. Artificial intelligence can let you quickly generate videos from scratch or from scratch in a matter of minutes.

Here’s how it functions:

- Type a script or text here.
- Based on the screenplay, Lumen5 will automatically select the ideal audio and images.
- You can upload your own text, music, and logos.
- Download and distribute the movie

### [Designs.AI](https://designs.ai/)

<div align="center">
<img src="https://mpost.io/wp-content/uploads/image-51-28-1024x665.jpg" width="600px"></img>
</div>


You may convert your blog entries and articles into interesting movies with the help of the amazing AI-powered content creation tool called [Design.AI](https://designs.ai/). It can also help you swiftly design logos, films, and banners.

Here’s how it functions:

- Insert your text or script first.
- Choose an industry.
- Choose a voice you prefer and a style of video.
- The AI will immediately produce a video preview after this. After that, you can modify your video and add text and music to make it more visually appealing.

### [Synthesia.io](https://www.synthesia.io/)


<div align="center">
<img src="https://mpost.io/wp-content/uploads/image-51-27.jpg" width="600px"></img>
</div>


One of the amazing AI video generators is [Synthesia](https://www.synthesia.io/), which makes it simple to make realistic AI videos in a matter of minutes. Synthesia is an AI video creator that uses advanced [natural language processing](https://www.makeuseof.com/what-is-natural-language-processing-and-how-does-it-work/) (NLP) and machine learning algorithms to create high-quality videos from text in over 50 languages without any actors, cameras, or mics. Syhthesia is a great option if you want to make budget-friendly videos that appear professional. To build your own AI video, follow these three simple steps.

- Select your AI presenter first (Synthesia provides more than 40 avatars for your AI films; alternatively, you can make your own avatar).
- Enter your AI video script secondly.
- Third, create your AI video and then download, stream, or translate it.

### [InVideo.io](https://invideo.io/)

<div align="center">
<img src="https://mpost.io/wp-content/uploads/image-51-26.jpg" width="600px"></img>
</div>


You can convert text into videos using the effective video editing program [InVideo](https://invideo.io/). You can use more than 5000 layouts, iStock media, a music library, filters, and other features.

For simple video conversion of text-based information, InVideo provides more than 50 AI-powered themes. From their library of 5000+ configurable templates, you may make all different types of videos, including video commercials, promos, YouTube videos, intros, and more.

You must choose any template or theme and type any text when creating videos. That’s it; you can quickly create an incredible AI video with that script. You can add media, such as audio, video, text, and more.

### [GliaCloud](https://www.gliacloud.com/en/)

You can use GliaCloud to seamlessly create professional-looking videos from existing text content in minutes. There’s no need for special equipment or prior knowledge of video editing software. Simply upload your article or post the URL, and it will automatically create an engaging video.

You can then preview and edit this script if required before generating an HD-quality video file ready to upload to your website or social media channels.

### [Fliki AI](https://fliki.ai/)

Fliki is a tool that converts text into audio and video in under a minute, utilizing artificially intelligent voices.

With just a few simple steps, Fliki can transform your blog into narrated videos, like Lumen5, podcasts, or audiobooks. 850+ voices are available on Fliki, including 77+ languages and 100+ regional dialects.

It is one of the best AI video generators for content creation. Click [here](https://fliki.ai/) and try Fliki AI.

## Text to Video Papers

### 2023
-  Text-To-4D Dynamic Scene Generation, Uriel Singer et al. [[Paper](https://arxiv.org/abs/2301.11280)] [[Project](https://make-a-video3d.github.io/)]

### 2022

-  Tune-A-Video: One-Shot Tuning of Image Diffusion Models for Text-to-Video Generation, Jay Zhangjie Wu et al. [[Paper](https://arxiv.org/abs/2212.11565)] [[Project](https://tuneavideo.github.io/)] [[Code](https://github.com/showlab/Tune-A-Video)]
-  MagicVideo: Efficient Video Generation With Latent Diffusion Models, Daquan Zhou et al. [[Paper](https://arxiv.org/abs/2211.11018)] [[Project](https://magicvideo.github.io/#)]
-  Phenaki: Variable Length Video Generation From Open Domain Textual Description, Ruben Villegas et al. [[Paper](https://arxiv.org/abs/2210.02399)]
-  Imagen Video: High Definition Video Generation with Diffusion Models, Jonathan Ho et al. [[Paper](https://arxiv.org/abs/2210.02303v1)] [[Project](https://imagen.research.google/video/)]
-  Text-driven Video Prediction, Xue Song et al. [[Paper](https://arxiv.org/abs/2210.02872)]
-  Make-A-Video: Text-to-Video Generation without Text-Video Data, Uriel Singer et al. [[Paper](https://arxiv.org/abs/2209.14792)] [[Project](https://makeavideo.studio/)] [[Short read](https://www.louisbouchard.ai/make-a-video/)] [[Code](https://github.com/lucidrains/make-a-video-pytorch)]
- StoryDALL-E: Adapting Pretrained Text-to-Image Transformers for Story Continuation, Adyasha Maharana et al. [[Paper](https://arxiv.org/abs/2209.06192)] [[Code](https://github.com/adymaharana/storydalle)]
- Word-Level Fine-Grained Story Visualization, Bowen Li et al. [[Paper](https://arxiv.org/abs/2208.02341)] [[Code](https://github.com/mrlibw/Word-Level-Story-Visualization)]
-  CogVideo: Large-scale Pretraining for Text-to-Video Generation via Transformers, Wenyi Hong et al. [[Paper](https://arxiv.org/abs/2205.15868)] [[Code](https://github.com/THUDM/CogVideo)]
- Show Me What and Tell Me How: Video Synthesis via Multimodal Conditioning, Yogesh Balaji et al. [[Paper](https://arxiv.org/abs/2203.02573)] [[Code](https://github.com/snap-research/MMVID)] [Project](https://snap-research.github.io/MMVID/)
-  Video Diffusion Models, Jonathan Ho et al. [[Paper](https://arxiv.org/abs/2204.03458)] [[Project](https://video-diffusion.github.io/)]

# Human-Video-Generation


## Table of Contents <!-- omit in toc -->
- [Text Guided Human Video Generation](#Text-Guided-Human-Video-Generation)
- [Audio Guided Human Video Generation](#Audio-Guided-Human-Video-Generation)
- - [Dance Video Generation](#Dance-Video-Generation)
- - [Performance Video Generation](#Performance-Video-Generation)
- - [Co-Speech Gesture Video Generation](#Co-Speech-Gesture-Video-Generation)
- [Pose Guided Human Video Generation](#Pose-Guided-Human-Video-Generation)
- [Applications](#Applications)
- [Datasets](#Datasets)
  
## Text Guided Human Video Generation
+ [HMTV (WACV 2024)](https://github.com/CSJasper/HMTV)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://openaccess.thecvf.com/content/WACV2024/papers/Kim_Human_Motion_Aware_Text-to-Video_Generation_With_Explicit_Camera_Control_WACV_2024_paper.pdf2)
  [![Star](https://img.shields.io/github/stars/CSJasper/HMTV.svg?style=social&label=Star)](https://github.com/CSJasper/HMTV)

+ [SignLLM](https://signllm.github.io/)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.10718v1)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://signllm.github.io/)

+ [Text2Performer (ICCV2023)](https://github.com/yumingj/Text2Performer)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2304.08483)
  [![Star](https://img.shields.io/github/stars/yumingj/Text2Performer.svg?style=social&label=Star)](https://github.com/yumingj/Text2Performer)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://yumingj.github.io/projects/Text2Performer.html)

## Audio Guided Human Video Generation

### Performance Video Generation
+ [Music2Play (CAC 2023)](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10450842)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10450842)

### Co-Speech Gesture Video Generation
+ [S2G-MDDiffusion (CVPR 2024)](https://github.com/thuhcsi/S2G-MDDiffusion)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2404.01862)
  [![Star](https://img.shields.io/github/stars/thuhcsi/S2G-MDDiffusion.svg?style=social&label=Star)](https://github.com/thuhcsi/S2G-MDDiffusion)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://thuhcsi.github.io/S2G-MDDiffusion/)

+ [ANGIE (NeurIPS 2022)](https://github.com/alvinliu0/ANGIE)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2212.02350)
  [![Star](https://img.shields.io/github/stars/alvinliu0/ANGIE.svg?style=social&label=Star)](https://github.com/alvinliu0/ANGIEn)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://alvinliu0.github.io/projects/ANGIE)

## Pose Guided Human Video Generation

+ [FollowYourPose](https://github.com/mayuelala/followyourpose)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.01186)
  [![Star](https://img.shields.io/github/stars/mayuelala/followyourpose.svg?style=social&label=Star)](https://github.com/mayuelala/followyourpose)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://follow-your-pose.github.io/)

+ [PSGAN](https://arxiv.org/pdf/1807.11152v1)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/1807.11152v1)

+ [DwNet](https://arxiv.org/pdf/1910.09139)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/1910.091396)
  [![Star](https://img.shields.io/github/stars/ubc-vision/DwNet.svg?style=social&label=Star)](https://github.com/ubc-vision/DwNet)

+ [Animateanyone](https://arxiv.org/pdf/2311.17117)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2311.17117)
  [![Star](https://img.shields.io/github/stars/MooreThreads/Moore-AnimateAnyone.svg?style=social&label=Star)](https://github.com/MooreThreads/Moore-AnimateAnyone?tab=readme-ov-file#train)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://humanaigc.github.io/animate-anyone/)

+ [ID-Animator](https://arxiv.org/abs/2404.15275)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.15275)
  [![Star](https://img.shields.io/github/stars/ID-Animator/ID-Animator.svg?style=social&label=Star)](https://github.com/ID-Animator/ID-Animator)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://id-animator.github.io/)


+ [DreaMoving](https://dreamoving.github.io/dreamoving/)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.05107)
  [![Star](https://img.shields.io/github/stars/dreamoving/dreamoving-project.svg?style=social&label=Star)](https://github.com/dreamoving/dreamoving-project)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://dreamoving.github.io/dreamoving/)

+ [MagicPose](https://boese0601.github.io/magicdance/)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2311.12052)
  [![Star](https://img.shields.io/github/stars/Boese0601/MagicDance.svg?style=social&label=Star)](https://github.com/Boese0601/MagicDance)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://boese0601.github.io/magicdance/)

+ [LEO](https://wyhsirius.github.io/LEO-project/)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.03989)
  [![Star](https://img.shields.io/github/stars/wyhsirius/LEO.svg?style=social&label=Star)](https://github.com/wyhsirius/LEO)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://wyhsirius.github.io/LEO-project/)

+ [MuseV](https://github.com/TMElyralab/MuseV)
  [![Star](https://img.shields.io/github/stars/TMElyralab/MuseV.svg?style=social&label=Star)](https://github.com/TMElyralab/MuseV)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://tmelyralab.github.io/MuseV_Page/)

+ [MusePose](https://github.com/TMElyralab/MusePose)
  [![Star](https://img.shields.io/github/stars/TMElyralab/MusePose.svg?style=social&label=Star)](https://github.com/TMElyralab/MusePose)

+ [MagicAnimate](https://showlab.github.io/magicanimate/)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.16498)
  [![Star](https://img.shields.io/github/stars/magic-research/magic-animate.svg?style=social&label=Star)](https://github.com/magic-research/magic-animate)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://showlab.github.io/magicanimate/)

+ [UniAnimate](https://github.com/ali-vilab/UniAnimate)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.01188)
  [![Star](https://img.shields.io/github/stars/ali-vilab/UniAnimate.svg?style=social&label=Star)](https://github.com/ali-vilab/UniAnimate)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://unianimate.github.io/)

+ [Champ](https://github.com/fudan-generative-vision/champ)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.14781)
  [![Star](https://img.shields.io/github/stars/fudan-generative-vision/champ.svg?style=social&label=Star)](https://github.com/fudan-generative-vision/champ)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://fudan-generative-vision.github.io/champ/#/)

+ [Magic-Me](https://github.com/zhen-dong/magic-me)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2402.09368)
  [![Star](https://img.shields.io/github/stars/Zhen-Dong/Magic-Me.svg?style=social&label=Star)](https://github.com/Zhen-Dong/Magic-Me)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://magic-me-webpage.github.io/)

+ [Disco](https://disco-dance.github.io/)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2307.00040)
  [![Star](https://img.shields.io/github/stars/Wangt-CN/DisCo.svg?style=social&label=Star)](https://github.com/Wangt-CN/DisCo)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://disco-dance.github.io/)

+ [TwoStreamVAN](https://arxiv.org/pdf/1812.01037)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/1812.01037)
  [![Star](https://img.shields.io/github/stars/sunxm2357/TwoStreamVAN.svg?style=social&label=Star)](https://github.com/sunxm2357/TwoStreamVAN)

+ [MoCoGAN](https://github.com/sergeytulyakov/mocogan)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/1707.04993)
  [![Star](https://img.shields.io/github/stars/sergeytulyakov/mocogan.svg?style=social&label=Star)](https://github.com/sergeytulyakov/mocogan)

+ [Pose-Guided Human Animation from a Single Image in the Wild](https://arxiv.org/pdf/2012.03796)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2012.03796)

+ [MimicMotion](https://arxiv.org/abs/2406.19680)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.19680)

+ [Human4DiT](https://arxiv.org/pdf/2405.17405)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2405.17405)

+ [FollowYourPose-v2 ](https://arxiv.org/pdf/2406.03035)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2406.03035)

+ [IDOL](https://yhzhai.github.io/idol/)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.10937)

+ [MagicFight](https://openreview.net/pdf?id=7JhV3Pbfgk)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://openreview.net/pdf?id=7JhV3Pbfgk)

+ [DiffPerformer CVPR(2024)](https://openaccess.thecvf.com//content/CVPR2024/papers/Wang_DiffPerformer_Iterative_Learning_of_Consistent_Latent_Guidance_for_Diffusion-based_Human_CVPR_2024_paper.pdf)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://openaccess.thecvf.com//content/CVPR2024/papers/Wang_DiffPerformer_Iterative_Learning_of_Consistent_Latent_Guidance_for_Diffusion-based_Human_CVPR_2024_paper.pdf)



### Applications
+ [Keling](https://kling.kuaishou.com/)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://kling.kuaishou.com/)

+ [Viggle](https://viggle.ai/)
  [![Star](https://img.shields.io/github/stars/hoachen/veggieai-generate-video.svg?style=social&label=Star)](https://github.com/hoachen/veggieai-generate-video)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://viggle.ai/)

+ [Luma](https://lumalabs.ai/dream-machine)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://lumalabs.ai/dream-machine)

+ [Runway](https://runwayml.com/)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://runwayml.com/)


### Datasets
+ [Text2performer](https://drive.google.com/drive/folders/1NFd_irnw8kgNcu5KfWhRA8RZPdBK5p1I)
+ [Tiktok](https://www.kaggle.com/datasets/yasaminjafarian/tiktokdataset?resource=download)
+ [Tiktok-v4](https://drive.google.com/file/d/1jEK0YJ5AfZZuFNqGGqOtUPFx--TIebT9/view)
+ [TED gesture dataset](https://github.com/youngwoo-yoon/youtube-gesture-dataset)
+ [Bold](https://cydar.ist.psu.edu/emotionchallenge/dataset.php)
+ [DeepFashion](https://mmlab.ie.cuhk.edu.hk/projects/DeepFashion.html)
+ [Taichi](https://github.com/AliaksandrSiarohin/video-preprocessing)
+ [Ubody](https://osx-ubody.github.io/)
+ [ASTS](https://www.wisdom.weizmann.ac.il/~vision/SpaceTimeActions.html)
+ [UCF-101](https://www.crcv.ucf.edu/data/UCF101.php)
+ [human3.6m](http://vision.imar.ro/human3.6m/description.php)
+ [NTU RGB+D](https://rose1.ntu.edu.sg/dataset/actionRecognition/)
+ [HAR](https://www.kaggle.com/datasets/sharjeelmazhar/human-activity-recognition-video-dataset)
+ [3D People Synthetic](https://drive.google.com/file/d/1N9gioWnkb3ZZytmT3Nzx4VjXjHxLsVB9/view)
+ [MSP-Avatar](https://ecs.utdallas.edu/research/researchlabs/msp-lab/MSP-AVATAR.html)
+ [EverybodyDance](https://github.com/carolineec/EverybodyDanceNow)
+ [AIST++](https://google.github.io/aistplusplus_dataset/factsfigures.html)
+ [DanceIt](https://github.com/iCVTEAM/DanceIt?tab=readme-ov-file)
+ [Disco](https://drive.google.com/file/d/1N9gioWnkb3ZZytmT3Nzx4VjXjHxLsVB9/view)
+ [Sub-URMP](https://www.cs.rochester.edu/~cxu22/d/vagan/)
+ [URMP](https://labsites.rochester.edu/air/projects/URMP.html)

# Conditional-content-generation

## Contents
- Papers List
  - [Tracking Papers on Diffusion Models](https://vsehwag.github.io/blog/2023/2/all_papers_on_diffusion.html)
  - Conditional Human Motion Generation
    - [Music-Driven motion generation](#music-driven-motion-generation)
    - [Text-Driven motion generation](#text-driven-motion-generation)
    - [Audio-Driven motion generation](#audio-driven-motion-generation)
    - [Human Motion Prediction](#human-motion-prediction)
    - [Motion Applications](#motion-applications)
  - Conditional Image Generation
    - [Text-Image Generation](#text-image-generation)
    - [Text-3D Image Generation](#text-3d-image-generation)
  - Conditional Video Generation
    - [Text-Video Generation](#text-video-generation)

## Papers

### Music-Driven motion generation

[Taming Diffusion Models for Music-driven Conducting Motion Generation](https://arxiv.org/abs/2306.10065) \
NUS, AAAI 2023 Summer Symposium, [[Code]](https://github.com/viiika/Diffusion-Conductor)

[Music-Driven Group Choreography](http://128.84.21.203/abs/2303.12337) \
AIOZ AI, CVPR'23

[Discrete Contrastive Diffusion for Cross-Modal and Conditional Generation](https://github.com/L-YeZhu/CDCD) \
Illinois Institute of Technology, ICLR'23, [[Code]](https://github.com/L-YeZhu/CDCD)

[Magic: Multi Art Genre Intelligent Choreography Dataset and Network for 3D Dance Generation](https://arxiv.org/abs/2212.03741) \
 Tsinghua University, 7 Dec 2022

[Pretrained Diffusion Models for Unified Human Motion Synthesis](https://ofa-sys.github.io/MoFusion/) \
DAMO Academy, Alibaba Group, 6 Dec 2022

[EDGE: Editable Dance Generation From Music](https://arxiv.org/abs/2211.10658) \
Stanford University, 19 Nov 2022

[You Never Stop Dancing: Non-freezing Dance Generation via Bank-constrained Manifold Projection](https://openreview.net/forum?id=88ubVLwWvGD) \
MSRA, NeurIPS'22

[GroupDancer: Music to Multi-People Dance Synthesis with Style Collaboration](https://dl.acm.org/doi/abs/10.1145/3503161.3548090) \
Tsinghua University, ACMMM'22

[A Brand New Dance Partner: Music-Conditioned Pluralistic Dancing Controlled by Multiple Dance Genres](https://openaccess.thecvf.com/content/CVPR2022/papers/Kim_A_Brand_New_Dance_Partner_Music-Conditioned_Pluralistic_Dancing_Controlled_by_CVPR_2022_paper.pdf) \
Yonsei University, CVPR 2022, [[Code]](https://github.com/jw09191/MNET)

[Bailando: 3D Dance Generation by Actor-Critic GPT with Choreographic Memory](https://www.mmlab-ntu.com/project/bailando/index.html) \
NTU, CVPR 2022 (Oral), [[Code]](https://github.com/lisiyao21/Bailando)

[Dance Style Transfer with Cross-modal Transformer](https://arxiv.org/abs/2208.09406) \
KTH, 22 Aug 2022, [[Upcoming Code]](https://github.com/YIN95/cycledance-pytorch-lightning)

[Music-driven Dance Regeneration with Controllable Key Pose Constraints](https://arxiv.org/abs/2207.03682) \
Tencent, 8 July 2022


### Text-Driven motion generation

[ReMoDiffuse: Retrieval-Augmented Motion Diffusion Model](https://mingyuan-zhang.github.io/projects/ReMoDiffuse.html) \
NTU, CVPR'23, [[Code]](https://github.com/mingyuan-zhang/ReMoDiffuse)

[TEMOS: Generating diverse human motions from textual descriptions](mathis.petrovich.fr/temos/) \
ENPC, CVPR'23

[GestureDiffuCLIP: Gesture Diffusion Model with CLIP Latents](https://arxiv.org/abs/2303.14613) \
Peking University, CVPR'23

[Human Motion Diffusion as a Generative Prior](https://priormdm.github.io/priorMDM-page) \
Anonymous Authors, [[Code]](https://github.com/priorMDM/priorMDM)

[T2M-GPT: Generating Human Motion from Textual Descriptions with Discrete Representations](https://mael-zys.github.io/T2M-GPT/) \
Tencent AI Lab, 16 Jan 2023, [[Code]](https://github.com/Mael-zys/T2M-GPT)

[Modiff: Action-Conditioned 3D Motion Generation with Denoising Diffusion Probabilistic Models](https://arxiv.org/abs/2301.03949) \
Beihang University, 10 Jan 2023

[Executing your Commands via Motion Diffusion in Latent Space](https://chenxin.tech/mld/) \
Tencent, 8 Dec 2022, [[Code]](https://github.com/ChenFengYe/motion-latent-diffusion)

[MultiAct: Long-Term 3D Human Motion Generation from Multiple Action Labels](https://arxiv.org/abs/2212.05897) \
Seoul National University, AAAI 2023 Oral, [[Code]](https://github.com/TaeryungLee/MultiAct_RELEASE)

[MoFusion: A Framework for Denoising-Diffusion-based Motion Synthesis](https://vcai.mpi-inf.mpg.de/projects/MoFusion/) \
Max Planck Institute for Informatics, 8 Dec 2022

[Executing your Commands via Motion Diffusion in Latent Space](https://chenxin.tech/mld/) \
Tencent PCG, 8 Dec 2022, [[Upcoming Code]](https://github.com/ChenFengYe/motion-latent-diffusion)

[UDE: A Unified Driving Engine for Human Motion Generation](https://arxiv.org/pdf/2211.16016.pdf) \
Xiaobing Inc, 29 Nov 2022, [[Upcoming Code]](https://github.com/zixiangzhou916/UDE/)

[MotionBERT: Unified Pretraining for Human Motion Analysis](https://motionbert.github.io/) \
SenseTime Research, 12 Oct 2022, [[Code]](https://github.com/Walter0807/MotionBERT)

[Human Motion Diffusion Model](https://guytevet.github.io/mdm-page) \
Tel Aviv University, 3 Oct 2022, [[Code]](https://github.com/GuyTevet/motion-diffusion-model)

[FLAME: Free-form Language-based Motion Synthesis & Editing](https://arxiv.org/abs/2209.00349) \
Korea University, 1 Sep 2022

[MotionDiffuse: Text-Driven Human Motion Generation with Diffusion Model](https://mingyuan-zhang.github.io/projects/MotionDiffuse.html) \
NTU, 22 Aug 2022, [[Code]](https://github.com/mingyuan-zhang/MotionDiffuse)

[TEMOS: Generating diverse human motions from textual descriptions](https://mathis.petrovich.fr/temos/) \
MPI, ECCV 2022 (Oral), [[Code]](https://github.com/Mathux/TEMOS)

[GIMO: Gaze-Informed Human Motion Prediction in Context](https://geometry.stanford.edu/projects/gimo/) \
Stanford University, ECCV 2022, [[Code]](https://github.com/y-zheng18/GIMO)

[MotionCLIP: Exposing Human Motion Generation to CLIP Space](https://guytevet.github.io/motionclip-page/) \
Tel Aviv University, ECCV 2022, [[Code]](https://github.com/GuyTevet/MotionCLIP)

[Generating Diverse and Natural 3D Human Motions from Text](https://ericguo5513.github.io/text-to-motion/) \
University of Alberta, CVPR 2022, [[Code]](https://github.com/EricGuo5513/text-to-motion)

[AvatarCLIP: Zero-Shot Text-Driven Generation and Animation of 3D Avatars](https://hongfz16.github.io/projects/AvatarCLIP.html) \
NTU, SIGGRAPH 2022, [[Code]](https://github.com/hongfz16/AvatarCLIP)

### Audio-Driven motion generation

For more recent paper, you can find from [here](https://github.com/YunjinPark/awesome_talking_face_generation)

[Taming Diffusion Models for Audio-Driven Co-Speech Gesture Generation](https://github.com/Advocate99/DiffGesture) \
NTU, CVPR'23, [[Code]](https://github.com/Advocate99/DiffGesture)

[GeneFace: Generalized and High-Fidelity Audio-Driven 3D Talking Face Synthesis](https://geneface.github.io/) \
Zhejiang University, ICLR'23, [[Code]](https://github.com/yerfor/GeneFace)

[DiffMotion: Speech-Driven Gesture Synthesis Using Denoising Diffusion Model](https://arxiv.org/abs/2301.10047) \
 Macau University of Science and Technolog, 24 Jan 2023

[DiffTalk: Crafting Diffusion Models for Generalized Talking Head Synthesis](https://arxiv.org/abs/2301.03786) \
Tsinghua University, 10 Jan 2023

[Diffused Heads: Diffusion Models Beat GANs on Talking-Face Generation](https://mstypulkowski.github.io/diffusedheads/) \
University of Wrocław, 6 Jan 2023, [[Incoming Code]](https://github.com/MStypulkowski/diffused-heads)

[Generating Holistic 3D Human Motion from Speech](https://talkshow.is.tue.mpg.de/) \
Max Planck Institute for Intelligent Systems, 8 Dev 2022

[Audio-Driven Co-Speech Gesture Video Generation](https://arxiv.org/abs/2212.02350) \
NTU, 5 Dec 2022

[Listen, denoise, action! Audio-driven motion synthesis with diffusion models](https://www.speech.kth.se/research/listen-denoise-action/) \
KTH Royal Institute of Technology, 17 Nov 2022

[ZeroEGGS: Zero-shot Example-based Gesture Generation from Speech](https://arxiv.org/abs/2209.07556) \
York University, 23 Sep 2022, [[Code]](https://github.com/ubisoft/ubisoft-laforge-ZeroEGGS)

[BEAT: A Large-Scale Semantic and Emotional Multi-Modal Dataset for Conversational Gestures Synthesis](https://pantomatrix.github.io/BEAT/) \
The University of Tokyo, ECCV 2022, [[Code]](https://github.com/PantoMatrix/BEAT)

[EAMM: One-Shot Emotional Talking Face via Audio-Based Emotion-Aware Motion Model](https://jixinya.github.io/projects/EAMM/)\
Nanjing University, SIGGRAPH 2022, [[Code]](https://github.com/jixinya/EAMM/)

[Learning Hierarchical Cross-Modal Association for Co-Speech Gesture Generation](https://openaccess.thecvf.com/content/CVPR2022/papers/Liu_Learning_Hierarchical_Cross-Modal_Association_for_Co-Speech_Gesture_Generation_CVPR_2022_paper.pdf) \
The Chinese University of Hong Kong, CVPR 2022, [[Code]](https://github.com/alvinliu0/HA2G)

[SEEG: Semantic Energized Co-speech Gesture Generation](https://ffmpbgrnn.github.io/publications/pdf/seeg.pdf) \
Alibaba DAMO Academy, CVPR 2022, [[Code]](https://github.com/akira-l/SEEG)

[FaceFormer: Speech-Driven 3D Facial Animation with Transformers](https://evelynfan.github.io/audio2face/) \
The University of Hong Kong, CVPR 2022, [[Code]](https://github.com/EvelynFan/FaceFormer)

[Freeform Body Motion Generation from Speech](https://arxiv.org/abs/2203.02291) \
JD AI Research, 4 Mar 2022, [[Code]](https://github.com/TheTempAccount/Co-Speech-Motion-Generation)

### Human motion prediction

For more recent more, you can find from [here](https://github.com/aras62/vision-based-prediction/blob/master/papers/motion_papers.md)

[InterDiff: Generating 3D Human-Object Interactions with Physics-Informed Diffusion](https://sirui-xu.github.io/InterDiff/)\
UIUC, ICCV 2023, [[Code]](https://github.com/Sirui-Xu/InterDiff)

[Stochastic Multi-Person 3D Motion Forecasting](https://sirui-xu.github.io/DuMMF/)\
UIUC, ICLR 2023 (Spotlight), [[Code]](https://github.com/Sirui-Xu/DuMMF)

[HumanMAC: Masked Motion Completion for Human Motion Prediction](https://lhchen.top/Human-MAC/)\
Tsinghua University, ICCV 2023, [[Code]](https://github.com/LinghaoChan/HumanMAC)

[BeLFusion: Latent Diffusion for Behavior-Driven Human Motion Prediction](https://barquerogerman.github.io/BeLFusion/) \
University of Barcelona, 25 Nov 2022, [[Upcoming Code]](https://github.com/BarqueroGerman/BeLFusion)

[Diverse Human Motion Prediction Guided by Multi-Level Spatial-Temporal Anchors](https://sirui-xu.github.io/STARS/)\
UIUC, ECCV 2022 (Oral), [[Code]](https://github.com/Sirui-Xu/STARS)

[PoseGPT: Quantization-based 3D Human Motion Generation and Forecasting](https://europe.naverlabs.com/research/computer-vision/posegpt/) \
NAVER LABS, ECCV'2022, [[Code]](https://github.com/naver/PoseGPT)

[NeMF: Neural Motion Fields for Kinematic Animation](https://cs.yale.edu/homes/che/projects/nemf/) \
Yale University, NeurIPS 2022 (Spotlight), [[Code]](https://github.com/c-he/NeMF)

[Multi-Person Extreme Motion Prediction](https://openaccess.thecvf.com/content/CVPR2022/papers/Guo_Multi-Person_Extreme_Motion_Prediction_CVPR_2022_paper.pdf) \
Inria University, CVPR 2022, [[Code]](https://github.com/GUO-W/MultiMotion)

[MotionMixer: MLP-based 3D Human Body Pose Forecasting](https://arxiv.org/abs/2207.00499) \
Mercedes-Benz, IJCAI 2022 (Oral), [[Code]](https://github.com/MotionMLP/MotionMixer)

### Motion Applications

[MIME: Human-Aware 3D Scene Generation](https://mime.is.tue.mpg.de/) \
MPI

[Scene Synthesis from Human Motion](https://lijiaman.github.io/projects/summon/) \
Stanford University, SIGGRAPH Asia 2022, [[Code]](https://github.com/onestarYX/summon)

[TEACH: Temporal Action Compositions for 3D Humans](https://teach.is.tue.mpg.de/) \
MPI, 3DV 2022, [[Code]](https://github.com/athn-nik/teach)

[Motion In-betweening via Two-stage Transformers](http://kunzhou.net/2022/motion-siga22.pdf) \
Zhejiang University, SIGGRAPH Asia 2022

[Skeleton2Humanoid: Animating Simulated Characters for Physically-plausible Motion In-betweening](https://dl.acm.org/doi/abs/10.1145/3503161.3548093) \
Shanghai Jiaotong University, ACMMM 2022, [[Upcoming Code]](https://github.com/michaelliyunhao/Skeleton2Humanoid)

[Conditional Motion In-betweening](https://arxiv.org/abs/2202.04307) \
Korea University, 6 Oct 2022, [[Code]](https://github.com/jihoonerd/Conditional-Motion-In-Betweening)

[SkeletonMAE: Spatial-Temporal Masked Autoencoders for Self-supervised Skeleton Action Recognition](https://arxiv.org/abs/2209.02399) \
University of North Carolina, 1 Sep 2022

[A Unified Framework for Real Time Motion Completion](https://ojs.aaai.org/index.php/AAAI/article/view/20368) \
NetEase Games AI Lab, AAAI 2022

[Transformer based Motion In-betweening](https://openaccess.thecvf.com/content/ACCV2022W/TCV/papers/Sridhar_Transformer_Based_Motion_In-Betweening_ACCVW_2022_paper.pdf) \
National Institute of Technology - Tiruchirappalli, ACCV 2022 Workshop, [[Code]](https://github.com/Pavi114/motion-completion-using-transformers)



### Text-Image Generation

For more recent paper, you can find from [here](https://github.com/heejkoo/Awesome-Diffusion-Models#text-to-image)

[Adding Conditional Control to Text-to-Image Diffusion Models](https://github.com/lllyasviel/ControlNet) \
Stanford, Feb 2023

[SpaText: Spatio-Textual Representation for Controllable Image Generation](https://omriavrahami.com/spatext/) \
Meta AI (FAIR), 25 Nov 2022

[Sketch-Guided Text-to-Image Diffusion Models](https://arxiv.org/pdf/2211.13752.pdf) \
Google Research, 24 Nov 2022

[Make-A-Story: Visual Memory Conditioned Consistent Story Generation](https://arxiv.org/abs/2211.13319) \
University of British Columbia, 23 Nov 2022

[Synthesizing Coherent Story with Auto-Regressive Latent Diffusion Models](https://arxiv.org/pdf/2211.10950.pdf) \
University of Waterloo, 20 Nov 2022, [[Upcoming Code]](https://github.com/Flash-321/ARLDM)

[InstructPix2Pix: Learning to Follow Image Editing Instructions](https://arxiv.org/abs/2211.09800) \
UC Berkeley, 17 Nov 2022

[Null-text Inversion for Editing Real Images using Guided Diffusion Models](https://arxiv.org/abs/2211.09794) \
Google Research, 17 Nov 2022

[HumanDiffusion: a Coarse-to-Fine Alignment Diffusion Framework for Controllable Text-Driven Person Image Generation](https://arxiv.org/abs/2211.06235) \
University of Chinese Academy of Sciences, 11 Nov 2022

[Imagic: Text-Based Real Image Editing with Diffusion Models](https://imagic-editing.github.io/) \
Google Research, 17 Oct 2022

[Self-Guided Diffusion Models](https://arxiv.org/abs/2210.06462) \
University of Amsterdam, 12 Oct 2022

[On Distillation of Guided Diffusion Models](https://arxiv.org/abs/2210.03142) \
Stanford University, NeurIPS 2022 Workshop, 6 Oct 2022

[DreamBooth: Fine Tuning Text-to-Image Diffusion Models for Subject-Driven Generation](https://dreambooth.github.io/) \
Google Research, 25 Aug 2022, [[Code]](https://github.com/XavierXiao/Dreambooth-Stable-Diffusion)

[Prompt-to-Prompt Image Editing with Cross Attention Control](https://arxiv.org/abs/2208.01626) \
Google Research, 2 Aug 2022, [[Code]](https://github.com/bloc97/CrossAttentionControl)

[Improved Vector Quantized Diffusion Models](https://arxiv.org/abs/2205.16007) \
University of Science and Technology of China, 31 May 2022, [[Code]](https://github.com/cientgu/VQ-Diffusion)

[Make-A-Scene: Scene-Based Text-to-Image Generation with Human Priors](https://arxiv.org/pdf/2203.13131.pdf) \
Meta AI Research, 24 Mar 2022

[Diffusion Autoencoders: Toward a Meaningful and Decodable Representation](https://diff-ae.github.io/) \
Vidyasirimedhi Institute of Science and Technology, CVPR 2022 (Oral), [[Code]](https://github.com/phizaz/diffae)

[Vector Quantized Diffusion Model for Text-to-Image Synthesis](https://openaccess.thecvf.com/content/CVPR2022/papers/Gu_Vector_Quantized_Diffusion_Model_for_Text-to-Image_Synthesis_CVPR_2022_paper.pdf) \
University of Science and Technology of China, CVPR 2022, [[Code]](https://github.com/cientgu/VQ-Diffusion)

[High-Resolution Image Synthesis with Latent Diffusion Models](https://openaccess.thecvf.com/content/CVPR2022/papers/Rombach_High-Resolution_Image_Synthesis_With_Latent_Diffusion_Models_CVPR_2022_paper.pdf) \
Runway ML, CVPR 2022, [[Code]](https://github.com/CompVis/latent-diffusion)

### Text-Video Generation
[TI2V-Zero: Zero-Shot Image Conditioning for Text-to-Video Diffusion Models](https://arxiv.org/pdf/2404.16306) \
Penn State University, CVPR 2024, [[Code]](https://github.com/merlresearch/TI2V-Zero)

[Conditional Image-to-Video Generation with Latent Flow Diffusion Models](https://arxiv.org/pdf/2303.13744) \
Penn State University, CVPR 2023, [[Code]](https://github.com/nihaomiao/CVPR2023_LFDM)

[Text-To-4D Dynamic Scene Generation](https://make-a-video3d.github.io/) \
Meta AI, 2023, [[Code]](https://github.com/Make-A-Video3D/Make-A-Video3D.github.io)

[Structure and Content-Guided Video Synthesis with Diffusion Models](https://research.runwayml.com/gen1) \
Runway, 6 Feb 2023

[Latent Video Diffusion Models for High-Fidelity Video Generation with Arbitrary Lengths](https://yingqinghe.github.io/LVDM/) \
The Hong Kong University of Science and Technology, 23 Nov 2022, [[Upcoming Code]](https://github.com/YingqingHe/LVDM)

[MagicVideo: Efficient Video Generation With Latent Diffusion Models](https://magicvideo.github.io/) \
ByteDance Inc, 20 Nov 2022

[Text2LIVE: Text-Driven Layered Image and Video Editing](https://text2live.github.io/) \
NVIDIA Research, ECCV 2022 (Oral), [[Code]](https://github.com/omerbt/Text2LIVE)

### Text-3D Image Generation
[Point-E: A System for Generating 3D Point Clouds from Complex Prompts](https://arxiv.org/abs/2212.08751) \
OpenAI, 16 Dec 2022

[DreamFusion: Text-to-3D using 2D Diffusion](https://dreamfusion3d.github.io/) \
Google Research, 29 Sep 2022

# Digital Human 

## Table of Contents
	
- [Industry Demo or Product](#industry-demo-or-product)
- [3D Human Avatar Generation and Animation](#3d-human-avatar-generation-and-animation)
- [3D Head Animatable Avatar (from 2D Image Collections)](#3d-head-animatable-avatar--from-2d-image-collections-)
- [(Clothed) Human Motion Generation](#-clothed--human-motion-generation)
- [Clothed Human Digitalization](#clothed-human-digitalization)
- [Cloth Modelling, Draping, Simulation, and Dressing](#cloth-modelling--draping--simulation--and-dressing)
- [Human Image and Video Generation](#human-image-and-video-generation)
- [Image-Based Virtual Try-On](#image-based-virtual-try-on)
- [Human Body Reshaping](#human-body-reshaping)
- [Garment Design](#garment-design)
- [Fashion Style Influences](#fashion-style-influences)
- [Team and People](#team-and-people)
- [Dataset](#dataset)
- [Applications](#applications)


## Industry Demo or Product

Highavenue: Turn yourself into a 3D model.

## 3D Human Avatar Generation and Animation

**RodinHD: High-Fidelity 3D Avatar Generation with Diffusion Models.**<br>
*Bowen Zhang, Yiji Cheng, Chunyu Wang, Ting Zhang, Jiaolong Yang, Yansong Tang, Feng Zhao, Dong Chen, Baining Guo.*<br>
ECCV 2024. [[PDF](https://arxiv.org/abs/2407.06938)] [[Project](https://rodinhd.github.io/;)] [[Code]()]

**Animatable Gaussians: Learning Pose-dependent Gaussian Maps for High-fidelity Human Avatar Modeling.**<br>
*Zhe Li, Zerong Zheng, Lizhen Wang, Yebin Liu..*<br> 
CVPR 2024. [[PDF](http://arxiv.org/abs/2311.16096)] [[Project](https://animatable-gaussians.github.io)] [[Code](https://github.com/lizhe00/AnimatableGaussians)]

**HumanNorm: Learning Normal Diffusion Model for High-quality and Realistic 3D Human Generation.**<br>
*Xin Huang, Ruizhi Shao, Qi Zhang, Hongwen Zhang, Ying Feng, Yebin Liu, Qing Wang..*<br> 
CVPR 2024. [[PDF]()] [[Project](https://humannorm.github.io/)]

**RAM-Avatar: Real-time Photo-Realistic Avatar from Monocular Videos with Full-body Control.**<br>
*Xiang Deng, Zerong Zheng, Yuxiang Zhang, Jingxiang Sun, Chao Xu, XiaoDong Yang, Lizhen Wang, Yebin Liu.*<br> 
CVPR 2024. [[PDF](https://cloud.tsinghua.edu.cn/f/6b7a88c3b4ac43b0b506/?dl=1)] [[Project](https://github.com/Xiang-Deng00/RAM-Avatar/)] [[Code](https://github.com/Xiang-Deng00/RAM-Avatar)]

**TexVocab:Texture Vocabulary-conditioned Human Avatars.**<br>
*Yuxiao Liu, Zhe Li, Yebin Liu, Haoqian Wang.*<br> 
CVPR 2024. [[PDF](https://arxiv.org/abs/2404.00524)] [[Project](https://texvocab.github.io/)]

**HumanGaussian: Text-Driven 3D Human Generation with Gaussian Splatting.**<br>
*Xian Liu, Xiaohang Zhan, Jiaxiang Tang, Ying Shan, Gang Zeng, Dahua Lin, Xihui Liu, Ziwei Liu.*<br> 
CVPR 2024. [[PDF](http://arxiv.org/abs/2311.17061)] [[Project](https://alvinliu0.github.io/projects/HumanGaussian)]

**DreamAvatar: Text-and-Shape Guided 3D Human Avatar Generation via Diffusion Models.**<br>
*[Yukang Cao](https://yukangcao.github.io/), [Yan-Pei Cao](https://yanpei.me/), [Kai Han](https://www.kaihan.org/), [Ying Shan](https://scholar.google.com/citations?user=4oXBp9UAAAAJ&hl=zh-CN), [Kwan-Yee K. Wong](https://i.cs.hku.hk/~kykwong/).*<br>
CVPR 2024. [[PDF](https://arxiv.org/abs/2304.00916)] [[Project](https://yukangcao.github.io/DreamAvatar/)] [[Code](https://yukangcao.github.io/DreamAvatar/)]

**SCULPT: Shape-Conditioned Unpaired Learning of Pose-dependent Clothed and Textured Human Meshes.**<br>
*Soubhik Sanyal, Partha Ghosh, Jinlong Yang, Michael J. Black, Justus Thies, Timo Bolkart.*<br>
CVPR 2024. [[PDF](https://arxiv.org/abs/2308.10638)] [[Project](https://huangyangyi.github.io/tech/)]

**3DGS-Avatar: Animatable Avatars via Deformable 3D Gaussian Splatting.**<br>
*Zhiyin Qian, Shaofei Wang, Marko Mihajlovic, Andreas Geiger, Siyu Tang.*<br> 
CVPR 2024. [[PDF](https://arxiv.org/abs/2312.09228)] [[Project](https://neuralbodies.github.io/3DGS-Avatar/)]

**Emotional Speech-driven 3D Body Animation Via Disentangled Latent Diffusion.**<br>
*Kiran Chhatre, Radek Daněček, Nikos Athanasiou, Giorgio Becherini, Christopher Peters, Michael J. Black, Timo Bolkart.*<br> 
CVPR 2024. [[PDF](http://arxiv.org/abs/2312.04466)]

**GauHuman: Articulated Gaussian Splatting from Monocular Human Videos.**<br>
*Shoukang Hu, Ziwei Liu.*<br> 
CVPR 2024. [[PDF](http://arxiv.org/abs/2312.02973v1)] [[Project](https://skhu101.github.io/GauHuman/)] [[Code](https://github.com/skhu101/GauHuman)]

**FlashAvatar: High-Fidelity Digital Avatar Rendering at 300FPS.**<br>
*Jun Xiang, Xuan Gao, Yudong Guo, Juyong Zhang.*<br> 
CVPR 2024. [[PDF](http://arxiv.org/abs/2312.02214v1)] [[Project](https://ustc3dv.github.io/FlashAvatar/)]

**PEGASUS: Personalized Generative 3D Avatars with Composable Attributes.**<br>
*[Hyunsoo Cha](https://research.hyunsoocha.com/), [Byungjun Kim](https://bjkim95.github.io/), [Hanbyul Joo](https://jhugestar.github.io/).*<br>
CVPR 2024. [[PDF](https://arxiv.org/pdf/2402.10636)] [[Project](https://snuvclab.github.io/pegasus/)] [[Code](https://github.com/snuvclab/pegasus)]

**TADA! Text to Animatable Digital Avatars.**<br>
*[Tingting Liao](https://github.com/TingtingLiao), [Hongwei Yi](https://xyyhw.top/), [Yuliang Xiu](http://xiuyuliang.cn/), [Jiaxiang Tang](https://me.kiui.moe/), [Yangyi Huang](https://github.com/huangyangyi/), [Justus Thies](https://justusthies.github.io/), [Michael J. Black](https://ps.is.tuebingen.mpg.de/person/black).*<br>
3DV 2024. [[PDF](https://arxiv.org)] [[Project](https://tada.is.tue.mpg.de/)] [[Code](https://github.com/TingtingLiao/TADA)]

**Efficient 3D Articulated Human Generation with Layered Surface Volumes.**<br>
*Yinghao Xu, Wang Yifan, Alexander W. Bergman, Menglei Chai, Bolei Zhou, Gordon Wetzstein.*<br> 
3DV 2024. [[PDF](https://arxiv.org/abs/2307.05462)] [[Project](https://www.computationalimaging.org/publications/lsv/)]

**TECA: Text-Guided Generation and Editing of Compositional 3D Avatars.**<br>
*[Hao Zhang](https://haozhang990127.github.io/), [Yao Feng](https://scholar.google.com/citations?user=wNQQhSIAAAAJ&hl=en&oi=ao), [Peter Kulits](https://kulits.github.io/), [Yandong Wen](https://is.mpg.de/person/ydwen), [Justus Thies](https://justusthies.github.io/), [Michael J. Black](https://ps.is.mpg.de/person/black).*<br> 
3DV 2024. [[PDF](https://arxiv.org/abs/2309.07125)] [[Project](https://yfeng95.github.io/teca/)]

**FLARE: Fast Learning of Animatable and Relightable Mesh Avatars.**<br>
*Shrisha Bharadwaj, Yufeng Zheng, Otmar Hilliges, Michael J. Black, Victoria Fernandez-Abrevaya.*<br>
SIGGRAPH Asia 2023. [[PDF](https://arxiv.org/abs/2310.17519)]

**Single-Shot Implicit Morphable Faces with Consistent Texture Parameterization.**<br>
*Connor Z. Lin, Koki Nagano, Jan Kautz, Eric R. Chan, Umar Iqbal, Leonidas Guibas, Gordon Wetzstein, Sameh Khamis.*<br>
SIGGRAPH 2023. [[PDF](https://arxiv.org/abs/2305.03043)] [[Project](https://research.nvidia.com/labs/toronto-ai/ssif/)] [[Code]()]

**DELIFFAS: Deformable Light Fields for Fast Avatar Synthesis.**<br>
*Youngjoong Kwon, Lingjie Liu, Henry Fuchs, Marc Habermann, Christian Theobalt.*<br> 
NeurIPS 2023. [[PDF](http://arxiv.org/abs/2310.11449)]

**PrimDiffusion: Volumetric Primitives Diffusion for 3D Human Generation.**<br>
*Zhaoxi Chen, Fangzhou Hong, Haiyi Mei, Guangcong Wang, Lei Yang, Ziwei Liu.*<br> 
NeurIPS 2023. [[PDF](http://arxiv.org/abs/2312.04559)] [[Project](https://frozenburning.github.io/projects/primdiffusion/)] [[Code](https://github.com/FrozenBurning/PrimDiffusion)]

**XAGen: 3D Expressive Human Avatars Generation.**<br>
*Zhongcong Xu, Jianfeng Zhang, Jun Hao Liew, Jiashi Feng, Mike Zheng Shou.*<br>
NeurIPS 2023. [[PDF](https://arxiv.org/abs/2311.13574)] [[Project](https://showlab.github.io/xagen/)] [[Code](https://github.com/magic-research/xagen)]

**DreamHuman: Animatable 3D Avatars from Text.**<br>
*[Nikos Kolotouros](https://www.nikoskolot.com/), [Thiemo Alldieck](https://research.google/people/107250/), [Andrei Zanfir](https://scholar.google.com/citations?user=8lmzWycAAAAJ&hl=en&oi=ao), [Eduard Gabriel Bazavan](https://research.google/people/107659/), [Mihai Fieraru](https://mihaifieraru.github.io/), [Cristian Sminchisescu](https://research.google/people/CristianSminchisescu/).*<br> 
NeurIPS 2023. [[PDF](https://arxiv.org/abs/2306.09329)] [[Project](https://dream-human.github.io/)] [[Avatar Gallery](https://dream-human.github.io/avatar_gallery.html)]

**DINAR: Diffusion Inpainting of Neural Textures for One-Shot Human Avatars.**<br>
*David Svitov, Dmitrii Gudkov, Renat Bashirov, Victor Lempitsky.*<br> 
ICCV 2023. [[PDF](https://arxiv.org/abs/2303.09375)] [[Code](https://github.com/SamsungLabs/DINAR)]

**AvatarCraft: Transforming Text into Neural Human Avatars with Parameterized Shape and Pose Control.**<br>
*[Ruixiang Jiang](https://j-rx.com/), [Can Wang](https://cassiepython.github.io/), [Jingbo Zhang](https://eckertzhang.github.io/), [Menglei Chai](https://mlchai.com/), [Mingming He](https://mingminghe.com/), [Dongdong Chen](https://www.dongdongchen.bid/), [Jing Liao](https://liaojing.github.io/html/).*<br>
ICCV 2023. [[PDF](https://arxiv.org/abs/2303.17606)] [[Project](https://avatar-craft.github.io/)] [[Code](https://github.com/songrise/avatarcraft)] [[Data](https://drive.google.com/drive/folders/1m97mmoAtDes0mBwkS4q2VNBivXSmRkOK)]

**StyleAvatar3D: Leveraging Image-Text Diffusion Models for High-Fidelity 3D Avatar Generation.**<br>
*Chi Zhang, Yiwen Chen, Yijun Fu, Zhenglin Zhou, Gang YU, Billzb Wang, Bin Fu, Tao Chen, Guosheng Lin, Chunhua Shen.*<br> 
ICCV 2023. [[PDF](http://arxiv.org/abs/2305.19012)] [[Project](https://x-zhangyang.github.io/2023_Get3DHuman/)] [[Code](https://github.com/icoz69/StyleAvatar3D)]

**Get3DHuman: Lifting StyleGAN-Human into a 3D Generative Model using Pixel-aligned Reconstruction Priors.**<br>
*Zhangyang Xiong, Di Kang, Derong Jin, Weikai Chen, Linchao Bao, Xiaoguang Han.*<br>
ICCV 2023. [[PDF](https://arxiv.org/abs/2302.01162)] [[Code](https://github.com/X-zhangyang/Get3DHuman/)]

**GETAvatar: Generative Textured Meshes for Animatable Human Avatars.**<br>
*Xuanmeng Zhang, Jianfeng Zhang, Rohan Chacko, Hongyi Xu, Guoxian Song, Yi Yang, Jiashi Feng.*<br>
ICCV 2023. [[PDF](https://arxiv.org/abs/2310.02714)] [[Project](https://getavatar.github.io/)]

**AG3D: Learning to Generate 3D Avatars from 2D Image Collections.**<br>
*[Zijian Dong](https://ait.ethz.ch/people/zijian/), [Xu Chen](https://ait.ethz.ch/people/xu/), [Jinlong Yang](https://is.mpg.de/~jyang), [Michael J. Black](https://ps.is.mpg.de/~black), [Otmar Hilliges](https://ait.ethz.ch/people/hilliges), [Andreas Geiger](http://www.cvlibs.net/).*<br> 
ICCV 2023. [[PDF](http://arxiv.org/abs/2305.02312)] [[Project](https://zj-dong.github.io/AG3D/)] [[Code](https://github.com/zj-dong/AG3D)]

**Learning Locally Editable Virtual Humans.**<br>
*[Hsuan-I Ho](https://azuxmioy.github.io/), [Lixin Xue](https://lxxue.github.io/), [Jie Song](https://ait.ethz.ch/people/song), [Otmar Hilliges](https://ait.ethz.ch/people/hilliges).*<br>
CVPR 2023. [[PDF](https://files.ait.ethz.ch/projects/custom-humans/paper.pdf)] [[Project](https://custom-humans.github.io/)] [[Code](https://github.com/custom-humans/editable-humans)]

**PersonNeRF: Personalized Reconstruction from Photo Collections.**<br>
*[Chung-Yi Weng](https://homes.cs.washington.edu/~chungyi/), Pratul P. Srinivasan, Brian Curless, Ira Kemelmacher-Shlizerman.*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/2302.01162)] [[Project](https://grail.cs.washington.edu/projects/personnerf/)] [[Code]()]

**Latent-NeRF for Shape-Guided Generation of 3D Shapes and Textures.**<br>
*Gal Metzer, Elad Richardson, Or Patashnik, Raja Giryes, Daniel Cohen-Or.*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/2211.07600)]  [[Code](https://github.com/eladrich/latent-nerf)]

**EVA3D: Compositional 3D Human Generation from 2D Image Collections.**<br>
*[Fangzhou Hong](https://hongfz16.github.io/), [Zhaoxi Chen](https://frozenburning.github.io/), [Yushi Lan](https://github.com/NIRVANALAN), [Liang Pan](https://scholar.google.com/citations?user=lSDISOcAAAAJ&hl=zh-CN), [Ziwei Liu](https://liuziwei7.github.io/).*<br>
ICLR 2023. [[PDF](https://arxiv.org/abs/2210.04888)] [[Project](https://hongfz16.github.io/projects/EVA3D.html)] [[Code]()]

**CLIP-Actor: Text-Driven Recommendation and Stylization for Animating Human Meshes.**<br>
*Kim Youwang, Kim Ji-Yeon, Tae-Hyun Oh.*<br>
ECCV 2022. [[PDF](https://arxiv.org/abs/2208.03550)] [[Project](https://clip-actor.github.io/)] [[Code](https://github.com/postech-ami/CLIP-Actor)]

**AvatarCLIP: Zero-Shot Text-Driven Generation and Animation of 3D Avatars.**<br>
*[Fangzhou Hong](https://hongfz16.github.io/), Mingyuan Zhang, Liang Pan, Zhongang Cai, Lei Yang, Ziwei Liu.*<br>
SIGGRAPH (TOG) 2022. [[PDF](https://arxiv.org/abs/2205.08535)] [[Project](https://hongfz16.github.io/projects/AvatarCLIP.html)] [[Code](https://github.com/hongfz16/AvatarCLIP)] 

**WildAvatar: Web-scale In-the-wild Video Dataset for 3D Avatar Creation.**<br>
*Zihao Huang, ShouKang Hu, Guangcong Wang, Tianqi Liu, Yuhang Zang, Zhiguo Cao, Wei Li, Ziwei Liu.*<br> 
arXiv 2024. [[PDF](https://arxiv.org/abs/2407.02165)] [[Project](https://wildavatar.github.io/)]

**Drivable 3D Gaussian Avatars.**<br>
*Wojciech Zielonka, Timur Bagautdinov, Shunsuke Saito, Michael Zollhöfer, Justus Thies, Javier Romero.*<br> 
arXiv 2023. [[PDF](https://arxiv.org/abs/2311.08581)] [[Project](https://zielon.github.io/d3ga/)]

**MagicAvatar: Multimodal Avatar Generation and Animation.**<br>
*Jianfeng Zhang, Hanshu Yan, Zhongcong Xu, Jiashi Feng, Jun Hao Liew.*<br> 
arXiv 2023. [[PDF](http://arxiv.org/abs/2308.14748)] [[Project](https://magic-avatar.github.io/)]

**DELTA: Learning Disentangled Avatars with Hybrid 3D Representations.**<br>
*[Yao Feng](https://scholar.google.com/citations?user=wNQQhSIAAAAJ&hl=en&oi=ao), [Weiyang Liu](https://wyliu.com/), [Timo Bolkart](https://sites.google.com/site/bolkartt/), [Jinlong Yang](https://is.mpg.de/~jyang), [Marc Pollefeys](https://people.inf.ethz.ch/pomarc/), [Michael J. Black](https://ps.is.mpg.de/person/black).*<br> 
arXiv 2023. [[PDF](https://arxiv.org/abs/2309.06441)] [[Project](https://yfeng95.github.io/delta/)] [[Code](https://github.com/yfeng95/DELTA)]

**AvatarBooth: High-Quality and Customizable 3D Human Avatar Generation.**<br>
*[Yifei Zeng](https://github.com/zeng-yifei), [Yuanxun Lu](https://github.com/YuanxunLu), [Xinya Ji](https://github.com/jixinya), [Yao Yao](https://yoyo000.github.io/), [Hao Zhu](http://zhuhao.cc/), [Xun Cao](https://cite.nju.edu.cn/People/Faculty/20190621/i5054.html).*<br> 
arXiv 2023. [[PDF](https://arxiv.org/abs/2306.09864)] [[Project](https://zeng-yifei.github.io/avatarbooth_page/)] [[Code](https://github.com/zeng-yifei/AvatarBooth)]

## 3D Head Animatable Avatar (from 2D Image Collections)

**PAV: Personalized Head Avatar from Unstructured Video Collection.**<br>
*Akin Caliskan, Berkay Kicanaoglu, Hyeongwoo Kim.*<br>
ECCV 2024. [[PDF](https://arxiv.org/abs/2407.21047)] [[Project](https://akincaliskan3d.github.io/PAV/)] 

**Gaussian Head Avatar: Ultra High-fidelity Head Avatar via Dynamic Gaussians.**<br>
*Yuelang Xu, Benwang Chen, Zhe Li, Hongwen Zhang, Lizhen Wang, Zerong Zheng, Yebin Liu.*<br>
CVPR 2024. [[PDF](https://arxiv.org/abs/2312.03029)] [[Project](https://yuelangx.github.io/gaussianheadavatar/)] 

**HeadArtist: Text-conditioned 3D Head Generation with Self Score Distillation.**<br>
*Hongyu Liu, Xuan Wang, Ziyu Wan, Yujun Shen, Yibing Song, Jing Liao, Qifeng Chen.*<br> 
SIGGRAPH 2024. [[PDF](http://arxiv.org/abs/2312.07539)] [[Project](https://kumapowerliu.github.io/HeadArtist)]

**GAN-Avatar: Controllable Personalized GAN-based Human Head Avatar.**<br>
*Berna Kabadayi, Wojciech Zielonka, Bharat Lal Bhatnagar, Gerard Pons-Moll, Justus Thies.*<br>
3DV 2024. [[PDF](https://arxiv.org/abs/2311.13655)] [[Project](https://ganavatar.github.io/)] 

**NeRFEditor: Differentiable Style Decomposition for Full 3D Scene Editing.**<br>
*[Chunyi Sun](https://chuny1.github.io/NeRFEditor/nerfeditor.html), [Yanbin Liu](https://chuny1.github.io/NeRFEditor/nerfeditor.html), [Junlin Han](https://junlinhan.github.io/), [Stephen Gould](https://chuny1.github.io/NeRFEditor/nerfeditor.html).*<br>
WACV 2024. [[PDF](https://arxiv.org/abs/2212.03848)] [[Project](https://chuny1.github.io/NeRFEditor/nerfeditor.html)]

**AlbedoGAN: Towards Realistic Generative 3D Face Models.**<br>
*[Aashish Rai](https://aashishrai3799.github.io/), [Hiresh Gupta](https://hireshgupta1997.github.io/), Ayush Pandey, Francisco Vicente Carrasco, Shingo Jason Takagi, Amaury Aubel, Daeil Kim, [Aayush Prakash](https://aayushp.github.io/), [Fernando de la Torre](https://www.cs.cmu.edu/~ftorre/).*<br>
WACV 2024. [[PDF](https://arxiv.org/abs/2304.12483)] [[Project](https://aashishrai3799.github.io/Towards-Realistic-Generative-3D-Face-Models/)] [[Code](https://lnkd.in/gVz8Hzn3)]

**AvatarStudio: Text-driven Editing of 3D Dynamic Human Head Avatars.**<br>
*Mohit Mendiratta. Xingang Pan, Mohamed Elgharib, Kartik Teotia, Mallikarjun B R, Ayush Tewari, Vladislav Golyanik, Adam Kortylewski, Christian Theobalt.*<br> 
TOG 2024. [[PDF](http://arxiv.org/abs/2306.00547)] [[Project](https://vcai.mpi-inf.mpg.de/projects/AvatarStudio/)]

**HQ3DAvatar: High Quality Controllable 3D Head Avatar.**<br>
*[Kartik Teotia](https://www.linkedin.com/in/kartik-teotia/?originalSubdomain=de), Mallikarjun B R, Xingang Pan, Hyeongwoo Kim, Pablo Garrido, Mohamed Elgharib, Christian Theobalt.*<br>
TOG 20234. [[PDF](https://vcai.mpi-inf.mpg.de/projects/HQ3DAvatar/)] [[Project](https://vcai.mpi-inf.mpg.de/projects/HQ3DAvatar/)] [[Code]()]

**CLIPFace: Text-guided Editing of Textured 3D Morphable Models.**<br>
*[Shivangi Aneja](https://niessnerlab.org/members/shivangi_aneja/profile.html), [Justus Thies](https://is.mpg.de/~jthies), [Angela Dai](https://www.professoren.tum.de/en/dai-angela), [Matthias Nießner](https://niessnerlab.org/members/matthias_niessner/profile.html).*<br>
SIGGRAPH 2023. [[PDF](https://arxiv.org/abs/2212.01406)] [[Project](https://shivangi-aneja.github.io/projects/clipface/)] [[Code](https://github.com/shivangi-aneja/ClipFace)]

**DreamFace: Progressive Generation of Animatable 3D Faces under Text Guidance.**<br>
*Longwen Zhang, Qiwei Qiu, Hongyang Lin, Qixuan Zhang, Cheng Shi, Wei Yang, Ye Shi, Sibei Yang, Lan Xu, Jingyi Yu.*<br>
SIGGRAPH 2023. [[PDF](https://arxiv.org/abs/2304.03117)] [[Project](https://sites.google.com/view/dreamface)] [[Demo](https://hyperhuman.deemos.com/)] [[HuggingFace](https://huggingface.co/spaces/DEEMOSTECH/ChatAvatar)]

**StyleAvatar: Real-time Photo-realistic Neural Portrait Avatar from a Single Video.**<br>
*Lizhen Wang, Xiaochen Zhao, Jingxiang Sun, Yuxiang Zhang, Hongwen Zhang, Tao Yu✝, Yebin Liu.*<br>
SIGGRAPH 2023. [[PDF](https://arxiv.org/abs/2305.00942)]

**LatentAvatar: Learning Latent Expression Code for Expressive Neural Head Avatar.**<br>
*Yuelang Xu, Hongwen Zhang, Lizhen Wang, Xiaochen Zhao, Han Huang, Guojun Qi, Yebin Liu.*<br>
SIGGRAPH 2023. [[PDF](https://arxiv.org/abs/2305.01190)], [[Project](https://www.liuyebin.com/latentavatar/)],[[Code](https://github.com/YuelangX/LatentAvatar)]

**NeRSemble: Multi-view Radiance Field Reconstruction of Human Heads.**<br>
*[Tobias Kirschstein](https://tobias-kirschstein.github.io/), [Shenhan Qian](https://shenhanqian.com/), [Simon Giebenhain](https://simongiebenhain.github.io/), Tim Walter, Matthias Nießner.*<br> 
SIGGRAPH 2023. [[PDF](http://arxiv.org/abs/2305.03027)] [[Project](https://tobias-kirschstein.github.io/nersemble/)] [[Video](https://youtu.be/a-OAWqBzldU)]

**GOHA: Generalizable One-shot Neural Head Avatar.**<br>
*[Xueting Li](https://sunshineatnoon.github.io/), [Shalini De Mello](https://research.nvidia.com/person/shalini-de-mello), [Sifei Liu](https://www.sifeiliu.net/), [Koki Nagano](https://luminohope.org/), [Umar Iqbal](https://research.nvidia.com/person/umar-iqbal), [Jan Kautz](https://jankautz.com/).*<br> 
NeurIPS 2023. [[PDF](https://arxiv.org/abs/2306.08768)] [[Project](https://research.nvidia.com/labs/lpr/one-shot-avatar)]

**GANHead: Towards Generative Animatable Neural Head Avatars.**<br>
*[Sijing Wu]((https://wsj-sjtu.github.io), [Yichao Yan](https://daodaofr.github.io/), Yunhao Li, Yuhao Cheng, Wenhan Zhu, Ke Gao, Xiaobo Li, [Guangtao Zhai](https://scholar.google.com/citations?user=E6zbSYgAAAAJ&hl=en&oi=ao).*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/2304.03950)] [[Project](https://wsj-sjtu.github.io/GANHead/)]

**FitMe: Deep Photorealistic 3D Morphable Model Avatars.**<br>
*[Alexandros Lattas](https://alexlattas.com/), [Stylianos Moschoglou](https://moschoglou.com/), [Stylianos Ploumpis](https://www.ploumpis.com/), [Baris Gecer](https://barisgecer.github.io/), [Jiankang Deng](https://jiankangdeng.github.io/), [Stefanos Zafeiriou](https://www.imperial.ac.uk/people/s.zafeiriou).*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/2305.09641)] [[Project](https://alexlattas.com/fitme)]

**Next3D: Generative Neural Texture Rasterization for 3D-Aware Head Avatars.**<br>
*[Jingxiang Sun](https://mrtornado24.github.io/), [Xuan Wang](https://xuanwangvc.github.io/), [Lizhen Wang](https://lizhenwangt.github.io/), [Xiaoyu Li](https://xiaoyu258.github.io/), [Yong Zhang](https://yzhang2016.github.io/yongnorriszhang.github.io/), [Hongwen Zhang](https://hongwenzhang.github.io/), [Yebin Liu](http://www.liuyebin.com/).*<br>
CVPR 2023 (Highlight). [[PDF](https://arxiv.org/pdf/2211.11208.pdf)] [[Project](https://mrtornado24.github.io/Next3D/)] [[Code](https://github.com/MrTornado24/Next3D)]

**BlendFields: Few-Shot Example-Driven Facial Modeling.**<br>
*Kacper Kania, Stephan J. Garbin, Andrea Tagliasacchi, Virginia Estellers, Kwang Moo Yi, Julien Valentin, Tomasz Trzciński, Marek Kowalski.*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/2305.07514)] [[Project](https://blendfields.github.io/)]

**OTAvatar: One-shot Talking Face Avatar with Controllable Tri-plane Rendering.**<br>
*Zhiyuan Ma, Xiangyu Zhu, Guojun Qi, Zhen Lei, Lei Zhang.*<br>
CVPR 2023. [[PDF](https://arxiv.org/pdf/2303.14662)] [[Code](https://github.com/theEricMa/OTAvatar)] [[Demo](https://youtu.be/qpIoMYFr7Aw)]

**PanoHead: Geometry-Aware 3D Full-Head Synthesis in 360∘.**<br>
*Sizhe An, Hongyi Xu, Yichun Shi, Guoxian Song, Umit Ogras, Linjie Luo.*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/2303.13071) [[Project](https://sizhean.github.io/panohead)]

**Efficient Meshy Neural Fields for Animatable Human Avatars.**<br>
*Xiaoke Huang, Yiji Cheng, Yansong Tang, Xiu Li, Jie Zhou, Jiwen Lu .*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/2303.12965)] [[Project](https://xk-huang.github.io/ema/)]

**Rodin: A Generative Model for Sculpting 3D Digital Avatars Using Diffusion.**<br>
*Tengfei Wang, Bo Zhang, Ting Zhang, Shuyang Gu, Jianmin Bao, Tadas Baltrusaitis, Jingjing Shen, Dong Chen, Fang Wen, Qifeng Chen, Baining Guo.*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/2212.06135)] [[Project](https://3d-avatar-diffusion.microsoft.com/)]

**OmniAvatar: Geometry-Guided Controllable 3D Head Synthesis.**<br>
*Hongyi Xu, Guoxian Song, Zihang Jiang, Jianfeng Zhang, Yichun Shi, Jing Liu, Wanchun Ma, Jiashi Feng, Linjie Luo.*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/2303.15539)]

**PointAvatar: Deformable Point-based Head Avatars from Videos.**<br>
*Yufeng Zheng, Wang Yifan, Gordon Wetzstein, Michael J. Black, Otmar Hilliges.*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/2212.08377)] [[Project](https://zhengyuf.github.io/PointAvatar/)] [[Code](https://github.com/zhengyuf/pointavatar)]

**MEGANE: Morphable Eyeglass and Avatar Network.**<br>
*Junxuan Li, Shunsuke Saito, Tomas Simon, Stephen Lombardi, Hongdong Li, Jason Saragih.*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/2302.04868)] [[Project](https://junxuan-li.github.io/megane/)] 

**Reconstructing Personalized Semantic Facial NeRF Models From Monocular Video.**<br>
*Xuan Gao, ChengLai Zhong, Jun Xiang, Yang Hong, Yudong Guo, Juyong Zhang.*<br>
TOG 2022. [[PDF](https://arxiv.org/abs/2210.06108)] [[Project](https://ustc3dv.github.io/NeRFBlendShape/)] [[Code](https://github.com/USTC3DV/NeRFBlendShape-code)]


## (Clothed) Human Motion Generation

**TLControl: Trajectory and Language Control for Human Motion Synthesis.**<br>
*Weilin Wan, Zhiyang Dou, Taku Komura, Wenping Wang, Dinesh Jayaraman, Lingjie Liu.*<br> 
ECCV 2024. [[PDF](http://arxiv.org/abs/2311.17135)] [[Project](https://tlcontrol.weilinwl.com/)]

**CoMo: Controllable Motion Generation through Language Guided Pose Code Editing.**<br>
*Yiming Huang, Weilin Wan, Yue Yang, Chris Callison-Burch, Mark Yatskar, Lingjie Liu.*<br> 
ECCV 2024. [[PDF](https://arxiv.org/abs/2403.13900)] [[Project](https://yh2371.github.io/como/)]

**Total Selfie: Generating Full-Body Selfies.**<br>
*Bowei Chen, Brian Curless, Ira Kemelmacher-Shlizerman, Steve Seitz.*<br> 
CVPR 2024 (Highlight). [[PDF](http://arxiv.org/abs/2308.14740)] [[Project](https://homes.cs.washington.edu/~boweiche/project_page/totalselfie/)]

**OmniControl: Control Any Joint at Any Time for Human Motion Generation.**<br>
*Yiming Xie, Varun Jampani, Lei Zhong, Deqing Sun, Huaizu Jiang.*<br> 
ICLR 2024. [[PDF](http://arxiv.org/abs/2310.08580)] [[Project](https://neu-vi.github.io/omnicontrol/)]

**MotionDiffuse: Text-Driven Human Motion Generation with Diffusion Model.**<br>
*[Mingyuan Zhang](https://mingyuan-zhang.github.io/), [Zhongang Cai](https://caizhongang.github.io/), [Liang Pan](https://github.com/paul007pl), [Fangzhou Hong](https://hongfz16.github.io/), [Xinying Guo](https://gxyes.github.io/), [Lei Yang](https://yanglei.me/), [Ziwei Liu](https://liuziwei7.github.io/).*<br>
TPAMI 2024. [[PDF](https://arxiv.org/abs/2208.15001)] [[Project](https://mingyuan-zhang.github.io/projects/MotionDiffuse.html)] [[Code](https://github.com/mingyuan-zhang/MotionDiffuse)]

**TMR: Text-to-Motion Retrieval Using Contrastive 3D Human Motion Synthesis.**<br>
*Mathis Petrovich, Michael J. Black and Gül Varol.*<br>
ICCV 2023. [[PDF](https://arxiv.org/abs/2305.00976)] [[Project](https://mathis.petrovich.fr/tmr/index.html)] [[Code](https://github.com/Mathux/TMR)]

**SINC: Spatial Composition of 3D Human Motions for Simultaneous Action Generation.**<br>
*Nikos Athanasiou, Mathis Petrovich, Michael J. Black, Gül Varol.*<br>
ICCV 2023. [[PDF](https://arxiv.org/abs/2304.10417)] [[Project](https://sinc.is.tue.mpg.de/)] [[Code](https://github.com/athn-nik/sinc)]

**HumanRF: High-Fidelity Neural Radiance Fields for Humans in Motion.**<br>
*[Mustafa Işık](https://www.mustafaisik.net/), Martin Rünz, Markos Georgopoulos, Taras Khakhulin, Jonathan Starck, Lourdes Agapito, Matthias Nießner.*<br> 
SIGGRAPH 2023. [[PDF](http://arxiv.org/abs/2305.06356)] [[Project](http://www.synthesiaresearch.github.io/humanrf)] [[Code](https://github.com/synthesiaresearch/humanrf)] [[Data](http://www.actors-hq.com/)]

**GestureDiffuCLIP: Gesture Diffusion Model with CLIP Latents.**<br>
*[Tenglong Ao](https://aubrey-ao.github.io/), Zeyi Zhang, [Libin Liu](https://libliu.info/).*<br>
SIGGRAPH 2023 (Journal Track). [[PDF](https://arxiv.org/abs/2303.14613)] [[Project](https://pku-mocca.github.io/GestureDiffuCLIP-Page/)] [[Code]()]

**MDM: Human Motion Diffusion Model.**<br>
*Guy Tevet, Sigal Raab, Brian Gordon, Yonatan Shafir, Daniel Cohen-Or, Amit H. Bermano.*<br>
ICLR 2023. [[PDF](https://arxiv.org/abs/2209.14916)] [[Project](https://guytevet.github.io/mdm-page/)] [[Code](https://github.com/GuyTevet/motion-diffusion-model)]

**MoFusion: A Framework for Denoising-Diffusion-based Motion Synthesis.**<br>
*[Rishabh Dabral](https://www.cse.iitb.ac.in/~rdabral/), [Muhammad Hamza Mughal](https://m-hamza-mughal.github.io/), [Vladislav Golyanik](https://people.mpi-inf.mpg.de/~golyanik/), [Christian Theobalt](https://people.mpi-inf.mpg.de/~theobalt/).*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/2212.04495)] [[Project](https://vcai.mpi-inf.mpg.de/projects/MoFusion/)] 

**MotionCLIP: Exposing Human Motion Generation to CLIP Space.**<br>
*Guy Tevet, Brian Gordon, Amir Hertz, Amit H. Bermano, Daniel Cohen-Or.*<br>
ECCV 2022. [[PDF](https://arxiv.org/abs/2203.08063)] [[Project](https://guytevet.github.io/motionclip-page/)] [[Code](https://github.com/GuyTevet/MotionCLIP)]

**TEMOS: Generating diverse human motions from textual descriptions.**<br>
*[Mathis Petrovich](https://mathis.petrovich.fr/), Michael J. Black, Gül Varol.*<br>
ECCV 2022. [[PDF](https://arxiv.org/abs/2204.14109)] [[Project](https://mathis.petrovich.fr/temos/)] [[Code](https://github.com/Mathux/TEMOS)]

**TEACH: Temporal Action Composition for 3D Human.**<br>
*Nikos Athanasiou, Mathis Petrovich, Michael J. Black, Gül Varol.*<br>
3DV 2022. [[PDF](https://arxiv.org/abs/2209.04066)] [[Project](https://teach.is.tue.mpg.de/)] [[Code](https://github.com/athn-nik/teach)]

## Clothed Human Digitalization

[Project Splinter](https://project-splinter.github.io/): Human Digitalization with Implicit Representation.

**PuzzleAvatar: Assembling 3D Avatars from Personal Albums.**<br>
*Yuliang Xiu, Yufei Ye, Zhen Liu, Dimitrios Tzionas, Michael J. Black.*<br>
SIGGRAPH Asia (TOG) 2024. [[PDF](https://arxiv.org/abs/2405.14869)]

**iHuman: Instant Animatable Digital Humans From Monocular Videos.**<br> 
*Pramish Paudel, Anubhav Khanal, Ajad Chhatkuli, Danda Pani Paudel, Jyoti Tandukar.*<br> 
ECCV 2024. [[PDF](https://arxiv.org/abs/2407.11174)]

**HiLo: Detailed and Robust 3D Clothed Human Reconstruction with High-and Low-Frequency Information of Parametric Models.**<br>
*Yifan Yang, Dong Liu, Shuhai Zhang, Zeshuai Deng, Zixiong Huang, Mingkui Tan.*<br> 
CVPR 2024. [[PDF](https://arxiv.org/abs/2404.04876)] [[Github](https://github.com/YifYang993/HiLo)]

**IntrinsicAvatar: Physically Based Inverse Rendering of Dynamic Humans from Monocular Videos Via Explicit Ray Tracing.**<br>
*Shaofei Wang, Božidar Antić, Andreas Geiger, Siyu Tang.*<br> 
CVPR 2024. [[PDF](http://arxiv.org/abs/2312.05210)] [[Project](https://neuralbodies.github.io/IntrinsicAvatar)]

**GaussianAvatar: Towards Realistic Human Avatar Modeling from A Single Video Via Animatable 3D Gaussians.**<br>
*Liangxiao Hu, Hongwen Zhang, Yuxiang Zhang, Boyao Zhou, Boning Liu, Shengping Zhang, Liqiang Nie.*<br> 
CVPR 2024. [[PDF](http://arxiv.org/abs/2312.02134)] [[Project](https://huliangxiao.github.io/GaussianAvatar)] [[Github](https://github.com/aipixel/GaussianAvatar)]

**SiTH: Single-view Textured Human Reconstruction with Image-Conditioned Diffusion.**<br>
*[Hsuan-I Ho](https://azuxmioy.github.io/), [Jie Song](https://ait.ethz.ch/people/song), [Otmar Hilliges](https://ait.ethz.ch/people/hilliges).*<br> 
CVPR 2024. [[PDF](https://arxiv.org/abs/2311.15855)] [[Project](https://sith-diffusion.github.io/)]

**Recovering 3D Human Mesh from Monocular Images: A Survey.**<br>
*[Yating Tian](https://github.com/tinatiansjz), [Hongwen Zhang](https://github.com/HongwenZhang), [Yebin Liu](https://www.liuyebin.com/), [Limin Wang](https://wanglimin.github.io/).*<br>
TPAMI 2023. [[PDF](https://arxiv.org/abs/2203.01923)] [[Project](https://github.com/tinatiansjz/hmr-survey)] [[Dataset](https://github.com/tinatiansjz/hmr-survey#datasets)] [[Benchmarks](https://github.com/tinatiansjz/hmr-survey#benchmarks)]

**Mirror-Aware Neural Humans.**<br>
*Daniel Ajisafe, James Tang, Shih-Yang Su, Bastian Wandt, Helge Rhodin.*<br> 
3DV 2024. [[PDF](https://arxiv.org/abs/2311.09221)] [[Project](https://danielajisafe.github.io/mirror-aware-neural-humans/)]

**TeCH: Text-guided Reconstruction of Lifelike Clothed Humans.**<br>
*[Yangyi Huang](https://huangyangyi.github.io/), [Hongwei Yi](https://xyyhw.top/), [Yuliang Xiu](https://xiuyuliang.cn/), [Tingting Liao](https://github.com/tingtingliao), [Jiaxiang Tang](https://me.kiui.moe/), [Deng Cai](http://www.cad.zju.edu.cn/home/dengcai/), [Justus Thies](http://justusthies.github.io/).*<br>
3DV 2024. [[PDF](https://arxiv.org/abs/2308.08545)] [[Project](https://huangyangyi.github.io/TeCH/)]

**Single-Image 3D Human Digitization with Shape-Guided Diffusion.**<br>
*Badour AlBahar, Shunsuke Saito, Hung-Yu Tseng, Changil Kim, Johannes Kopf, Jia-Bin Huang.*<br>
SIGGRAPH Asia 2023. [[PDF](https://arxiv.org/abs/2208.15001)] [[Project](https://human-sgd.github.io/)]

**Global-correlated 3D-decoupling Transformer for Clothed Avatar Reconstruction.**<br>
*Zechuan Zhang, Li Sun, Zongxin Yang, Ling Chen, Yi Yang.*<br>
NeurIPS 2023. [[PDF](https://arxiv.org/abs/2309.13524)]

**ISP: Multi-Layered Garment Draping with Implicit Sewing Patterns.**<br>
*Ren Li, Benoît Guillard, Pascal Fua.*<br> 
NeurIPS 2023. [[PDF](http://arxiv.org/abs/2305.14100)]

**NCHO: Unsupervised Learning for Neural 3D Composition of Humans and Objects.**<br>
*[Taeksoo Kim](https://taeksuu.github.io/), [Shunsuke Saito](https://shunsukesaito.github.io/), [Hanbyul Joo](https://jhugestar.github.io/).*<br>
ICCV 2023. [[PDF](https://arxiv.org/abs/2305.14345)] [[Project](https://taeksuu.github.io/ncho/)]

**Chupa: Carving 3D Clothed Humans from Skinned Shape Priors using 2D Diffusion Probabilistic Models.**<br>
*[Byungjun Kim](https://bjkim95.github.io/), Patrick Kwon, Kwangho Lee, Myunggi Lee, Sookwan Han, Daesik Kim, Hanbyul Joo.*<br>
ICCV 2023 (Oral). [[PDF](https://arxiv.org/abs/2305.11870)] [[Project](https://snuvclab.github.io/chupa)]

**SHERF: Generalizable Human NeRF from a Single Image.**<br>
*[Shoukang Hu](https://skhu101.github.io/), [Fangzhou Hong](https://hongfz16.github.io/), [Liang Pan](https://scholar.google.com/citations?user=lSDISOcAAAAJ), Haiyi Mei, [Lei Yang](https://scholar.google.com.hk/citations?user=jZH2IPYAAAAJ&hl=en), [Ziwei Liu](https://liuziwei7.github.io/).*<br>
ICCV 2023. [[PDF](https://arxiv.org/abs/2303.12791)] [[Project](https://skhu101.github.io/SHERF/)] [[Code](https://github.com/skhu101/SHERF)]

**SynBody: Synthetic Dataset with Layered Human Models for 3D Human Perception and Modeling.**<br>
*Zhitao Yang, Zhongang Cai, Haiyi Mei, Shuai Liu, Zhaoxi Chen, Weiye Xiao, Yukun Wei, Zhongfei Qing, Chen Wei, Bo Dai, Wayne Wu, Chen Qian, Dahua Lin, Ziwei Liu, Lei Yang.*<br>
ICCV 2023. [[PDF](https://arxiv.org/abs/2303.17368)] [[Project](https://maoxie.github.io/SynBody/)]

**Cyclic Test-Time Adaptation on Monocular Video for 3D Human Mesh Reconstruction.**<br>
*Hyeongjin Nam, Daniel Sungho Jung, Yeonguk Oh, Kyoung Mu Lee.*<br>
ICCV 2023. [[PDF](https://arxiv.org/abs/2308.06554)]

**HumanRF: High-Fidelity Neural Radiance Fields for Humans in Motion.**<br>
*[Mustafa Işık](https://www.mustafaisik.net/), Martin Rünz, Markos Georgopoulos, Taras Khakhulin, Jonathan Starck, Lourdes Agapito, Matthias Nießner.*<br> 
SIGGRAPH 2023. [[PDF](http://arxiv.org/abs/2305.06356)] [[Project](http://www.synthesiaresearch.github.io/humanrf)] [[Code](https://github.com/synthesiaresearch/humanrf)] [[Data](http://www.actors-hq.com/)]

**AvatarReX: Real-time Expressive Full-body Avatars.**<br>
*Zerong Zheng, Xiaochen Zhao, Hongwen Zhang, Boning Liu, Yebin Liu.*<br>
SIGGRAPH 2023 [[PDF](https://arxiv.org/abs/2305.04789)] [[Project](https://liuyebin.com/AvatarRex/)]

**PoseVocab: Learning Joint-structured Pose Embeddings for Human Avatar Modeling.**<br>
*Zhe Li, Zerong Zheng, Yuxiao Liu, Boyao Zhou, Yebin Liu.*<br>
SIGGRAPH 2023 [[PDF](https://arxiv.org/abs/2304.13006)] [[Project](https://lizhe00.github.io/projects/posevocab)]

**High-Fidelity Clothed Avatar Reconstruction from a Single Image.**<br>
*Tingting Liao, Xiaomei Zhang, Yuliang Xiu, Hongwei Yi, Xudong Liu, Guo-Jun Qi, Yong Zhang, Xuan Wang, Xiangyu Zhu, Zhen Lei.*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/2304.03903)] [[Code](https://github.com/TingtingLiao/CAR)]

**SeSDF: Self-evolved Signed Distance Field for Implicit 3D Clothed Human Reconstruction.**<br>
*[Yukang Cao](https://yukangcao.github.io/), [Kai Han](https://www.kaihan.org/), [Kenneth Kwan-Yee K. Wong](https://i.cs.hku.hk/~kykwong/).*<br> 
CVPR 2023. [[PDF](https://arxiv.org/abs/2304.00359)] [[Project](https://yukangcao.github.io/SeSDF/)] [[Code](https://yukangcao.github.io/)]

**Structured 3D Features for Reconstructing Relightable and Animatable Avatars.**<br>
*Enric Corona, Mihai Zanfir, Thiemo Alldieck, Eduard Gabriel Bazavan, Andrei Zanfir, Cristian Sminchisescu.*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/2212.06820)] [[Project](https://enriccorona.github.io/s3f/)]

**Reconstructing Animatable Categories from Videos.**<br>
*[Gengshan Yang](https://gengshan-y.github.io/), [Chaoyang Wang](https://mightychaos.github.io/), [N Dinesh Reddy](https://dineshreddy91.github.io/), [Deva Ramanan](http://www.cs.cmu.edu/~deva/).*<br> 
CVPR 2023. [[PDF](http://arxiv.org/abs/2305.06351)] [[Project](https://gengshan-y.github.io/rac-www/)] [[Code](https://github.com/gengshan-y/rac)]

**Representing Volumetric Videos as Dynamic MLP Maps.**<br>
*Sida Peng, Yunzhi Yan, Qing Shuai, Hujun Bao, Xiaowei Zhou.*<br>
CVPR 2023. [[PDF](https://arxiv.org/pdf/2304.06717.pdf)] [[Project](https://zju3dv.github.io/mlp_maps)] [[Code](https://github.com/zju3dv/mlp_maps)]

**Learning Neural Volumetric Representations of Dynamic Humans in Minutes.**<br>
*[Chen Geng](https://chen-geng.com/), Sida Peng, Zhen Xu, Hujun Bao, Xiaowei Zhou.*<br>
CVPR 2023. [[PDF](https://chen-geng.com/files/instant_nvr.pdf)] [[Project](https://zju3dv.github.io/instant_nvr/)] [[Code](https://github.com/zju3dv/instant-nvr/)]

**CloSET: Modeling Clothed Humans on Continuous Surface with Explicit Template Decomposition.**<br>
*[Hongwen Zhang](https://hongwenzhang.github.io/), [Siyou Lin](https://jsnln.github.io/), [Ruizhi Shao](https://dsaurus.github.io/saurus), [Yuxiang Zhang](https://zhangyux15.github.io/), [Zerong Zheng](https://zhengzerong.github.io/), [Han Huang](http://www.liuyebin.com/closet/#), [Yandong Guo](http://www.liuyebin.com/closet/#), [Yebin Liu](https://liuyebin.com/).*<br>
CVPR 2023. [[PDF](http://www.liuyebin.com/closet/assets/CloSET_CVPR2023.pdf)] [[Project](http://www.liuyebin.com/closet/)]

**MonoHuman: Animatable Human Neural Field from Monocular Video.**<br>
*Zhengming Yu, Wei Cheng, Xian Liu, Wayne Wu, Kwan-Yee Lin.*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/2304.02001)] [[Project](https://yzmblog.github.io/projects/MonoHuman/)]

**FlexNeRF: Photorealistic Free-viewpoint Rendering of Moving Humans from Sparse Views.**<br>
*Vinoj Jayasundara, Amit Agrawal, Nicolas Heron, Abhinav Shrivastava, Larry S. Davis.*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/2303.14368)]

**High-fidelity 3D Human Digitization from Single 2K Resolution Images.**<br>
*Sang-Hun Han, Min-Gyu Park, Ju Hong Yoon, Ju-Mi Kang, Young-Jae Park, Hae-Gon Jeon.*<br>
CVPR 2023 (Highlight). [[PDF](https://arxiv.org/abs/2303.15108)] [[Code](https://github.com/SangHunHan92/2K2K)]

**Learning Neural Volumetric Representations of Dynamic Humans in Minutes.**<br>
*Chen Geng, Sida Peng, Zhen Xu, Hujun Bao, Xiaowei Zhou.*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/2302.12237)] [[Project](https://zju3dv.github.io/instant_nvr/)] 

**Vid2Avatar: 3D Avatar Reconstruction from Videos in the Wild via Self-supervised Scene Decomposition.**<br>
*Chen Guo, Tianjian Jiang, Xu Chen, Jie Song, Otmar Hilliges.*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/2302.11566)] [[Project](https://moygcc.github.io/vid2avatar/)]

**Rodin: A Generative Model for Sculpting 3D Digital Avatars Using Diffusion.**<br>
*Tengfei Wang, Bo Zhang, Ting Zhang, Shuyang Gu, Jianmin Bao, Tadas Baltrusaitis, Jingjing Shen, Dong Chen, Fang Wen, Qifeng Chen, Baining Guo.*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/2212.06135)] [[Project](https://3d-avatar-diffusion.microsoft.com/)]

**ECON: Explicit Clothed humans Obtained from Normals.**<br>
*Yuliang Xiu, Jinlong Yang, Xu Cao, Dimitrios Tzionas, Michael J. Black.*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/)] [[Project](https://xiuyuliang.cn/econ)] [[Code](https://github.com/YuliangXiu/ECON)]

**X-Avatar: Expressive Human Avatars.**<br>
*[Kaiyue Shen](https://skype-line.github.io/), Chen Guo, Manuel Kaufmann, Juan Jose Zarate, Julien Valentin, Jie Song, Otmar Hilliges.*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/2303.04805)] [[Project](https://skype-line.github.io/projects/X-Avatar/)] [[Code](https://github.com/Skype-line/X-Avatar)]

**InstantAvatar: Learning Avatars from Monocular Video in 60 Seconds.**<br>
*Tianjian Jiang, Xu Chen, Jie Song, Otmar Hilliges.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2212.10550)] [[Project](https://tijiang13.github.io/InstantAvatar/)] [[Code](https://github.com/tijiang13/InstantAvatar)]

**Learning Visibility Field for Detailed 3D Human Reconstruction and Relighting.**<br>
*Ruichen Zheng, Peng Li, Haoqian Wang, Tao Yu.*<br> 
CVPR 2023. [[PDF](http://arxiv.org/abs/2304.11900)]

**HumanGen: Generating Human Radiance Fields with Explicit Priors.**<br>
*Suyi Jiang, Haoran Jiang, Ziyu Wang, Haimin Luo, Wenzheng Chen, Lan Xu.*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/2212.05321)]

**SHARP: Shape-Aware Reconstruction of People In Loose Clothing.**<br>
*Sai Sagar Jinka, Rohan Chacko, Astitva Srivastava, Avinash Sharma, P.J. Narayanan.*<br>
IJCV 2023. [[PDF](https://arxiv.org/abs/2106.04778)]

**Geometry-aware Two-scale PIFu Representation for Human Reconstruction.**<br>
*Zheng Dong, Ke Xu, Ziheng Duan, Hujun Bao, Weiwei Xu, Rynson W.H. Lau.*<br>
NeurIPS 2022. [[PDF](https://arxiv.org/abs/2112.02082)]

**TotalSelfScan: Learning Full-body Avatars from Self-Portrait Videos of Faces, Hands, and Bodies.**<br>
*[Junting Dong](https://jtdong.com/), [Qi Fang](https://raypine.github.io/), Yudong Guo, Sida Peng, Qing Shuai, Hujun Bao, Xiaowei Zhou.*<br>
NeurIPS 2022. [[PDF](https://openreview.net/pdf?id=lgj33-O1Ely)] [[Project](https://zju3dv.github.io/TotalSelfScan/)] [[Data](http://jtdong.com/)]

**FOF: Learning Fourier Occupancy Field for Monocular Real-time Human Reconstruction.**<br>
*[Qiao Feng](https://fengq1a0.github.io/), [Yebin Liu](http://www.liuyebin.com/), [Yu-Kun Lai](https://users.cs.cf.ac.uk/Yukun.Lai/), [Jingyu Yang](http://seea.tju.edu.cn/info/1015/1608.htm), [Kun Li](http://cic.tju.edu.cn/faculty/likun/).*<br>
NeurIPS 2022. [[PDF](https://arxiv.org/abs/2206.02194)] [[Project](https://cic.tju.edu.cn/faculty/likun/projects/FOF/index.html)] [[Code](https://github.com/fengq1a0/FOF)]

Dual-Space NeRF: Learning Animatable Avatars and Scene Lighting in Separate Spaces
Yihao Zhi, Shenhan Qian, Xinhao Yan, Shenghua Gao
3DV 2022. [[PDF](https://arxiv.org/abs/2208.14851)] [[Code](https://github.com/zyhbili/Dual-Space-NeRF)]

**Neural Point-based Shape Modeling of Humans in Challenging Clothing.**<br>
*Qianli Ma, Jinlong Yang, Michael J. Black, Siyu Tang.*<br>
3DV 2022. [[PDF](https://arxiv.org/abs/2209.06814)]

**HVTR: Hybrid Volumetric-Textural Rendering for Human Avatars.**<br>
*Tao Hu, Tao Yu, Zerong Zheng, He Zhang, Yebin Liu, Matthias Zwicker.*<br>
3DV 2022. [[PDF](https://arxiv.org/abs/2112.10203)] [[Project](https://www.cs.umd.edu/~taohu/hvtr/)]

**Human Performance Modeling and Rendering via Neural Animated Mesh.**<br>
*[Fuqiang Zhao](https://zhaofuq.github.io/), Yuheng Jiang, Kaixin Yao, Jiakai Zhang, Liao Wang, Haizhao Dai, Yuhui Zhong, Yingliang Zhang, Minye Wu, Lan Xu, Jingyi Yu.*<br>
SIGGRAPH Asia 2022. [[PDF](https://arxiv.org/abs/2209.08468)] [[Project](https://zhaofuq.github.io/NeuralAM/)]

**FloRen: Real-time High-quality Human Performance Rendering via Appearance Flow Using Sparse RGB Cameras.**<br>
*Ruizhi Shao, Liliang Chen, Zerong Zheng, Hongwen Zhang, Yuxiang Zhang, Han Huang, Yandong Guo, Yebin Liu.*<br>
SIGGRAPH Asia 2022. [[PDF](https://dl.acm.org/doi/abs/10.1145/3550469.3555409)] 

**Occupancy Planes for Single-view RGB-D Human Reconstruction.**<br>
*Xiaoming Zhao, Yuan-Ting Hu, Zhongzheng Ren, Alexander G. Schwing.*<br>
AAAI 2023. [[PDF](https://arxiv.org/abs/2208.02817)] [[Code](https://github.com/Xiaoming-Zhao/oplanes)]

**HuMMan: Multi-Modal 4D Human Dataset for Versatile Sensing and Modeling.**<br>
*[Zhongang Cai](https://caizhongang.github.io/), [Daxuan Ren](https://kimren227.github.io/), [Ailing Zeng](https://ailingzeng.site/), [Zhengyu Lin](https://www.linkedin.com/in/zhengyu-lin-a908aba8/), [Tao Yu](https://ytrock.com/), [Wenjia Wang](https://scholar.google.com/citations?user=cVWmlYQAAAAJ&hl), Xiangyu Fan, Yang Gao, Yifan Yu, Liang Pan, Fangzhou Hong, Mingyuan Zhang, Chen Change Loy, Lei Yang, Ziwei Liu.*<br>
ECCV 2022 (Oral). [[PDF](https://arxiv.org/abs/2204.13686)] [[Project](https://caizhongang.github.io/projects/HuMMan/)]

**Unsupervised Learning of Efficient Geometry-Aware Neural Articulated Representations.**<br>
*Atsuhiro Noguchi, Xiao Sun, Stephen Lin, Tatsuya Harada.*<br>
ECCV 2022. [[PDF](https://arxiv.org/abs/2204.08839)] [[Project](https://nogu-atsu.github.io/ENARF-GAN/)] [[Code](https://github.com/nogu-atsu/ENARF-GAN)]

**NeuMan: Neural Human Radiance Field from a Single Video.**<br>
*Wei Jiang, Kwang Moo Yi, Golnoosh Samei, Oncel Tuzel, Anurag Ranjan.*<br>
ECCV 2022. [[PDF](https://arxiv.org/abs/2203.10157)] [[Code](https://github.com/apple/ml-neuman)]

**ARAH: Animatable Volume Rendering of Articulated Human SDFs.**<br>
*[Shaofei Wang](https://taconite.github.io/), [Katja Schwarz](https://katjaschwarz.github.io/), [Andreas Geiger](http://www.cvlibs.net/), [Siyu Tang](https://vlg.inf.ethz.ch/team/Prof-Dr-Siyu-Tang.html).*<br>
ECCV 2022. [[PDF](https://arxiv.org/abs/2210.10036)] [[Project](https://neuralbodies.github.io/arah/)] [[Code](https://github.com/taconite/arah-release)]

**DiffuStereo: High Quality Human Reconstruction via Diffusion-based Stereo Using Sparse Cameras.**<br>
*Ruizhi Shao, Zerong Zheng, Hongwen Zhang, Jingxiang Sun, Yebin Liu.*<br>
ECCV (Oral) 2022. [[PDF](https://arxiv.org/abs/2207.08000)] [[Code](https://github.com/DSaurus/DiffuStereo)]

**LoRD: Local 4D Implicit Representation for High-Fidelity Dynamic Human Modeling.**<br>
*Boyan Jiang, Xinlin Ren, Mingsong Dou, Xiangyang Xue, Yanwei Fu, Yinda Zhang.*<br>
ECCV 2022. [[PDF](https://arxiv.org/abs/2208.08622)] [[Code](https://boyanjiang.github.io/LoRD/)]

**Neural Capture of Animatable 3D Human from Monocular Video.**<br>
*Gusi Te, Xiu Li, Xiao Li, Jinglu Wang, Wei Hu, Yan Lu.*<br>
ECCV 2022. [[PDF](https://arxiv.org/abs/2208.08728)]

**The One Where They Reconstructed 3D Humans and Environments in TV Shows.**<br>
*Georgios Pavlakos, Ethan Weber, Matthew Tancik, Angjoo Kanazawa.*<br>
ECCV 2022. [[PDF](https://arxiv.org/abs/2207.14279)] [[Project](http://ethanweber.me/sitcoms3D/)]

**UNIF: United Neural Implicit Functions for Clothed Human Reconstruction and Animation.**<br>
*Shenhan Qian, Jiale Xu, Ziwei Liu, Liqian Ma, Shenghua Gao.*<br>
ECCV 2022. [[PDF](https://arxiv.org/abs/2207.09835)]

**3D Clothed Human Reconstruction in the Wild.**<br>
*Gyeongsik Moon, Hyeongjin Nam, Takaaki Shiratori, Kyoung Mu Lee.*<br>
ECCV 2022. [[PDF](https://arxiv.org/abs/2207.10053)] [[Project](https://github.com/hygenie1228/ClothWild_RELEASE/blob/main)]

**NDF: Neural Deformable Fields for Dynamic Human Modelling.**<br>
*Ruiqi Zhang, Jie Chen.*<br>
ECCV 2022. [[PDF](https://arxiv.org/abs/2207.09193)]

**Animatable Volume Rendering of Articulated Human SDFs.**<br>
*[Shaofei Wang](https://taconite.github.io/), [Katja Schwarz](https://katjaschwarz.github.io/), [Andreas Geiger](http://www.cvlibs.net/), [Siyu Tang](https://vlg.inf.ethz.ch/team/Prof-Dr-Siyu-Tang.html).*<br>
ECCV 2022. [[PDF](https://drive.google.com/file/d/10yCrdOadwKNiDQBni23_W03ZwVafkfCJ/view)] [[Project](https://neuralbodies.github.io/arah/)] [[Project](https://github.com/taconite/arah-release)]

**Learning Implicit Templates for Point-Based Clothed Human Modeling.**<br>
*Siyou Lin, Hongwen Zhang, Zerong Zheng, Ruizhi Shao, Yebin Liu.*<br>
ECCV 2022. [[PDF](https://arxiv.org/abs/2207.06955)] [[Project](https://jsnln.github.io/fite)] [[Project](https://github.com/jsnln/fite)]

**DANBO: Disentangled Articulated Neural Body Representations via Graph Neural Networks.**<br>
*[Shih-Yang Su](https://lemonatsu.github.io/), [Timur Bagautdinov](https://scholar.google.ch/citations?user=oLi7xJ0AAAAJ&hl=en), and [Helge Rhodin](http://helge.rhodin.de/).*<br>
ECCV 2022. [[PDF](https://arxiv.org/abs/2205.01666)] [[Project](https://lemonatsu.github.io/danbo/)] [[Code](https://github.com/LemonATsu/DANBO-pytorch)]

**Geometry-Guided Progressive NeRF for Generalizable and Efficient Neural Human Rendering.**<br>
*Mingfei Chen, Jianfeng Zhang, Xiangyu Xu, Lijuan Liu, Jiashi Feng, Shuicheng Yan.*<br>
ECCV 2022. [[PDF](https://arxiv.org/abs/2112.04312)]

**AvatarCap: Animatable Avatar Conditioned Monocular Human Volumetric Capture.**<br>
*Zhe Li, Zerong Zheng, Hongwen Zhang, Chaonan Ji, Yebin Liu.*<br>
ECCV 2022. [[PDF](https://arxiv.org/abs/2207.02031)] [[Project](http://www.liuyebin.com/avatarcap/avatarcap.html)]

**Authentic Volumetric Avatars From a Phone Scan.**<br>
*[Chen Cao](https://sites.google.com/site/zjucaochen/home), Tomas Simon, Jin Kyu Kim, Gabe Schwartz, Michael Zollhoefer, Shunsuke Saito, Stephen Lombardi, Shih-en Wei, Danielle Belko, Shoou-i Yu, Yaser Sheikh, Jason Saragih.*<br>
SIGGRAPH 2022. [[PDF](https://drive.google.com/file/d/1i4NJKAggS82wqMamCJ1OHRGgViuyoY6R/view?usp=sharing)] [[Project](https://zollhoefer.com/papers/arXiv22_InstantAvatars/page.html)]

**HumanNeRF: Efficiently Generated Human Radiance Field from Sparse Inputs.**<br>
*[Fuqiang Zhao](https://zhaofuq.github.io/), Wei Yang, Jiakai Zhang, Pei Lin, Yingliang Zhang, Jingyi Yu, Lan Xu.*<br>
CVPR 2022. [[PDF](https://arxiv.org/pdf/2112.02789.pdf)] [[Project](https://zhaofuq.github.io/humannerf/)] 

**Photorealistic Monocular 3D Reconstruction of Humans Wearing Clothing.**<br>
*[Thiemo Alldieck](https://scholar.google.com/citations?user=tJlD24EAAAAJ), [Mihai Zanfir](https://scholar.google.com/citations?user=af68sKkAAAAJ), [Cristian Sminchisescu](https://scholar.google.com/citations?user=LHTI1W8AAAAJ).*<br>
CVPR 2022. [[PDF](https://phorhum.github.io/static/assets/alldieck2022phorhum.pdf)] [[Project](https://phorhum.github.io/)]

**HumanNeRF: Free-viewpoint Rendering of Moving People from Monocular Video.**<br>
*[Chung-Yi Weng](https://homes.cs.washington.edu/~chungyi/), Brian Curless, Pratul Srinivasan,Jonathan T. Barron, Ira Kemelmacher-Shlizerman.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2201.04127)] [[Project](https://grail.cs.washington.edu/projects/humannerf/)]

**H4D: Human 4D Modeling by Learning Neural Compositional Representation.**<br>
*Boyan Jiang, Yinda Zhang, Xingkui Wei, Xiangyang Xue, Yanwei Fu.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2203.01247)]

**OcclusionFusion: Occlusion-aware Motion Estimation for Real-time Dynamic 3D Reconstruction.**<br>
*[Wenbin Lin](https://wenbin-lin.github.io/), Chengwei Zheng, Jun-Hai Yong, Feng Xu.*<br>
CVPR 2022. [[PDF](https://arxiv.org/pdf/2203.07977.pdf)] [[Project](https://wenbin-lin.github.io/OcclusionFusion/)]

**PINA: Learning a Personalized Implicit Neural Avatar from a Single RGB-D Video Sequence.**<br>
*Zijian Dong, Chen Guo, Jie Song, Xu Chen, Andreas Geiger, Otmar Hilliges.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2203.01754)] [[Project](https://zj-dong.github.io/pina/)]

**SelfRecon: Self Reconstruction Your Digital Avatar from Monocular Video.**<br>
*[Boyi Jiang](https://scholar.google.com/citations?user=lTlZV8wAAAAJ&hl=zh-CN), Yang Hong, Hujun Bao, Juyong Zhang.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2201.12792)] [[Project](https://jby1993.github.io/SelfRecon/)]

**Fourier PlenOctrees for Dynamic Radiance Field Rendering in Real-time.**<br>
*Liao Wang, Jiakai Zhang, Xinhang Liu, Fuqiang Zhao, Yanshun Zhang, Yingliang Zhang, Minye Wu, Lan Xu, Jingyi Yu.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2202.08614)]

**NeuralHOFusion: Neural Volumetric Rendering under Human-object Interactions.**<br>
*Yuheng Jiang, Suyi Jiang, Guoxing Sun, Zhuo Su, Kaiwen Guo, Minye Wu, Jingyi Yu, Lan Xu.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2202.12825)] [[Project](https://nowheretrix.github.io/neuralfusion/)]

**JIFF: Jointly-aligned Implicit Face Function for High Quality Single View Clothed Human Reconstruction.**<br>
*[Yukang Cao](https://github.com/yukangcao), [Guanying Chen](https://guanyingc.github.io/), [Kai Han](http://www.hankai.org/), [Wenqi Yang](https://github.com/ywq), [Kwan-Yee K. Wong](http://i.cs.hku.hk/~kykwong/).*<br>
CVPR 2022 (oral). [[PDF](https://arxiv.org/abs/2204.10549)] [[Project](https://yukangcao.github.io/JIFF)]

**High-Fidelity Human Avatars from a Single RGB Camera.**<br>
*Hao Zhao, [Jinsong Zhang](https://zhangjinso.github.io/), [Yu-Kun Lai](https://users.cs.cf.ac.uk/Yukun.Lai/), [Zerong Zheng](https://zhengzerong.github.io/), Yingdi Xie, [Yebin Liu](http://www.liuyebin.com/), [Kun Li](http://cic.tju.edu.cn/faculty/likun/).*<br>
CVPR 2022. [[PDF](http://cic.tju.edu.cn/faculty/likun/projects/HF-Avatar/assets/main.pdf)] [[Project](http://cic.tju.edu.cn/faculty/likun/projects/HF-Avatar/index.html)] [[Project](https://github.com/hzhao1997/HF-Avatar)] [[Data](https://drive.google.com/file/d/1qh1dj5ZoUBst_02UJY7IWstQMhb8L5IA/view?usp=sharing)]

**ICON: Implicit Clothed humans Obtained from Normals.**<br>
*[Yuliang Xiu](https://ps.is.tuebingen.mpg.de/person/yxiu), [Jinlong Yang](https://ps.is.tuebingen.mpg.de/person/jyang), [Dimitrios Tzionas](https://ps.is.mpg.de/~dtzionas), [Michael J. Black](https://ps.is.tuebingen.mpg.de/person/black).*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2112.09127)] [[Code](https://github.com/YuliangXiu/ICON)]

**DoubleField: Bridging the Neural Surface and Radiance Fields for High-fidelity Human Rendering.**<br>
*Ruizhi Shao, Hongwen Zhang, He Zhang, Yanpei Cao, Tao Yu, Yebin Liu.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2106.03798)] [[Project](http://www.liuyebin.com/dbfield/dbfield.html)]

**Structured Local Radiance Fields for Human Avatar Modeling.**<br>
*[Zerong Zheng](https://zhengzerong.github.io/), Han Huang, Tao Yu, Hongwen Zhang, Yandong Guo, Yebin Liu.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2203.14478)] [[Project](https://liuyebin.com/slrf/slrf.html)] [[Code](https://zhengzerong.github.io/)]

**DoubleField: Bridging the Neural Surface and Radiance Fields for High-fidelity Human Reconstruction and Rendering.**<br>
*Ruizhi Shao, [Hongwen Zhang](https://hongwenzhang.github.io/), He Zhang, Mingjia Chen, Yanpei Cao, Tao Yu, Yebin Liu.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2106.03798)] [[Project](http://www.liuyebin.com/dbfield/dbfield.html)]

**I M Avatar: Implicit Morphable Head Avatars from Videos.**<br>
*Yufeng Zheng, Victoria Fernández Abrevaya, Xu Chen, Marcel C. Bühler, Michael J. Black, Otmar Hilliges.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2112.07471)]

**Surface-Aligned Neural Radiance Fields for Controllable 3D Human Synthesis.**<br>
*Tianhan Xu, Yasuhiro Fujita, Eiichi Matsumoto.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2201.01683)]

**Neural Head Avatars from Monocular RGB Videos.**<br>
*[Philip-William Grassal](https://hci.iwr.uni-heidelberg.de/vislearn/people), [Malte Prinzler](https://de.linkedin.com/in/malte-prinzler), [Titus Leistner](https://titus-leistner.de/pages/about-me.html), [Carsten Rother](https://hci.iwr.uni-heidelberg.de/vislearn/people/carsten-rother/), [Matthias Nießner](https://www.niessnerlab.org/members/matthias_niessner/profile.html), [Justus Thies](https://justusthies.github.io/).*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2112.01554)] [[Project](https://philgras.github.io/neural_head_avatars/neural_head_avatars.html)]

**gDNA: Towards Generative Detailed Neural Avatars.**<br>
*[Xu Chen](https://ait.ethz.ch/people/xu/), [Tianjian Jiang](https://ait.ethz.ch/people/zhengyuf/), [Jie Song](https://ait.ethz.ch/people/song/), [Jinlong Yang](https://is.mpg.de/person/jyang), [Michael J. Black](https://ps.is.mpg.de/~black), [Andreas Geiger](http://www.cvlibs.net/), [Otmar Hilliges](https://ait.ethz.ch/people/hilliges/).*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2201.04123)] [[Project](https://ait.ethz.ch/projects/2022/gdna/downloads/)] [[Code](https://github.com/xuchen-ethz/gdna)]

**HumanNeRF: Generalizable Neural Human Radiance Field from Sparse Inputs.**<br>
*Fuqiang Zhao, Wei Yang, Jiakai Zhang, Pei Lin, Yingliang Zhang, Jingyi Yu, Lan Xu.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2112.02789)] [[Project](https://zhaofuq.github.io/humannerf/)]

**PERGAMO: Personalized 3D Garments from Monocular Video.**<br>
*Andrés Casado-Elvira, Marc Comino Trinidad, Dan Casas.*<br>
CFG 2022. [[PDF](https://arxiv.org/abs/2210.15040)] [[Project](http://mslab.es/projects/PERGAMO/)]

## Cloth Modelling, Draping, Simulation, and Dressing

**4D-DRESS: A 4D Dataset of Real-world Human Clothing with Semantic Annotations.**<br>
*[Wenbo Wang](https://wenbwa.github.io), [Hsuan-I Ho](https://ait.ethz.ch/people/hohs), [Chen Guo](https://ait.ethz.ch/people/cheguo), [Boxiang Rong](https://ribosome-rbx.github.io), [Artur Grigorev](https://ait.ethz.ch/people/agrigorev), [Jie Song](https://ait.ethz.ch/people/song), [Juan Jose Zarate](https://ait.ethz.ch/people/jzarate), [Otmar Hilliges](https://ait.ethz.ch/people/hilliges).*<br>
CVPR 2024 (Highlight). [[PDF](https://arxiv.org/abs/2404.18630)] [[Project](https://eth-ait.github.io/4d-dress/)] [[Data](https://4d-dress.ait.ethz.ch/)] [[Code](https://github.com/eth-ait/4d-dress)]

**A Generative Multi-Resolution Pyramid and Normal-Conditioning 3D Cloth Draping.**<br>
*Hunor Laczkó, Meysam Madadi, Sergio Escalera, Jordi Gonzalez.*<br>
WACV 2024. [[PDF](https://arxiv.org/abs/2311.02700)]

**Towards Multi-Layered 3D Garments Animation.**<br>
*Yidi Shao, Chen Change Loy, Bo Dai.*<br>
ICCV 2023. [[PDF](https://arxiv.org/pdf/2305.10418.pdf)] [[Project](https://mmlab-ntu.github.io/project/layersnet/index.html)]

**REC-MV: REconstructing 3D Dynamic Cloth from Monocular Videos.**<br>
*[Lingteng Qiu](https://lingtengqiu.github.io/), [Guanying Chen](https://guanyingc.github.io/), Jiapeng Zhou, [Mutian Xu](https://mutianxu.github.io/), Junle Wang, [Xiaoguang Han](https://mypage.cuhk.edu.cn/academics/hanxiaoguang/).*<br> 
CVPR 2023. [[PDF](http://arxiv.org/abs/2305.14236)] [[Project](https://lingtengqiu.github.io/2023/REC-MV/)] [[Code](https://github.com/GAP-LAB-CUHK-SZ/REC-MV)]

**HOOD: Hierarchical Graphs for Generalized Modelling of Clothing Dynamics.**<br>
*[Artur Grigorev](https://dolorousrtur.github.io/), [Bernhard Thomaszewski](https://n.ethz.ch/~bthomasz/index.html), [Michael J. Black](https://ps.is.mpg.de/~black), [Otmar Hilliges](https://ait.ethz.ch/people/hilliges/).*<br> 
CVPR 2023. [[PDF](https://arxiv.org/abs/2212.07242)] [[Project](https://dolorousrtur.github.io/hood/)] [[Code](https://github.com/Dolorousrtur/HOOD)]

**Deep Deformation Detail Synthesis for Thin Shell Models.**<br>
*Lan Chen, Lin Gao, Jie Yang, Shibiao Xu, Juntao Ye, Xiaopeng Zhang, Yu-Kun Lai.*<br>
CGF 2023. [[PDF](https://arxiv.org/abs/2102.11541)]

**Motion Guided Deep Dynamic 3D Garments.**<br>
*[Meng Zhang](https://mengzephyr.com/), [Duygu Ceylan](https://research.adobe.com/person/duygu-ceylan/), [Niloy J. Mitra](http://www0.cs.ucl.ac.uk/staff/n.mitra/).*<br>
SIGGRAPH Asia 2022. [[PDF](https://arxiv.org/pdf/2209.11449.pdf)] [[Project](http://geometry.cs.ucl.ac.uk/projects/2022/MotionDeepGarment/)]

**Predicting Loose-Fitting Garment Deformations Using Bone-Driven Motion Networks.**<br>
*Xiaoyu Pan, Jiaming Mai, Xinwei Jiang, Dongxue Tang, Jingxiang Li, Tianjia Shao, Kun Zhou, Xiaogang Jin, Dinesh Manocha.*<br>
SIGGRAPH 2022. [[PDF](https://arxiv.org/abs/2205.01355)] [[Code](https://github.com/non-void/VirtualBones)]

**DiffCloth: Differentiable Cloth Simulation with Dry Frictional Contact.**<br>
*[Yifei Li](https://people.csail.mit.edu/liyifei/), [Tao Du](https://people.csail.mit.edu/taodu/), [Kui Wu](https://people.csail.mit.edu/kuiwu/), [Jie Xu](http://people.csail.mit.edu/jiex/), [Wojciech Matusik](https://cdfg.csail.mit.edu/wojciech).*<br>
TOG 2022. [[PDF](https://arxiv.org/abs/2106.05306)] [[Project](https://people.csail.mit.edu/liyifei/publication/diffcloth-differentiable-cloth-simulator/)] [[Code](https://github.com/omegaiota/DiffCloth)]

**DIG: Draping Implicit Garment over the Human Body.**<br>
*Ren Li, Benoît Guillard, Edoardo Remelli, Pascal Fua.*<br>
ACCV 2022. [[PDF](https://arxiv.org/abs/2209.10845)]

**SNUG: Self-Supervised Neural Dynamic Garments.**<br>
*Igor Santesteban, Miguel A. Otaduy, Dan Casas.*<br>
CVPR 2022 (Oral). [[PDF](https://arxiv.org/abs/2204.02219)] [[Project](http://mslab.es/projects/SNUG/)] [[Code](https://github.com/isantesteban/snug)]

**Registering Explicit to Implicit: Towards High-Fidelity Garment mesh Reconstruction from Single Images.**<br>
*Heming Zhu, Lingteng Qiu, Yuda Qiu, Xiaoguang Han.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2203.15007)] [[Project](https://kv2000.github.io/2022/03/28/reef/)]

## Human Image and Video Generation

**Gaussian Shell Maps for Efficient 3D Human Generation.**<br>
*Rameen Abdal, Wang Yifan, Zifan Shi, Yinghao Xu, Ryan Po, Zhengfei Kuang, Qifeng Chen, Dit-Yan Yeung, Gordon Wetzstein.*<br> 
CVPR 2024. [[PDF](http://arxiv.org/abs/2311.17857)] [[Project](https://rameenabdal.github.io/GaussianShellMaps/)]

**HyperHuman: Hyper-Realistic Human Generation with Latent Structural Diffusion.**<br>
*Xian Liu, Jian Ren, Aliaksandr Siarohin, Ivan Skorokhodov, Yanyu Li, Dahua Lin, Xihui Liu, Ziwei Liu, Sergey Tulyakov.*<br> 
ICLR 2024. [[PDF](http://arxiv.org/abs/2310.08579)] [[Project](https://snap-research.github.io/HyperHuman/)]

**VeRi3D: Generative Vertex-based Radiance Fields for 3D Controllable Human Image Synthesis.**<br>
*Xinya Chen, Jiaxin Huang, Yanrui Bin, Lu Yu, Yiyi Liao.*<br> 
ICCV 2023. [[PDF](http://arxiv.org/abs/2309.04800)]

**UnitedHuman: Harnessing Multi-Source Data for High-Resolution Human Generation.**<br>
*Jianglin Fu, Shikai Li, Yuming Jiang, Kwan-Yee Lin, Wayne Wu, Ziwei Liu.*<br>
ICCV 2023. [[PDF](https://arxiv.org/abs/2309.14335)] [[Project](https://unitedhuman.github.io/)] [[Github](https://github.com/UnitedHuman/UnitedHuman)] 

**Text2Performer: Text-Driven Human Video Generation.**<br>
*Yuming Jiang, Shuai Yang, Tong Liang Koh, Wayne Wu, Chen Change Loy, Ziwei Liu.*<br>
ICCV 2023. [[PDF](https://arxiv.org/pdf/2304.08483.pdf)] [[Project](https://yumingj.github.io/projects/Text2Performer.html)] [[Code](https://github.com/yumingj/Text2Performer)]

**Text-guided 3D Human Generation from 2D Collections.**<br>
*Tsu-Jui Fu, Wenhan Xiong, Yixin Nie, Jingyu Liu, Barlas Oğuz, William Yang Wang.*<br> 
EMNLP 2023 (Findings). [[PDF](http://arxiv.org/abs/2305.14312)] [[Project](https://text-3dh.github.io/)]

**Cross Attention Based Style Distribution for Controllable Person Image Synthesis.**<br>
*Xinyue Zhou, Mingyu Yin, Xinyuan Chen, Li Sun, Changxin Gao, Qingli Li.*<br>
ECCV 2022. [[PDF](https://arxiv.org/abs/2208.00712)] 

**StyleGAN-Human: A Data-Centric Odyssey of Human Generation.**<br>
*Jianglin Fu, Shikai Li, [Yuming Jiang](https://yumingj.github.io/), [Kwan-Yee Lin](https://kwanyeelin.github.io/), [Chen Qian](https://scholar.google.com/citations?user=AerkT0YAAAAJ&hl=zh-CN), [Chen Change Loy](https://www.mmlab-ntu.com/person/ccloy/), [Wayne Wu](https://dblp.org/pid/50/8731.html), [Ziwei Liu](https://liuziwei7.github.io/).*<br>
ECCV 2022. [[PDF](https://arxiv.org/abs/2204.11823)] [[Code](https://youtu.be/nIrb9hwsdcI)] [[Project](https://stylegan-human.github.io/)] [[Colab Demo](https://colab.research.google.com/drive/1sgxoDM55iM07FS54vz9ALg1XckiYA2On)] [[Hugging Face Demo](https://huggingface.co/spaces/hysts/StyleGAN-Human)]

**Text2Human: Text-Driven Controllable Human Image Generation.**<br>
*Yuming Jiang, Shuai Yang, Haonan Qiu, Wayne Wu, Chen Change Loy, Ziwei Liu.*<br>
SIGGRAPH 2022. [[PDF](https://arxiv.org/abs/2205.15996)] [[Code](https://github.com/yumingj/Text2Human)] [[Project](https://yumingj.github.io/projects/Text2Human.html)] 

**Self-Supervised Correlation Mining Network for Person Image Generation.**<br>
*Zijian Wang, Xingqun Qi, Kun Yuan, Muyi Sun.*<br>
CVPR 2022. [[PDF](https://openaccess.thecvf.com/content/CVPR2022/html/Wang_Self-Supervised_Correlation_Mining_Network_for_Person_Image_Generation_CVPR_2022_paper.html)] 

**BodyGAN: General-Purpose Controllable Neural Human Body Generation.**<br>
*Chaojie Yang, Hanhui Li, Shengjie Wu, Shengkai Zhang, Haonan Yan, Nianhong Jiao, Jie Tang, Runnan Zhou, Xiaodan Liang, Tianxiang Zheng.*<br>
CVPR 2022. [[PDF](https://openaccess.thecvf.com/content/CVPR2022/html/Yang_BodyGAN_General-Purpose_Controllable_Neural_Human_Body_Generation_CVPR_2022_paper.html)] 

**InsetGAN for Full-Body Image Generation.**<br>
*[Anna Frühstück](https://afruehstueck.github.io/), [Krishna Kumar Singh](http://krsingh.cs.ucdavis.edu/), [Eli Shechtman](https://research.adobe.com/person/eli-shechtman/), [Niloy J. Mitra](https://research.adobe.com/person/niloy-mitra/), [Peter Wonka](http://peterwonka.net/), [Jingwan Lu](https://research.adobe.com/person/jingwan-lu/).*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2112.07200)] [[Project](http://afruehstueck.github.io/insetgan)]

**Neural Texture Extraction and Distribution for Controllable Person Image Synthesis.**<br>
*Yurui Ren, Xiaoqing Fan, Ge Li, Shan Liu, Thomas H. Li.*<br>
CVPR 2022 (oral). [[PDF](https://arxiv.org/abs/2203.10496)] [[Code](https://github.com/RenYurui/Neural-Texture-Extraction-Distribution)]

**Exploring Dual-task Correlation for Pose Guided Person Image Generation.**<br>
*Pengze Zhang, Lingxiao Yang, Jianhuang Lai, Xiaohua Xie.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2203.02910)]

## Image-Based Virtual Try-On

[[Awesome Virtual Try-on (VTON)](https://github.com/minar09/awesome-virtual-try-on)]

**FashionTex: Controllable Virtual Try-on with Text and Texture.**<br>
*Anran Lin, Nanxuan Zhao, Shuliang Ning, Yuda Qiu, Baoyuan Wang, Xiaoguang Han.*<br> 
SIGGRAPH 2023. [[PDF](http://arxiv.org/abs/2305.04451)]

**TryOnDiffusion: A Tale of Two UNets.**<br>
*[Luyang Zhu](https://homes.cs.washington.edu/~lyzhu/), [Dawei Yang](http://www-personal.umich.edu/~ydawei/), [Tyler Zhu](https://research.google/people/TylerZhu/), [Fitsum Reda](https://fitsumreda.github.io/), [William Chan](http://williamchan.ca/), [Chitwan Saharia](https://scholar.google.co.in/citations?user=JApued4AAAAJ&hl=en), [Mohammad Norouzi](https://norouzi.github.io/), [Ira Kemelmacher-Shlizerman](https://www.irakemelmacher.com/).*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/2306.08276)] [[Project](https://tryondiffusion.github.io/)]

**High-Resolution Virtual Try-On with Misalignment and Occlusion-Handled Conditions.**<br>
*Sangyun Lee, Gyojung Gu, Sunghyun Park, Seunghwan Choi, Jaegul Choo.*<br>
ECCV 2022. [[PDF](https://arxiv.org/pdf/2206.14180.pdf)] [[Project](https://koo616.github.io/HR-VITON/)] [[Code](https://github.com/sangyun884/HR-VITON)]

**Single Stage Virtual Try-on via Deformable Attention Flows.**<br>
*Shuai Bai, Huiling Zhou, Zhikang Li, Chang Zhou, Hongxia Yang.*<br>
ECCV 2022. [[PDF](https://arxiv.org/abs/2207.09161)]

**MGN: A Regional Mask Guided Network for Parser-free Virtual Try-on.**<br>
*Chao Lin, Zhao Li, Sheng Zhou, Shichang Hu, Jialun Zhang, Linhao Luo, Jiarun Zhang, Longtao Huang, Yuan He.*<br>
IJCAI 2022. [[PDF](https://arxiv.org/abs/2204.11258)]

**ClothFormer: Taming Video Virtual Try-on in All Module.**<br> 
*Jianbin Jiang, Tan Wang, He Yan, Junhui Liu.*<br> 
CVPR 2022 (oral). [[PDF](https://arxiv.org/abs/2204.07154)] [[Project](https://arxiv.org/abs/2204.12151)]

**Style-Based Global Appearance Flow for Virtual Try-On.**<br>
*Sen He, Yi-Zhe Song, Tao Xiang.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2204.01046)] 

**Dressing in the Wild by Watching Dance Videos.**<br>
*Xin Dong, Fuwei Zhao, Zhenyu Xie, Xijin Zhang, Daniel K. Du, Min Zheng, Xiang Long, Xiaodan Liang, Jianchao Yang.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2203.15320)] [[Project](https://awesome-wflow.github.io/)]

**CIT: Cloth Interactive Transformer for Virtual Try-On.**<br>
*[Bin Ren](https://scholar.google.com/citations?user=Md9maLYAAAAJ&hl=en), Hao Tang, Fanyang Meng, Runwei Ding, Ling Shao, Philip H.S. Torr, Nicu Sebe.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2104.05519)] [[Code](https://github.com/Amazingren/CIT)]

**Weakly Supervised High-Fidelity Clothing Model Generation.**<br>
*Ruili Feng, Cheng Ma, Chengji Shen, Xin Gao, Zhenjiang Liu, Xiaobo Li, Kairi Ou, Zhengjun Zha.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2112.07200)]

## Human Body Reshaping

**Structure-Aware Flow Generation for Human Body Reshaping.**<br>
*[Jianqiang Ren](https://github.com/JianqiangRen), Yuan Yao, Biwen Lei, Miaomiao Cui, Xuansong Xie.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2203.04670)] [[Code](https://github.com/JianqiangRen/FlowBasedBodyReshaping)]

### Scene context-aware Human Body Generation

**Putting People in Their Place: Affordance-Aware Human Insertion Into Scenes.**<br>
*Sumith Kulal, Tim Brooks, Alex Aiken, Jiajun Wu, Jimei Yang, Jingwan Lu, Alexei A. Efros, Krishna Kumar Singh.*<br> 
CVPR 2023. [[PDF](http://arxiv.org/abs/2304.14406)] [[Project](https://sumith1896.github.io/affordance-insertion/)]

### Human Mesh Recovery

**GLAMR: Global Occlusion-Aware Human Mesh Recovery with Dynamic Cameras.**<br>
*[Ye Yuan](https://www.ye-yuan.com/), [Umar Iqbal](http://www.umariqbal.info/), [Pavlo Molchanov](https://research.nvidia.com/person/pavlo-molchanov/), [Kris Kitani](http://www.cs.cmu.edu/~kkitani/), [Jan Kautz](https://jankautz.com/).*<br>
CVPR 2022 (Oral). [[PDF](https://arxiv.org/abs/2112.01524)] [[Project](https://nvlabs.github.io/GLAMR)] [[Code](https://github.com/NVlabs/GLAMR)]

**Shapy: Accurate 3D Body Shape Regression Using Metric and Semantic Attributes.**<br>
*Vasileios Choutas, Lea Muller, Chun-Hao P. Huang, Siyu Tang, Dimitrios Tzionas, Michael J. Black.*<br> 
CVPR 2022. [[PDF](http://arxiv.org/abs/2206.07036)] [[Project](https://shapy.is.tue.mpg.de/)] [[Code](https://github.com/muelea/shapy)]

**PoseScript: 3D Human Poses from Natural Language.**<br>
*Ginger Delmas, Philippe Weinzaepfel, Thomas Lucas, Francesc Moreno-Noguer, Grégory Rogez.*<br> 
ECCV 2022. [[PDF](http://arxiv.org/abs/2210.11795)] [[Code](https://github.com/naver/posescript)]

### Human-Centric Perception

**Versatile Multi-Modal Pre-Training for Human-Centric Perception.**<br>
*[Fangzhou Hong](https://hongfz16.github.io/), [Liang Pan](), [Zhongang Cai](), [Ziwei Liu](https://liuziwei7.github.io/).*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2203.13815)] [[Code](https://github.com/hongfz16/HCMoCo)] [[Project](https://hongfz16.github.io/projects/HCMoCo.html;)]

### Datasets
- WildAvatar (2024). [[Website]](https://arxiv.org/pdf/2407.02165)
- Fashionpedia. [[Website]](https://fashionpedia.github.io/home/index.html)
- DeepFashion2 Dataset. [[Website]](<https://github.com/switchablenorms/DeepFashion2>)
- DeepFashion Dataset. [[Website]](http://mmlab.ie.cuhk.edu.hk/projects/DeepFashion.html)
- FashionGen. [[Website]](https://fashion-gen.com/)
- FashionAI. [[Tianchi]](http://fashionai.alibaba.com/datasets/?spm=a2c22.11190735.991137.8.501b6d83ilPJsX)
- TaobaoClothMatch. [[Tianchi]](TaobaoClothMatch)
- Fashion-MNIST. [[Fashion-MNIST]](https://github.com/zalandoresearch/fashion-mnist)
- Fashion IQ. [[Website]](https://www.spacewu.com/posts/fashion-iq/)
- NTURGBD-Parsing-4K Dataset. [[Website](https://github.com/hongfz16/HCMoCo)]

## Garment Design

## Fashion Style Influences

## Team and People 

- [Real Virtual Humans](http://virtualhumans.mpi-inf.mpg.de/), **Max Planck Institute for Informatics**, by [Gerard Pons-Moll](http://virtualhumans.mpi-inf.mpg.de/people/pons-moll.html).
- [Perceiving Systems, Tubingen Compus](http://ps.is.tuebingen.mpg.de/), **Max Planck Institute for Intelligent Systems**, by [Michael Black](http://ps.is.tuebingen.mpg.de/person/black).
- [Visual Computer Lab](https://niessnerlab.org/opening.html), **Technical University Munich (TUM)**, by [Prof. Dr. Matthias Nießner](https://niessnerlab.org/members/matthias_niessner/profile.html) and his [team](https://niessnerlab.org/team.html).
- [Broadband Network and Digital Media Lab](http://www.liuyebin.com/student.html), Department of Automation, **Tsinghua University**, by [Yebin Liu](http://www.liuyebin.com/).
- [Vision and Graphics Lab](https://ict.usc.edu/), **University of Southern California**, by [Hao Li](http://hao-li.com/Hao_Li/Hao_Li_-_publications.html).

## Dataset

- `SMPL`. To download the [SMPL-X](https://smpl-x.is.tue.mpg.de/), [SMPL+H](http://mano.is.tue.mpg.de/) and SMPL ([Male and Female](http://smpl.is.tue.mpg.de/), [Gender Neural Model](http://smplify.is.tue.mpg.de/)) model, go to this project website and register to get access to the downloads section. [[Code](https://github.com/vchoutas/smplx#loading-smpl-x-smplh-and-smpl)]

- `THUmanDataset`. [THUman](https://github.com/ZhengZerong/DeepHuman/tree/master/THUmanDataset) is a 3D real-world human model dataset containing approximately 7000 models.

- `AGORA`. AGORA, proposed at CVPR 2021 [paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Patel_AGORA_Avatars_in_Geography_Optimized_for_Regression_Analysis_CVPR_2021_paper.pdf), consists of 4240 scans spanning more than 350 unique subjects, all paired with SMPL-X fits.

# LLMs Enhanced by Multimodal Generation and Editing

# 📋 Contents
- [🤗 Introduction](#-introduction)
- [📋 Contents](#-contents)
- [💘 Tips](#-tips)
- [📍 Multimodal Generation](#-multimodal-generation)
  - [Image Generation](#image-generation)
    - [🔅 LLM-based](#-llm-based)
    - [Non-LLM-based (Clip/T5)](#non-llm-based-clipt5)
    - [Datasets](#datasets)
  - [Video Generation](#video-generation)
    - [🔅 LLM-based](#-llm-based-1)
    - [Non-LLM-based](#non-llm-based)
    - [Datasets](#datasets-1)
  - [3D Generation](#3d-generation)
    - [🔅 LLM-based](#-llm-based-2)
    - [Non-LLM-based (Clip/T5)](#non-llm-based-clipt5-1)
    - [Datasets](#datasets-2)
  - [Audio Generation](#audio-generation)
    - [🔅 LLM-based](#-llm-based-3)
    - [Non-LLM-based](#non-llm-based-1)
    - [Datasets](#datasets-3)
  - [Generation with Multiple Modalities](#generation-with-multiple-modalities)
    - [🔅 LLM-based](#-llm-based-4)
    - [Non-LLM-based](#non-llm-based-2)
- [📍 Multimodal Editing](#-multimodal-editing)
  - [Image Editing](#image-editing)
    - [🔅 LLM-based](#-llm-based-5)
    - [Non-LLM-based (Clip/T5)](#non-llm-based-clipt5-2)
  - [Video Editing](#video-editing)
    - [🔅 LLM-based](#-llm-based-6)
    - [Non-LLM-based (Clip/T5)](#non-llm-based-clipt5-3)
  - [3D Editing](#3d-editing)
    - [🔅 LLM-based](#-llm-based-7)
    - [Non-LLM-based (Clip/T5)](#non-llm-based-clipt5-4)
  - [Audio Editing](#audio-editing)
    - [🔅 LLM-based](#-llm-based-8)
    - [Non-LLM-based (Clip/T5)](#non-llm-based-clipt5-5)
- [📍 Multimodal Agents](#-multimodal-agents)
- [📍 Multimodal Understanding with LLMs](#-multimodal-understanding-with-llms)
  - [Multiple modalities](#multiple-modalities)
  - [Image Understanding](#image-understanding)
  - [Video Understanding](#video-understanding)
  - [3D Understanding](#3d-understanding)
  - [Audio Understanding](#audio-understanding)
- [📍 Multimodal LLM Safety](#-multimodal-llm-safety)
  - [Attack](#attack)
  - [Defense and Detect](#defense-and-detect)
  - [Alignment](#alignment)
  - [Datasets](#datasets-4)
  - [3D, Video and Audio Safety](#3d-video-and-audio-safety)
- [📍 Related Surveys](#-related-surveys)
  - [LLM](#llm)
  - [Vision](#vision)
- [👨‍💻 Team](#-team)
- [😉 Citation](#-citation)
- [⭐️ Star History](#️-star-history)



# 💘 Tips
- **✅ Paper searching via catatogue**: directly clicking the content of the catatogue to select the area of your research and browse related papers.
- **✅ Paper searching via author name**: Free feel to search papers of a specific author via `ctrl + F` and then type the author name. The dropdown list of authors will automatically expand when searching.
- **✅ Paper searching via tag**: You can also search the related papers via the following tags: `customization`, `iteractive`, `human motion generation` `tokenizer`. (More tags are ongoing)


# 📍 Multimodal Generation

## Image Generation

### 🔅 LLM-based

+ **InstantUnify: Integrates Multimodal LLM into Diffusion Models** (Aug 2024)<details><summary>Qixun Wang, Xu Bai, Rui Wang et al.</summary>Qixun Wang, Xu Bai, Rui Wang, Haofan Wang</details></details>
[![Code](https://img.shields.io/github/stars/instantX-research/InstantUnify.svg?style=social&label=Star)](https://github.com/instantX-research/InstantUnify)

+ **Image Textualization: An Automatic Framework for Creating Accurate and Detailed Image Descriptions** (11 June 2024)<details><summary>Renjie Pi, Jianshu Zhang, Jipeng Zhang et al.</summary> Renjie Pi, Jianshu Zhang, Jipeng Zhang, Rui Pan, Zhekai Chen, Tong Zhang</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.07502)
[![citation](https://img.shields.io/badge/citation-0-blue.svg?paper=da0d382c7fa981ba185ca633868442b75cb76de6)](https://www.semanticscholar.org/paper/91b4f447bb06d081a7947b42df57491a04fa46f9)



+ **T2S-GPT: Dynamic Vector Quantization for Autoregressive Sign Language Production from Text** (11 June 2024)<details><summary>[ACL 2024] Aoxiong Yin, Haoyuan Li, Kai Shen et al.</summary> Aoxiong Yin, Haoyuan Li, Kai Shen, Siliang Tang, Yueting Zhuang</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.07119)
[![citation](https://img.shields.io/badge/citation-0-blue.svg?paper=da0d382c7fa981ba185ca633868442b75cb76de6)](https://www.semanticscholar.org/paper/186910d697bf7eb605aa055aee78fd91ce3ce9fe)


+ **Open-World Human-Object Interaction Detection via Multi-modal Prompts** (11 June 2024)<details><summary>Jie Yang, Bingliang Li, Ailing Zeng et al.</summary>Jie Yang, Bingliang Li, Ailing Zeng, Lei Zhang, Ruimao Zhang</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.07119)
[![citation](https://img.shields.io/badge/citation-0-blue.svg?paper=da0d382c7fa981ba185ca633868442b75cb76de6)](https://www.semanticscholar.org/paper/186910d697bf7eb605aa055aee78fd91ce3ce9fe)


+ **Commonsense-T2I Challenge: Can Text-to-Image Generation Models Understand Commonsense?** (11 June 2024)<details><summary>Xingyu Fu, Muyu He, Yujie Lu et al.</summary>Xingyu Fu, Muyu He, Yujie Lu, William Yang Wang, Dan Roth</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.07221v1)
[![citation](https://img.shields.io/badge/citation-0-blue.svg?paper=da0d382c7fa981ba185ca633868442b75cb76de6)](https://www.semanticscholar.org/paper/f0acf2a2293d963c3786e83bb198c75612adc446)



+ **An Image is Worth 32 Tokens for Reconstruction and Generation** (11 June 2024)<details><summary>Qihang Yu, Mark Weber, Xueqing Deng et al.</summary> Qihang Yu, Mark Weber, Xueqing Deng, Xiaohui Shen, Daniel Cremers, Liang-Chieh Chen</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.07550)
[![citation](https://img.shields.io/badge/citation-0-blue.svg?paper=da0d382c7fa981ba185ca633868442b75cb76de6)](https://www.semanticscholar.org/paper/1e31f4a4ccfc0d1e461be05361d77b5e045f4d37)


+ **TRINS: Towards Multimodal Language Models that Can Read** (10 June 2024)<details><summary>[CVPR 2024] Ruiyi Zhang, Yanzhe Zhang, Jian Chen et al.</summary> Ruiyi Zhang, Yanzhe Zhang, Jian Chen, Yufan Zhou, Jiuxiang Gu, Changyou Chen, Tong Sun</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.06730)
[![citation](https://img.shields.io/badge/citation-0-blue.svg?paper=da0d382c7fa981ba185ca633868442b75cb76de6)](https://www.semanticscholar.org/paper/784260e953b2ce34df52086804681e35d57e5843)



<!-- + **Genie: Generative Interactive Environments** (26 Feb 2024)<details><summary>Jake Bruce, Michael Dennis, Ashley Edwards, et al.</summary> Jake Bruce, Michael Dennis, Ashley Edwards, Jack Parker-Holder, Yuge Shi, Edward Hughes, Matthew Lai, Aditi Mavalankar, Richie Steigerwald, Chris Apps, Yusuf Aytar, Sarah Bechtle, Feryal Behbahani, Stephanie Chan, Nicolas Heess, Lucy Gonzalez, Simon Osindero, Sherjil Ozair, Scott Reed, Jingwei Zhang, Konrad Zolna, Jeff Clune, Nando de Freitas, Satinder Singh, Tim Rocktäschel</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.15391v1) -->

+ **Chameleon: Mixed-Modal Early-Fusion Foundation Models** (16 May 2024)<details><summary>Chameleon Team</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2405.09818)
[![citation](https://img.shields.io/badge/citation-1-blue.svg?paper=32112b798f70faab00e14806f51d46058cf5e597)](https://www.semanticscholar.org/paper/Chameleon%3A-Mixed-Modal-Early-Fusion-Foundation-Team/32112b798f70faab00e14806f51d46058cf5e597?utm_source=direct_link)



+ **Graphic Design with Large Multimodal Model** (22 Apr 2024)<details><summary>Yutao Cheng, Zhao Zhang, Maoke Yang, et al.</summary> Yutao Cheng, Zhao Zhang, Maoke Yang, Hui Nie, Chunyuan Li, Xinglong Wu, and Jie Shao</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.14368)
[![citation](https://img.shields.io/badge/citation-1-blue.svg?paper=9259b476c31ba52b7e9ed059e5fbce2125092738)](https://www.semanticscholar.org/paper/9259b476c31ba52b7e9ed059e5fbce2125092738)
[![Code](https://img.shields.io/github/stars/graphic-design-ai/graphist.svg?style=social&label=Star)](https://github.com/graphic-design-ai/graphist)


+ **PMG : Personalized Multimodal Generation with Large Language Models** (7 Apr 2024)<details><summary>Xiaoteng Shen, Rui Zhang, Xiaoyan Zhao, et al.</summary>Xiaoteng Shen, Rui Zhang, Xiaoyan Zhao, Jieming Zhu, Xi Xiao</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.08677)
[![citation](https://img.shields.io/badge/citation-1-blue.svg?paper=cfb9eba1b5c55bb0052df41eaaff8716f9c420bd)](https://www.semanticscholar.org/paper/PMG-%3A-Personalized-Multimodal-Generation-with-Large-Shen-Zhang/cfb9eba1b5c55bb0052df41eaaff8716f9c420bd)


+ **MineDreamer: Learning to Follow Instructions via Chain-of-Imagination for Simulated-World Control** (19 Mar 2024)<details><summary>Enshen Zhou, Yiran Qin, Zhenfei Yin, et al.</summary>Enshen Zhou, Yiran Qin, Zhenfei Yin, Yuzhou Huang, Ruimao Zhang, Lu Sheng, Yu Qiao, Jing Shao</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.12037)
[![citation](https://img.shields.io/badge/citation-1-blue.svg?paper=ae06df762adcc4221162e83a737ea63cff47e65d)](https://www.semanticscholar.org/paper/ae06df762adcc4221162e83a737ea63cff47e65d)
[![Code](https://img.shields.io/github/stars/Zhoues/MineDreamer.svg?style=social&label=Star)](https://github.com/Zhoues/MineDreamer)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://sites.google.com/view/minedreamer/main)



+ **ELLA: Equip Diffusion Models with LLM for Enhanced Semantic Alignment** (8 Mar 2024)<details><summary>Xiwei Hu, Rui Wang, Yixiao Fang, et al.</summary> Xiwei Hu, Rui Wang, Yixiao Fang, Bin Fu, Pei Cheng, Gang Yu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.05135)
[![citation](https://img.shields.io/badge/citation-0-blue.svg?paper=da0d382c7fa981ba185ca633868442b75cb76de6)](https://www.semanticscholar.org/paper/da0d382c7fa981ba185ca633868442b75cb76de6)
[![Code](https://img.shields.io/github/stars/ELLA-Diffusion/ELLA.svg?style=social&label=Star)](https://github.com/ELLA-Diffusion/ELLA)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://ella-diffusion.github.io/)


+ **StrokeNUWA: Tokenizing Strokes for Vector Graphic Synthesis** (30 Jan 2024)<details><summary>Zecheng Tang, Chenfei Wu, Zekai Zhang, et al.</summary>Zecheng Tang, Chenfei Wu, Zekai Zhang, Mingheng Ni, Shengming Yin, Yu Liu, Zhengyuan Yang, Lijuan Wang, Zicheng Liu, Juntao Li, Nan Duan</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.17093)
[![citation](https://img.shields.io/badge/citation-1-blue.svg?paper=b2f6830afe63eb477294f17f0d3a6923135950f9)](https://www.semanticscholar.org/paper/StrokeNUWA%3A-Tokenizing-Strokes-for-Vector-Graphic-Tang-Wu/b2f6830afe63eb477294f17f0d3a6923135950f9)
`tokenizer`

+ **DiffusionGPT: LLM-Driven Text-to-Image Generation System** (18 Jan 2024)<details><summary>Jie Qin, Jie Wu, Weifeng Chen, et al.</summary> Jie Qin, Jie Wu, Weifeng Chen, Yuxi Ren, Huixia Li, Hefeng Wu, Xuefeng Xiao, Rui Wang, Shilei Wen</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.10061)
[![citation](https://img.shields.io/badge/citation-1-blue.svg?paper=d4b1a1c62a03ccffcf24983eb4fe22335cbb89b6)](https://www.semanticscholar.org/paper/d4b1a1c62a03ccffcf24983eb4fe22335cbb89b6)
[![Code](https://img.shields.io/github/stars/DiffusionGPT/DiffusionGPT.svg?style=social&label=Star)](https://github.com/DiffusionGPT/DiffusionGPT)


+ **StarVector: Generating Scalable Vector Graphics Code from Images** (17 Dec 2023)<details><summary>Juan A. Rodriguez, Shubham Agarwal, Issam H. Laradji, et al.</summary> Juan A. Rodriguez, Shubham Agarwal, Issam H. Laradji, Pau Rodriguez, David Vazquez, Christopher Pal, Marco Pedersoli</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.11556)
[![citation](https://img.shields.io/badge/citation-0-blue.svg?paper=60d3ade5c0085f5de1f5ab944cc058c78706ac66)](https://www.semanticscholar.org/paper/60d3ade5c0085f5de1f5ab944cc058c78706ac66)
[![Code](https://img.shields.io/github/stars/joanrod/star-vector.svg?style=social&label=Star)](https://github.com/joanrod/star-vector)


+ **VL-GPT: A Generative Pre-trained Transformer for Vision and Language Understanding and Generation** (14 Dec 2023)<details><summary>Jinguo Zhu, Xiaohan Ding, Yixiao Ge, et al.</summary> Jinguo Zhu, Xiaohan Ding, Yixiao Ge, Yuying Ge, Sijie Zhao, Hengshuang Zhao, Xiaohua Wang, Ying Shan</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.09251)
[![citation](https://img.shields.io/badge/citation-6-blue.svg?paper=ea6982a936a2b263bbf46ff6eb27fc0b63fddaf7)](https://www.semanticscholar.org/paper/ea6982a936a2b263bbf46ff6eb27fc0b63fddaf7)
[![Code](https://img.shields.io/github/stars/AILab-CVC/VL-GPT.svg?style=social&label=Star)](https://github.com/AILab-CVC/VL-GPT)


+ **StoryGPT-V: Large Language Models as Consistent Story Visualizers** (13 Dec 2023)<details><summary>Xiaoqian Shen, Mohamed Elhoseiny</summary> Xiaoqian Shen, Mohamed Elhoseiny</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.02252)
[![citation](https://img.shields.io/badge/citation-1-blue.svg?paper=e49cb2ab3a7990e3d05042197ae8b3fd934453de)](https://www.semanticscholar.org/paper/e49cb2ab3a7990e3d05042197ae8b3fd934453de)



+ **GENIXER: Empowering Multimodal Large Language Models as a Powerful
Data Generator** (11 Dec 2023)<details><summary>Henry Hengyuan Zhao, Pan Zhou, Mike Zheng Shou</summary> Henry Hengyuan Zhao, Pan Zhou, Mike Zheng Shou</details> 
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.06731)
[![citation](https://img.shields.io/badge/citation-0-blue.svg?paper=cb2295766b2f8f35524f6a9f93ae39d948d50bd4)](https://www.semanticscholar.org/paper/cb2295766b2f8f35524f6a9f93ae39d948d50bd4)


+ **Customization Assistant for Text-to-image Generation** (5 Dec 2023)<details><summary>Yufan Zhou, Ruiyi Zhang, Jiuxiang Gu, et al.</summary> Yufan Zhou, Ruiyi Zhang, Jiuxiang Gu, Tong Sun</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.03045)
[![citation](https://img.shields.io/badge/citation-1-blue.svg?paper=f30bb09dbd95845d792bdac217a9a652635ee8a5)](https://www.semanticscholar.org/paper/f30bb09dbd95845d792bdac217a9a652635ee8a5)`customization`



+ **ChatIllusion: Efficient-Aligning Interleaved Generation ability with Visual Instruction Model** (29 Nov 2023) <details><summary>Xiaowei Chi, Yijiang Liu, Zhengkai Jiang, et al.</summary> Xiaowei Chi, Yijiang Liu, Zhengkai Jiang, Rongyu Zhang, Ziyi Lin, Renrui Zhang, Peng Gao, Chaoyou Fu, Shanghang Zhang, Qifeng Liu, Yike Guo</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.17963)
[![citation](https://img.shields.io/badge/citation-0-blue.svg?paper=22d55c52f43f59634586ab95fefbb7dba8c8b190)](https://www.semanticscholar.org/paper/22d55c52f43f59634586ab95fefbb7dba8c8b190)
[![Code](https://img.shields.io/github/stars/litwellchi/ChatIllusion.svg?style=social&label=Star)](https://github.com/litwellchi/ChatIllusion)


+ **DreamSync: Aligning Text-to-Image Generation with Image Understanding Feedback** (29 Nov 2023) <details><summary>Jiao Sun, Deqing Fu, Yushi Hu, et al.</summary>Jiao Sun, Deqing Fu, Yushi Hu, Su Wang, Royi Rassin, Da-Cheng Juan, Dana Alon, Charles Herrmann, Sjoerd van Steenkiste, Ranjay Krishna, Cyrus Rashtchian</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.17946)
[![citation](https://img.shields.io/badge/citation-5-blue.svg?paper=d16f72b7be526dee5eb49e5afffeea2bddba5e66)](https://www.semanticscholar.org/paper/d16f72b7be526dee5eb49e5afffeea2bddba5e66)




+ **COLE: A Hierarchical Generation Framework for Graphic Design** (28 Nov 2023) <details><summary>Peidong Jia, Chenxuan Li, Zeyu Liu, et al.</summary>Peidong Jia, Chenxuan Li, Zeyu Liu, Yichao Shen, Xingru Chen, Yuhui Yuan, Yinglin Zheng, Dong Chen, Ji Li, Xiaodong Xie, Shanghang Zhang, Baining Guo</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.16974)
[![citation](https://img.shields.io/badge/citation-1-blue.svg?paper=8441c30ad4abdca9ee380aa6f22ffd731b10231b)](https://www.semanticscholar.org/paper/8441c30ad4abdca9ee380aa6f22ffd731b10231b)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://graphic-design-generation.github.io/)



+ **TextDiffuser-2: Unleashing the Power of Language Models for Text Rendering** (28 Nov 2023) <details><summary>Jingye Chen, Yupan Huang, Tengchao Lv, et al.</summary>Jingye Chen, Yupan Huang, Tengchao Lv, Lei Cui, Qifeng Chen, Furu Wei</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.16465)
[![citation](https://img.shields.io/badge/citation-1-blue.svg?paper=1c6e2a4da1ead685a95c079751bf4d7a727d8180)](https://www.semanticscholar.org/paper/1c6e2a4da1ead685a95c079751bf4d7a727d8180)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://jingyechen.github.io/textdiffuser2/)
[![Code](https://img.shields.io/github/stars/microsoft/unilm.svg?style=social&label=Star)](https://github.com/microsoft/unilm/tree/master/textdiffuser-2)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/JingyeChen22/TextDiffuser-2)

+ **LLMGA: Multimodal Large Language Model based Generation Assistant** (27 Nov 2023)<details><summary>Bin Xia, Shiyin Wang, Yingfan Tao, et al.</summary> Bin Xia, Shiyin Wang, Yingfan Tao, Yitong Wang, Jiaya Jia</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.16500)
[![citation](https://img.shields.io/badge/citation-2-blue.svg?paper=769a924d0af014acec326f50c15c5d70d258a969)](https://www.semanticscholar.org/paper/769a924d0af014acec326f50c15c5d70d258a969)
[![Code](https://img.shields.io/github/stars/dvlab-research/LLMGA.svg?style=social&label=Star)](https://github.com/dvlab-research/LLMGA)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://llmga.github.io/)





+ **Self-correcting LLM-controlled Diffusion Models** (27 Nov 2023)<details><summary>Tsung-Han Wu, Long Lian, Joseph E. Gonzalez, et al.</summary> Tsung-Han Wu, Long Lian, Joseph E. Gonzalez, Boyi Li, Trevor Darrell</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.16090)
[![citation](https://img.shields.io/badge/citation-4-blue.svg?paper=42c4315b5d2e33d7d9a0afdf84e6a47ccd7a700e)](https://www.semanticscholar.org/paper/42c4315b5d2e33d7d9a0afdf84e6a47ccd7a700e)
[![Code](https://img.shields.io/github/stars/tsunghan-wu/SLD.svg?style=social&label=Star)](https://github.com/tsunghan-wu/SLD)


+ **Tokenize and Embed ALL for Multi-modal Large Language Models** (8 Nov 2023)<details><summary>Zhen Yang, Yingxue Zhang, Fandong Meng, et al.</summary> Zhen Yang, Yingxue Zhang, Fandong Meng, Jie Zhou</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.04589)
[![citation](https://img.shields.io/badge/citation-1-blue.svg?paper=59d716b442ab760a78f58de6748c0fa1d507bfc1)](https://www.semanticscholar.org/paper/59d716b442ab760a78f58de6748c0fa1d507bfc1)
`tokenizer`


+ **WordArt Designer: User-Driven Artistic Typography Synthesis using Large Language Models** (20 Oct 2023)<details><summary>Jun-Yan He, Zhi-Qi Cheng, Chenyang Li, et al.</summary> Jun-Yan He, Zhi-Qi Cheng, Chenyang Li, Jingdong Sun, Wangmeng Xiang, Xianhui Lin, Xiaoyang Kang, Zengke Jin, Yusen Hu, Bin Luo, Yifeng Geng, Xuansong Xie, Jingren Zhou</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.18332)
[![citation](https://img.shields.io/badge/citation-4-blue.svg?paper=58b77dc0603eb52559d98a383bf9649fd31d0bc5)](https://www.semanticscholar.org/paper/58b77dc0603eb52559d98a383bf9649fd31d0bc5)


+ **LLM Blueprint: Enabling Text-to-Image Generation with Complex and Detailed Prompts** (16 Oct 2023)<details><summary>[ICLR 2024] Hanan Gani, Shariq Farooq Bhat, Muzammal Naseer, et al.</summary>Hanan Gani, Shariq Farooq Bhat, Muzammal Naseer, Salman Khan, Peter Wonka</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.10640)
[![citation](https://img.shields.io/badge/citation-4-blue.svg?paper=4cb2c262ce34f41974f1b1623fc5a6e32956ded3)](https://www.semanticscholar.org/paper/4cb2c262ce34f41974f1b1623fc5a6e32956ded3)
[![Code](https://img.shields.io/github/stars/hananshafi/llmblueprint.svg?style=social&label=Star)](https://github.com/hananshafi/llmblueprint)



+ **Making Multimodal Generation Easier: When Diffusion Models Meet LLMs** (13 Oct 2023)<details><summary>Xiangyu Zhao, Bo Liu, Qijiong Liu, et al.</summary>Xiangyu Zhao, Bo Liu, Qijiong Liu, Guangyuan Shi, Xiao-Ming Wu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.08949v1)
[![citation](https://img.shields.io/badge/citation-N/A-blue.svg?paper=833cdd713c27ab5899bb912a1d511c10af61cefb)](https://www.semanticscholar.org/paper/833cdd713c27ab5899bb912a1d511c10af61cefb)
[![Code](https://img.shields.io/github/stars/zxy556677/EasyGen.svg?style=social&label=Star)](https://github.com/zxy556677/EasyGen)


+ **Idea2Img: Iterative Self-Refinement with GPT-4V(ision) for Automatic Image Design and Generation** (12 Oct 2023)<details><summary>Zhengyuan Yang, Jianfeng Wang, Linjie Li, et al.</summary>Zhengyuan Yang, Jianfeng Wang, Linjie Li, Kevin Lin, Chung-Ching Lin, Zicheng Liu, Lijuan Wang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.08541)
[![citation](https://img.shields.io/badge/citation-6-blue.svg?paper=1d14a708622917da4b9820ada6d32af24fc1651a)](https://www.semanticscholar.org/paper/1d14a708622917da4b9820ada6d32af24fc1651a)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://idea2img.github.io/)
[![Code](https://img.shields.io/github/stars/zyang-ur/Idea2Img.svg?style=social&label=Star)](https://github.com/zyang-ur/Idea2Img)


+ **OpenLEAF: Open-Domain Interleaved Image-Text Generation and Evaluation** (11 Oct 2023)<details><summary>Jie An, Zhengyuan Yang, Linjie Li, et al.</summary>Jie An, Zhengyuan Yang, Linjie Li, Jianfeng Wang, Kevin Lin, Zicheng Liu, Lijuan Wang, Jiebo Luo</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.07749)
[![citation](https://img.shields.io/badge/citation-3-blue.svg?paper=7f1ba5630c3baa09b11cc665b3f71cdb117e5ffb)](https://www.semanticscholar.org/paper/7f1ba5630c3baa09b11cc665b3f71cdb117e5ffb)



+ **Mini-DALLE3: Interactive Text to Image by Prompting Large Language Models** (11 Oct 2023)<details><summary>Zeqiang Lai, Xizhou Zhu, Jifeng Dai, et al.</summary>Zeqiang Lai, Xizhou Zhu, Jifeng Dai, Yu Qiao, Wenhai Wang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.07653)
[![citation](https://img.shields.io/badge/citation-6-blue.svg?paper=f669d7a6fab0147253178a6fc854e05e3d92fb3f)](https://www.semanticscholar.org/paper/f669d7a6fab0147253178a6fc854e05e3d92fb3f)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://minidalle3.github.io/)
[![Code](https://img.shields.io/github/stars/Zeqiang-Lai/Mini-DALLE3.svg?style=social&label=Star)](https://github.com/Zeqiang-Lai/Mini-DALLE3)


+ **[DALL-E 3] Improving Image Generation with Better Captions** <details><summary>James Betker, Gabriel Goh, Li Jing, et al.</summary>James Betker, Gabriel Goh, Li Jing, Tim Brooks, Jianfeng Wang, Linjie Li, Long Ouyang, Juntang Zhuang, Joyce Lee, Yufei Guo, Wesam Manassra, Prafulla Dhariwal, Casey Chu, Yunxin Jiao, Aditya Ramesh</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://cdn.openai.com/papers/dall-e-3.pdf)
[![citation](https://img.shields.io/badge/citation-146-blue.svg?paper=cfee1826dd4743eab44c6e27a0cc5970effa4d80)](https://www.semanticscholar.org/paper/cfee1826dd4743eab44c6e27a0cc5970effa4d80)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://openai.com/dall-e-3)


+ **MiniGPT-5: Interleaved Vision-and-Language Generation via Generative Vokens** (3 Oct 2023)\
Kaizhi Zheng, Xuehai He, Xin Eric Wang.\
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.02239)
[![citation](https://img.shields.io/badge/citation-26-blue.svg?paper=e7d09b6f2bc878cf2c993acf675f409d0b55f35a)](https://www.semanticscholar.org/paper/e7d09b6f2bc878cf2c993acf675f409d0b55f35a)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://eric-ai-lab.github.io/minigpt-5.github.io/)
[![Code](https://img.shields.io/github/stars/eric-ai-lab/MiniGPT-5.svg?style=social&label=Star)](https://github.com/eric-ai-lab/MiniGPT-5)


+ **Making LLaMA SEE and Draw with SEED Tokenizer** (2 Oct 2023)<details><summary>Yuying Ge, Sijie Zhao, Ziyun Zeng, et al.</summary>Yuying Ge, Sijie Zhao, Ziyun Zeng, Yixiao Ge, Chen Li, Xintao Wang, Ying Shan</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.01218)
[![citation](https://img.shields.io/badge/citation-19-blue.svg?paper=5ba1525dc6d382ee0a4a1ca3c64fc5907ca64c67)](https://www.semanticscholar.org/paper/5ba1525dc6d382ee0a4a1ca3c64fc5907ca64c67)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://ailab-cvc.github.io/seed/)
[![Code](https://img.shields.io/github/stars/AILab-CVC/SEED.svg?style=social&label=Star)](https://github.com/AILab-CVC/SEED)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://dad1ed9a9fb76fe83b.gradio.live/)
`tokenizer`


+ **InstructCV: Instruction-Tuned Text-to-Image Diffusion Models as Vision Generalists** (30 Sep 2023)<details><summary>Yulu Gan, Sungwoo Park, Alexander Schubert, et al.</summary>Yulu Gan, Sungwoo Park, Alexander Schubert, Anthony Philippakis, Ahmed M. Alaa</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.00390)
[![citation](https://img.shields.io/badge/citation-5-blue.svg?paper=819f477065088220a6f706cd9ef76dbcb4b4c134)](https://www.semanticscholar.org/paper/819f477065088220a6f706cd9ef76dbcb4b4c134)
[![Code](https://img.shields.io/github/stars/AlaaLab/InstructCV.svg?style=social&label=Star)](https://github.com/AlaaLab/InstructCV)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/alaa-lab/InstructCV)

+ **InternLM-XComposer: A Vision-Language Large Model for Advanced Text-image Comprehension and Composition** (26 Sep 2023)<details><summary>Pan Zhang, Xiaoyi Dong, Bin Wang, et al.</summary> Pan Zhang, Xiaoyi Dong, Bin Wang, Yuhang Cao, Chao Xu, Linke Ouyang, Zhiyuan Zhao, Haodong Duan, Songyang Zhang, Shuangrui Ding, Wenwei Zhang, Hang Yan, Xinyue Zhang, Wei Li, Jingwen Li, Kai Chen, Conghui He, Xingcheng Zhang, Yu Qiao, Dahua Lin, Jiaqi Wang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.15112)
[![citation](https://img.shields.io/badge/citation-48-blue.svg?paper=c1e450284e7d6cac1855330a1197df8537df653f)](https://www.semanticscholar.org/paper/c1e450284e7d6cac1855330a1197df8537df653f)
[![Code](https://img.shields.io/github/stars/InternLM/InternLM-XComposer.svg?style=social&label=Star)](https://github.com/InternLM/InternLM-XComposer)




+ **Text-to-Image Generation for Abstract Concepts** (26 Sep 2023) <details><summary>Jiayi Liao, Xu Chen, Qiang Fu, et al.</summary>Jiayi Liao, Xu Chen, Qiang Fu, Lun Du, Xiangnan He, Xiang Wang, Shi Han, Dongmei Zhang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.14623)
[![citation](https://img.shields.io/badge/citation-1-blue.svg?paper=0d38f1edac66b4645cf5fa05abaf9d92cba5d5d3)](https://www.semanticscholar.org/paper/0d38f1edac66b4645cf5fa05abaf9d92cba5d5d3)




+ **DreamLLM: Synergistic Multimodal Comprehension and Creation** (20 Sep 2023)<details><summary>[ICLR 2024] Runpei Dong, Chunrui Han, Yuang Peng, et al.</summary>Runpei Dong, Chunrui Han, Yuang Peng, Zekun Qi, Zheng Ge, Jinrong Yang, Liang Zhao, Jianjian Sun, Hongyu Zhou, Haoran Wei, Xiangwen Kong, Xiangyu Zhang, Kaisheng Ma, Li Yi</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.11499)
[![citation](https://img.shields.io/badge/citation-38-blue.svg?paper=7b689adb8c156d6158660f90d1c86888ee281f63)](https://www.semanticscholar.org/paper/7b689adb8c156d6158660f90d1c86888ee281f63)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://dreamllm.github.io/)
[![Code](https://img.shields.io/github/stars/RunpeiDong/DreamLLM.svg?style=social&label=Star)](https://github.com/RunpeiDong/DreamLLM)


+ **SwitchGPT: Adapting Large Language Models for Non-Text Outputs** (14 Sep 2023)\
Wang, Xinyu, Bohan Zhuang, and Qi Wu.\
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.07623)
[![citation](https://img.shields.io/badge/citation-2-blue.svg?paper=366564d210768814bc880e391b909cfbd95f8964)](https://www.semanticscholar.org/paper/366564d210768814bc880e391b909cfbd95f8964)
[![Code](https://img.shields.io/github/stars/xinke-wang/SwitchGPT.svg?style=social&label=Star)](https://github.com/xinke-wang/SwitchGPT)

+ **NExT-GPT: Any-to-Any Multimodal LLM** (11 Sep 2023)<details><summary>Shengqiong Wu, Hao Fei, Leigang Qu, et al.</summary>Shengqiong Wu, Hao Fei, Leigang Qu, Wei Ji, Tat-Seng Chua</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.05519)
[![citation](https://img.shields.io/badge/citation-94-blue.svg?paper=fa75a55760e6ea49b39b83cb85c99a22e1088254)](https://www.semanticscholar.org/paper/fa75a55760e6ea49b39b83cb85c99a22e1088254)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://next-gpt.github.io/)
[![Code](https://img.shields.io/github/stars/NExT-GPT/NExT-GPT.svg?style=social&label=Star)](https://github.com/NExT-GPT/NExT-GPT)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://9704af1b453125102e.gradio.live/)

+ **LayoutLLM-T2I: Eliciting Layout Guidance from LLM for Text-to-Image Generation** (9 Aug 2023)<details><summary>Leigang Qu, Shengqiong Wu, Hao Fei, et al. ACM MM 2023</summary>Leigang Qu, Shengqiong Wu, Hao Fei, Liqiang Nie, Tat-Seng Chua</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.05095)
[![citation](https://img.shields.io/badge/citation-10-blue.svg?paper=7d78238a9bad60433d616abdd93c735087d99670)](https://www.semanticscholar.org/paper/7d78238a9bad60433d616abdd93c735087d99670)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://layoutllm-t2i.github.io/)
[![Code](https://img.shields.io/github/stars/LayoutLLM-T2I/LayoutLLM-T2I.svg?style=social&label=Star)](https://github.com/LayoutLLM-T2I/LayoutLLM-T2I)

+ **Planting a SEED of Vision in Large Language Model** (16 Jul 2023)<details><summary>Yuying Ge, Yixiao Ge, Ziyun Zeng, et al.</summary>Yuying Ge, Yixiao Ge, Ziyun Zeng, Xintao Wang, Ying Shan</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2307.08041)
[![citation](https://img.shields.io/badge/citation-30-blue.svg?paper=40298b8d50109c52fc10763eddc64a07cf8acb31)](https://www.semanticscholar.org/paper/40298b8d50109c52fc10763eddc64a07cf8acb31)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://ailab-cvc.github.io/seed/)
[![Code](https://img.shields.io/github/stars/AILab-CVC/SEED.svg?style=social&label=Star)](https://github.com/AILab-CVC/SEED)

+ **Generative Pretraining in Multimodality** (11 Jul 2023)<details><summary>Quan Sun, Qiying Yu, Yufeng Cui, et al.</summary>Quan Sun, Qiying Yu, Yufeng Cui, Fan Zhang, Xiaosong Zhang, Yueze Wang, Hongcheng Gao, Jingjing Liu, Tiejun Huang, Xinlong Wang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2307.05222)
[![citation](https://img.shields.io/badge/citation-43-blue.svg?paper=94053805cd59f2e9a47fe3f080c7e7afefb337cc)](https://www.semanticscholar.org/paper/94053805cd59f2e9a47fe3f080c7e7afefb337cc)
[![Code](https://img.shields.io/github/stars/baaivision/Emu.svg?style=social&label=Star)](https://github.com/baaivision/Emu)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](http://218.91.113.230:9002)

+ **SPAE: Semantic Pyramid AutoEncoder for Multimodal Generation with Frozen LLMs** (30 Jun 2023) <details><summary>[NeurIPS 2023 Spotlight] Lijun Yu, Yong Cheng, Zhiruo Wang, et al.</summary>Lijun Yu, Yong Cheng, Zhiruo Wang, Vivek Kumar, Wolfgang Macherey, Yanping Huang, David A. Ross, Irfan Essa, Yonatan Bisk, Ming-Hsuan Yang, Kevin Murphy, Alexander G. Hauptmann, Lu Jiang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.17842)
[![citation](https://img.shields.io/badge/citation-12-blue.svg?paper=376f494126d1ea4f571ea0263c43ac2b6331800a)](https://www.semanticscholar.org/paper/376f494126d1ea4f571ea0263c43ac2b6331800a)

+ **Controllable Text-to-Image Generation with GPT-4** (29 May 2023) <details><summary>Tianjun Zhang, Yi Zhang, Vibhav Vineet, et al.</summary>Tianjun Zhang, Yi Zhang, Vibhav Vineet, Neel Joshi, Xin Wang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.18583)
[![citation](https://img.shields.io/badge/citation-20-blue.svg?paper=3a79545719fb193a6b4042ef7d1d87cfd267be06)](https://www.semanticscholar.org/paper/3a79545719fb193a6b4042ef7d1d87cfd267be06)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://github.com/tianjunz/Control-GPT) 

+ **Generating Images with Multimodal Language Models** (26 May 2023)\
[NeurIPS 2023] Koh, Jing Yu, Daniel Fried, and Ruslan Salakhutdinov. \
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.17216)
[![citation](https://img.shields.io/badge/citation-73-blue.svg?paper=6fb5c0eff3696ef252aca9638e10176ecce7cecb)](https://www.semanticscholar.org/paper/6fb5c0eff3696ef252aca9638e10176ecce7cecb)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://jykoh.com/gill)
[![Code](https://img.shields.io/github/stars/kohjingyu/gill.svg?style=social&label=Star)](https://github.com/kohjingyu/gill)

+ **LayoutGPT: Compositional Visual Planning and Generation with Large Language Models** (24 May 2023)<details><summary>[NeurIPS 2023] Weixi Feng, Wanrong Zhu, Tsu-jui Fu, et al.</summary>Weixi Feng, Wanrong Zhu, Tsu-jui Fu, Varun Jampani, Arjun Akula, Xuehai He, Sugato Basu, Xin Eric Wang, William Yang Wang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.15393)
[![citation](https://img.shields.io/badge/citation-31-blue.svg?paper=66d755730f5d08a6f4fcc5e81f24982ba389dca9)](https://www.semanticscholar.org/paper/66d755730f5d08a6f4fcc5e81f24982ba389dca9)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://layoutgpt.github.io/)
[![Code](https://img.shields.io/github/stars/weixi-feng/LayoutGPT.svg?style=social&label=Star)](https://github.com/weixi-feng/LayoutGPT)

+ **Visual Programming for Text-to-Image Generation and Evaluation** (24 May 2023)\
[NeurIPS 2023] Jaemin Cho, Abhay Zala, Mohit Bansal.\
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.15328)
[![citation](https://img.shields.io/badge/citation-24-blue.svg?paper=9837349417e36ef5be06da0fd6c74042148bdaa2)](https://www.semanticscholar.org/paper/9837349417e36ef5be06da0fd6c74042148bdaa2)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://vp-t2i.github.io/)
[![Code](https://img.shields.io/github/stars/j-min/VPGen.svg?style=social&label=Star)](https://github.com/j-min/VPGen)

+ **LLM-grounded Diffusion: Enhancing Prompt Understanding of Text-to-Image Diffusion Models with Large Language Models** (23 May 2023) <details><summary>Long Lian, Boyi Li, Adam Yala, et al.</summary>Long Lian, Boyi Li, Adam Yala, Trevor Darrell</details>[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.13655)
[![citation](https://img.shields.io/badge/citation-39-blue.svg?paper=e9ae0c76a71b8f302eb17b1c4462b9cc97d87cd0)](https://www.semanticscholar.org/paper/e9ae0c76a71b8f302eb17b1c4462b9cc97d87cd0)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://llm-grounded-diffusion.github.io/)
[![Code](https://img.shields.io/github/stars/TonyLianLong/LLM-groundedDiffusion.svg?style=social&label=Star)](https://github.com/TonyLianLong/LLM-groundedDiffusion)

+ **Interactive Data Synthesis for Systematic Vision Adaptation via LLMs-AIGCs Collaboration** (22 May 2023)<details><summary>Qifan Yu, Juncheng Li, Wentao Ye, et al.</summary>Qifan Yu, Juncheng Li, Wentao Ye, Siliang Tang, Yueting Zhuang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.12799)
[![citation](https://img.shields.io/badge/citation-7-blue.svg?paper=43a55dbd95c9d5cd82de8db276f41adeec4a937d)](https://www.semanticscholar.org/paper/43a55dbd95c9d5cd82de8db276f41adeec4a937d)
[![Code](https://img.shields.io/github/stars/Yuqifan1117/Labal-Anything-Pipeline.svg?style=social&label=Star)](https://github.com/Yuqifan1117/Labal-Anything-Pipeline)

+ **LLMScore: Unveiling the Power of Large Language Models in Text-to-Image Synthesis Evaluation** (18 May 2023)<details><summary>[NeurIPS 2023] Yujie Lu, Xianjun Yang, Xiujun Li, et al.</summary>Yujie Lu, Xianjun Yang, Xiujun Li, Xin Eric Wang, William Yang Wang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.11116)
[![citation](https://img.shields.io/badge/citation-10-blue.svg?paper=972501b057e2b84d6ce6506f70bcac697bab7872)](https://www.semanticscholar.org/paper/972501b057e2b84d6ce6506f70bcac697bab7872)
[![Code](https://img.shields.io/github/stars/YujieLu10/LLMScore.svg?style=social&label=Star)](https://github.com/YujieLu10/LLMScore)

+ **SUR-adapter: Enhancing Text-to-Image Pre-trained Diffusion Models with Large Language Models** (9 May 2023)<details><summary>[ACM MM 2023] Shanshan Zhong, Zhongzhan Huang, Wushao Wen, et al.</summary>Shanshan Zhong, Zhongzhan Huang, Wushao Wen, Jinghui Qin, Liang Lin</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.05189)
[![Code](https://img.shields.io/github/stars/Qrange-group/SUR-adapter.svg?style=social&label=Star)](https://github.com/Qrange-group/SUR-adapter)

+ **Grounding Language Models to Images for Multimodal Inputs and Outputs** (31 Jan 2023)\
[ICML 2023] Koh, Jing Yu, Ruslan Salakhutdinov, and Daniel Fried.\
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2301.13823)
[![citation](https://img.shields.io/badge/citation-35-blue.svg?paper=6173520a1eb2814d067e8c5fd16212b7cbf6ee78)](https://www.semanticscholar.org/paper/6173520a1eb2814d067e8c5fd16212b7cbf6ee78)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://jykoh.com/fromage)
[![Code](https://img.shields.io/github/stars/kohjingyu/fromage.svg?style=social&label=Star)](https://github.com/kohjingyu/fromage)

+ **[RPG-DiffusionMaster] Mastering Text-to-Image Diffusion: Recaptioning, Planning, and Generating with Multimodal LLMs** (22 Jan 2024) <details><summary>[ICML 2024] Ling Yang, Zhaochen Yu, Chenlin Meng, et al.</summary>Ling Yang, Zhaochen Yu, Chenlin Meng, Minkai Xu, Stefano Ermon, Bin Cui</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.11708)
[![citation](https://img.shields.io/badge/citation-23-blue.svg?paper=140cfda71bfff852c3e205b7ad61854b78c76982)](https://www.semanticscholar.org/paper/140cfda71bfff852c3e205b7ad61854b78c76982)
[![Code](https://img.shields.io/github/stars/YangLing0818/RPG-DiffusionMaster.svg?style=social&label=Star)](https://github.com/YangLing0818/RPG-DiffusionMaster)

+ **RealCompo: Balancing Realism and Compositionality Improves Text-to-Image Diffusion Models** (20 Feb 2024)<details><summary>Xinchen Zhang, Ling Yang, Yaqi Cai, et al.</summary>Xinchen Zhang, Ling Yang, Yaqi Cai, Zhaochen Yu, Kai-Ni Wang, Jiake Xie, Ye Tian, Minkai Xu, Yong Tang, Yujiu Yang, Bin Cui</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.12908)
[![citation](https://img.shields.io/badge/citation-6-blue.svg?paper=9c2ba04c376f127da506b63c566887fca2861b25)](https://www.semanticscholar.org/paper/9c2ba04c376f127da506b63c566887fca2861b25)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://cominclip.github.io/RealCompo_Page/)
[![Code](https://img.shields.io/github/stars/YangLing0818/RealCompo.svg?style=social&label=Star)](https://github.com/YangLing0818/RealCompo)

### Non-LLM-based (Clip/T5)

+ **InstantStyle: Free Lunch towards Style-Preserving in Text-to-Image Generation** (3 Apr 2024)<details><summary>Haofan Wang, Matteo Spinelli, Qixun Wang, et al.</summary>Haofan Wang, Matteo Spinelli, Qixun Wang, Xu Bai, Zekui Qin, Anthony Chen</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.02733)
[![citation](https://img.shields.io/badge/citation-N/A-blue.svg?paper=6b5fc164c4f21e4a4f151df60bfd5e32b061a903)](https://www.semanticscholar.org/paper/InstantStyle%3A-Free-Lunch-towards-Style-Preserving-Wang-Spinelli/6b5fc164c4f21e4a4f151df60bfd5e32b061a903)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://instantstyle.github.io/)
[![Code](https://img.shields.io/github/stars/instantX-research/InstantStyle.svg?style=social&label=Star)](https://github.com/instantX-research/InstantStyle)

+ **InstantID: Zero-shot Identity-Preserving Generation in Seconds** (15 Jan 2024)<details><summary>Qixun Wang, Xu Bai, Haofan Wang, et al.</summary>Qixun Wang, Xu Bai, Haofan Wang, Zekui Qin, Anthony Chen, Huaxia Li, Xu Tang, Yao Hu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.07519)
[![citation](https://img.shields.io/badge/citation-N/A-blue.svg?paper=0f9b66c9208b11369e9d94d85b7dc23bcc5115e9)](https://www.semanticscholar.org/paper/InstantID%3A-Zero-shot-Identity-Preserving-Generation-Wang-Bai/0f9b66c9208b11369e9d94d85b7dc23bcc5115e9)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://instantid.github.io/)
[![Code](https://img.shields.io/github/stars/instantX-research/InstantID.svg?style=social&label=Star)](https://github.com/instantX-research/InstantID)

+ **PIXART-α: Fast Training of Diffusion Transformer for Photorealistic Text-to-Image Synthesis** (30 Sep 2023)<details><summary>[ICLR 2024] Junsong Chen, Jincheng Yu, Chongjian Ge, et al.</summary>Junsong Chen, Jincheng Yu, Chongjian Ge, Lewei Yao, Enze Xie, Yue Wu, Zhongdao Wang, James Kwok, Ping Luo, Huchuan Lu, Zhenguo Li</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.00426)
[![citation](https://img.shields.io/badge/citation-N/A-blue.svg?paper=7dfe1c9f1d7120102499c7e561efc2326e7a0358)](https://www.semanticscholar.org/paper/7dfe1c9f1d7120102499c7e561efc2326e7a0358)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://pixart-alpha.github.io/)
[![Code](https://img.shields.io/github/stars/PixArt-alpha/PixArt-alpha.svg?style=social&label=Star)](https://github.com/PixArt-alpha/PixArt-alpha)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/PixArt-alpha/PixArt-alpha)

+ **TextDiffuser: Diffusion Models as Text Painters** (18 May 2023) <details><summary>[NeurIPS 2023] Jingye Chen, Yupan Huang, Tengchao Lv, et al.</summary>Jingye Chen, Yupan Huang, Tengchao Lv, Lei Cui, Qifeng Chen, Furu Wei</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.10855)
[![citation](https://img.shields.io/badge/citation-12-blue.svg?paper=e779781f1bea273573fc9d3f1a5e874bcff2cd2b)](https://www.semanticscholar.org/paper/e779781f1bea273573fc9d3f1a5e874bcff2cd2b)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://jingyechen.github.io/textdiffuser/)
[![Code](https://img.shields.io/github/stars/microsoft/unilm.svg?style=social&label=Star)](https://github.com/microsoft/unilm/tree/master/textdiffuser)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/JingyeChen22/TextDiffuser)

+ **TiGAN: Text-Based Interactive Image Generation and Manipulation** (Dec 2022)<details><summary>[AAAI 2022] Yufan Zhou, Ruiyi Zhang, Jiuxiang Gu, et al.</summary>Yufan Zhou, Ruiyi Zhang, Jiuxiang Gu, Chris Tensmeyer, Tong Yu,Changyou Chen, Jinhui Xu, Tong Sun</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ojs.aaai.org/index.php/AAAI/article/view/20270)
[![citation](https://img.shields.io/badge/citation-9-blue.svg?paper=839dc73c1adae268144d9cfb9d70985b2001304f)](https://www.semanticscholar.org/paper/839dc73c1adae268144d9cfb9d70985b2001304f)
Tags: `iteractive`

+ **Multi-Concept Customization of Text-to-Image Diffusion** (8 Dec 2022)<details><summary>[CVPR 2023] Nupur Kumari, Bingliang Zhang, Richard Zhang, et al.</summary>Nupur Kumari, Bingliang Zhang, Richard Zhang, Eli Shechtman, Jun-Yan Zhu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2212.04488)
[![citation](https://img.shields.io/badge/citation-307-blue.svg?paper=144eca44e250cc462f6fc3a172abb865978f66f5)](https://www.semanticscholar.org/paper/144eca44e250cc462f6fc3a172abb865978f66f5)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://www.cs.cmu.edu/~custom-diffusion/)
[![Code](https://img.shields.io/github/stars/adobe-research/custom-diffusion.svg?style=social&label=Star)](https://github.com/adobe-research/custom-diffusion)\
Tags: `customization`

+ **DreamBooth: Fine Tuning Text-to-Image Diffusion Models for Subject-Driven Generation** (25 Aug 2022)<details><summary>[CVPR 2023] Nataniel Ruiz, Yuanzhen Li, Varun Jampani, et al.</summary>Nataniel Ruiz, Yuanzhen Li, Varun Jampani, Yael Pritch, Michael Rubinstein, Kfir Aberman</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2208.12242)
[![citation](https://img.shields.io/badge/citation-1090-blue.svg?paper=5b19bf6c3f4b25cac96362c98b930cf4b37f6744)](https://www.semanticscholar.org/paper/5b19bf6c3f4b25cac96362c98b930cf4b37f6744)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://dreambooth.github.io/)\
Tags: `customization`

+ **An Image is Worth One Word: Personalizing Text-to-Image Generation using Textual Inversion** (2 Aug 2022)<details><summary>Rinon Gal, Yuval Alaluf, Yuval Atzmon, et al. </summary>Rinon Gal, Yuval Alaluf, Yuval Atzmon, Or Patashnik, Amit H. Bermano, Gal Chechik, Daniel Cohen-Or</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2208.01618)
[![citation](https://img.shields.io/badge/citation-1090-blue.svg?paper=5b19bf6c3f4b25cac96362c98b930cf4b37f6744)](https://www.semanticscholar.org/paper/5b19bf6c3f4b25cac96362c98b930cf4b37f6744)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://dreambooth.github.io/)
[![Code](https://img.shields.io/github/stars/rinongal/textual_inversion.svg?style=social&label=Star)](https://github.com/rinongal/textual_inversion)\
Tags: `customization`

+ **Photorealistic Text-to-Image Diffusion Models with Deep Language Understanding** (23 May 2022)\
[NeurIPS 2022] <details><summary>Saharia, Chitwan Chan, William Saxena, Saurabh Li, Lala Whang, Jay Denton, Emily L Ghasemipour, Kamyar Gontijo Lopes, Raphael Karagol Ayan, Burcu Salimans, Tim others</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2205.11487)
[![citation](https://img.shields.io/badge/citation-2844-blue.svg?paper=9695824d7a01fad57ba9c01d7d76a519d78d65e7)](https://www.semanticscholar.org/paper/9695824d7a01fad57ba9c01d7d76a519d78d65e7)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://imagen.research.google/) 


### Datasets


+ **MIMIC-IT: Multi-Modal In-Context Instruction Tuning** (8 Jun 2023)<details><summary>[NeurIPS 2023] Bo Li, Yuanhan Zhang, Liangyu Chen, et al.</summary>Bo Li, Yuanhan Zhang, Liangyu Chen, Jinghao Wang, Fanyi Pu, Jingkang Yang, Chunyuan Li, Ziwei Liu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.05425)
[![citation](https://img.shields.io/badge/citation-78-blue.svg?paper=d47524cd5c3c4b57af2e5a29f6f91c420310f236)](https://www.semanticscholar.org/paper/d47524cd5c3c4b57af2e5a29f6f91c420310f236)
[![Code](https://img.shields.io/github/stars/Luodian/otter.svg?style=social&label=Star)](https://github.com/Luodian/otter)



+ **[LAION-Glyph] GlyphControl: Glyph Conditional Control for Visual Text Generation** (29 May 2023)<details><summary>[NeurIPS 2023] Yukang Yang, Dongnan Gui, Yuhui Yuan, et al.</summary>Yukang Yang, Dongnan Gui, Yuhui Yuan, Weicong Liang, Haisong Ding, Han Hu, Kai Chen</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.18259)
[![citation](https://img.shields.io/badge/citation-12-blue.svg?paper=5fbe4c92791fbecb179c1ab79bba9a59b2e155ba)](https://www.semanticscholar.org/paper/5fbe4c92791fbecb179c1ab79bba9a59b2e155ba)
[![Code](https://img.shields.io/github/stars/AIGText/GlyphControl-release.svg?style=social&label=Star)](https://github.com/AIGText/GlyphControl-release)





+ **[MARIO-10M] TextDiffuser: Diffusion Models as Text Painters** (18 May 2023)<details><summary>[NeurIPS 2023] Jingye Chen, Yupan Huang, Tengchao Lv, et al.</summary>Jingye Chen, Yupan Huang, Tengchao Lv, Lei Cui, Qifeng Chen, Furu Wei</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.14108)
[![citation](https://img.shields.io/badge/citation-12-blue.svg?paper=e779781f1bea273573fc9d3f1a5e874bcff2cd2b)](https://www.semanticscholar.org/paper/e779781f1bea273573fc9d3f1a5e874bcff2cd2b)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://jingyechen.github.io/textdiffuser/)
[![Code](https://img.shields.io/github/stars/microsoft/unilm.svg?style=social&label=Star)](https://github.com/microsoft/unilm)



+ **DataComp: In search of the next generation of multimodal datasets** (27 Apr 2023)<details><summary>[NeurIPS 2023] Samir Yitzhak Gadre, Gabriel Ilharco, Alex Fang, et al.</summary>Samir Yitzhak Gadre, Gabriel Ilharco, Alex Fang, Jonathan Hayase, Georgios Smyrnis, Thao Nguyen, Ryan Marten, Mitchell Wortsman, Dhruba Ghosh, Jieyu Zhang, Eyal Orgad, Rahim Entezari, Giannis Daras, Sarah Pratt, Vivek Ramanujan, Yonatan Bitton, Kalyani Marathe, Stephen Mussmann, Richard Vencu, Mehdi Cherti, Ranjay Krishna, Pang Wei Koh, Olga Saukh, Alexander Ratner, Shuran Song, Hannaneh Hajishirzi, Ali Farhadi, Romain Beaumont, Sewoong Oh, Alex Dimakis, Jenia Jitsev, Yair Carmon, Vaishaal Shankar, Ludwig Schmidt</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.14108)
[![citation](https://img.shields.io/badge/citation-103-blue.svg?paper=f9570989919338079088270a9cf1a7afc8db8093)](https://www.semanticscholar.org/paper/f9570989919338079088270a9cf1a7afc8db8093)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://www.datacomp.ai/)
[![Code](https://img.shields.io/github/stars/mlfoundations/datacomp.svg?style=social&label=Star)](https://github.com/mlfoundations/datacomp)

+ **[LLava-instruct] Visual Instruction Tuning** (17 Apr 2023)<details><summary>[NeurIPS 2023] Haotian Liu, Chunyuan Li, Qingyang Wu, et al.</summary>Haotian Liu, Chunyuan Li, Qingyang Wu, Yong Jae Lee</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.08485)
[![citation](https://img.shields.io/badge/citation-820-blue.svg?paper=a5036f31f0e629dc661f120b8c3b1f374d479ab8)](https://www.semanticscholar.org/paper/a5036f31f0e629dc661f120b8c3b1f374d479ab8)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://llava-vl.github.io//)
[![Code](https://img.shields.io/github/stars/haotian-liu/LLaVA.svg?style=social&label=Star)](https://github.com/haotian-liu/LLaVA)



+ **Multimodal C4: An Open, Billion-scale Corpus of Images Interleaved with Text** (14 Apr 2023)<details><summary>[NeurIPS 2023] Wanrong Zhu, Jack Hessel, Anas Awadalla, et al.</summary>Wanrong Zhu, Jack Hessel, Anas Awadalla, Samir Yitzhak Gadre, Jesse Dodge, Alex Fang, Youngjae Yu, Ludwig Schmidt, William Yang Wang, Yejin Choi</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.06939)
[![citation](https://img.shields.io/badge/citation-64-blue.svg?paper=df958800014d310b6df34ad83d771314d68fbb2d)](https://www.semanticscholar.org/paper/df958800014d310b6df34ad83d771314d68fbb2d)
[![Code](https://img.shields.io/github/stars/allenai/mmc4.svg?style=social&label=Star)](https://github.com/allenai/mmc4)





+ **Language Is Not All You Need: Aligning Perception with Language Models** (27 Feb 2023)<details><summary>[NeurIPS 2023] Shaohan Huang, Li Dong, Wenhui Wang, et al.</summary>Shaohan Huang, Li Dong, Wenhui Wang, Yaru Hao, Saksham Singhal, Shuming Ma, Tengchao Lv, Lei Cui, Owais Khan Mohammed, Barun Patra, Qiang Liu, Kriti Aggarwal, Zewen Chi, Johan Bjorck, Vishrav Chaudhary, Subhojit Som, Xia Song, Furu Wei</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2302.14045)
[![citation](https://img.shields.io/badge/citation-261-blue.svg?paper=fbfef4723d8c8467d7bd523e1d0b703cce0e0f9c)](https://www.semanticscholar.org/paper/fbfef4723d8c8467d7bd523e1d0b703cce0e0f9c)



+ **COYO-700M: Image-Text Pair Dataset** (31 Aug 2022)\
[![Code](https://img.shields.io/github/stars/kakaobrain/coyo-dataset.svg?style=social&label=Star)](https://github.com/kakaobrain/coyo-dataset)


+ **LAION-5B: An open large-scale dataset for training next generation image-text models** (16 Oct 2022)<details><summary>[NeurIPS 2022] Christoph Schuhmann, Romain Beaumont, Richard Vencu, et al. </summary>Christoph Schuhmann, Romain Beaumont, Richard Vencu, Cade Gordon, Ross Wightman, Mehdi Cherti, Theo Coombes, Aarush Katta, Clayton Mullis, Mitchell Wortsman, Patrick Schramowski, Srivatsa Kundurthy, Katherine Crowson, Ludwig Schmidt, Robert Kaczmarczyk, Jenia Jitsev</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2210.08402)
[![citation](https://img.shields.io/badge/citation-1288-blue.svg?paper=e5c8960eb2ec034ffbd353ef39fd1cb541d3c7c9)](https://www.semanticscholar.org/paper/e5c8960eb2ec034ffbd353ef39fd1cb541d3c7c9)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://laion.ai/blog/laion-5b/)




+ **LAION COCO: 600M SYNTHETIC CAPTIONS FROM LAION2B-EN** (15 Sep 2022)<details><summary>Christoph Schuhmann, Andreas Köpf , Theo Coombes, et al.</summary>Christoph Schuhmann, Andreas Köpf , Theo Coombes, Richard Vencu, Benjamin Trom , Romain Beaumont</details>
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://laion.ai/blog/laion-coco/)


+ **[M3W] Flamingo: a Visual Language Model for Few-Shot Learning** (29 Apr 2022)<details><summary>[NeurIPS 2022] Jean-Baptiste Alayrac, Jeff Donahue, Pauline Luc, et al.</summary>Jean-Baptiste Alayrac, Jeff Donahue, Pauline Luc, Antoine Miech, Iain Barr, Yana Hasson, Karel Lenc, Arthur Mensch, Katie Millican, Malcolm Reynolds, Roman Ring, Eliza Rutherford, Serkan Cabi, Tengda Han, Zhitao Gong, Sina Samangooei, Marianne Monteiro, Jacob Menick, Sebastian Borgeaud, Andrew Brock, Aida Nematzadeh, Sahand Sharifzadeh, Mikolaj Binkowski, Ricardo Barreira, Oriol Vinyals, Andrew Zisserman, Karen Simonyan</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2204.14198)
[![citation](https://img.shields.io/badge/citation-1483-blue.svg?paper=26218bdcc3945c7edae7aa2adbfba4cd820a2df3)](https://www.semanticscholar.org/paper/26218bdcc3945c7edae7aa2adbfba4cd820a2df3)


## Video Generation

### 🔅 LLM-based

+ **Compositional 3D-aware Video Generation with LLM Director** (31 Aug 2024)<details><summary>Hanxin Zhu, Tianyu He, Anni Tang, et al.</summary>Hanxin Zhu, Tianyu He, Anni Tang, Junliang Guo, Zhibo Chen, Jiang Bian</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.00558)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://www.microsoft.com/en-us/research/project/compositional-3d-aware-video-generation/)


+ **Anim-Director: A Large Multimodal Model Powered Agent for Controllable Animation Video Generation** (19 Aug 2024)<details><summary>[SIGGRAPH Asia 2024] Yunxin Li, Haoyuan Shi, Baotian Hu, et al.</summary>Yunxin Li, Haoyuan Shi, Baotian Hu, Longyue Wang, Jiashun Zhu, Jinyi Xu, Zhen Zhao, Min Zhang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.09787)
[![Code](https://img.shields.io/github/stars/HITsz-TMG/Anim-Director.svg?style=social&label=Star)](https://github.com/HITsz-TMG/Anim-Director?tab=readme-ov-file)

+ **[BSQ-ViT] Image and Video Tokenization with Binary Spherical Quantization** (11 Jun 2024)\
[Tech Report]Yue Zhao, Yuanjun Xiong, Philipp Krähenbühl\
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.07548v1)  `tokenizer`


+ **DriveDreamer-2: LLM-Enhanced World Models for Diverse Driving Video Generation** (11 Mar 2024)<details><summary>Guosheng Zhao, Xiaofeng Wang, Zheng Zhu, et al.</summary>Guosheng Zhao, Xiaofeng Wang, Zheng Zhu, Xinze Chen, Guan Huang, Xiaoyi Bao, Xingang Wang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.06845)
[![citation](https://img.shields.io/badge/citation-1-blue.svg?paper=b34fb645165da381e27077282d69ff224dd2d5f5)](https://www.semanticscholar.org/paper/DriveDreamer-2%3A-LLM-Enhanced-World-Models-for-Video-Zhao-Wang/b34fb645165da381e27077282d69ff224dd2d5f5)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://drivedreamer2.github.io/)


+ **[Sora] Video generation models as world simulators** (15 Feb 2024)<details><summary>Tim Brooks, Bill Peebles, Connor Holmes, et al.</summary>Tim Brooks and Bill Peebles and Connor Holmes and Will DePue and Yufei Guo and Li Jing and David Schnurr and Joe Taylor and Troy Luhman and Eric Luhman and Clarence Ng and Ricky Wang and Aditya Ramesh</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://openai.com/research/video-generation-models-as-world-simulators)

+ **[LGVI] Towards Language-Driven Video Inpainting via Multimodal Large Language Models** (18 Jan 2024)<details><summary>Jianzong Wu, Xiangtai Li, Chenyang Si, et al.</summary>Jianzong Wu, Xiangtai Li, Chenyang Si, Shangchen Zhou, Jingkang Yang, Jiangning Zhang, Yining Li, Kai Chen, Yunhai Tong, Ziwei Liu, Chen Change Loy</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.10226)
[![citation](https://img.shields.io/badge/citation-3-blue.svg?paper=02d96eb0da4a282831f14923d1a65976952b7177)](https://www.semanticscholar.org/paper/Towards-Language-Driven-Video-Inpainting-via-Large-Wu-Li/02d96eb0da4a282831f14923d1a65976952b7177)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://jianzongwu.github.io/projects/rovi/)

+ **Video-LaVIT: Unified Video-Language Pre-training with Decoupled Visual-Motional Tokenization: Content-Consistent Multi-Scene Video Generation with LLM** (2 Jan 2024)<details><summary>Yang Jin, Zhicheng Sun, Kun Xu, et al.</summary>Yang Jin, Zhicheng Sun, Kun Xu, Kun Xu, Liwei Chen, Hao Jiang, Quzhe Huang, Chengru Song, Yuliang Liu, Di Zhang, Yang Song, Kun Gai, Yadong Mu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.03161)
[![citation](https://img.shields.io/badge/citation-1-blue.svg?paper=c1b5195bc09a2232ec2b69e5a2a6bd39b3162c62)](https://www.semanticscholar.org/paper/c1b5195bc09a2232ec2b69e5a2a6bd39b3162c62)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://video-lavit.github.io/)
`tokenizer`

+ **VideoDrafter: Content-Consistent Multi-Scene Video Generation with LLM** (2 Jan 2024)<details><summary>Fuchen Long, Zhaofan Qiu, Ting Yao, et al.</summary>Fuchen Long, Zhaofan Qiu, Ting Yao, Tao Mei</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.01256)
[![citation](https://img.shields.io/badge/citation-1-blue.svg?paper=fc84fcf269a37ed7ddcb1b0f2d7d1a00f677eaea)](https://www.semanticscholar.org/paper/fc84fcf269a37ed7ddcb1b0f2d7d1a00f677eaea)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://videodrafter.github.io/)

+ **[PRO-Motion] Plan, Posture and Go: Towards Open-World Text-to-Motion Generation** (22 Dec 2023)<details><summary>Jinpeng Liu, Wenxun Dai, Chunyu Wang, et al.</summary>Jinpeng Liu, Wenxun Dai, Chunyu Wang, Yiji Cheng, Yansong Tang, Xin Tong</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.14828)
[![citation](https://img.shields.io/badge/citation-1-blue.svg?paper=4599d5af850da482f591a02a3b17d56e0d358771)](https://www.semanticscholar.org/paper/4599d5af850da482f591a02a3b17d56e0d358771)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://moonsliu.github.io/Pro-Motion/)

+ **VideoPoet: A Large Language Model for Zero-Shot Video Generation** (21 Dec 2023)<details><summary>Dan Kondratyuk, Lijun Yu, Xiuye Gu, et al.</summary>Dan Kondratyuk, Lijun Yu, Xiuye Gu, José Lezama, Jonathan Huang, Rachel Hornung, Hartwig Adam, Hassan Akbari, Yair Alon, Vighnesh Birodkar, Yong Cheng, Ming-Chang Chiu, Josh Dillon, Irfan Essa, Agrim Gupta, Meera Hahn, Anja Hauth, David Hendon, Alonso Martinez, David Minnen, David Ross, Grant Schindler, Mikhail Sirotenko, Kihyuk Sohn, Krishna Somandepalli, Huisheng Wang, Jimmy Yan, Ming-Hsuan Yang, Xuan Yang, Bryan Seybold, Lu Jiang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.14125)
[![citation](https://img.shields.io/badge/citation-18-blue.svg?paper=0c4f46e4dcae5527018e6432fb60cfe8c3354e97)](https://www.semanticscholar.org/paper/0c4f46e4dcae5527018e6432fb60cfe8c3354e97)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://sites.research.google/videopoet/)

+ **FlowZero: Zero-Shot Text-to-Video Synthesis with LLM-Driven Dynamic Scene Syntax** (27 Nov 2023)<details><summary>[arXiv 2023] Yu Lu, Linchao Zhu, Hehe Fan, et al.</summary>Yu Lu, Linchao Zhu, Hehe Fan, Yi Yang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.15813)
[![citation](https://img.shields.io/badge/citation-1-blue.svg?paper=9cdb7e415a96795dc6705e66f3b798238b4dec2c)](https://www.semanticscholar.org/paper/8feb33300c04fffa050e0dca59c3fdcafc920a3b)

+ **InterControl: Generate Human Motion Interactions by Controlling Every Joint** (27 Nov 2023)<details><summary>Zhenzhi Wang, Jingbo Wang, Dahua Lin, et al.</summary>Zhenzhi Wang, Jingbo Wang, Dahua Lin, Bo Dai</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.15864)
[![citation](https://img.shields.io/badge/citation-0-blue.svg?paper=9cdb7e415a96795dc6705e66f3b798238b4dec2c)](https://www.semanticscholar.org/paper/9cdb7e415a96795dc6705e66f3b798238b4dec2c)
[![Code](https://img.shields.io/github/stars/zhenzhiwang/intercontrol.svg?style=social&label=Star)](https://github.com/zhenzhiwang/intercontrol)\
Tags: `human motion generation`
+ **MotionLLM: Multimodal Motion-Language Learning with Large Language Models** (27 May 2024)<details><summary>Qi Wu, Yubo Zhao, Yifan Wang, et al.</summary>Qi Wu, Yubo Zhao, Yifan Wang, Yu-Wing Tai, Chi-Keung Tang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.17013)
[![citation](https://img.shields.io/badge/citation-0-blue.svg?paper=480da1ac2d39b5e036ce786af081366c23f08d1b)](https://www.semanticscholar.org/paper/480da1ac2d39b5e036ce786af081366c23f08d1b)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://knoxzhao.github.io/MotionLLM/)\
Tags: `general human motion generation`
+ **GPT4Motion: Scripting Physical Motions in Text-to-Video Generation via Blender-Oriented GPT Planning** (21 Nov 2023)<details><summary>Jiaxi Lv, Yi Huang, Mingfu Yan, et al.</summary>Jiaxi Lv, Yi Huang, Mingfu Yan, Jiancheng Huang, Jianzhuang Liu, Yifan Liu, Yafei Wen, Xiaoxin Chen, Shifeng Chen</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.12631)
[![citation](https://img.shields.io/badge/citation-0-blue.svg?paper=9cdb7e415a96795dc6705e66f3b798238b4dec2c)](https://www.semanticscholar.org/paper/9cdb7e415a96795dc6705e66f3b798238b4dec2c)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://gpt4motion.github.io/)

+ **[MAGVIT-v2] Language Model Beats Diffusion -- Tokenizer is Key to Visual Generation** (9 Oct 2023)<details><summary>Lijun Yu, José Lezama, Nitesh B. Gundavarapu, et al.</summary>Lijun Yu, José Lezama, Nitesh B. Gundavarapu, Luca Versari, Kihyuk Sohn, David Minnen, Yong Cheng, Agrim Gupta, Xiuye Gu, Alexander G. Hauptmann, Boqing Gong, Ming-Hsuan Yang, Irfan Essa, David A. Ross, Lu Jiang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.05737)
[![citation](https://img.shields.io/badge/citation-15-blue.svg?paper=985f0c89c5a607742ec43c1fdc2cbfe54541cbad)](https://www.semanticscholar.org/paper/985f0c89c5a607742ec43c1fdc2cbfe54541cbad)
`tokenizer`

+ **[LVD] LLM-grounded Video Diffusion Models** (29 Sep 2023)<details><summary>Long Lian, Baifeng Shi, Adam Yala, et al.</summary>Long Lian, Baifeng Shi, Adam Yala, Trevor Darrell, Boyi Li</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.17444)
[![citation](https://img.shields.io/badge/citation-10-blue.svg?paper=87bf66eb6d22df17f70170a0e575b4f12c4813ef)](https://www.semanticscholar.org/paper/87bf66eb6d22df17f70170a0e575b4f12c4813ef)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://llm-grounded-video-diffusion.github.io/)
[![Code](https://img.shields.io/github/stars/TonyLianLong/LLM-groundedVideoDiffusion.svg?style=social&label=Star)](https://github.com/TonyLianLong/LLM-groundedVideoDiffusion)

+ **VideoDirectorGPT: Consistent Multi-scene Video Generation via LLM-Guided Planning** (26 Sep 2023)<details><summary>[arXiv 2023] Han Lin, Abhay Zala, Jaemin Cho, et al.</summary>Han Lin, Abhay Zala, Jaemin Cho, Mohit Bansal</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.15091)
[![citation](https://img.shields.io/badge/citation-12-blue.svg?paper=16753e0317730e8c1b297338300a8c6163dd06f2)](https://www.semanticscholar.org/paper/16753e0317730e8c1b297338300a8c6163dd06f2)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://videodirectorgpt.github.io/)
[![Code](https://img.shields.io/github/stars/HL-hanlin/VideoDirectorGPT.svg?style=social&label=Star)](https://github.com/HL-hanlin/VideoDirectorGPT)

+ **Free-Bloom: Zero-Shot Text-to-Video Generator with LLM Director and LDM Animator** (25 Sep 2023)<details><summary>[NIPS 2023] Hanzhuo Huang, Yufan Feng, Cheng Shi, et al.</summary>Hanzhuo Huang, Yufan Feng, Cheng Shi, Lan Xu, Jingyi Yu, Sibei Yang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.14494)
[![citation](https://img.shields.io/badge/citation-24-blue.svg?paper=120aca3e415b6641a0b0cd20695ab85ed7789612)](https://www.semanticscholar.org/paper/120aca3e415b6641a0b0cd20695ab85ed7789612)
[![Code](https://img.shields.io/github/stars/SooLab/Free-Bloom.svg?style=social&label=Star)](https://github.com/SooLab/Free-Bloom)

+ **[Dysen-VDM] Empowering Dynamics-aware Text-to-Video Diffusion with Large Language Models** (26 Aug 2023)<details><summary>[CVPR 2024] Hao Fei, Shengqiong Wu, Wei Ji, et al.</summary>Hao Fei, Shengqiong Wu, Wei Ji, Hanwang Zhang, Tat-Seng Chua</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.13812)
[![citation](https://img.shields.io/badge/citation-6-blue.svg?paper=d0a7f7fe31e0e0c42b471b4c47a313bd8c8e5206)](https://www.semanticscholar.org/paper/d0a7f7fe31e0e0c42b471b4c47a313bd8c8e5206)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](http://haofei.vip/Dysen-VDM/)
[![Code](https://img.shields.io/github/stars/scofield7419/Dysen.svg?style=social&label=Star)](https://github.com/scofield7419/Dysen)

+ **[DirecT2V] Large Language Models are Frame-level Directors for Zero-shot Text-to-Video Generation** (23 May 2023)<details><summary>[arXiv 2023] Susung Hong, Junyoung Seo, Sunghwan Hong, et al.</summary>Susung Hong, Junyoung Seo, Sunghwan Hong, Heeseong Shin, Seungryong Kim</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.14330)
[![citation](https://img.shields.io/badge/citation-15-blue.svg?paper=b1750d2a6e3480e690999916a86c8b3876577b39)](https://www.semanticscholar.org/paper/b1750d2a6e3480e690999916a86c8b3876577b39)
[![Code](https://img.shields.io/github/stars/KU-CVLAB/DirecT2V.svg?style=social&label=Star)](https://github.com/KU-CVLAB/DirecT2V)

+ **Text2Motion: From Natural Language Instructions to Feasible Plans** (21 Mar 2023)<details><summary>[Autonomous Robots 2023] Kevin Lin, Christopher Agia, Toki Migimatsu, et al.</summary>Kevin Lin, Christopher Agia, Toki Migimatsu, Marco Pavone, Jeannette Bohg</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.12153)
[![citation](https://img.shields.io/badge/citation-110-blue.svg?paper=8f2d4758e6d525509ae36bb30224dc9259027e6b)](https://www.semanticscholar.org/paper/8f2d4758e6d525509ae36bb30224dc9259027e6b)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://sites.google.com/stanford.edu/text2motion)
[![Code](https://img.shields.io/github/stars/KU-CVLAB/DirecT2V.svg?style=social&label=Star)](https://github.com/KU-CVLAB/DirecT2V)

### Non-LLM-based


+ **OSV: One Step is Enough for High-Quality Image to Video Generation** (17 Sep 2024)<details><summary>Xiaofeng Mao, Zhengkai Jiang, Fu-Yun Wang, et al.</summary>Xiaofeng Mao, Zhengkai Jiang, Fu-Yun Wang, Wenbing Zhu, Jiangning Zhang, Hao Chen, Mingmin Chi, Yabiao Wang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://www.arxiv.org/abs/2409.11367)

+ **[PAB] Real-Time Video Generation with Pyramid Attention Broadcast** (26 Jun 2024)<details><summary>Xuanlei Zhao, Xiaolong Jin, Kai Wang, et al.</summary>Xuanlei Zhao,  Xiaolong Jin,  Kai Wang,  Yang You</details>
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://oahzxl.github.io/PAB/)
[![Code](https://img.shields.io/github/stars/NUS-HPC-AI-Lab/OpenDiT.svg?style=social&label=Star)](https://github.com/NUS-HPC-AI-Lab/OpenDiT)



+ **Video-Infinity: Distributed Long Video Generation** (24 Jun 2024)<details><summary>Zhenxiong Tan, Xingyi Yang, Songhua Liu, et al.</summary>Zhenxiong Tan, Xingyi Yang, Songhua Liu, Xinchao Wang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.16260)




+ **Pandora: Towards General World Model with Natural Language Actions and Video** (12 Jun 2024)<details><summary>Jiannan Xiang, Guangyi Liu, Yi Gu, et al.</summary>Jiannan Xiang, Guangyi Liu, Yi Gu, Qiyue Gao, Yuting Ning, Yuheng Zha, Zeyu Feng, Tianhua Tao, Shibo Hao, Yemin Shi, Zhengzhong Liu, Eric P. Xing, Zhiting Hu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.09455)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://world-model.maitrix.org/)
[![Code](https://img.shields.io/github/stars/yhZhai/mcm.svg?style=social&label=Star)](https://github.com/maitrix-org/Pandora)



+ **Text-Animator: Controllable Visual Text Video Generation** (25 Jun 2024)<details><summary>Lin Liu, Quande Liu, Shengju Qian, et al.</summary>Lin Liu, Quande Liu, Shengju Qian, Yuan Zhou, Wengang Zhou, Houqiang Li, Lingxi Xie, Qi Tian</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.09455)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://laulampaul.github.io/text-animator.html)


+ **MotionBooth: Motion-Aware Customized Text-to-Video Generation** (25 Jun 2024)<details><summary>Jianzong Wu, Xiangtai Li, Yanhong Zeng, et al.</summary>Jianzong Wu, Xiangtai Li, Yanhong Zeng, Jiangning Zhang, Qianyu Zhou, Yining Li, Yunhai Tong, Kai Chen</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.17758v1)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://jianzongwu.github.io/projects/motionbooth/)
[![citation](https://img.shields.io/badge/citation-0-blue.svg?paper=7178bbc5e8d2d9b11c890c60486ba2cc2b79b784)](https://www.semanticscholar.org/paper/MotionBooth%3A-Motion-Aware-Customized-Text-to-Video-Wu-Li/7178bbc5e8d2d9b11c890c60486ba2cc2b79b784)

+ **FreeTraj: Tuning-Free Trajectory Control in Video Diffusion Models** (24 Jun 2024)<details><summary>Haonan Qiu, Zhaoxi Chen, Zhouxia Wang, et al.</summary>Haonan Qiu, Zhaoxi Chen, Zhouxia Wang, Yingqing He, Menghan Xia, Ziwei Liu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.16863)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](http://haonanqiu.com/projects/FreeTraj.html)
[![citation](https://img.shields.io/badge/citation-0-blue.svg?paper=1868d2c2f56a92044908a789049fdd44094fc8f2)](https://www.semanticscholar.org/paper/FreeTraj%3A-Tuning-Free-Trajectory-Control-in-Video-Qiu-Chen/1868d2c2f56a92044908a789049fdd44094fc8f2)
[![Code](https://img.shields.io/github/stars/arthur-qiu/FreeTraj.svg?style=social&label=Star)](https://github.com/arthur-qiu/FreeTraj)


+ **Identifying and Solving Conditional Image Leakage in Image-to-Video Diffusion Model** (22 Jun 2024)<details><summary>Min Zhao, Hongzhou Zhu, Chendong Xiang, et al.</summary>Min Zhao, Hongzhou Zhu, Chendong Xiang, Kaiwen Zheng, Chongxuan Li, Jun Zhu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.15735v1)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://cond-image-leak.github.io/)
[![citation](https://img.shields.io/badge/citation-0-blue.svg?paper=ebf4f746d24d79d61c070f8c354b3371f461aafb)](https://www.semanticscholar.org/paper/Identifying-and-Solving-Conditional-Image-Leakage-Zhao-Zhu/ebf4f746d24d79d61c070f8c354b3371f461aafb)
[![Code](https://img.shields.io/github/stars/thu-ml/cond-image-leakage.svg?style=social&label=Star)](https://github.com/thu-ml/cond-image-leakage/)


+ **Image Conductor: Precision Control for Interactive Video Synthesis** (21 Jun 2024)<details><summary>Yaowei Li, Xintao Wang, Zhaoyang Zhang, et al.</summary>Yaowei Li, Xintao Wang, Zhaoyang Zhang, Zhouxia Wang, Ziyang Yuan, Liangbin Xie, Yuexian Zou, Ying Shan</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.15339)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://cond-image-leak.github.io/)
[![citation](https://img.shields.io/badge/citation-0-blue.svg?paper=b0bd64273dc8075db530fd696ee7eecb179bb908)](https://www.semanticscholar.org/paper/Image-Conductor%3A-Precision-Control-for-Interactive-Li-Wang/b0bd64273dc8075db530fd696ee7eecb179bb908)
[![Code](https://img.shields.io/github/stars/liyaowei-stu/ImageConductor.svg?style=social&label=Star)](https://github.com/liyaowei-stu/ImageConductor)


+ **VIDEOSCORE: Building Automatic Metrics to Simulate Fine-grained Human Feedback for Video Generation** (21 Jun 2024)<details><summary>Xuan He, Dongfu Jiang, Ge Zhang, et al.</summary>Xuan He, Dongfu Jiang, Ge Zhang, Max Ku, Achint Soni, Sherman Siu, Haonan Chen, Abhranil Chandra, Ziyan Jiang, Aaran Arulraj, Kai Wang, Quy Duc Do, Yuansheng Ni, Bohan Lyu, Yaswanth Narsupalli, Rongqi Fan, Zhiheng Lyu, Yuchen Lin, Wenhu Chen</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.15252)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://tiger-ai-lab.github.io/VideoScore/)
[![citation](https://img.shields.io/badge/citation-0-blue.svg?paper=1680eedc706ef081c0b103457bb52c071ab924b8)](https://www.semanticscholar.org/paper/VideoScore%3A-Building-Automatic-Metrics-to-Simulate-He-Jiang/1680eedc706ef081c0b103457bb52c071ab924b8)
[![Code](https://img.shields.io/github/stars/TIGER-AI-Lab/VideoScore/.svg?style=social&label=Star)](https://github.com/TIGER-AI-Lab/VideoScore/)


+ **Dreamitate: Real-World Visuomotor Policy Learning via Video Generation** (24 Jun 2024)<details><summary>Junbang Liang, Ruoshi Liu, Ege Ozguroglu, et al.</summary>Junbang Liang, Ruoshi Liu, Ege Ozguroglu, Sruthi Sudhakar, Achal Dave, Pavel Tokmakov, Shuran Song, Carl Vondrick</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.16862)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://dreamitate.cs.columbia.edu/)
[![citation](https://img.shields.io/badge/citation-0-blue.svg?paper=b0ac4f62f55bcf0427008e18f1b4b5bf7ee43df2)](https://www.semanticscholar.org/paper/Dreamitate%3A-Real-World-Visuomotor-Policy-Learning-Liang-Liu/b0ac4f62f55bcf0427008e18f1b4b5bf7ee43df2)





+ **ChronoMagic-Bench: A Benchmark for Metamorphic Evaluation of Text-to-Time-lapse Video Generation** (26 Jun 2024)<details><summary>Shenghai Yuan, Jinfa Huang, Yongqi Xu, et al.</summary>Shenghai Yuan, Jinfa Huang, Yongqi Xu, Yaoyang Liu, Shaofeng Zhang, Yujun Shi, Ruijie Zhu, Xinhua Cheng, Jiebo Luo, Li Yuan</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.18522v1)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://pku-yuangroup.github.io/ChronoMagic-Bench/)
[![Code](https://img.shields.io/github/stars/PKU-YuanGroup/ChronoMagic-Bench.svg?style=social&label=Star)](https://github.com/PKU-YuanGroup/ChronoMagic-Bench)

+ **[MCM] Motion Consistency Model: Accelerating Video Diffusion with Disentangled Motion-Appearance Distillation** (11 Jun 2024)<details><summary>Yuanhao Zhai, Kevin Lin, Zhengyuan Yang, et al.</summary>Yuanhao Zhai, Kevin Lin, Zhengyuan Yang, Linjie Li, Jianfeng Wang, Chung-Ching Lin, David Doermann, Junsong Yuan, Lijuan Wang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.06890v1)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://yhzhai.github.io/mcm/)
[![Code](https://img.shields.io/github/stars/yhZhai/mcm.svg?style=social&label=Star)](https://github.com/yhZhai/mcm)


+ **Searching Priors Makes Text-to-Video Synthesis Better** (5 Jun 2024)<details><summary>Haoran Cheng, Liang Peng, Linxuan Xia, et al.</summary>Haoran Cheng, Liang Peng, Linxuan Xia, Yuepeng Hu, Hengjia Li, Qinglin Lu, Xiaofei He, Boxi Wu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.03215)
[![citation](https://img.shields.io/badge/citation-0-blue.svg?paper=0dd0e0bdff37973e102a042f82cd882b890476cc)](https://www.semanticscholar.org/paper/Searching-Priors-Makes-Text-to-Video-Synthesis-Cheng-Peng/0dd0e0bdff37973e102a042f82cd882b890476cc)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://hrcheng98.github.io/Search_T2V/)

+ **ZeroSmooth: Training-free Diffuser Adaptation for High Frame Rate Video Generation** (3 Jun 2024)<details><summary>Shaoshu Yang, Yong Zhang, Xiaodong Cun, et al.</summary>Shaoshu Yang, Yong Zhang, Xiaodong Cun, Ying Shan, Ran He</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.00908v1)
[![citation](https://img.shields.io/badge/citation-0-blue.svg?paper=2917706886df4e3bf57acd0b41bd4e396be77506)](https://www.semanticscholar.org/paper/ZeroSmooth%3A-Training-free-Diffuser-Adaptation-for-Yang-Zhang/2917706886df4e3bf57acd0b41bd4e396be77506#cited-papers)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://ssyang2020.github.io/zerosmooth.github.io/)

+ **CV-VAE: A Compatible Video VAE for Latent Generative Video Models** (29 May 2024)<details><summary>Jiaqi Xu, Xinyi Zou, Kunzhe Huang, et al.</summary>Jiaqi Xu, Xinyi Zou, Kunzhe Huang, Yunkuo Chen, Bo Liu, MengLi Cheng, Xing Shi, Jun Huang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.18991)
[![citation](https://img.shields.io/badge/citation-0-blue.svg?paper=40122a222374504fda4997ef6204dcdcee1678da)](https://www.semanticscholar.org/paper/EasyAnimate%3A-A-High-Performance-Long-Video-Method-Xu-Zou/40122a222374504fda4997ef6204dcdcee1678da)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://ssyang2020.github.io/zerosmooth.github.io/)
[![Code](https://img.shields.io/github/stars/aigc-apps/EasyAnimate.svg?style=social&label=Star)](https://github.com/aigc-apps/EasyAnimate)


+ **EasyAnimate: A High-Performance Long Video Generation Method based on Transformer Architecture** (30 May 2024)<details><summary>Sijie Zhao, Yong Zhang, Xiaodong Cun, et al.</summary>Sijie Zhao, Yong Zhang, Xiaodong Cun, Shaoshu Yang, Muyao Niu, Xiaoyu Li, Wenbo Hu, Ying Shan</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.20279)
[![citation](https://img.shields.io/badge/citation-0-blue.svg?paper=70569a07d841f86faf8914aea435a1696f911a32)](https://www.semanticscholar.org/paper/CV-VAE%3A-A-Compatible-Video-VAE-for-Latent-Video-Zhao-Zhang/70569a07d841f86faf8914aea435a1696f911a32)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://ailab-cvc.github.io/cvvae/index.html)
[![Code](https://img.shields.io/github/stars/AILab-CVC/CV-VAE.svg?style=social&label=Star)](https://github.com/AILab-CVC/CV-VAE)

+ **[MOFT] Video Diffusion Models are Training-free Motion Interpreter and Controller** (23 Mar 2024)<details><summary>Zeqi Xiao, Yifan Zhou, Shuai Yang, et al.</summary>Zeqi Xiao, Yifan Zhou, Shuai Yang, Xingang Pan</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.14864)
[![citation](https://img.shields.io/badge/citation-0-blue.svg?paper=4f3e62c0fea3dc43f345e775192c972760b9d113)](https://www.semanticscholar.org/paper/Video-Diffusion-Models-are-Training-free-Motion-and-Xiao-Zhou/4f3e62c0fea3dc43f345e775192c972760b9d113)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://xizaoqu.github.io/moft/)

+ **StreamingT2V: Consistent, Dynamic, and Extendable Long Video Generation from Text** (21 Mar 2024)<details><summary>Roberto Henschel, Levon Khachatryan, Daniil Hayrapetyan, et al.</summary>Roberto Henschel, Levon Khachatryan, Daniil Hayrapetyan, Hayk Poghosyan, Vahram Tadevosyan, Zhangyang Wang, Shant Navasardyan, Humphrey Shi</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.14773)
[![citation](https://img.shields.io/badge/citation-0-blue.svg?paper=21a77ed349c8621d0a0ef8407eb744e3de3b13c5)](https://www.semanticscholar.org/paper/StreamingT2V%3A-Consistent%2C-Dynamic%2C-and-Extendable-Henschel-Khachatryan/21a77ed349c8621d0a0ef8407eb744e3de3b13c5)
[![Code](https://img.shields.io/github/stars/Vchitect/VBench.svg?style=social&label=Star)](https://github.com/Picsart-AI-Research/StreamingT2V)

+ **Snap Video: Scaled Spatiotemporal Transformers for Text-to-Video Synthesis** (22 Feb 2024)<details><summary>Willi Menapace, Aliaksandr Siarohin, Ivan Skorokhodov, et al.</summary>Willi Menapace, Aliaksandr Siarohin, Ivan Skorokhodov, Ekaterina Deyneka, Tsai-Shien Chen, Anil Kag, Yuwei Fang, Aleksei Stoliar, Elisa Ricci, Jian Ren, Sergey Tulyakov</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.14797)
[![citation](https://img.shields.io/badge/citation-7-blue.svg?paper=97cb2eb0d0517e34bf4202f0593600bb6fa043cd)](https://www.semanticscholar.org/paper/Snap-Video%3A-Scaled-Spatiotemporal-Transformers-for-Menapace-Siarohin/97cb2eb0d0517e34bf4202f0593600bb6fa043cd)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://snap-research.github.io/snapvideo/)

+ **VideoCrafter2: Overcoming Data Limitations for High-Quality Video Diffusion Models** (17 Jan 2024)<details><summary>Haoxin Chen, Yong Zhang, Xiaodong Cun, et al.</summary>Haoxin Chen, Yong Zhang, Xiaodong Cun, Menghan Xia, Xintao Wang, Chao Weng, Ying Shan</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.09047)
[![citation](https://img.shields.io/badge/citation-7-blue.svg?paper=492bc8339d8aac442c4ec13f8c1d59e980a3af2f)](https://www.semanticscholar.org/paper/VideoCrafter2%3A-Overcoming-Data-Limitations-for-Chen-Zhang/492bc8339d8aac442c4ec13f8c1d59e980a3af2f)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://ailab-cvc.github.io/videocrafter2/)
[![Code](https://img.shields.io/github/stars/AILab-CVC/VideoCrafter.svg?style=social&label=Star)](https://github.com/AILab-CVC/VideoCrafter)

+ **VBench: Comprehensive Benchmark Suite for Video Generative Models** (29 Nov 2023)<details><summary>Ziqi Huang, Yinan He, Jiashuo Yu, et al.</summary>Ziqi Huang, Yinan He, Jiashuo Yu, Fan Zhang, Chenyang Si, Yuming Jiang, Yuanhan Zhang, Tianxing Wu, Qingyang Jin, Nattapol Chanpaisit, Yaohui Wang, Xinyuan Chen, Limin Wang, Dahua Lin, Yu Qiao, Ziwei Liu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.17982)
[![citation](https://img.shields.io/badge/citation-7-blue.svg?paper=4e9a8141da2a8c603722b07d096109207f8e0b66)](https://www.semanticscholar.org/paper/4e9a8141da2a8c603722b07d096109207f8e0b66)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://vchitect.github.io/VBench-project/)
[![Code](https://img.shields.io/github/stars/Vchitect/VBench.svg?style=social&label=Star)](https://github.com/Vchitect/VBench)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/Vchitect/VBench_Leaderboard)

+ **Stable Video Diffusion: Scaling Latent Video Diffusion Models to Large Datasets** (25 Nov 2023)<details><summary>Andreas Blattmann, Tim Dockhorn, Sumith Kulal, et al.</summary>Andreas Blattmann, Tim Dockhorn, Sumith Kulal, Daniel Mendelevitch, Maciej Kilian, Dominik Lorenz, Yam Levi, Zion English, Vikram Voleti, Adam Letts, Varun Jampani, Robin Rombach</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.15127)
[![citation](https://img.shields.io/badge/citation-51-blue.svg?paper=1206b05eae5a06ba662ae79fb291b50e359c4f42)](https://www.semanticscholar.org/paper/1206b05eae5a06ba662ae79fb291b50e359c4f42)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://stability.ai/research/stable-video-diffusion-scaling-latent-video-diffusion-models-to-large-datasets)
[![Code](https://img.shields.io/github/stars/Stability-AI/generative-models.svg?style=social&label=Star)](https://github.com/Stability-AI/generative-models)

+ **VideoCrafter1: Open Diffusion Models for High-Quality Video Generation** (30 Oct 2023)<details><summary>Haoxin Chen, Menghan Xia, Yingqing He, et al.</summary>Haoxin Chen, Menghan Xia, Yingqing He, Yong Zhang, Xiaodong Cun, Shaoshu Yang, Jinbo Xing, Yaofang Liu, Qifeng Chen, Xintao Wang, Chao Weng, Ying Shan</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.19512)
[![citation](https://img.shields.io/badge/citation-38-blue.svg?paper=1891c3756f870d902a0b793a1dcd5cc34c778612)](https://www.semanticscholar.org/paper/1891c3756f870d902a0b793a1dcd5cc34c778612)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://ailab-cvc.github.io/videocrafter/)
[![Code](https://img.shields.io/github/stars/AILab-CVC/VideoCrafter.svg?style=social&label=Star)](https://github.com/AILab-CVC/VideoCrafter)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/VideoCrafter/VideoCrafter)

+ **DynamiCrafter: Animating Open-domain Images with Video Diffusion Priors** (18 Oct 2023)<details><summary>Jinbo Xing, Menghan Xia, Yong Zhang, et al.</summary>Jinbo Xing, Menghan Xia, Yong Zhang, Haoxin Chen, Wangbo Yu, Hanyuan Liu, Xintao Wang, Tien-Tsin Wong, Ying Shan</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.12190)
[![citation](https://img.shields.io/badge/citation-42-blue.svg?paper=083bab4a967c2221d9f4da9110fe37d8ca679078)](https://www.semanticscholar.org/paper/DynamiCrafter%3A-Animating-Open-domain-Images-with-Xing-Xia/083bab4a967c2221d9f4da9110fe37d8ca679078)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://doubiiu.github.io/projects/DynamiCrafter/)
[![Code](https://img.shields.io/github/stars/Doubiiu/DynamiCrafter.svg?style=social&label=Star)](https://github.com/Doubiiu/DynamiCrafter)

+ **FreeNoise: Tuning-Free Longer Video Diffusion via Noise Rescheduling** (23 Oct 2023)<details><summary>Haonan Qiu, Menghan Xia, Yong Zhang, et al.</summary>Haonan Qiu, Menghan Xia, Yong Zhang, Yingqing He, Xintao Wang, Ying Shan, Ziwei Liu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.15169)
[![citation](https://img.shields.io/badge/citation-7-blue.svg?paper=d831988859f0c077b38094446d8585a8340af223)](https://www.semanticscholar.org/paper/d831988859f0c077b38094446d8585a8340af223)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](http://haonanqiu.com/projects/FreeNoise.html)
[![Code](https://img.shields.io/github/stars/arthur-qiu/LongerCrafter.svg?style=social&label=Star)](https://github.com/arthur-qiu/LongerCrafter)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/MoonQiu/LongerCrafter)

+ **Animate-A-Story: Storytelling with Retrieval-Augmented Video Generation** (13 Jul 2023)<details><summary>Yingqing He, Menghan Xia, Haoxin Chen, et al.</summary>Yingqing He, Menghan Xia, Haoxin Chen, Xiaodong Cun, Yuan Gong, Jinbo Xing, Yong Zhang, Xintao Wang, Chao Weng, Ying Shan, Qifeng Chen</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2307.06940)
[![citation](https://img.shields.io/badge/citation-18-blue.svg?paper=77040969110fab39a55699cb06f9edf68789445a)](https://www.semanticscholar.org/paper/77040969110fab39a55699cb06f9edf68789445a)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://ailab-cvc.github.io/Animate-A-Story/)
[![Code](https://img.shields.io/github/stars/AILab-CVC/Animate-A-Story.svg?style=social&label=Star)](https://github.com/AILab-CVC/Animate-A-Story)

+ **Make-Your-Video: Customized Video Generation Using Textual and Structural Guidance** (1 Jun 2023)<details><summary>Jinbo Xing, Menghan Xia, Yuxin Liu, et al.</summary>Jinbo Xing, Menghan Xia, Yuxin Liu, Yuechen Zhang, Yong Zhang, Yingqing He, Hanyuan Liu, Haoxin Chen, Xiaodong Cun, Xintao Wang, Ying Shan, Tien-Tsin Wong</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.00943)
[![citation](https://img.shields.io/badge/citation-31-blue.svg?paper=52b10ae66d025e99fbb602935e155f97f4f0696f)](https://www.semanticscholar.org/paper/52b10ae66d025e99fbb602935e155f97f4f0696f)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://doubiiu.github.io/projects/Make-Your-Video/)
[![Code](https://img.shields.io/github/stars/AILab-CVC/Make-Your-Video.svg?style=social&label=Star)](https://github.com/AILab-CVC/Make-Your-Video)

+ **Follow Your Pose: Pose-Guided Text-to-Video Generation using Pose-Free Videos** (3 Apr 2023)<details><summary>Yue Ma, Yingqing He, Xiaodong Cun, et al.</summary>Yue Ma, Yingqing He, Xiaodong Cun, Xintao Wang, Siran Chen, Ying Shan, Xiu Li, Qifeng Chen</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.01186)
[![citation](https://img.shields.io/badge/citation-53-blue.svg?paper=ee73edebd42626d9c2d91e35fd2ed3cdb0fb26d0)](https://www.semanticscholar.org/paper/ee73edebd42626d9c2d91e35fd2ed3cdb0fb26d0)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://follow-your-pose.github.io/)
[![Code](https://img.shields.io/github/stars/mayuelala/FollowYourPose.svg?style=social&label=Star)](https://github.com/mayuelala/FollowYourPose)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/YueMafighting/FollowYourPose)

+ **Real-time Controllable Denoising for Image and Video** (29 Mar 2023)<details><summary>[CVPR 2023] Zhaoyang Zhang, Yitong Jiang, Wenqi Shao, et al.</summary>Zhaoyang Zhang, Yitong Jiang, Wenqi Shao, Xiaogang Wang, Ping Luo, Kaimo Lin, Jinwei Gu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.16425)
[![citation](https://img.shields.io/badge/citation-108-blue.svg?paper=3f3746c3c64212e97c877bd3d862b578fa24632c)](https://www.semanticscholar.org/paper/Real-Time-Controllable-Denoising-for-Image-and-Zhang-Jiang/3f3746c3c64212e97c877bd3d862b578fa24632c)

+ **VideoFusion: Decomposed Diffusion Models for High-Quality Video Generation** (15 Mar 2023)<details><summary>Zhengxiong Luo, Dayou Chen, Yingya Zhang, et al.</summary>Zhengxiong Luo, Dayou Chen, Yingya Zhang, Yan Huang, Liang Wang, Yujun Shen, Deli Zhao, Jingren Zhou, Tieniu Tan</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.08320)
[![citation](https://img.shields.io/badge/citation-108-blue.svg?paper=26c6090b7e7ba4513f82aa28d41360c60770c618)](https://www.semanticscholar.org/paper/26c6090b7e7ba4513f82aa28d41360c60770c618)


### Datasets

+ **InternVid: A Large-scale Video-Text Dataset for Multimodal Understanding and Generation** (13 Jul 2023)<details><summary>[ICLR 2024 Spotlight] Yi Wang, Yinan He, Yizhuo Li, et al.</summary>Yi Wang, Yinan He, Yizhuo Li, Kunchang Li, Jiashuo Yu, Xin Ma, Xinhao Li, Guo Chen, Xinyuan Chen, Yaohui Wang, Conghui He, Ping Luo, Ziwei Liu, Yali Wang, Limin Wang, Yu Qiao</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2307.06942)
[![citation](https://img.shields.io/badge/citation-36-blue.svg?paper=369b449415d50387fba048bbd4d26ee890df84b5)](https://www.semanticscholar.org/paper/369b449415d50387fba048bbd4d26ee890df84b5)
[![Code](https://img.shields.io/github/stars/OpenGVLab/InternVideo.svg?style=social&label=Star)](https://github.com/OpenGVLab/InternVideo)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/datasets/OpenGVLab/InternVid)

+ **[HD-VG-130M] VideoFactory: Swap Attention in Spatiotemporal Diffusions for Text-to-Video Generation** (18 May 2023)<details><summary>Wenjing Wang, Huan Yang, Zixi Tuo, et al.</summary>Wenjing Wang, Huan Yang, Zixi Tuo, Huiguo He, Junchen Zhu, Jianlong Fu, Jiaying Liu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.10874)
[![citation](https://img.shields.io/badge/citation-43-blue.svg?paper=50bbf2c11984d18aa14f964a4909ac25f07e50ea)](https://www.semanticscholar.org/paper/50bbf2c11984d18aa14f964a4909ac25f07e50ea)
[![Code](https://img.shields.io/github/stars/OpenGVLab/InternVideo.svg?style=social&label=Star)](https://github.com/daooshee/HD-VG-130M?tab=readme-ov-file)

+ **[VideoCC3M] Learning Audio-Video Modalities from Image Captions** (18 May 2023)<details><summary>[ECCV 2022] Arsha Nagrani, Paul Hongsuck Seo, Bryan Seybold, et al.</summary>Arsha Nagrani, Paul Hongsuck Seo, Bryan Seybold, Anja Hauth, Santiago Manen, Chen Sun, Cordelia Schmid</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2204.00679)
[![citation](https://img.shields.io/badge/citation-48-blue.svg?paper=aa1b722485106c84e52c5e35b2d4b2f8c7fb3135)](https://www.semanticscholar.org/paper/aa1b722485106c84e52c5e35b2d4b2f8c7fb3135)
[![Code](https://img.shields.io/github/stars/OpenGVLab/InternVideo.svg?style=social&label=Star)](https://github.com/google-research-datasets/videoCC-data)

+ **CelebV-Text: A Large-Scale Facial Text-Video Dataset** (26 Mar 2023)<details><summary>[CVPR 2023] Jianhui Yu, Hao Zhu, Liming Jiang, et al.</summary>Jianhui Yu, Hao Zhu, Liming Jiang, Chen Change Loy, Weidong Cai, Wayne Wu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.14717)
[![citation](https://img.shields.io/badge/citation-11-blue.svg?paper=484d2194ce8459bfa9da906e556f63812c6ca999)](https://www.semanticscholar.org/paper/484d2194ce8459bfa9da906e556f63812c6ca999)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://celebv-text.github.io/)
[![Code](https://img.shields.io/github/stars/CelebV-Text/CelebV-Text.svg?style=social&label=Star)](https://github.com/CelebV-Text/CelebV-Text)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://www.youtube.com/watch?v=0TS1hQwjNWw)


## 3D Generation

### 🔅 LLM-based
+ **SceneCraft: An LLM Agent for Synthesizing 3D Scene as Blender Code** (2 Mar 2024)<details><summary>Ziniu Hu, Ahmet Iscen, Aashi Jain, et al. </summary>Ziniu Hu, Ahmet Iscen, Aashi Jain, Thomas Kipf, Yisong Yue, David A. Ross, Cordelia Schmid, Alireza Fathi</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.01248v1)


+ **MotionScript: Natural Language Descriptions for Expressive 3D Human Motions** (19 Dec 2023)<details><summary>Payam Jome Yazdian, Eric Liu, Li Cheng, et al. </summary>Payam Jome Yazdian, Eric Liu, Li Cheng, Angelica Lim</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.12634)
[![citation](https://img.shields.io/badge/citation-0-blue.svg?paper=816792e66f463be2aa1888e4ecb51f8fb2b4dd79)](https://www.semanticscholar.org/paper/816792e66f463be2aa1888e4ecb51f8fb2b4dd79)

+ **HOLODECK: Language Guided Generation of 3D Embodied AI Environments** (19 Dec 2023)<details><summary>[CVPR 2024]Yue Yang, Fan-Yun Sun, Luca Weihs, et al. </summary>Yue Yang, Fan-Yun Sun, Luca Weihs, Eli VanderBilt, Alvaro Herrasti, Winson Han, Jiajun Wu, Nick Haber, Ranjay Krishna, Lingjie Liu, Chris Callison-Burch, Mark Yatskar, Aniruddha Kembhavi, Christopher Clark</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.09067)
[![citation](https://img.shields.io/badge/citation-2-blue.svg?paper=1dbc2cdcae3e17c3d721d12a5a2d98ced727681a)](https://www.semanticscholar.org/paper/1dbc2cdcae3e17c3d721d12a5a2d98ced727681a)
[![Code](https://img.shields.io/github/stars/allenai/Holodeck.svg?style=social&label=Star)](https://github.com/allenai/Holodeck)

+ **PoseGPT: Chatting about 3D Human Pose** (30 Nov 2023)<details><summary>Yao Feng, Jing Lin, Sai Kumar Dwivedi, et al. </summary>[CVPR 2024] Yao Feng, Jing Lin, Sai Kumar Dwivedi, Yu Sun, Priyanka Patel, Michael J. Black</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.18836)
[![citation](https://img.shields.io/badge/citation-0-blue.svg?paper=4673c2ac4abb4b055da87171231acb60801ffe74)](https://www.semanticscholar.org/paper/4673c2ac4abb4b055da87171231acb60801ffe74)
[![Code](https://img.shields.io/github/stars/yfeng95/PoseGPT.svg?style=social&label=Star)](https://github.com/yfeng95/PoseGPT)


+ **3D-GPT: Procedural 3D MODELING WITH LARGE LANGUAGE MODELS** (19 Oct 2023)<details><summary>Chunyi Sun*, Junlin Han*, Weijian Deng, et al. </summary>Chunyi Sun, Junlin Han, Weijian Deng, Xinlong Wang, Zishan Qin, Stephen Gould</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.12945)
[![citation](https://img.shields.io/badge/citation-7-blue.svg?paper=588930cdd801f335b5e524d13f99aa94136a20a0)](https://www.semanticscholar.org/paper/588930cdd801f335b5e524d13f99aa94136a20a0)
[![Code](https://img.shields.io/github/stars/Chuny1/3DGPT.svg?style=social&label=Star)](https://github.com/Chuny1/3DGPT)




### Non-LLM-based (Clip/T5)
+ **DreamPolisher: Towards High-Quality Text-to-3D Generation via Geometric Diffusion** (12 Mar 2024)<details><summary>Yuanze Lin, Ronald Clark, Philip Torr. </summary>Yuanze Lin, Ronald Clark, Philip Torr</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.17237)
[![citation](https://img.shields.io/badge/citation-2-blue.svg?paper=72e54db6eebb99d4039cd66cb5dad6a40b31cf87)](https://www.semanticscholar.org/paper/72e54db6eebb99d4039cd66cb5dad6a40b31cf87)
[![Code](https://img.shields.io/github/stars/yuanze-lin/DreamPolisher.svg?style=social&label=Star)](https://github.com/yuanze-lin/DreamPolisher)

+ **Consistent3D: Towards Consistent High-Fidelity Text-to-3D Generation with Deterministic Sampling Prior** (12 Mar 2024)<details><summary>Zike Wu, Pan Zhou, Xuanyu Yi, et al. </summary>[CVPR 2024]Zike Wu, Pan Zhou, Xuanyu Yi, Xiaoding Yuan, Hanwang Zhang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.09050)
[![citation](https://img.shields.io/badge/citation-4-blue.svg?paper=834f595fb25b8306b46f9e744ef8150f4971322f)](https://www.semanticscholar.org/paper/834f595fb25b8306b46f9e744ef8150f4971322f)
[![Code](https://img.shields.io/github/stars/sail-sg/Consistent3D.svg?style=social&label=Star)](https://github.com/sail-sg/Consistent3D)

+ **AToM: Amortized Text-to-Mesh using 2D Diffusion** (1 Feb 2024)<details><summary>Guocheng Qian, Junli Cao, Aliaksandr Siarohin, et al. </summary>Guocheng Qian, Junli Cao, Aliaksandr Siarohin, Yash Kant, Chaoyang Wang, Michael Vasilkovsky, Hsin-Ying Lee, Yuwei Fang, Ivan Skorokhodov, Peiye Zhuang, Igor Gilitschenski, Jian Ren, Bernard Ghanem, Kfir Aberman, Sergey Tulyakov</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.00867)
[![citation](https://img.shields.io/badge/citation-5-blue.svg?paper=ce2edcc6a0ef7592c385c5d8fd0924f79707e223)](https://www.semanticscholar.org/paper/ce2edcc6a0ef7592c385c5d8fd0924f79707e223)
[![Code](https://img.shields.io/github/stars/snap-research/AToM.svg?style=social&label=Star)](https://github.com/snap-research/AToM)


+ **DreamControl: Control-Based Text-to-3D Generation with 3D Self-Prior** ( 12 Mar 2024)<details><summary>Tianyu Huang, Yihan Zeng, Zhilu Zhang, et al. </summary>[CVPR 2024]Tianyu Huang, Yihan Zeng, Zhilu Zhang, Wan Xu, Hang Xu, Songcen Xu, Rynson W. H. Lau, Wangmeng Zuo</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.06439)
[![citation](https://img.shields.io/badge/citation-4-blue.svg?paper=c15380dcda5a010827e3b014dcebe95b1218c680)](https://www.semanticscholar.org/paper/c15380dcda5a010827e3b014dcebe95b1218c680)
[![Code](https://img.shields.io/github/stars/tyhuang0428/DreamControl.svg?style=social&label=Star)](https://github.com/tyhuang0428/DreamControl)


+ **UniDream: Unifying Diffusion Priors for Relightable Text-to-3D Generation** (14 Dec 2023)<details><summary>Zexiang Liu, Yangguang Li, Youtian Lin, et al. </summary>Zexiang Liu, Yangguang Li, Youtian Lin, Xin Yu, Sida Peng, Yan-Pei Cao, Xiaojuan Qi, Xiaoshui Huang, Ding Liang, Wanli Ouyang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.08754)
[![citation](https://img.shields.io/badge/citation-5-blue.svg?paper=210e63599d49abdb848a4440d4244cdcdedeadff)](https://www.semanticscholar.org/paper/210e63599d49abdb848a4440d4244cdcdedeadff)
[![Code](https://img.shields.io/github/stars/YG256Li/UniDream.svg?style=social&label=Star)](https://github.com/YG256Li/UniDream)

+ **Sherpa3D: Boosting High-Fidelity Text-to-3D Generation via Coarse 3D Prior** (11 Dec 2023)<details><summary>[CVPR 2024] Fangfu Liu, Diankun Wu, Yi Wei, et al. </summary>Fangfu Liu, Diankun Wu, Yi Wei, Yongming Rao, Yueqi Duan</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.06655)
[![citation](https://img.shields.io/badge/citation-5-blue.svg?paper=fe1b3f0d074974ce946f10f3bbf52e8351bc0156)](https://www.semanticscholar.org/paper/fe1b3f0d074974ce946f10f3bbf52e8351bc0156)
[![Code](https://img.shields.io/github/stars/liuff19/Sherpa3D.svg?style=social&label=Star)](https://github.com/liuff19/Sherpa3D)

+ **Learn to Optimize Denoising Scores for 3D Generation: A Unified and Improved Diffusion Prior on NeRF and 3D Gaussian Splatting** (8 Dec 2023)<details><summary>Xiaofeng Yang, Yiwen Chen, Cheng Chen, et al. </summary>Xiaofeng Yang, Yiwen Chen, Cheng Chen, Chi Zhang, Yi Xu, Xulei Yang, Fayao Liu, Guosheng Lin</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.04820)
[![citation](https://img.shields.io/badge/citation-3-blue.svg?paper=6d10f9b0e0a579a1359df7dfbdef00bc798d5714)](https://www.semanticscholar.org/paper/6d10f9b0e0a579a1359df7dfbdef00bc798d5714)
[![Code](https://img.shields.io/github/stars/yangxiaofeng/LODS.svg?style=social&label=Star)](https://github.com/yangxiaofeng/LODS)

+ **DreamPropeller: Supercharge Text-to-3D Generation with Parallel Sampling** (28 Nov 2023)<details><summary>Linqi Zhou, Andy Shih, Chenlin Meng, et al. </summary>Linqi Zhou, Andy Shih, Chenlin Meng, Stefano Ermon</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.16918)
[![citation](https://img.shields.io/badge/citation-3-blue.svg?paper=e88d5399956c9d9519a5cfd49308b7d439167543)](https://www.semanticscholar.org/paper/e88d5399956c9d9519a5cfd49308b7d439167543)
[![Code](https://img.shields.io/github/stars/alexzhou907/DreamPropeller.svg?style=social&label=Star)](https://github.com/alexzhou907/DreamPropeller)

+ **RichDreamer: A Generalizable Normal-Depth Diffusion Model for Detail Richness in Text-to-3D** (28 Nov 2023)<details><summary>[CVPR 2024] Lingteng Qiu, Guanying Chen, Xiaodong Gu, et al. </summary>Lingteng Qiu, Guanying Chen, Xiaodong Gu, Qi Zuo, Mutian Xu, Yushuang Wu, Weihao Yuan, Zilong Dong, Liefeng Bo, Xiaoguang Han</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.17082)
[![citation](https://img.shields.io/badge/citation-10-blue.svg?paper=cf60a639add75cdea4273697269ee463024b7926)](https://www.semanticscholar.org/paper/cf60a639add75cdea4273697269ee463024b7926)
[![Code](https://img.shields.io/github/stars/modelscope/richdreamer.svg?style=social&label=Star)](https://github.com/modelscope/richdreamer)

+ **DreamAvatar: Text-and-Shape Guided 3D Human Avatar Generation via Diffusion Models** (30 Nov 2023)<details><summary>[CVPR 2024] Yukang Cao, Yan-Pei Cao, Kai Han, et al. </summary>Yukang Cao, Yan-Pei Cao, Kai Han, Ying Shan, Kwan-Yee K. Wong</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.00916)
[![citation](https://img.shields.io/badge/citation-69-blue.svg?paper=0fa1501c7378a0dca2ac913fce9dcdcc2b1958a7)](https://www.semanticscholar.org/paper/0fa1501c7378a0dca2ac913fce9dcdcc2b1958a7)
[![Code](https://img.shields.io/github/stars/yukangcao/DreamAvatar.svg?style=social&label=Star)](https://github.com/yukangcao/DreamAvatar)

+ **LucidDreamer: Towards High-Fidelity Text-to-3D Generation via Interval Score Matching** (2 Dec 2023)<details><summary>[CVPR 2024] Yixun Liang, Xin Yang, Jiantao Lin, et al. </summary>Yixun Liang, Xin Yang, Jiantao Lin, Haodong Li, Xiaogang Xu, Yingcong Chen</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.11284)
[![citation](https://img.shields.io/badge/citation-12-blue.svg?paper=6f709278506813d04a074e6fa20188cce9bb927b)](https://www.semanticscholar.org/paper/6f709278506813d04a074e6fa20188cce9bb927b)
[![Code](https://img.shields.io/github/stars/EnVision-Research/LucidDreamer.svg?style=social&label=Star)](https://github.com/EnVision-Research/LucidDreamer)


+ **GaussianDreamer: Fast Generation from Text to 3D Gaussians by Bridging 2D and 3D Diffusion Models** (12 Oct 2023)<details><summary>[CVPR 2024] Taoran Yi, Jiemin Fang, Junjie Wang, et al. </summary>Taoran Yi, Jiemin Fang, Junjie Wang, Guanjun Wu, Lingxi Xie, Xiaopeng Zhang, Wenyu Liu, Qi Tian, Xinggang Wang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.08529)
[![citation](https://img.shields.io/badge/citation-230-blue.svg?paper=c5e9fd131cde68c218d0ea69cd617a67c7f35d42)](https://www.semanticscholar.org/paper/c5e9fd131cde68c218d0ea69cd617a67c7f35d42)
[![Code](https://img.shields.io/github/stars/hustvl/GaussianDreamer.svg?style=social&label=Star)](https://github.com/hustvl/GaussianDreamer)

+ **Text-to-3D using Gaussian Splatting** (28 Sep 2023)<details><summary>[CVPR 2024] Zilong Chen, Feng Wang, Huaping Liu </summary>Zilong Chen, Feng Wang, Huaping Liu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.16585)
[![citation](https://img.shields.io/badge/citation-57-blue.svg?paper=86b5318b0a69ccdeec17abb0120e4bd7688a4b59)](https://www.semanticscholar.org/paper/86b5318b0a69ccdeec17abb0120e4bd7688a4b59)
[![Code](https://img.shields.io/github/stars/gsgen3d/gsgen.svg?style=social&label=Star)](https://github.com/gsgen3d/gsgen)

+ **EfficientDreamer: High-Fidelity and Robust 3D Creation via Orthogonal-view Diffusion Prior** (10 Sep 2023)<details><summary>[CVPR 2024] Zhipeng Hu, Minda Zhao, Chaoyi Zhao, Xinyue Liang, Lincheng Li, Zeng Zhao, Changjie Fan, Xiaowei Zhou, Xin Yu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.13223)
[![citation](https://img.shields.io/badge/citation-23-blue.svg?paper=fec17239569efd6914f0df9e25b66b310969d3c5)](https://www.semanticscholar.org/paper/fec17239569efd6914f0df9e25b66b310969d3c5)

+ **TADA! Text to Animatable Digital Avatars** (21 Aug 2023)<details><summary>[3DV 2024] Tingting Liao, Hongwei Yi, Yuliang Xiu, et al.</summary>Tingting Liao, Hongwei Yi, Yuliang Xiu, Jiaxaing Tang, Yangyi Huang, Justus Thies, Michael J. Black</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.10899)
[![citation](https://img.shields.io/badge/citation-36-blue.svg?paper=303f466fb823112f79a9f36637c7084dd8363fc5)](https://www.semanticscholar.org/paper/303f466fb823112f79a9f36637c7084dd8363fc5)
[![Code](https://img.shields.io/github/stars/TingtingLiao/TADA.svg?style=social&label=Star)](https://github.com/TingtingLiao/TADA)

+ **SweetDreamer: Aligning Geometric Priors in 2D Diffusion for Consistent Text-to-3D** (20 Oct 2023 )<details><summary>[ICLR 2024] Weiyu Li, Rui Chen, Xuelin Chen, et al.</summary>Weiyu Li, Rui Chen, Xuelin Chen, Ping Tan</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.02596)
[![citation](https://img.shields.io/badge/citation-29-blue.svg?paper=438e9fb79c9e37d43223e61bb575ebd2dae0b0a7)](https://www.semanticscholar.org/paper/438e9fb79c9e37d43223e61bb575ebd2dae0b0a7)
[![Code](https://img.shields.io/github/stars/wyysf-98/SweetDreamer.svg?style=social&label=Star)](https://github.com/wyysf-98/SweetDreamer)

+ **Noise-Free Score Distillation** (26 Oct 2023)<details><summary>[ICLR 2024] Oren Katzir, Or Patashnik, Daniel Cohen-Or, et al.</summary>Oren Katzir, Or Patashnik, Daniel Cohen-Or, Dani Lischinski</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.17590)
[![citation](https://img.shields.io/badge/citation-14-blue.svg?paper=85a70c0a048cba4f53dcf332ee73f6032a2e53bc)](https://www.semanticscholar.org/paper/85a70c0a048cba4f53dcf332ee73f6032a2e53bc)
[![Code](https://img.shields.io/github/stars/orenkatzir/nfsd.svg?style=social&label=Star)](https://github.com/orenkatzir/nfsd)

+ **Text-to-3D with Classifier Score Distillation** (26 Oct 2023 )<details><summary>[ICLR 2024] Xin Yu, Yuan-Chen Guo, Yangguang Li, et al. </summary>Xin Yu, Yuan-Chen Guo, Yangguang Li, Ding Liang, Song-Hai Zhang, Xiaojuan Qi</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.19415)
[![citation](https://img.shields.io/badge/citation-13-blue.svg?paper=4e21879b564cc2e803b16edf0dda9f1edb91b497)](https://www.semanticscholar.org/paper/4e21879b564cc2e803b16edf0dda9f1edb91b497)
[![Code](https://img.shields.io/github/stars/CVMI-Lab/Classifier-Score-Distillation.svg?style=social&label=Star)](https://github.com/CVMI-Lab/Classifier-Score-Distillation)

+ **HiFA: High-fidelity Text-to-3D Generation with Advanced Diffusion Guidance** (28 Nov 2023)<details><summary>[ICLR 2024] Junzhe Zhu, Peiye Zhuang. </summary>Junzhe Zhu, Peiye Zhuang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.18766)
[![citation](https://img.shields.io/badge/citation-17-blue.svg?paper=daf3b117f789b2b95223e58592979fb57627515e)](https://www.semanticscholar.org/paper/daf3b117f789b2b95223e58592979fb57627515e)
[![Code](https://img.shields.io/github/stars/JunzheJosephZhu/HiFA.svg?style=social&label=Star)](https://github.com/JunzheJosephZhu/HiFA)

+ **MVDream: Multi-view Diffusion for 3D Generation** (31 Aug 2023)<details><summary>[ICLR 2024] Yichun Shi, Peng Wang, Jianglong Ye, et al. </summary>Yichun Shi, Peng Wang, Jianglong Ye, Mai Long, Kejie Li, Xiao Yang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.16512)
[![citation](https://img.shields.io/badge/citation-154-blue.svg?paper=9aa01997226b5c4d705ae2e2f52c32681006654b)](https://www.semanticscholar.org/paper/9aa01997226b5c4d705ae2e2f52c32681006654b)
[![Code](https://img.shields.io/github/stars/bytedance/MVDream.svg?style=social&label=Star)](https://github.com/bytedance/MVDream)

+ **DreamGaussian: Generative Gaussian Splatting for Efficient 3D Content Creation** (28 Sep 2023)<details><summary>[ICLR 2024] Jiaxiang Tang, Jiawei Ren, Hang Zhou, et al.</summary>Jiaxiang Tang, Jiawei Ren, Hang Zhou, Ziwei Liu, Gang Zeng</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.16653)
[![citation](https://img.shields.io/badge/citation-99-blue.svg?paper=cc1a674bb164d09a060cf5b26fe518c02fae0ddc)](https://www.semanticscholar.org/paper/cc1a674bb164d09a060cf5b26fe518c02fae0ddc)
[![Code](https://img.shields.io/github/stars/dreamgaussian/dreamgaussian.svg?style=social&label=Star)](https://github.com/dreamgaussian/dreamgaussian)

+ **Let 2D Diffusion Model Know 3D-Consistency for Robust Text-to-3D Generation** (11 Apr 2023)<details><summary>[ICLR 2024] Junyoung Seo, Wooseok Jang, Min-Seop Kwak, et al.</summary>Junyoung Seo, Wooseok Jang, Min-Seop Kwak, Hyeonsu Kim, Jaehoon Ko, Junho Kim, Jin-Hwa Kim, Jiyoung Lee, Seungryong Kim</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.07937)
[![citation](https://img.shields.io/badge/citation-81-blue.svg?paper=5356c3dac654854a0842753bcc2e3433dc4a2afd)](https://www.semanticscholar.org/paper/5356c3dac654854a0842753bcc2e3433dc4a2afd)
[![Code](https://img.shields.io/github/stars/eladrich/latent-nerf.svg?style=social&label=Star)](https://github.com/eladrich/latent-nerf)


+ **IT3D: Improved Text-to-3D Generation with Explicit View Synthesis** (22 Aug 2023)<details><summary>[AAAI 2024] Yiwen Chen, Chi Zhang, Xiaofeng Yang, et al. </summary>Yiwen Chen, Chi Zhang, Xiaofeng Yang, Zhongang Cai, Gang Yu, Lei Yang, Guosheng Lin</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.11473)
[![citation](https://img.shields.io/badge/citation-30-blue.svg?paper=2b94785cbfd865a01cc68d7d4c7500b710e5e2fb)](https://www.semanticscholar.org/paper/2b94785cbfd865a01cc68d7d4c7500b710e5e2fb)
[![Code](https://img.shields.io/github/stars/buaacyw/IT3D-text-to-3D.svg?style=social&label=Star)](https://github.com/buaacyw/IT3D-text-to-3D)


+ **HD-Fusion: Detailed Text-to-3D Generation Leveraging Multiple Noise Estimation** (30 Jul 2023)<details><summary>[WACV 2024] Jinbo Wu, Xiaobo Gao, Xing Liu, et al. </summary>Jinbo Wu, Xiaobo Gao, Xing Liu, Zhengyang Shen, Chen Zhao, Haocheng Feng, Jingtuo Liu, Errui Ding</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2307.16183)
[![citation](https://img.shields.io/badge/citation-12-blue.svg?paper=d8aaed01dffc621488aecbb0ef01b50f86e44bc1)](https://www.semanticscholar.org/paper/d8aaed01dffc621488aecbb0ef01b50f86e44bc1)


+ **Re-imagine the Negative Prompt Algorithm: Transform 2D Diffusion into 3D, alleviate Janus problem and Beyond** (11 Apr 2023)<details><summary>Mohammadreza Armandpour, Ali Sadeghian, Huangjie Zheng, et al. </summary>Mohammadreza Armandpour, Ali Sadeghian, Huangjie Zheng, Amir Sadeghian, Mingyuan Zhou</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.04968)
[![citation](https://img.shields.io/badge/citation-50-blue.svg?paper=b19ca192a5bebbc3473be61989baf085ff21daa5)](https://www.semanticscholar.org/paper/b19ca192a5bebbc3473be61989baf085ff21daa5)
[![Code](https://img.shields.io/github/stars/Perp-Neg/Perp-Neg-stablediffusion.svg?style=social&label=Star)](https://github.com/Perp-Neg/Perp-Neg-stablediffusion)


+ **Latent-NeRF for Shape-Guided Generation of 3D Shapes and Textures** (14 Nov 2022)<details><summary>[CVPR 2023] Gal Metzer, Elad Richardson, Or Patashnik, et al.</summary>Gal Metzer, Elad Richardson, Or Patashnik, Raja Giryes, Daniel Cohen-Or</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2211.07600)
[![citation](https://img.shields.io/badge/citation-212-blue.svg?paper=793939b83e10903f58d8edbb7534963df627a1fe)](https://www.semanticscholar.org/paper/793939b83e10903f58d8edbb7534963df627a1fe)
[![Code](https://img.shields.io/github/stars/eladrich/latent-nerf.svg?style=social&label=Star)](https://github.com/eladrich/latent-nerf)

+ **Magic3D: High-Resolution Text-to-3D Content Creation** (18 Nov 2022)<details><summary>[CVPR 2023 Highlight] Chen-Hsuan Lin, Jun Gao, Luming Tang, et al. </summary>Chen-Hsuan Lin, Jun Gao, Luming Tang, Towaki Takikawa, Xiaohui Zeng, Xun Huang, Karsten Kreis, Sanja Fidler, Ming-Yu Liu, Tsung-Yi Lin</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://openaccess.thecvf.com/content/CVPR2023/papers/Lin_Magic3D_High-Resolution_Text-to-3D_Content_Creation_CVPR_2023_paper.pdf)
[![citation](https://img.shields.io/badge/citation-466-blue.svg?paper=bdf4af8311637c681904e71cf50f96fd0026f578)](https://www.semanticscholar.org/paper/bdf4af8311637c681904e71cf50f96fd0026f578)

+ **Score Jacobian Chaining: Lifting Pretrained 2D Diffusion Models for 3D Generation** (1 Dec 2022)<details><summary>[CVPR 2023] Haochen Wang, Xiaodan Du, Jiahao Li, et al. </summary>Haochen Wang, Xiaodan Du, Jiahao Li, Raymond A. Yeh, Greg Shakhnarovich</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2212.00774)
[![citation](https://img.shields.io/badge/citation-238-blue.svg?paper=fc011ed5ee986332523a62d2783adee1179dc1ed)](https://www.semanticscholar.org/paper/fc011ed5ee986332523a62d2783adee1179dc1ed)
[![Code](https://img.shields.io/github/stars/pals-ttic/sjc.svg?style=social&label=Star)](https://github.com/pals-ttic/sjc)

+ **High-fidelity 3D Face Generation from Natural Language Descriptions** (5 May 2023)<details><summary>[CVPR 2023] Menghua Wu, Hao Zhu, Linjia Huang, et al. </summary>Menghua Wu, Hao Zhu, Linjia Huang, Yiyu Zhuang, Yuanxun Lu, Xun Cao</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.03302)
[![citation](https://img.shields.io/badge/citation-13-blue.svg?paper=012d7d3ee690e5acadf416787651a8fe425e8eb3)](https://www.semanticscholar.org/paper/012d7d3ee690e5acadf416787651a8fe425e8eb3)
[![Code](https://img.shields.io/github/stars/zhuhao-nju/describe3d.svg?style=social&label=Star)](https://github.com/zhuhao-nju/describe3d)

+ **RODIN: A Generative Model for Sculpting 3D Digital Avatars Using Diffusion** (12 Dec 2022)<details><summary>[CVPR 2023 Highlight] Tengfei Wang, Bo Zhang, Ting Zhang, et al. </summary>Tengfei Wang, Bo Zhang, Ting Zhang, Shuyang Gu, Jianmin Bao, Tadas Baltrusaitis, Jingjing Shen, Dong Chen, Fang Wen, Qifeng Chen, Baining Guo</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2212.06135)
[![citation](https://img.shields.io/badge/citation-158-blue.svg?paper=7e993a9ca01dcd4538362454aaac29a18a63c000)](https://www.semanticscholar.org/paper/7e993a9ca01dcd4538362454aaac29a18a63c000)

+ **ClipFace: Text-guided Editing of Textured 3D Morphable Models** (24 Apr 2023)<details><summary>[SIGGRAPH 2023] Tengfei Wang, Bo Zhang, Ting Zhang, et al. </summary>Tengfei Wang, Bo Zhang, Ting Zhang, Shuyang Gu, Jianmin Bao, Tadas Baltrusaitis, Jingjing Shen, Dong Chen, Fang Wen, Qifeng Chen, Baining Guo</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2212.01406)
[![citation](https://img.shields.io/badge/citation-40-blue.svg?paper=f21e8eddf42580d1f38a11ec5acd8891c0454a1f)](https://www.semanticscholar.org/paper/f21e8eddf42580d1f38a11ec5acd8891c0454a1f)
[![Code](https://img.shields.io/github/stars/shivangi-aneja/ClipFace.svg?style=social&label=Star)](https://github.com/shivangi-aneja/ClipFace)

+ **DreamFusion: Text-to-3D using 2D Diffusion** (29 Sep 2022)<details><summary>[ICLR 2023 Oral] Ben Poole, Ajay Jain, Jonathan T. Barron, et al.</summary>Ben Poole, Ajay Jain, Jonathan T. Barron, Ben Mildenhall</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2209.14988)
[![citation](https://img.shields.io/badge/citation-908-blue.svg?paper=4c94d04afa4309ec2f06bdd0fe3781f91461b362)](https://www.semanticscholar.org/paper/4c94d04afa4309ec2f06bdd0fe3781f91461b362)

+ **ProlificDreamer: High-Fidelity and Diverse Text-to-3D Generation with Variational Score Distillation** (25 May 2023)<details><summary>[NeurIPS 2023 Spotlight] Zhengyi Wang, Cheng Lu, Yikai Wang, et al. </summary>Zhengyi Wang, Cheng Lu, Yikai Wang, Fan Bao, Chongxuan Li, Hang Su, Jun Zhu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.13873)
[![citation](https://img.shields.io/badge/citation-230-blue.svg?paper=c5e9fd131cde68c218d0ea69cd617a67c7f35d42)](https://www.semanticscholar.org/paper/c5e9fd131cde68c218d0ea69cd617a67c7f35d42)
[![Code](https://img.shields.io/github/stars/KU-CVLAB/3DFuse-threestudio.svg?style=social&label=Star)](https://github.com/KU-CVLAB/3DFuse-threestudio)

+ **HeadSculpt: Crafting 3D Head Avatars with Text** (25 May 2023)<details><summary>[NeurIPS 2023] Xiao Han, Yukang Cao, Kai Han, et al. </summary>Xiao Han, Yukang Cao, Kai Han, Xiatian Zhu, Jiankang Deng, Yi-Zhe Song, Tao Xiang, Kwan-Yee K. Wong</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.03038)
[![citation](https://img.shields.io/badge/citation-230-blue.svg?paper=4e8cf9602d4ef714dcdb8580de40e1a2a717ab11)](https://www.semanticscholar.org/paper/4e8cf9602d4ef714dcdb8580de40e1a2a717ab11)
[![Code](https://img.shields.io/github/stars/BrandonHanx/HeadSculpt.svg?style=social&label=Star)](https://github.com/BrandonHanx/HeadSculpt)

+ **ATT3D: Amortized Text-to-3D Object Synthesis** (6 Jun 2023)<details><summary>[ICCV 2023] Jonathan Lorraine, Kevin Xie, Xiaohui Zeng, et al. </summary>Jonathan Lorraine, Kevin Xie, Xiaohui Zeng, Chen-Hsuan Lin, Towaki Takikawa, Nicholas Sharp, Tsung-Yi Lin, Ming-Yu Liu, Sanja Fidler, James Lucas</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.07349)
[![citation](https://img.shields.io/badge/citation-25-blue.svg?paper=1e8403af2e1e7a8f803d8df9e8daac584f99c2a0)](https://www.semanticscholar.org/paper/1e8403af2e1e7a8f803d8df9e8daac584f99c2a0)

+ **Fantasia3D: Disentangling Geometry and Appearance for High-quality Text-to-3D Content Creation** (24 Mar 2023)<details><summary>[ICCV 2023] Rui Chen, Yongwei Chen, Ningxin Jiao, et al. </summary>Rui Chen, Yongwei Chen, Ningxin Jiao, Kui Jia</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.13873)
[![citation](https://img.shields.io/badge/citation-202-blue.svg?paper=0cbb518c364067200476a51e5ce7476a4f582770)](https://www.semanticscholar.org/paper/0cbb518c364067200476a51e5ce7476a4f582770)
[![Code](https://img.shields.io/github/stars/Gorilla-Lab-SCUT/Fantasia3D.svg?style=social&label=Star)](https://github.com/Gorilla-Lab-SCUT/Fantasia3D)

+ **Text2Room: Extracting Textured 3D Meshes from 2D Text-to-Image Models** (10 Sep 2023)<details><summary>[ICCV 2023] Lukas Höllein, Ang Cao, Andrew Owens, et al. </summary>Lukas Höllein, Ang Cao, Andrew Owens, Justin Johnson, Matthias Nießner</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.11989)
[![citation](https://img.shields.io/badge/citation-55-blue.svg?paper=95aa6fa4e42387561cff22378348d528adea37f2)](https://www.semanticscholar.org/paper/95aa6fa4e42387561cff22378348d528adea37f2)
[![Code](https://img.shields.io/github/stars/lukasHoel/text2room.svg?style=social&label=Star)](https://github.com/lukasHoel/text2room)

+ **X-Mesh: Towards Fast and Accurate Text-driven 3D Stylization via Dynamic Textual Guidance** (28 Mar 2023) <details><summary>[ICCV 2023] Yiwei Ma, Xiaioqing Zhang, Xiaoshuai Sun, et al.</summary>Yiwei Ma, Xiaioqing Zhang, Xiaoshuai Sun, Jiayi Ji, Haowei Wang, Guannan Jiang, Weilin Zhuang, Rongrong Ji</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.15764)
[![citation](https://img.shields.io/badge/citation-18-blue.svg?paper=f8bf2225a2993e3ead73d886b5797378d6e53186)](https://www.semanticscholar.org/paper/f8bf2225a2993e3ead73d886b5797378d6e53186)
[![Code](https://img.shields.io/github/stars/xmu-xiaoma666/X-Mesh.svg?style=social&label=Star)](https://github.com/xmu-xiaoma666/X-Mesh)

+ **StyleAvatar3D: Leveraging Image-Text Diffusion Models for High-Fidelity 3D Avatar Generation** (31 May 2023) <details><summary> Chi Zhang, Yiwen Chen, Yijun Fu, et al.</summary>Chi Zhang, Yiwen Chen, Yijun Fu, Zhenglin Zhou, Gang YU, Billzb Wang, Bin Fu, Tao Chen, Guosheng Lin, Chunhua Shen</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.19012)
[![citation](https://img.shields.io/badge/citation-13-blue.svg?paper=b980d98c81252dfbed334728c46625e58f54dd9d)](https://www.semanticscholar.org/paper/b980d98c81252dfbed334728c46625e58f54dd9d)
[![Code](https://img.shields.io/github/stars/icoz69/StyleAvatar3D.svg?style=social&label=Star)](https://github.com/icoz69/StyleAvatar3D)

+ **TextMesh: Generation of Realistic 3D Meshes From Text Prompts** (24 Apr 2023) <details><summary>[3DV 2023] Christina Tsalicoglou, Fabian Manhardt, Alessio Tonioni, et al.</summary>Christina Tsalicoglou, Fabian Manhardt, Alessio Tonioni, Michael Niemeyer, Federico Tombari</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.12439)
[![citation](https://img.shields.io/badge/citation-67-blue.svg?paper=2c6392491b6a942e08db46c8fff0ef5ba1fd9de8)](https://www.semanticscholar.org/paper/2c6392491b6a942e08db46c8fff0ef5ba1fd9de8)
[![Code](https://img.shields.io/github/stars/threestudio-project/threestudio.svg?style=social&label=Star)](https://github.com/threestudio-project/threestudio)

+ **Clip-forge: Towards zero-shot text-to-shape generation** (28 Apr 2022)<details><summary>[CVPR 2022] Aditya Sanghi, Hang Chu, Joseph G. Lambourne, et al. </summary>Aditya Sanghi, Hang Chu, Joseph G. Lambourne, Ye Wang, Chin-Yi Cheng, Marco Fumero, Kamal Rahimi Malekshan</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2110.02624)
[![citation](https://img.shields.io/badge/citation-197-blue.svg?paper=738e3e0623054da29dc57fc6aee5e6711867c4e8)](https://www.semanticscholar.org/paper/738e3e0623054da29dc57fc6aee5e6711867c4e8)
[![Code](https://img.shields.io/github/stars/AutodeskAILab/Clip-Forge.svg?style=social&label=Star)](https://github.com/AutodeskAILab/Clip-Forge)


+ **Zero-Shot Text-Guided Object Generation with Dream Fields** (2 Dec 2021) <details><summary>[CVPR 2022] Ajay Jain, Ben Mildenhall, Jonathan T. Barron, et al.</summary>Ajay Jain, Ben Mildenhall, Jonathan T. Barron, Pieter Abbeel, Ben Poole</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2112.01455)
[![citation](https://img.shields.io/badge/citation-345-blue.svg?paper=03e1c3b5fdad9b21bbed3d13af7e8d6c73cbcfa6)](https://www.semanticscholar.org/paper/03e1c3b5fdad9b21bbed3d13af7e8d6c73cbcfa6)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://ajayj.com/dreamfields)
[![Code](https://img.shields.io/github/stars/google-research/google-research.svg?style=social&label=Star)](https://github.com/google-research/google-research/)

+ **Text2Mesh: Text-Driven Neural Stylization for Meshes** (6 Dec 2021) <details><summary>[CVPR 2022] Oscar Michel, Roi Bar-On, Richard Liu, et al. </summary>Oscar Michel, Roi Bar-On, Richard Liu, Sagie Benaim, Rana Hanocka</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2110.02624)
[![citation](https://img.shields.io/badge/citation-222-blue.svg?paper=d15b27edf3630728cdb40f49946365d9011641cf)](https://www.semanticscholar.org/paper/d15b27edf3630728cdb40f49946365d9011641cf)
[![Code](https://img.shields.io/github/stars/threedle/text2mesh.svg?style=social&label=Star)](https://github.com/threedle/text2mesh)

+ **TANGO: Text-driven Photorealistic and Robust 3D Stylization via Lighting Decomposition** (20 Oct 2022) <details><summary>[NeurIPS 2022 Spotlight] Yongwei Chen, Rui Chen, Jiabao Lei, et al. </summary>Yongwei Chen, Rui Chen, Jiabao Lei, Yabin Zhang, Kui Jia</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2210.11277)
[![citation](https://img.shields.io/badge/citation-47-blue.svg?paper=44e49f72fb6b97f52c25a30f0adc68c2384430ba)](https://www.semanticscholar.org/paper/44e49f72fb6b97f52c25a30f0adc68c2384430ba)
[![Code](https://img.shields.io/github/stars/Gorilla-Lab-SCUT/tango.svg?style=social&label=Star)](https://github.com/Gorilla-Lab-SCUT/tango)

+ **CLIP-Mesh: Generating textured meshes from text using pretrained image-text models** (24 Mar 2022) <details><summary>[SIGGRAPH ASIA 2022] Nasir Mohammad Khalid, Tianhao Xie, Eugene Belilovsky, et al. </summary>Nasir Mohammad Khalid, Tianhao Xie, Eugene Belilovsky, Tiberiu Popa</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2203.13333)
[![citation](https://img.shields.io/badge/citation-167-blue.svg?paper=8941e477b2f39eb92712f04400412da60d349ec1)](https://www.semanticscholar.org/paper/8941e477b2f39eb92712f04400412da60d349ec1)
[![Code](https://img.shields.io/github/stars/NasirKhalid24/CLIP-Mesh.svg?style=social&label=Star)](https://github.com/NasirKhalid24/CLIP-Mesh)

+ **MotionCLIP: Exposing Human Motion Generation to CLIP Space** (15 Mar 2022) <details><summary>[ECCV 2022] Guy Tevet, Brian Gordon, Amir Hertz, et al. </summary>Guy Tevet, Brian Gordon, Amir Hertz, Amit H. Bermano, Daniel Cohen-Or</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2203.08063)
[![citation](https://img.shields.io/badge/citation-140-blue.svg?paper=e82df4b6a3628501fce67835ad8316d6525ad133)](https://www.semanticscholar.org/paper/e82df4b6a3628501fce67835ad8316d6525ad133)
[![Code](https://img.shields.io/github/stars/GuyTevet/MotionCLIP.svg?style=social&label=Star)](https://github.com/GuyTevet/MotionCLIP)

  
### Datasets

+ **Objaverse-XL: A Universe of 10M+ 3D Objects** (11 Jul 2023) <details><summary>Matt Deitke, Dustin Schwenk, Jordi Salvador, et al. </summary>Matt Deitke, Ruoshi Liu, Matthew Wallingford, Huong Ngo, Oscar Michel, Aditya Kusupati, Alan Fan, Christian Laforte, Vikram Voleti, Samir Yitzhak Gadre, Eli VanderBilt, Aniruddha Kembhavi, Carl Vondrick, Georgia Gkioxari, Kiana Ehsani, Ludwig Schmidt, Ali Farhadi</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2307.05663)
[![citation](https://img.shields.io/badge/citation-70-blue.svg?paper=1b90e9e9734bed6b379ae87d688cb3b887baf597)](https://www.semanticscholar.org/paper/1b90e9e9734bed6b379ae87d688cb3b887baf597)
[![Code](https://img.shields.io/github/stars/allenai/objaverse-xl.svg?style=social&label=Star)](https://github.com/allenai/objaverse-xl)

+ **Objaverse: A Universe of Annotated 3D Objects** (15 Dec 2022) <details><summary>[CVPR 2023] Matt Deitke, Dustin Schwenk, Jordi Salvador, et al. </summary>Matt Deitke, Dustin Schwenk, Jordi Salvador, Luca Weihs, Oscar Michel, Eli VanderBilt, Ludwig Schmidt, Kiana Ehsani, Aniruddha Kembhavi, Ali Farhadi</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2212.08051)
[![citation](https://img.shields.io/badge/citation-230-blue.svg?paper=1b31dbf44e68b698120552366df03e6e35a1e428)](https://www.semanticscholar.org/paper/1b31dbf44e68b698120552366df03e6e35a1e428)
[![Code](https://img.shields.io/github/stars/allenai/objaverse-xl.svg?style=social&label=Star)](https://github.com/allenai/objaverse-xl)

 
## Audio Generation

### 🔅 LLM-based

+ **SongComposer: A Large Language Model for Lyric and Melody Composition in Song Generation** (27 Feb 2024)<details><summary>Shuangrui Ding, Zihan Liu, Xiaoyi Dong, et al.</summary>Shuangrui Ding, Zihan Liu, Xiaoyi Dong, Pan Zhang, Rui Qian, Conghui He, Dahua Lin, Jiaqi Wang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.17645)
[![citation](https://img.shields.io/badge/citation-0-blue.svg?paper=e7c8a74423a5811a3aac5f33001fce32d2e2386c)](https://www.semanticscholar.org/paper/e7c8a74423a5811a3aac5f33001fce32d2e2386c)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://pjlab-songcomposer.github.io/)
[![Code](https://img.shields.io/github/stars/pjlab-songcomposer/songcomposer.svg?style=social&label=Star)](https://github.com/pjlab-songcomposer/songcomposer)

+ **ChatMusician: Understanding and Generating Music Intrinsically with LLM** (25 Feb 2024)<details><summary>Ruibin Yuan, Hanfeng Lin, Yi Wang, et al.</summary>Ruibin Yuan, Hanfeng Lin, Yi Wang, Zeyue Tian, Shangda Wu, Tianhao Shen, Ge Zhang, Yuhang Wu, Cong Liu, Ziya Zhou, Ziyang Ma, Liumeng Xue, Ziyu Wang, Qin Liu, Tianyu Zheng, Yizhi Li, Yinghao Ma, Yiming Liang, Xiaowei Chi, Ruibo Liu, Zili Wang, Pengfei Li, Jingcheng Wu, Chenghua Lin, Qifeng Liu, Tao Jiang, Wenhao Huang, Wenhu Chen, Emmanouil Benetos, Jie Fu, Gus Xia, Roger Dannenberg, Wei Xue, Shiyin Kang, Yike Guo</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.16153)
[![citation](https://img.shields.io/badge/citation-0-blue.svg?paper=48494aa30f35a64858644aba839c8cba38c0cf2a)](https://www.semanticscholar.org/paper/48494aa30f35a64858644aba839c8cba38c0cf2a)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://shanghaicannon.github.io/ChatMusician/)
[![Code](https://img.shields.io/github/stars/hf-lin/ChatMusician.svg?style=social&label=Star)](https://github.com/hf-lin/ChatMusician)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/m-a-p/ChatMusician)

+ **AnyGPT: Unified Multimodal LLM with Discrete Sequence Modeling** (19 Feb 2024)<details><summary>Jun Zhan, Junqi Dai, Jiasheng Ye, et al.</summary>Jun Zhan, Junqi Dai, Jiasheng Ye, Yunhua Zhou, Dong Zhang, Zhigeng Liu, Xin Zhang, Ruibin Yuan, Ge Zhang, Linyang Li, Hang Yan, Jie Fu, Tao Gui, Tianxiang Sun, Yugang Jiang, Xipeng Qiu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.12226)
[![citation](https://img.shields.io/badge/citation-0-blue.svg?paper=14191e9f12913ad8c7ac6e1188682afac04aad09)](https://www.semanticscholar.org/paper/14191e9f12913ad8c7ac6e1188682afac04aad09)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://junzhan2000.github.io/AnyGPT.github.io/)
[![Code](https://img.shields.io/github/stars/OpenMOSS/AnyGPT.svg?style=social&label=Star)](https://github.com/OpenMOSS/AnyGPT)

+ **Boosting Large Language Model for Speech Synthesis: An Empirical Study** (30 Dec 2023)<details><summary>Hongkun Hao, Long Zhou, Shujie Liu, et al.</summary>Hongkun Hao, Long Zhou, Shujie Liu, Jinyu Li, Shujie Hu, Rui Wang, Furu Wei</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.00246)
[![citation](https://img.shields.io/badge/citation-2-blue.svg?paper=c1dd77e48dd615ee6881b2cc876a00a92cae6eac)](https://www.semanticscholar.org/paper/c1dd77e48dd615ee6881b2cc876a00a92cae6eac)

+ **Unified-IO 2: Scaling Autoregressive Multimodal Models with Vision, Language, Audio, and Action** (28 Dec 2023)<details><summary>Jiasen Lu, Christopher Clark, Sangho Lee, et al.</summary>Jiasen Lu, Christopher Clark, Sangho Lee, Zichen Zhang, Savya Khosla, Ryan Marten, Derek Hoiem, Aniruddha Kembhavi</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.17172)
[![citation](https://img.shields.io/badge/citation-8-blue.svg?paper=6c64ddd2190909de2c680dd18abc9b92e80c39f9)](https://www.semanticscholar.org/paper/6c64ddd2190909de2c680dd18abc9b92e80c39f9)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://unified-io-2.allenai.org/)
[![Code](https://img.shields.io/github/stars/allenai/unified-io-2.svg?style=social&label=Star)](https://github.com/allenai/unified-io-2)

+ **M2UGen: Multi-modal Music Understanding and Generation with the Power of Large Language Models** (19 Nov 2023)<details><summary>Atin Sakkeer Hussain, Shansong Liu, Chenshuo Sun, et al.</summary>Atin Sakkeer Hussain, Shansong Liu, Chenshuo Sun, Ying Shan</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.11255)
[![citation](https://img.shields.io/badge/citation-N/A-blue.svg?paper=1e84d7c45f70038574fcdb7bc1b20da9b348a092)](https://www.semanticscholar.org/paper/1e84d7c45f70038574fcdb7bc1b20da9b348a092)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://crypto-code.github.io/M2UGen-Demo/)
[![Code](https://img.shields.io/github/stars/shansongliu/M2UGen.svg?style=social&label=Star)](https://github.com/shansongliu/M2UGen)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/M2UGen/M2UGen-Demo)

+ **LauraGPT: Listen, Attend, Understand, and Regenerate Audio with GPT** (7 Oct 2023)<details><summary>Jiaming Wang, Zhihao Du, Qian Chen, et al.</summary>Jiaming Wang, Zhihao Du, Qian Chen, Yunfei Chu, Zhifu Gao, Zerui Li, Kai Hu, Xiaohuan Zhou, Jin Xu, Ziyang Ma, Wen Wang, Siqi Zheng, Chang Zhou, Zhijie Yan, Shiliang Zhang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.04673)
[![citation](https://img.shields.io/badge/citation-13-blue.svg?paper=ffa05cb5504ba08254f498223f613b3ebcf87692)](https://www.semanticscholar.org/paper/ffa05cb5504ba08254f498223f613b3ebcf87692)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://lauragpt.github.io/)

+ **LLaSM: Large Language and Speech Model** (30 Aug 2023)<details><summary>Yu Shu, Siwei Dong, Guangyao Chen, et al.</summary>Yu Shu, Siwei Dong, Guangyao Chen, Wenhao Huang, Ruihua Zhang, Daochen Shi, Qiqi Xiang, Yemin Shi</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.15930)
[![citation](https://img.shields.io/badge/citation-10-blue.svg?paper=7b22ecd9f1ced58c1704ac6191e029b98054e330)](https://www.semanticscholar.org/paper/7b22ecd9f1ced58c1704ac6191e029b98054e330)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://huggingface.co/spaces/LinkSoul/LLaSM)
[![Code](https://img.shields.io/github/stars/LinkSoul-AI/LLaSM.svg?style=social&label=Star)](https://github.com/LinkSoul-AI/LLaSM)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/LinkSoul/LLaSM)

+ **AudioPaLM: A Large Language Model That Can Speak and Listen** (22 Jun 2023)<details><summary>Paul K. Rubenstein, Chulayuth Asawaroengchai, Duc Dung Nguyen, et al.</summary>Paul K. Rubenstein, Chulayuth Asawaroengchai, Duc Dung Nguyen, Ankur Bapna, Zalán Borsos, Félix de Chaumont Quitry, Peter Chen, Dalia El Badawy, Wei Han, Eugene Kharitonov, Hannah Muckenhirn, Dirk Padfield, James Qin, Danny Rozenberg, Tara Sainath, Johan Schalkwyk, Matt Sharifi, Michelle Tadmor Ramanovich, Marco Tagliasacchi, Alexandru Tudor, Mihajlo Velimirović, Damien Vincent, Jiahui Yu, Yongqiang Wang, Vicky Zayats, Neil Zeghidour, Yu Zhang, Zhishuai Zhang, Lukas Zilka, Christian Frank</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.12925)
[![citation](https://img.shields.io/badge/citation-69-blue.svg?paper=3efb81de24eb88017d6dbcf22cb4215084223fd8)](https://www.semanticscholar.org/paper/3efb81de24eb88017d6dbcf22cb4215084223fd8)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://google-research.github.io/seanet/audiopalm/examples/)

+ **Pengi: An Audio Language Model for Audio Tasks** (19 May 2023)<details><summary>Soham Deshmukh, Benjamin Elizalde, Rita Singh, et al.</summary>Soham Deshmukh, Benjamin Elizalde, Rita Singh, Huaming Wang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.11834)
[![citation](https://img.shields.io/badge/citation-35-blue.svg?paper=ad22af138fa1d1490cda0301abf8159a7c30c5a2)](https://www.semanticscholar.org/paper/ad22af138fa1d1490cda0301abf8159a7c30c5a2)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://github.com/microsoft/Pengi)
[![Code](https://img.shields.io/github/stars/microsoft/Pengi.svg?style=social&label=Star)](https://github.com/microsoft/Pengi)

+ **Speechgpt: Empowering large language models with intrinsic cross-modal conversational abilities** (18 May 2023)<details><summary>Dong Zhang, Shimin Li, Xin Zhang, et al.</summary>Dong Zhang, Shimin Li, Xin Zhang, Jun Zhan, Pengyu Wang, Yaqian Zhou, Xipeng Qiu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.11000)
[![citation](https://img.shields.io/badge/citation-76-blue.svg?paper=5cac6430bd379c9d2fe13137dfd6ae7721a2679f)](https://www.semanticscholar.org/paper/5cac6430bd379c9d2fe13137dfd6ae7721a2679f)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://0nutation.github.io/SpeechGPT.github.io/)
[![Code](https://img.shields.io/github/stars/0nutation/SpeechGPT.svg?style=social&label=Star)](https://github.com/0nutation/SpeechGPT)

+ **Sparks of Artificial General Intelligence: Early experiments with GPT-4** (22 Mar 2023)<details><summary>Sébastien Bubeck, Varun Chandrasekaran, Ronen Eldan, et al.</summary>Sébastien Bubeck, Varun Chandrasekaran, Ronen Eldan, Johannes Gehrke, Eric Horvitz, Ece Kamar, Peter Lee, Yin Tat Lee, Yuanzhi Li, Scott Lundberg, Harsha Nori, Hamid Palangi, Marco Tulio Ribeiro, Yi Zhang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.12712)
[![citation](https://img.shields.io/badge/citation-1407-blue.svg?paper=574beee702be3856d60aa482ec725168fe64fc99)](https://www.semanticscholar.org/paper/574beee702be3856d60aa482ec725168fe64fc99)

### Non-LLM-based
+ **Audiobox: Unified Audio Generation with Natural Language Prompts** (25 Dec 2023)\
Apoorv Vyas, Bowen Shi, Matthew Le\
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.15821)
[![citation](https://img.shields.io/badge/citation-6-blue.svg?paper=f124ae1e4663359193be32adb37b07b3252d5329)](https://www.semanticscholar.org/paper/f124ae1e4663359193be32adb37b07b3252d5329)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://audiobox.metademolab.com/)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://audiobox.metademolab.com/capabilities)

+ **Music ControlNet: Multiple Time-varying Controls for Music Generation** (13 Nov 2023)<details><summary>Shih-Lun Wu, Chris Donahue, Shinji Watanabe, et al.</summary>Shih-Lun Wu, Chris Donahue, Shinji Watanabe, Nicholas J. Bryan</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.07069)
[![citation](https://img.shields.io/badge/citation-3-blue.svg?paper=42239e71a712d70cd24e06ffc0cf0d22fc628a36)](https://www.semanticscholar.org/paper/42239e71a712d70cd24e06ffc0cf0d22fc628a36)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://musiccontrolnet.github.io/web/)

+ **Loop Copilot: Conducting AI Ensembles for Music Generation and Iterative Editing** (19 Oct 2023)<details><summary>Yixiao Zhang, Akira Maezawa, Gus Xia, et al.</summary>Yixiao Zhang, Akira Maezawa, Gus Xia, Kazuhiko Yamamoto, Simon Dixon</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.12404)
[![citation](https://img.shields.io/badge/citation-3-blue.svg?paper=cca4218dd7c10c1614bbd84aa7cd7e00027bdc7c)](https://www.semanticscholar.org/paper/cca4218dd7c10c1614bbd84aa7cd7e00027bdc7c)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://sites.google.com/view/loop-copilot)
[![Code](https://img.shields.io/github/stars/ldzhangyx/loop-copilot.svg?style=social&label=Star)](https://github.com/ldzhangyx/loop-copilot/)

+ **MusicAgent: An AI Agent for Music Understanding and Generation with Large Language Models** (18 Oct 2023)<details><summary>Dingyao Yu, Kaitao Song, Peiling Lu, et al.</summary>Dingyao Yu, Kaitao Song, Peiling Lu, Tianyu He, Xu Tan, Wei Ye, Shikun Zhang, Jiang Bian</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.11954)
[![citation](https://img.shields.io/badge/citation-2-blue.svg?paper=beaf64df85f8204b8cd89a7f46827608e6d16922)](https://www.semanticscholar.org/paper/beaf64df85f8204b8cd89a7f46827608e6d16922)
[![Code](https://img.shields.io/github/stars/microsoft/muzic/tree/main/musicagent.svg?style=social&label=Star)](https://github.com/microsoft/muzic/tree/main/musicagent)

+ **UniAudio: An Audio Foundation Model Toward Universal Audio Generation** (1 Oct 2023)\
Dongchao Yang, Jinchuan Tian, Xu Tan\
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.00704)
[![citation](https://img.shields.io/badge/citation-15-blue.svg?paper=74bfbbb7307a7af2686043ea97ab8b34cb062ba8)](https://www.semanticscholar.org/paper/74bfbbb7307a7af2686043ea97ab8b34cb062ba8)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://dongchaoyang.top/UniAudio_demo/)
[![Code](https://img.shields.io/github/stars/yangdongchao/UniAudio.svg?style=social&label=Star)](https://github.com/yangdongchao/UniAudio)

+ **AudioLM: a Language Modeling Approach to Audio Generation** (7 Sep 2022)<details><summary>Zalán Borsos, Raphaël Marinier, Damien Vincent, et al. (IEEE/ACM Transactions on Audio, Speech, and Language Processing)</summary>Zalán Borsos, Raphaël Marinier, Damien Vincent, Eugene Kharitonov, Olivier Pietquin, Matt Sharifi, Dominik Roblek, Olivier Teboul, David Grangier, Marco Tagliasacchi, Neil Zeghidour</details>[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2209.03143)
[![citation](https://img.shields.io/badge/citation-232-blue.svg?paper=8c870bef01a4fbb20f60722ffc2f6bee3870b18b)](https://www.semanticscholar.org/paper/8c870bef01a4fbb20f60722ffc2f6bee3870b18b)

+ **Wavjourney: Compositional audio creation with large language models** (26 Jul 2023)<details><summary>Xubo Liu, Zhongkai Zhu, Haohe Liu, et al.</summary>Xubo Liu, Zhongkai Zhu, Haohe Liu, Yi Yuan, Meng Cui, Qiushi Huang, Jinhua Liang, Yin Cao, Qiuqiang Kong, Mark D. Plumbley, Wenwu Wang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2307.14335)
[![citation](https://img.shields.io/badge/citation-9-blue.svg?paper=aa7bcd1f9453c9096ec78900a7b94e816ed0e1c5)](https://www.semanticscholar.org/paper/aa7bcd1f9453c9096ec78900a7b94e816ed0e1c5)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://audio-agi.github.io/WavJourney_demopage/)
[![Code](https://img.shields.io/github/stars/Audio-AGI/WavJourney.svg?style=social&label=Star)](https://github.com/Audio-AGI/WavJourney)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/Audio-AGI/WavJourney)

+ **Investigating the Utility of Surprisal from Large Language Models for Speech Synthesis Prosody** (16 Jun 2023)<details><summary>Sofoklis Kakouros, Juraj Šimko, Martti Vainio, et al. (2023 SSW)</summary>Sofoklis Kakouros, Juraj Šimko, Martti Vainio, Antti Suni</details>[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.09814)
[![citation](https://img.shields.io/badge/citation-2-blue.svg?paper=63aad36dc981348493be6743292a04234b29ba4e)](https://www.semanticscholar.org/paper/63aad36dc981348493be6743292a04234b29ba4e)

+ **Simple and Controllable Music Generation** (8 Jun 2023)<details><summary>Jade Copet, Felix Kreuk, Itai Gat, et al.</summary>Jade Copet, Felix Kreuk, Itai Gat, Tal Remez, David Kant, Gabriel Synnaeve, Yossi Adi, Alexandre Défossez</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.05284)
[![citation](https://img.shields.io/badge/citation-71-blue.svg?paper=4cc8e18f5eece0b0d8e1abcb8ee10fb33680fbb2)](https://www.semanticscholar.org/paper/4cc8e18f5eece0b0d8e1abcb8ee10fb33680fbb2)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://ai.honu.io/papers/musicgen/)
[![Code](https://img.shields.io/github/stars/facebookresearch/audiocraft.svg?style=social&label=Star)](https://github.com/facebookresearch/audiocraft)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/facebook/MusicGen)

+ **Make-An-Audio 2: Temporal-Enhanced Text-to-Audio Generation** (29 May 2023)<details><summary>Jiawei Huang, Yi Ren, Rongjie Huang, et al.</summary>Jiawei Huang, Yi Ren, Rongjie Huang, Dongchao Yang, Zhenhui Ye, Chen Zhang, Jinglin Liu, Xiang Yin, Zejun Ma, Zhou Zhao</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.18474)
[![citation](https://img.shields.io/badge/citation-10-blue.svg?paper=83d4b22d803ae856cf6b308482bd504fa151d39e)](https://www.semanticscholar.org/paper/83d4b22d803ae856cf6b308482bd504fa151d39e)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://make-an-audio-2.github.io/)

+ **Audiogpt: Understanding and generating speech, music, sound, and talking head** (25 Apr 2023)<details><summary>Rongjie Huang, Mingze Li, Dongchao Yang, et al.</summary>Rongjie Huang, Mingze Li, Dongchao Yang, Jiatong Shi, Xuankai Chang, Zhenhui Ye, Yuning Wu, Zhiqing Hong, Jiawei Huang, Jinglin Liu, Yi Ren, Zhou Zhao, Shinji Watanabe</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.12995)
[![citation](https://img.shields.io/badge/citation-83-blue.svg?paper=8bc617c9139648d7a92991d70c671230bac7b2e2)](https://www.semanticscholar.org/paper/8bc617c9139648d7a92991d70c671230bac7b2e2)
[![Code](https://img.shields.io/github/stars/AIGC-Audio/AudioGPT.svg?style=social&label=Star)](https://github.com/AIGC-Audio/AudioGPT)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/AIGC-Audio/AudioGPT)

+ **TANGO: Text-to-Audio Generation using Instruction Tuned LLM and Latent Diffusion Model** (24 Apr 2023)<details><summary>Deepanway Ghosal, Navonil Majumder, Ambuj Mehrish, et al.</summary>Deepanway Ghosal, Navonil Majumder, Ambuj Mehrish, Soujanya Poria</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.13731)
[![citation](https://img.shields.io/badge/citation-51-blue.svg?paper=f51bc74814a3452009ea5ca262d9768d08149ee6)](https://www.semanticscholar.org/paper/f51bc74814a3452009ea5ca262d9768d08149ee6)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://tango-web.github.io/)
[![Code](https://img.shields.io/github/stars/declare-lab/tango.svg?style=social&label=Star)](https://github.com/declare-lab/tango)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/declare-lab/tango)

+ **Hugginggpt: Solving ai tasks with chatgpt and its friends in huggingface** (30 Mar 2023)<details><summary>Yongliang Shen, Kaitao Song, Xu Tan, et al.</summary>Yongliang Shen, Kaitao Song, Xu Tan, Dongsheng Li, Weiming Lu, Yueting Zhuang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.17580)
[![citation](https://img.shields.io/badge/citation-413-blue.svg?paper=d1120d67b700e4dfe8b39eb1e48fbdea4e1a0c43)](https://www.semanticscholar.org/paper/d1120d67b700e4dfe8b39eb1e48fbdea4e1a0c43)
[![Code](https://img.shields.io/github/stars/microsoft/JARVIS.svg?style=social&label=Star)](https://github.com/microsoft/JARVIS)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/microsoft/HuggingGPT)

+ **Neural codec language models are zero-shot text to speech synthesizers** (5 Jan 2023)<details><summary>Chengyi Wang, Sanyuan Chen, Yu Wu, et al.</summary>Chengyi Wang, Sanyuan Chen, Yu Wu, Ziqiang Zhang, Long Zhou, Shujie Liu, Zhuo Chen, Yanqing Liu, Huaming Wang, Jinyu Li, Lei He, Sheng Zhao, Furu Wei</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2301.02111)
[![citation](https://img.shields.io/badge/citation-203-blue.svg?paper=c2f91f35df893714418cc29096083dce0b441229)](https://www.semanticscholar.org/paper/c2f91f35df893714418cc29096083dce0b441229)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://www.microsoft.com/en-us/research/project/vall-e-x/)

+ **MusicLM: Generating Music From Text** (26 Jan 2023)<details><summary>Andrea Agostinelli, Timo I. Denk, Zalán Borsos, et al.</summary>Andrea Agostinelli, Timo I. Denk, Zalán Borsos, Jesse Engel, Mauro Verzetti, Antoine Caillon, Qingqing Huang, Aren Jansen, Adam Roberts, Marco Tagliasacchi, Matt Sharifi, Neil Zeghidour, Christian Frank</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2301.11325)
[![citation](https://img.shields.io/badge/citation-171-blue.svg?paper=428854d9e75f94f0e61f37c6887c77800437d516)](https://www.semanticscholar.org/paper/428854d9e75f94f0e61f37c6887c77800437d516)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://google-research.github.io/seanet/musiclm/examples/)
### Datasets
+ **Libriheavy: a 50,000 hours ASR corpus with punctuation casing and context** (15 Sep 2023)<details><summary>Wei Kang, Xiaoyu Yang, Zengwei Yao, et al.</summary>Wei Kang, Xiaoyu Yang, Zengwei Yao, Fangjun Kuang, Yifan Yang, Liyong Guo, Long Lin, Daniel Povey</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.08105)
[![citation](https://img.shields.io/badge/citation-2-blue.svg?paper=e99b45179686982401d2d6ec919e42b327f04c0b)](https://www.semanticscholar.org/paper/e99b45179686982401d2d6ec919e42b327f04c0b)

## Generation with Multiple Modalities
### 🔅 LLM-based



+ **C3LLM: Conditional Multimodal Content Generation Using Large Language Models** (25 May 2024) <details><summary>Zixuan Wang, Qinkai Duan, Yu-Wing Tai, et al.</summary>Zixuan Wang, Qinkai Duan, Yu-Wing Tai, Chi-Keung Tang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.16136)
[![citation](https://img.shields.io/badge/citation-0-blue.svg?paper=78582ad19779a69d97b797a3c6eb2397f99398b6)](https://www.semanticscholar.org/paper/C3LLM%3A-Conditional-Multimodal-Content-Generation-Wang-Duan/f9151b94ff5476cf155c085cf4c3280715cf9bde)



+ **CoDi-2: In-Context, Interleaved, and Interactive Any-to-Any Generation** (30 Nov 2023) <details><summary>Zineng Tang, Ziyi Yang, Mahmoud Khademi, et al.</summary>Zineng Tang, Ziyi Yang, Mahmoud Khademi, Yang Liu, Chenguang Zhu, Mohit Bansal</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.18775)
[![citation](https://img.shields.io/badge/citation-5-blue.svg?paper=78582ad19779a69d97b797a3c6eb2397f99398b6)](https://www.semanticscholar.org/paper/78582ad19779a69d97b797a3c6eb2397f99398b6)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://codi-2.github.io/)
[![Code](https://img.shields.io/github/stars/microsoft/i-Code.svg?style=social&label=Star)](https://github.com/microsoft/i-Code/tree/main/CoDi-2)



+ **TEAL: Tokenize and Embed ALL for Multi-modal Large Language Models** (8 Nov 2023)<details><summary>Zhen Yang, Yingxue Zhang, Fandong Meng, et al.</summary>Zhen Yang, Yingxue Zhang, Fandong Meng, Jie Zhou</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.04589)
[![citation](https://img.shields.io/badge/citation-1-blue.svg?paper=9f411fda2ad5b141a3115f707bcf5ee865b3fb94)](https://www.semanticscholar.org/paper/TEAL%3A-Tokenize-and-Embed-ALL-for-Multi-modal-Large-Yang-Zhang/59d716b442ab760a78f58de6748c0fa1d507bfc1)
`tokenizer`



+ **NExT-GPT: Any-to-Any Multimodal LLM** (11 Sep 2023)<details><summary>Shengqiong Wu, Hao Fei, Leigang Qu, et al.</summary>Shengqiong Wu, Hao Fei, Leigang Qu, Wei Ji, Tat-Seng Chua</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.05519)
[![citation](https://img.shields.io/badge/citation-94-blue.svg?paper=fa75a55760e6ea49b39b83cb85c99a22e1088254)](https://www.semanticscholar.org/paper/fa75a55760e6ea49b39b83cb85c99a22e1088254)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://next-gpt.github.io/)
[![Code](https://img.shields.io/github/stars/NExT-GPT/NExT-GPT.svg?style=social&label=Star)](https://github.com/NExT-GPT/NExT-GPT)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://1ca8b1601858a12830.gradio.live/)


+ **CoDi: Any-to-Any Generation via Composable Diffusion** (19 May 2023)<details><summary>[NeurIPS 2023] Zineng Tang, Ziyi Yang, Chenguang Zhu, et al.</summary>Zineng Tang, Ziyi Yang, Chenguang Zhu, Michael Zeng, Mohit Bansal</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.11846)
[![citation](https://img.shields.io/badge/citation-41-blue.svg?paper=9f411fda2ad5b141a3115f707bcf5ee865b3fb94)](https://www.semanticscholar.org/paper/9f411fda2ad5b141a3115f707bcf5ee865b3fb94)
[![Code](https://img.shields.io/github/stars/microsoft/i-Code.svg?style=social&label=Star)](https://github.com/microsoft/i-Code/tree/main/i-Code-V3)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://codi-gen.github.io/)



### Non-LLM-based


+ **DiffSHEG: A Diffusion-Based Approach for Real-Time Speech-driven Holistic 3D Expression and Gesture Generation** (9 Jan 2024)<details><summary>[CVPR 2024] Junming Chen, et al.</summary>Junming Chen, Yunfei Liu, Jianan Wang, Ailing Zeng, Yu Li, Qifeng Chen</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.04747)
[![citation](https://img.shields.io/badge/citation-4-blue.svg?paper=1370d74ff6f7857a84da952e2f4cb6f42da40615)](https://www.semanticscholar.org/paper/1370d74ff6f7857a84da952e2f4cb6f42da40615)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://jeremycjm.github.io/proj/DiffSHEG/)
[![Code](https://img.shields.io/github/stars/JeremyCJM/DiffSHEG.svg?style=social&label=Star)](https://github.com/JeremyCJM/DiffSHEG) 

+ **TAVGBench: Benchmarking Text to Audible-Video Generation** (22 Apr 2024)<details><summary>Yuxin Mao, Xuyang Shen, Jing Zhang, et al.</summary>Yuxin Mao, Xuyang Shen, Jing Zhang, Zhen Qin, Jinxing Zhou, Mochu Xiang, Yiran Zhong, Yuchao Dai</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.14381)
[![citation](https://img.shields.io/badge/citation-0-blue.svg?paper=21a77ed349c8621d0a0ef8407eb744e3de3b13c5)](https://www.semanticscholar.org/paper/TAVGBench%3A-Benchmarking-Text-to-Audible-Video-Mao-Shen/4ba90678411ddc0a2eb997e1184b059bdc955fd5)
[![Code](https://img.shields.io/github/stars/Vchitect/VBench.svg?style=social&label=Star)](https://github.com/OpenNLPLab/TAVGBench)


+ **Seeing and Hearing: Open-domain Visual-Audio Generation with Diffusion Latent Aligners** (27 Feb 2024)<details><summary>[CVPR 2024] Yazhou Xing, Yingqing He, Zeyue Tian, et al.</summary>Yazhou Xing, Yingqing He, Zeyue Tian, Xintao Wang, Qifeng Chen</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.17723)
[![citation](https://img.shields.io/badge/citation-4-blue.svg?paper=21a77ed349c8621d0a0ef8407eb744e3de3b13c5)](https://www.semanticscholar.org/paper/Seeing-and-Hearing%3A-Open-domain-Visual-Audio-with-Xing-He/d9822d11ae4ead1f1d32c43124a6a0eb80ea4f0c)
[![Code](https://img.shields.io/github/stars/Vchitect/VBench.svg?style=social&label=Star)](https://github.com/yzxing87/Seeing-and-Hearing)



# 📍 Multimodal Editing

## Image Editing

### 🔅 LLM-based



+ **UltraEdit: Instruction-based Fine-Grained Image Editing at Scale** (7 Jul 2024)<details><summary>Haozhe Zhao, Xiaojian Ma, Liang Chen, et al.</summary> Haozhe Zhao, Xiaojian Ma, Liang Chen, Shuzheng Si, Rujie Wu, Kaikai An, Peiyu Yu, Minjia Zhang, Qing Li, Baobao Chang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.06739)
[![citation](https://img.shields.io/badge/citation-16-blue.svg?paper=388b0f44faf0a14cc402c2554ec36a868cf59129)](https://www.semanticscholar.org/paper/SmartEdit%3A-Exploring-Complex-Instruction-Based-with-Huang-Xie/388b0f44faf0a14cc402c2554ec36a868cf59129)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://ultra-editing.github.io/)
[![Code](https://img.shields.io/github/stars/HaozheZhao/UltraEdit.svg?style=social&label=Star)](https://github.com/HaozheZhao/UltraEdit)


+ **SmartEdit: Exploring Complex Instruction-based Image Editing with Multimodal Large Language Models** (11 Dec 2023)<details><summary>[CVPR 2024] Yuzhou Huang, Liangbin Xie, Xintao Wang, et al.</summary> Yuzhou Huang, Liangbin Xie, Xintao Wang, Ziyang Yuan, Xiaodong Cun, Yixiao Ge, Jiantao Zhou, Chao Dong, Rui Huang, Ruimao Zhang, Ying Shan</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.06739)
[![citation](https://img.shields.io/badge/citation-1-blue.svg?paper=388b0f44faf0a14cc402c2554ec36a868cf59129)](https://www.semanticscholar.org/paper/388b0f44faf0a14cc402c2554ec36a868cf59129)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://yuzhou914.github.io/SmartEdit/)
[![Code](https://img.shields.io/github/stars/TencentARC/SmartEdit.svg?style=social&label=Star)](https://github.com/TencentARC/SmartEdit)


+ **Self-correcting LLM-controlled Diffusion Models** (27 Nov 2023)<details><summary>[CVPR 2024] Tsung-Han Wu, Long Lian, Joseph E. Gonzalez, et al.</summary> Tsung-Han Wu, Long Lian, Joseph E. Gonzalez, Boyi Li, Trevor Darrell</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.16090)
[![citation](https://img.shields.io/badge/citation-4-blue.svg?paper=42c4315b5d2e33d7d9a0afdf84e6a47ccd7a700e)](https://www.semanticscholar.org/paper/42c4315b5d2e33d7d9a0afdf84e6a47ccd7a700e)


+ **Emu Edit: Precise Image Editing via Recognition and Generation Tasks** (16 Nov 2023)<details><summary>[ArXiv 2023] Shelly Sheynin, Adam Polyak, Uriel Singer, et al.</summary> Shelly Sheynin, Adam Polyak, Uriel Singer, Yuval Kirstain, Amit Zohar, Oron Ashual, Devi Parikh, Yaniv Taigman</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.10089)
[![citation](https://img.shields.io/badge/citation-8-blue.svg?paper=5bcb0153dd0840113eb27d4d6f753414ef656a03)](https://www.semanticscholar.org/paper/5bcb0153dd0840113eb27d4d6f753414ef656a03)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://emu-edit.metademolab.com/)


+ **Guiding Instruction-based Image Editing via Multimodal Large Language Models** <details><summary>[ICLR 2024 (Spotlight)] Tsu-Jui Fu, Wenze Hu, Xianzhi Du, et al.</summary> Tsu-Jui Fu, Wenze Hu, Xianzhi Du, William Yang Wang, Yinfei Yang, Zhe Gan</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.17102v1)
[![citation](https://img.shields.io/badge/citation-11-blue.svg?paper=092245d86b77181c36f972b1b7a17a59cd989c4a)](https://www.semanticscholar.org/paper/092245d86b77181c36f972b1b7a17a59cd989c4a)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://mllm-ie.github.io/)
[![Code](https://img.shields.io/github/stars/tsujuifu/pytorch_mgie.svg?style=social&label=Star)](https://github.com/tsujuifu/pytorch_mgie)




+ **CHATEDIT: Towards Multi-turn Interactive Facial Image Editing via Dialogue** (20 Mar 2023)<details><summary>[EMNLP 2023] Xing Cui, Zekun Li, Peipei Li, et al.</summary> Xing Cui, Zekun Li, Peipei Li, Yibo Hu, Hailin Shi, Zhaofeng He</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.11108)
[![citation](https://img.shields.io/badge/citation-1-blue.svg?paper=5a185965ad1e87367d044b47043706d00b85b007)](https://www.semanticscholar.org/paper/5a185965ad1e87367d044b47043706d00b85b007)
[![Code](https://img.shields.io/github/stars/cuixing100876/ChatEdit.svg?style=social&label=Star)](https://github.com/cuixing100876/ChatEdit)




+ **HIVE: Harnessing Human Feedback for Instructional Visual Editing** (16 Mar 2023)<details><summary>Shu Zhang, Xinyi Yang, Yihao Feng, et al.</summary> Shu Zhang, Xinyi Yang, Yihao Feng, Can Qin, Chia-Chih Chen, Ning Yu, Zeyuan Chen, Huan Wang, Silvio Savarese, Stefano Ermon, Caiming Xiong, Ran Xu.</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.09618)
[![citation](https://img.shields.io/badge/citation-28-blue.svg?paper=372bc41602bbd21f192305775f0a58de9880e454)](https://www.semanticscholar.org/paper/372bc41602bbd21f192305775f0a58de9880e454)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://shugerdou.github.io/hive/)
[![Code](https://img.shields.io/github/stars/salesforce/HIVE.svg?style=social&label=Star)](https://github.com/salesforce/HIVE)


+ **Visual ChatGPT: Talking, Drawing and Editing with Visual Foundation Models** (8 Mar 2023) <details><summary>Chenfei Wu, Shengming Yin, Weizhen Qi, et al.</summary> Chenfei Wu, Shengming Yin, Weizhen Qi, Xiaodong Wang, Zecheng Tang, Nan Duan</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.04671)
[![citation](https://img.shields.io/badge/citation-337-blue.svg?paper=af997821231898a5f8d0fd78dad4eec526acabe5)](https://www.semanticscholar.org/paper/af997821231898a5f8d0fd78dad4eec526acabe5)
[![Code](https://img.shields.io/github/stars/microsoft/JARVIS.svg?style=social&label=Star)](https://github.com/moymix/TaskMatrix)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/microsoft/visual_chatgpt)

+ **InstructPix2Pix: Learning to Follow Image Editing Instructions** (17 Nov 2022)\
[CVPR 2023 (Highlight)] Brooks, Tim, Aleksander Holynski, and Alexei A. Efros.\
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2211.09800)
[![citation](https://img.shields.io/badge/citation-582-blue.svg?paper=a2d2bbe4c542173662a444b33b76c66992697830)](https://www.semanticscholar.org/paper/a2d2bbe4c542173662a444b33b76c66992697830)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://www.timothybrooks.com/instruct-pix2pix)
[![Code](https://img.shields.io/github/stars/timothybrooks/instruct-pix2pix.svg?style=social&label=Star)](https://github.com/timothybrooks/instruct-pix2pix)



### Non-LLM-based (Clip/T5)

+ **DiffEditor: Boosting Accuracy and Flexibility on Diffusion-based Image Editing** (4 Feb 2024)<details><summary>[CVPR 2024] Chong Mou, Xintao Wang, Jiechong Song, et al.</summary>Chong Mou, Xintao Wang, Jiechong Song, Ying Shan, Jian Zhang. </details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.02583)
[![citation](https://img.shields.io/badge/citation-1-blue.svg?paper=198b3d809594a76bc473927af37b858132ac7fdd)](https://www.semanticscholar.org/paper/198b3d809594a76bc473927af37b858132ac7fdd)
[![Code](https://img.shields.io/github/stars/MC-E/DragonDiffusion.svg?style=social&label=Star)](https://github.com/MC-E/DragonDiffusion)



+ **ZONE: Zero-Shot Instruction-Guided Local Editing** (28 Dec 2023)<details><summary>Shanglin Li, Bohan Zeng, Yutang Feng, et al.</summary>Shanglin Li, Bohan Zeng, Yutang Feng, Sicheng Gao, Xuhui Liu, Jiaming Liu, Li Lin, Xu Tang, Yao Hu, Jianzhuang Liu, Baochang Zhang. </details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.16794)
[![citation](https://img.shields.io/badge/citation-0-blue.svg?paper=05eb2ad3af471c05a24abbf70258688e579cdf22)](https://www.semanticscholar.org/paper/05eb2ad3af471c05a24abbf70258688e579cdf22)




+ **Watch Your Steps: Local Image and Scene Editing by Text Instructions** (17 Aug 2023 )<details><summary>Ashkan Mirzaei, Tristan Aumentado-Armstrong, Marcus A. Brubaker, et al.</summary>Ashkan Mirzaei, Tristan Aumentado-Armstrong, Marcus A. Brubaker, Jonathan Kelly, Alex Levinshtein, Konstantinos G. Derpanis, Igor Gilitschenski. </details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.08947)
[![citation](https://img.shields.io/badge/citation-9-blue.svg?paper=737ad8905228cd410e3342b5cceefd4feb57d166)](https://www.semanticscholar.org/paper/737ad8905228cd410e3342b5cceefd4feb57d166)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://ashmrz.github.io/WatchYourSteps/)


+ **Dragondiffusion: Enabling drag-style manipulation on diffusion models** (5 Jul 2023)<details><summary>[ICLR 2024] Chong Mou, Xintao Wang, Jiechong Song, et al.</summary>Chong Mou, Xintao Wang, Jiechong Song, Ying Shan, Jian Zhang. </details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2307.14331)
[![citation](https://img.shields.io/badge/citation-36-blue.svg?paper=2cfaa5b3571d3b75f040f6d639359a3c673f5561)](https://www.semanticscholar.org/paper/2cfaa5b3571d3b75f040f6d639359a3c673f5561)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://mc-e.github.io/project/DragonDiffusion/)
[![Code](https://img.shields.io/github/stars/MC-E/DragonDiffusion.svg?style=social&label=Star)](https://github.com/MC-E/DragonDiffusion)


+ **Differential Diffusion: Giving Each Pixel Its Strength** (1 Jun 2023)<details><summary>[Arxiv 2023] Thao Nguyen, Yuheng Li, Utkarsh Ojha, et al.</summary>Thao Nguyen, Yuheng Li, Utkarsh Ojha, Yong Jae Lee</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2307.14331)
[![citation](https://img.shields.io/badge/citation-3-blue.svg?paper=6e5760e5d4b468bbf01a95a6f64bd65c3aa3d798)](https://www.semanticscholar.org/paper/6e5760e5d4b468bbf01a95a6f64bd65c3aa3d798)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://differential-diffusion.github.io/)
[![Code](https://img.shields.io/github/stars/exx8/differential-diffusion.svg?style=social&label=Star)](https://github.com/exx8/differential-diffusion)


+ **Visual Instruction Inversion: Image Editing via Visual Prompting** (26 Jul 2023)<details><summary>[ArXiv 2023] Thao Nguyen, Yuheng Li, Utkarsh Ojha, et al.</summary> Thao Nguyen, Yuheng Li, Utkarsh Ojha, Yong Jae Lee. </details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2307.14331)
[![citation](https://img.shields.io/badge/citation-11-blue.svg?paper=f4c62aa336de45273e0fdfcfbd65b3c2e552ad56)](https://www.semanticscholar.org/paper/f4c62aa336de45273e0fdfcfbd65b3c2e552ad56)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://thaoshibe.github.io/visii/)
[![Code](https://img.shields.io/github/stars/thaoshibe/visii.svg?style=social&label=Star)](https://github.com/thaoshibe/visii)

+ **MasaCtrl: Tuning-Free Mutual Self-Attention Control for Consistent Image Synthesis and Editing** (17 Apr 2023)<details><summary>[ICCV 2023] Mingdeng Cao, Xintao Wang, Zhongang Qi, et al.</summary> Mingdeng Cao, Xintao Wang, Zhongang Qi, Ying Shan, Xiaohu Qie, Yinqiang Zheng. </details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.08947)
[![citation](https://img.shields.io/badge/citation-102-blue.svg?paper=85963807c11abe38e9a2797d9860e012238607ef)](https://www.semanticscholar.org/paper/85963807c11abe38e9a2797d9860e012238607ef)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://ljzycmd.github.io/projects/MasaCtrl/)
[![Code](https://img.shields.io/github/stars/TencentARC/MasaCtrl.svg?style=social&label=Star)](https://github.com/TencentARC/MasaCtrl)


+ **PAIR-Diffusion: A Comprehensive Multimodal Object-Level Image Editor** (30 Mar 2023)<details><summary>[ArXiv 2023] Vidit Goel, Elia Peruzzo, Yifan Jiang, et al.</summary> Vidit Goel, Elia Peruzzo, Yifan Jiang, Dejia Xu, Xingqian Xu, Nicu Sebe, Trevor Darrell, Zhangyang Wang, Humphrey Shi. </details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.17546)
[![citation](https://img.shields.io/badge/citation-0-blue.svg?paper=c614a4da924466f62ca39002af425c9d14d240a3)](https://www.semanticscholar.org/paper/c614a4da924466f62ca39002af425c9d14d240a3)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://vidit98.github.io/publication/conference-paper/pair_diff.html)
[![Code](https://img.shields.io/github/stars/pix2pixzero/pix2pix-zero.svg?style=social&label=Star)](https://github.com/Picsart-AI-Research/PAIR-Diffusion)



+ **Zero-shot Image-to-Image Translation** (6 Feb 2023)<details><summary>[SIGGRAPH 2023] Gaurav Parmar, Krishna Kumar Singh, Richard Zhang, et al.</summary> Gaurav Parmar, Krishna Kumar Singh, Richard Zhang, Yijun Li, Jingwan Lu, Jun-Yan Zhu. </details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2302.03027)
[![citation](https://img.shields.io/badge/citation-159-blue.svg?paper=daf61010eee0fbf6f9bab7db71c395ffca6f3ff3)](https://www.semanticscholar.org/paper/daf61010eee0fbf6f9bab7db71c395ffca6f3ff3)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://pix2pixzero.github.io/)
[![Code](https://img.shields.io/github/stars/pix2pixzero/pix2pix-zero.svg?style=social&label=Star)](https://github.com/pix2pixzero/pix2pix-zero)

+ **SINE: SINgle Image Editing with Text-to-Image Diffusion Models** (8 Dec 2022)<details><summary>[CVPR 2023] Zhixing Zhang, Ligong Han, Arnab Ghosh, et al.</summary> Zhixing Zhang, Ligong Han, Arnab Ghosh, Dimitris Metaxas, Jian Ren. </details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2212.04489)
[![citation](https://img.shields.io/badge/citation-69-blue.svg?paper=a6ad30123bef4b19ee40c3d63cfabf00d211f0ef)](https://www.semanticscholar.org/paper/a6ad30123bef4b19ee40c3d63cfabf00d211f0ef)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://zhang-zx.github.io/SINE/)
[![Code](https://img.shields.io/github/stars/zhang-zx/SINE.svg?style=social&label=Star)](https://github.com/zhang-zx/SINE)

+ **Interactive Image Manipulation with Complex Text Instructions** (25 Nov 2022)<details><summary>[WACV 2023] Ryugo Morita, Zhiqiang Zhang, Man M. Ho, et al.</summary> Ryugo Morita, Zhiqiang Zhang, Man M. Ho, Jinjia Zhou. </details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2211.15352)
[![citation](https://img.shields.io/badge/citation-1-blue.svg?paper=387144d293567408c363313aac971294e7ec8547)](https://www.semanticscholar.org/paper/387144d293567408c363313aac971294e7ec8547)


+ **Plug-and-Play Diffusion Features for Text-Driven Image-to-Image Translation** (22 Nov 2022)<details><summary>[CVPR 2023] Narek Tumanyan, Michal Geyer, Shai Bagon, et al.</summary> Narek Tumanyan, Michal Geyer, Shai Bagon, Tali Dekel. </details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2211.12572)
[![citation](https://img.shields.io/badge/citation-224-blue.svg?paper=b000d6865db824af1563708fb7a545ddd65c6b3a)](https://www.semanticscholar.org/paper/b000d6865db824af1563708fb7a545ddd65c6b3a)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://pnp-diffusion.github.io/)
[![Code](https://img.shields.io/github/stars/MichalGeyer/plug-and-play.svg?style=social&label=Star)](https://github.com/MichalGeyer/plug-and-play)

+ **Imagic: Text-Based Real Image Editing with Diffusion Models** (17 Oct 2022)<details><summary>[CVPR 2023] Bahjat Kawar, Shiran Zada, Oran Lang, et al.</summary> Bahjat Kawar, Shiran Zada, Oran Lang, Omer Tov, Huiwen Chang, Tali Dekel, Inbar Mosseri, Michal Irani. </details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2210.09276)
[![citation](https://img.shields.io/badge/citation-496-blue.svg?paper=23e261a20a315059b4de5492ed071c97a20c12e7)](https://www.semanticscholar.org/paper/23e261a20a315059b4de5492ed071c97a20c12e7)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://imagic-editing.github.io/)
<!-- [![Code](https://img.shields.io/github/stars/pix2pixzero/pix2pix-zero.svg?style=social&label=Star)](https://github.com/pix2pixzero/pix2pix-zero) -->



+ **Null-text Inversion for Editing Real Images using Guided Diffusion Models**<details><summary>[ICLR 2023] Ron Mokady, Amir Hertz, Kfir Aberman, et al.</summary> Ron Mokady, Amir Hertz, Kfir Aberman, Yael Pritch, Daniel Cohen-Or. </details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2211.09794)
[![citation](https://img.shields.io/badge/citation-N/A-blue.svg?paper=4de94949daf9bc8dd0e5161d20dfe83198d20ec1)](https://www.semanticscholar.org/paper/4de94949daf9bc8dd0e5161d20dfe83198d20ec1)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://null-text-inversion.github.io/)
[![Code](https://img.shields.io/github/stars/google/prompt-to-prompt.svg?style=social&label=Star)](https://github.com/google/prompt-to-prompt/#null-text-inversion-for-editing-real-images)


+ **Prompt-to-Prompt Image Editing with Cross Attention Control** <details><summary>[ICLR 2023] Amir Hertz, Ron Mokady, Jay Tenenbaum, et al.</summary> Amir Hertz, Ron Mokady, Jay Tenenbaum, Kfir Aberman, Yael Pritch, Daniel Cohen-Or. </details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2208.01626)
[![citation](https://img.shields.io/badge/citation-717-blue.svg?paper=04e541391e8dce14d099d00fb2c21dbbd8afe87f)](https://www.semanticscholar.org/paper/04e541391e8dce14d099d00fb2c21dbbd8afe87f)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://prompt-to-prompt.github.io/)
[![Code](https://img.shields.io/github/stars/google/prompt-to-prompt.svg?style=social&label=Star)](https://github.com/google/prompt-to-prompt)


+ **DiffEdit: Diffusion-based semantic image editing with mask guidance** (20 Oct 2022) <details><summary>[ICLR 2023] Guillaume Couairon, Jakob Verbeek, Holger Schwenk, et al.</summary> Guillaume Couairon, Jakob Verbeek, Holger Schwenk, Matthieu Cord. </details> 
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2210.11427)
[![citation](https://img.shields.io/badge/citation-208-blue.svg?paper=064ccebc03d3afabaae30fe29a457c1cfcdff7e3)](https://www.semanticscholar.org/paper/064ccebc03d3afabaae30fe29a457c1cfcdff7e3)
<!-- [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://ashmrz.github.io/WatchYourSteps/) -->
<!-- [![Code](https://img.shields.io/github/stars/Xiang-cd/DiffEdit-stable-diffusion.svg?style=social&label=Star)](https://github.com/Xiang-cd/DiffEdit-stable-diffusion) -->


## Video Editing

### 🔅 LLM-based


+ **CONSISTENT VIDEO-TO-VIDEO TRANSFER USING SYNTHETIC DATASET** (1 Nov 2023)\
Jiaxin Cheng, Tianjun Xiao, Tong He.\
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.00213)
[![citation](https://img.shields.io/badge/citation-2-blue.svg?paper=e8bbffb8413cb1f88e99a7ecbabd21a6eac82271)](https://www.semanticscholar.org/paper/e8bbffb8413cb1f88e99a7ecbabd21a6eac82271)
[![Code](https://img.shields.io/github/stars/amazon-science/instruct-video-to-video.svg?style=social&label=Star)](https://github.com/amazon-science/instruct-video-to-video)

+ **InstructVid2Vid: Controllable Video Editing with Natural Language Instructions** (21 May 2023)<details><summary>Bosheng Qin, Juncheng Li, Siliang Tang, et al.</summary>Bosheng Qin, Juncheng Li, Siliang Tang, Tat-Seng Chua, Yueting Zhuang. </details> [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.12328)
[![citation](https://img.shields.io/badge/citation-6-blue.svg?paper=205d2ed0906440f07a0275d7d6a63bced60951fc)](https://www.semanticscholar.org/paper/205d2ed0906440f07a0275d7d6a63bced60951fc)
<!-- [![Code](https://img.shields.io/github/stars/duyguceylan/pix2video.svg?style=social&label=Star)](https://github.com/duyguceylan/pix2video) -->

### Non-LLM-based (Clip/T5)



+ **AudioScenic: Audio-Driven Video Scene Editing** (25 Apr 2024)<details><summary>Kaixin Shen, Ruijie Quan, Linchao Zhu, et al.</summary>Kaixin Shen, Ruijie Quan, Linchao Zhu, Jun Xiao, Yi Yang</details>[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.16581)
[![citation](https://img.shields.io/badge/citation-0-blue.svg?paper=6fa898ed5e58ade17a020e3251687b811ff1d023)](https://www.semanticscholar.org/paper/AudioScenic%3A-Audio-Driven-Video-Scene-Editing-Shen-Quan/6fa898ed5e58ade17a020e3251687b811ff1d023)


+ **LATENTWARP: CONSISTENT DIFFUSION LATENTS FOR ZERO-SHOT VIDEO-TO-VIDEO TRANSLATION** (1 Nov 2023)<details><summary>Yuxiang Bao, Di Qiu, Guoliang Kang, et al.</summary>Yuxiang Bao, Di Qiu, Guoliang Kang, Baochang Zhang, Bo Jin, Kaiye Wang, Pengfei Yan. </details>[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.00353)
[![citation](https://img.shields.io/badge/citation-0-blue.svg?paper=1b4323a5324ee20fe9b2ff2a65ec26550a51ec2c)](https://www.semanticscholar.org/paper/1b4323a5324ee20fe9b2ff2a65ec26550a51ec2c)
<!-- [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://diffusion-tokenflow.github.io/) -->
<!-- [![Code](https://img.shields.io/github/stars/omerbt/TokenFlow.svg?style=social&label=Star)](https://github.com/omerbt/TokenFlow) -->

+ **MagicStick: Controllable Video Editing via Control Handle Transformations** (1 Nov 2023)<details><summary>Yue Ma, Xiaodong Cun, Yingqing He, et al.</summary>Yue Ma, Xiaodong Cun, Yingqing He, Chenyang Qi, Xintao Wang, Ying Shan, Xiu Li, Qifeng Chen</details>[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.03047)
[![citation](https://img.shields.io/badge/citation-N/A-blue.svg?paper=xxx)
)](https://www.semanticscholar.org/paper/xxx)
)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://magic-stick-edit.github.io/)
[![Code](https://img.shields.io/github/stars/mayuelala/MagicStick.svg?style=social&label=Star)](https://github.com/mayuelala/MagicStick)


+ **MagicEdit: High-Fidelity Temporally Coherent Video Editing** (28 Aug 2023) <details><summary>Jun Hao Liew, Hanshu Yan, Jianfeng Zhang, et al.</summary>Jun Hao Liew, Hanshu Yan, Jianfeng Zhang, Zhongcong Xu, Jiashi Feng. </details>[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.14749)
[![citation](https://img.shields.io/badge/citation-20-blue.svg?paper=8819777e104f8c4197c262e11a01b070b50007aa)](https://www.semanticscholar.org/paper/8819777e104f8c4197c262e11a01b070b50007aa)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://magic-edit.github.io/)
[![Code](https://img.shields.io/github/stars/magic-research/magic-edit.svg?style=social&label=Star)](https://github.com/magic-research/magic-edit)


+ **StableVideo: Text-driven Consistency-aware Diffusion Video Editing** (18 Aug 2023)<details><summary>[ICCV 2023] Wenhao Chai, Xun Guo, Gaoang Wang, et al.</summary>Wenhao Chai, Xun Guo, Gaoang Wang, Yan Lu. </details>[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.09592)
[![citation](https://img.shields.io/badge/citation-41-blue.svg?paper=05cbac9a5101f47a6fabad72398616506572c9fa)](https://www.semanticscholar.org/paper/05cbac9a5101f47a6fabad72398616506572c9fa)
[![Code](https://img.shields.io/github/stars/rese1f/StableVideo.svg?style=social&label=Star)](https://github.com/rese1f/StableVideo)


+ **CoDeF: Content Deformation Fields for Temporally Consistent Video Processing** (15 Aug 2023) <details><summary>Hao Ouyang, Qiuyu Wang, Yuxi Xiao, et al.</summary>Hao Ouyang, Qiuyu Wang, Yuxi Xiao, Qingyan Bai, Juntao Zhang, Kecheng Zheng, Xiaowei Zhou, Qifeng Chen. </details>[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.07926)
[![citation](https://img.shields.io/badge/citation-28-blue.svg?paper=c2d65fc3a7fde3f7662c6ef9448e5737d7e5551f)](https://www.semanticscholar.org/paper/c2d65fc3a7fde3f7662c6ef9448e5737d7e5551f)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://qiuyu96.github.io/CoDeF/)
[![Code](https://img.shields.io/github/stars/qiuyu96/CoDeF.svg?style=social&label=Star)](https://github.com/qiuyu96/CoDeF)


+ **TokenFlow: Consistent Diffusion Features for Consistent Video Editing** (19 Jul 2023) <details><summary>Michal Geyer, Omer Bar-Tal, Shai Bagon, et al.</summary>Michal Geyer, Omer Bar-Tal, Shai Bagon, Tali Dekel. </details>[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2307.10373)
[![citation](https://img.shields.io/badge/citation-80-blue.svg?paper=4761f173965195798cd3046ef4af608a83504e4d)](https://www.semanticscholar.org/paper/4761f173965195798cd3046ef4af608a83504e4d)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://diffusion-tokenflow.github.io/)
[![Code](https://img.shields.io/github/stars/omerbt/TokenFlow.svg?style=social&label=Star)](https://github.com/omerbt/TokenFlow)

+ **Rerender A Video: Zero-Shot Text-Guided Video-to-Video Translation** (13 Jun 2023)<details><summary>Shuai Yang, Yifan Zhou, Ziwei Liu, et al.</summary>Shuai Yang, Yifan Zhou, Ziwei Liu, Chen Change Loy. </details>[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.07954)
[![citation](https://img.shields.io/badge/citation-74-blue.svg?paper=1e09b83fe064826a9a1ac61a7bdc00f26be41aee)](https://www.semanticscholar.org/paper/1e09b83fe064826a9a1ac61a7bdc00f26be41aee)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://www.mmlab-ntu.com/project/rerender/)
[![Code](https://img.shields.io/github/stars/williamyang1991/Rerender_A_Video.svg?style=social&label=Star)](https://github.com/williamyang1991/Rerender_A_Video)

+ **ControlVideo: Adding Conditional Control for One Shot Text-to-Video Editing** (26 May 2023)<details><summary>Min Zhao, Rongzhen Wang, Fan Bao, et al.</summary>Min Zhao, Rongzhen Wang, Fan Bao, Chongxuan Li, Jun Zhu. </details>[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.17098)
[![citation](https://img.shields.io/badge/citation-0-blue.svg?paper=14acc36d8c87f31f8dcbbf8433b91af70a2a516a)](https://www.semanticscholar.org/paper/14acc36d8c87f31f8dcbbf8433b91af70a2a516a)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://ml.cs.tsinghua.edu.cn/controlvideo/)
[![Code](https://img.shields.io/github/stars/thu-ml/controlvideo.svg?style=social&label=Star)](https://github.com/thu-ml/controlvideo)



+ **Make-A-Protagonist: Generic Video Editing with An Ensemble of Experts** (15 May 2023)
Michal Geyer, Omer Bar-Tal, Shai Bagon, Tali Dekel.\
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.08850)
[![citation](https://img.shields.io/badge/citation-13-blue.svg?paper=5f51eda9f7abddca027941d50fb0b6bf6f508eff)](https://www.semanticscholar.org/paper/5f51eda9f7abddca027941d50fb0b6bf6f508eff)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://make-a-protagonist.github.io/)
[![Code](https://img.shields.io/github/stars/HeliosZhao/Make-A-Protagonist.svg?style=social&label=Star)](https://github.com/HeliosZhao/Make-A-Protagonist)


+ **Pix2Video: Video Editing using Image Diffusion** (22 Mar 2023)\
[ICCV 2023] Ceylan, Duygu, Chun-Hao P. Huang, and Niloy J. Mitra.\
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.12688)
[![citation](https://img.shields.io/badge/citation-92-blue.svg?paper=32a3c2fbd3e733bd0eea938517fec2ff8dc7c701)](https://www.semanticscholar.org/paper/32a3c2fbd3e733bd0eea938517fec2ff8dc7c701)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://duyguceylan.github.io/pix2video.github.io/)
[![Code](https://img.shields.io/github/stars/duyguceylan/pix2video.svg?style=social&label=Star)](https://github.com/duyguceylan/pix2video)


+ **FateZero: Fusing Attentions for Zero-shot Text-based Video Editing** (16 Mar 2023)<details><summary>[ICCV 2023] Chenyang Qi, Xiaodong Cun, Yong Zhang, et al.</summary>Chenyang Qi, Xiaodong Cun, Yong Zhang, Chenyang Lei, Xintao Wang, Ying Shan, Qifeng Chen. </details>[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.09535)
[![citation](https://img.shields.io/badge/citation-133-blue.svg?paper=14ccb8bcceb6de10eda6ad08bec242a4f2946497)](https://www.semanticscholar.org/paper/14ccb8bcceb6de10eda6ad08bec242a4f2946497)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://fate-zero-edit.github.io/)
[![Code](https://img.shields.io/github/stars/ChenyangQiQi/FateZero.svg?style=social&label=Star)](https://github.com/ChenyangQiQi/FateZero)

+ **Video-P2P: Video Editing with Cross-attention Control** (8 Mar 2023)<details><summary>Shaoteng Liu, Yuechen Zhang, Wenbo Li, et al.</summary>Shaoteng Liu, Yuechen Zhang, Wenbo Li, Zhe Lin, Jiaya Jia. </details>[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.04761)
[![citation](https://img.shields.io/badge/citation-81-blue.svg?paper=6283502d6900a0b403e2454b1cb1cf16ddefd5a7)](https://www.semanticscholar.org/paper/6283502d6900a0b403e2454b1cb1cf16ddefd5a7)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://video-p2p.github.io/)
[![Code](https://img.shields.io/github/stars/ShaoTengLiu/Video-P2P.svg?style=social&label=Star)](https://github.com/ShaoTengLiu/Video-P2P)

+ **Dreamix: Video Diffusion Models are General Video Editors** (2 Feb 2023)<details><summary>Eyal Molad, Eliahu Horwitz, Dani Valevski, et al.</summary>Eyal Molad, Eliahu Horwitz, Dani Valevski, Alex Rav Acha, Yossi Matias, Yael Pritch, Yaniv Leviathan, Yedid Hoshen. </details>[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2302.01329)
[![citation](https://img.shields.io/badge/citation-107-blue.svg?paper=9758ddd6ffbaac75aa0447a9664e6989811a05e2)](https://www.semanticscholar.org/paper/9758ddd6ffbaac75aa0447a9664e6989811a05e2)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://dreamix-video-editing.github.io/)


+ **Tune-A-Video: One-Shot Tuning of Image Diffusion Models for Text-to-Video Generation** (22 Dec 2022)<details><summary>[ICCV 2023] Jay Zhangjie Wu, Yixiao Ge, Xintao Wang, et al.</summary>Jay Zhangjie Wu, Yixiao Ge, Xintao Wang, Weixian Lei, Yuchao Gu, Yufei Shi, Wynne Hsu, Ying Shan, Xiaohu Qie, Mike Zheng Shou. </details>[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2212.11565)
[![citation](https://img.shields.io/badge/citation-275-blue.svg?paper=1367dcff4ccb927a5e95c452041288b3f0dd0eff)](https://www.semanticscholar.org/paper/1367dcff4ccb927a5e95c452041288b3f0dd0eff)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://fate-zero-edit.github.io/)
[![Code](https://img.shields.io/github/stars/showlab/Tune-A-Video.svg?style=social&label=Star)](https://tuneavideo.github.io/)

## 3D Editing

### 🔅 LLM-based
+ **SceneCraft: An LLM Agent for Synthesizing 3D Scene as Blender Code** (2 Mar 2024)<details><summary>Ziniu Hu, Ahmet Iscen, Aashi Jain, et al. </summary>Ziniu Hu, Ahmet Iscen, Aashi Jain, Thomas Kipf, Yisong Yue, David A. Ross, Cordelia Schmid, Alireza Fathi</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.01248v1)

+ **3D-GPT: Procedural 3D MODELING WITH LARGE LANGUAGE MODELS** (19 Oct 2023)<details><summary>Chunyi Sun*, Junlin Han*, Weijian Deng, et al. </summary>Chunyi Sun, Junlin Han, Weijian Deng, Xinlong Wang, Zishan Qin, Stephen Gould</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.12945)
[![citation](https://img.shields.io/badge/citation-7-blue.svg?paper=588930cdd801f335b5e524d13f99aa94136a20a0)](https://www.semanticscholar.org/paper/588930cdd801f335b5e524d13f99aa94136a20a0)
[![Code](https://img.shields.io/github/stars/Chuny1/3DGPT.svg?style=social&label=Star)](https://github.com/Chuny1/3DGPT)

### Non-LLM-based (Clip/T5)
+ **Paint3D: Paint Anything 3D with Lighting-Less Texture Diffusion Models** (16 Nov 2023)<details><summary>Xianfang Zeng, Xin Chen, Zhongqi Qi, et al.</summary>Xianfang Zeng, Xin Chen, Zhongqi Qi, Wen Liu, Zibo Zhao, Zhibin Wang, Bin Fu, Yong Liu, Gang Yu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.13913)
[![citation](https://img.shields.io/badge/citation-7-blue.svg?paper=e90883da4ee8c947a8b97422c95bde905a257a74)](https://www.semanticscholar.org/paper/e90883da4ee8c947a8b97422c95bde905a257a74)
[![Code](https://img.shields.io/github/stars/OpenTexture/Paint3D?style=social&label=Star)](https://github.com/OpenTexture/Paint3D)

+ **3D Paintbrush: Local Stylization of 3D Shapes with Cascaded Score Distillation** (16 Nov 2023)<details><summary>Dale Decatur, Itai Lang, Kfir Aberman, et al.</summary>Dale Decatur, Itai Lang, Kfir Aberman, Rana Hanocka</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.09571)
[![citation](https://img.shields.io/badge/citation-1-blue.svg?paper=496bdd2804a231a3336463fca8e0a4c6a46f0304)](https://www.semanticscholar.org/paper/496bdd2804a231a3336463fca8e0a4c6a46f0304)
[![Code](https://img.shields.io/github/stars/threedle/3d-paintbrush?style=social&label=Star)](https://github.com/threedle/3d-paintbrush)

+ **Blending-NeRF: Text-Driven Localized Editing in Neural Radiance Fields** (23 Aug 2023)<details><summary>Hyeonseop Song, Seokhun Choi, Hoseok Do, et al. </summary>Hyeonseop Song, Seokhun Choi, Hoseok Do, Chul Lee, Taehyeong Kim</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.11974)
[![citation](https://img.shields.io/badge/citation-9-blue.svg?paper=bf7f31e07d9b128a0f555c275bc3fdb851f725b8)](https://www.semanticscholar.org/paper/bf7f31e07d9b128a0f555c275bc3fdb851f725b8)

+ **SINE: Semantic-driven Image-based NeRF Editing with Prior-guided Editing Field** (23 Mar 2023)<details><summary>[CVPR 2023] Chong Bao, Yinda Zhang, Bangbang Yang, et al.</summary>Chong Bao, Yinda Zhang, Bangbang Yang, Tianxing Fan, Zesong Yang, Hujun Bao, Guofeng Zhang, Zhaopeng Cui</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.13277)
[![citation](https://img.shields.io/badge/citation-44-blue.svg?paper=222c47b81fe04598fd84fe8b9a43f694415ec7e9)](https://www.semanticscholar.org/paper/222c47b81fe04598fd84fe8b9a43f694415ec7e9)
[![Code](https://img.shields.io/github/stars/zju3dv/SINE?style=social&label=Star)](https://github.com/zju3dv/SINE)

+ **TextDeformer: Geometry Manipulation using Text Guidance** (26 Apr 2023)<details><summary> [TVCG 2022] William Gao, Noam Aigerman, Thibault Groueix, et al.</summary>William Gao, Noam Aigerman, Thibault Groueix, Vladimir G. Kim, Rana Hanocka</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.13348)
[![citation](https://img.shields.io/badge/citation-21-blue.svg?paper=4974186c3b5b50112cfd909de115d5fbe25411fd)](https://www.semanticscholar.org/paper/4974186c3b5b50112cfd909de115d5fbe25411fd)
[![Code](https://img.shields.io/github/stars/threedle/TextDeformer.svg?style=social&label=Star)](https://github.com/threedle/TextDeformer)

+ **Instruct-NeRF2NeRF: Editing 3D Scenes with Instructions** (22 Mar 2023)<details><summary>[SIGGRAPH Asia 2023] Ayaan Haque, Matthew Tancik, Alexei A. Efros, et al. </summary>Ayaan Haque, Matthew Tancik, Alexei A. Efros, Aleksander Holynski, Angjoo Kanazawa</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.12789)
[![citation](https://img.shields.io/badge/citation-131-blue.svg?paper=26c22380282a00166273038bc5ba785d845d61ad)](https://www.semanticscholar.org/paper/26c22380282a00166273038bc5ba785d845d61ad)
[![Code](https://img.shields.io/github/stars/ayaanzhaque/instruct-nerf2nerf.svg?style=social&label=Star)](https://github.com/ayaanzhaque/instruct-nerf2nerf)

+ **DreamEditor: Text-Driven 3D Scene Editing with Neural Fields** (23 Jun 2023)<details><summary>[SIGGRAPH Asia 2023] Jingyu Zhuang, Chen Wang, Lingjie Liu, et al. </summary>Jingyu Zhuang, Chen Wang, Lingjie Liu, Liang Lin, Guanbin Li</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.13455)
[![citation](https://img.shields.io/badge/citation-39-blue.svg?paper=029f3e2c215edac138be26ade67b3d70b8f74dd7)](https://www.semanticscholar.org/paper/029f3e2c215edac138be26ade67b3d70b8f74dd7)
[![Code](https://img.shields.io/github/stars/zjy526223908/DreamEditor.svg?style=social&label=Star)](https://github.com/zjy526223908/DreamEditor)

+ **SKED: Sketch-guided Text-based 3D Editing** (19 Mar 2023)<details><summary>[ICCV 2023] Aryan Mikaeili, Or Perel, Mehdi Safaee, et al.</summary>Aryan Mikaeili, Or Perel, Mehdi Safaee, Daniel Cohen-Or, Ali Mahdavi-Amiri</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.10735)
[![citation](https://img.shields.io/badge/citation-27-blue.svg?paper=6ebec1ece44daa090158ff2531d6fabb94a4e683)](https://www.semanticscholar.org/paper/6ebec1ece44daa090158ff2531d6fabb94a4e683)
[![Code](https://img.shields.io/github/stars/aryanmikaeili/SKED.svg?style=social&label=Star)](https://github.com/aryanmikaeili/SKED)

+ **Blended-NeRF: Zero-Shot Object Generation and Blending in Existing Neural Radiance Fields** (22 Jun 2023)<details><summary>[ICCVW 2023] Ori Gordon, Omri Avrahami, Dani Lischinski.</summary>Ori Gordon, Omri Avrahami, Dani Lischinski</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.12760)
[![citation](https://img.shields.io/badge/citation-12-blue.svg?paper=3a5d4352d3dd53148a9544233bb59f88d2504910)](https://www.semanticscholar.org/paper/3a5d4352d3dd53148a9544233bb59f88d2504910)


+ **ClipFace: Text-guided Editing of Textured 3D Morphable Modelssting Neural Radiance Fields** (2 Dec 2022)<details><summary>[SIGGRAPH 2023] Shivangi Aneja, Justus Thies, Angela Dai, et al. </summary>Shivangi Aneja, Justus Thies, Angela Dai, Matthias Nießner</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2212.01406)
[![citation](https://img.shields.io/badge/citation-31-blue.svg?paper=f21e8eddf42580d1f38a11ec5acd8891c0454a1f)](https://www.semanticscholar.org/paper/f21e8eddf42580d1f38a11ec5acd8891c0454a1f)
[![Code](https://img.shields.io/github/stars/cassiePython/CLIPNeRF.svg?style=social&label=Star)](https://github.com/cassiePython/CLIPNeRF)



## Audio Editing

### 🔅 LLM-based

+ **Loop Copilot: Conducting AI Ensembles for Music Generation and Iterative Editing** (19 Oct 2023)<details><summary>Yixiao Zhang, Akira Maezawa, Gus Xia, et al.</summary>Yixiao Zhang, Akira Maezawa, Gus Xia, Kazuhiko Yamamoto, Simon Dixon</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.12404)
[![citation](https://img.shields.io/badge/citation-3-blue.svg?paper=cca4218dd7c10c1614bbd84aa7cd7e00027bdc7c)](https://www.semanticscholar.org/paper/cca4218dd7c10c1614bbd84aa7cd7e00027bdc7c)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://sites.google.com/view/loop-copilot)
[![Code](https://img.shields.io/github/stars/ldzhangyx/loop-copilot/.svg?style=social&label=Star)](https://github.com/ldzhangyx/loop-copilot/)

+ **UniAudio: An Audio Foundation Model Toward Universal Audio Generation** (1 Oct 2023)\
Dongchao Yang, Jinchuan Tian, Xu Tan\
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.00704)
[![citation](https://img.shields.io/badge/citation-15-blue.svg?paper=74bfbbb7307a7af2686043ea97ab8b34cb062ba8)](https://www.semanticscholar.org/paper/74bfbbb7307a7af2686043ea97ab8b34cb062ba8)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://dongchaoyang.top/UniAudio_demo/)
[![Code](https://img.shields.io/github/stars/yangdongchao/UniAudio.svg?style=social&label=Star)](https://github.com/yangdongchao/UniAudio)

### Non-LLM-based (Clip/T5)

# 📍 Multimodal Agents

+ **LLaVA-Interactive: An All-in-One Demo for Image Chat, Segmentation, Generation and Editing** (1 Nov 2023) <details><summary>Wei-Ge Chen, Irina Spiridonova, Jianwei Yang, et al.</summary> Wei-Ge Chen, Irina Spiridonova, Jianwei Yang, Jianfeng Gao, Chunyuan Li</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.00571)
[![citation](https://img.shields.io/badge/citation-7-blue.svg?paper=c020f15be1dee20f9e2e0c5a6f05f272b5508325)](https://www.semanticscholar.org/paper/c020f15be1dee20f9e2e0c5a6f05f272b5508325)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://llava-vl.github.io/llava-interactive)
[![Code](https://img.shields.io/github/stars/LLaVA-VL/LLaVA-Interactive-Demo.svg?style=social&label=Star)](https://github.com/LLaVA-VL/LLaVA-Interactive-Demo)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://llavainteractive.ngrok.app/)\
**Tags:** `Image Chat` `Image Segmentation`, `Image Generation` `Image Editing`

+ **ControlLLM: Augment Language Models with Tools by Searching on Graphs** (26 Oct 2023) <details><summary>Zhaoyang Liu, Zeqiang Lai, Zhangwei Gao, et al.</summary>Zhaoyang Liu, Zeqiang Lai, Zhangwei Gao, Erfei Cui, Ziheng Li, Xizhou Zhu, Lewei Lu, Qifeng Chen, Yu Qiao, Jifeng Dai, Wenhai Wang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.17796)
[![citation](https://img.shields.io/badge/citation-11-blue.svg?paper=288e7224d53d68669eb67f2496e068dc965c639e)](https://www.semanticscholar.org/paper/288e7224d53d68669eb67f2496e068dc965c639e)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://controlllm.github.io/)
[![Code](https://img.shields.io/github/stars/OpenGVLab/ControlLLM.svg?style=social&label=Star)](https://github.com/OpenGVLab/ControlLLM)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://cllm.opengvlab.com/)\
**Tags:** `Image Understanding` `Image Generation` `Image Editing` `Video Understanding` `Video Generation` `Video Editing` `Audio Understanding` `Audio Generation`

+ **ImageBind-LLM: Multi-modality Instruction Tuning** (7 Sep 2023) <details><summary>Jiaming Han, Renrui Zhang, Wenqi Shao, et al.</summary>Jiaming Han, Renrui Zhang, Wenqi Shao, Peng Gao, Peng Xu, Han Xiao, Kaipeng Zhang, Chris Liu, Song Wen, Ziyu Guo, Xudong Lu, Shuai Ren, Yafei Wen, Xiaoxin Chen, Xiangyu Yue, Hongsheng Li, Yu Qiao</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.03905)
[![citation](https://img.shields.io/badge/citation-33-blue.svg?paper=54c68b8623505dc6bf7a0b08aaa77ca9165f2d7f)](https://www.semanticscholar.org/paper/54c68b8623505dc6bf7a0b08aaa77ca9165f2d7f)
[![Code](https://img.shields.io/github/stars/OpenGVLab/LLaMA-Adapter.svg?style=social&label=Star)](https://github.com/OpenGVLab/LLaMA-Adapter)\
**Modalities:** `text` `image` `video` `audio` `point cloud`

+ **ModelScope-Agent: Building Your Customizable Agent System with Open-source Large Language Models** (2 Sep 2023) <details><summary>Chenliang Li, Hehong Chen, Ming Yan, et al.</summary>Chenliang Li, Hehong Chen, Ming Yan, Weizhou Shen, Haiyang Xu, Zhikai Wu, Zhicheng Zhang, Wenmeng Zhou, Yingda Chen, Chen Cheng, Hongzhu Shi, Ji Zhang, Fei Huang, Jingren Zhou</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.00986)
[![citation](https://img.shields.io/badge/citation-6-blue.svg?paper=e2f1f04f648a8863d11439aa4c80ee65d6caccda)](https://www.semanticscholar.org/paper/e2f1f04f648a8863d11439aa4c80ee65d6caccda)
[![Code](https://img.shields.io/github/stars/modelscope/modelscope-agent.svg?style=social&label=Star)](https://github.com/modelscope/modelscope-agent)

+ **InternGPT: Solving Vision-Centric Tasks by Interacting with ChatGPT Beyond Language** (9 May 2023) <details><summary>Zhaoyang Liu, Yinan He, Wenhai Wang, et al.</summary>Zhaoyang Liu, Yinan He, Wenhai Wang, Weiyun Wang, Yi Wang, Shoufa Chen, Qinglong Zhang, Zeqiang Lai, Yang Yang, Qingyun Li, Jiashuo Yu, Kunchang Li, Zhe Chen, Xue Yang, Xizhou Zhu, Yali Wang, Limin Wang, Ping Luo, Jifeng Dai, Yu Qiao</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.05662)
[![citation](https://img.shields.io/badge/citation-40-blue.svg?paper=54a8b153ed04a872da878d695239bdc413dc782c)](https://www.semanticscholar.org/paper/54a8b153ed04a872da878d695239bdc413dc782c)
[![Code](https://img.shields.io/github/stars/OpenGVLab/InternGPT.svg?style=social&label=Star)](https://github.com/OpenGVLab/InternGPT)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://igpt.opengvlab.com/)\
**Condition Modality:** `text` `image` `video` `audio`

+ **HuggingGPT: Solving AI Tasks with ChatGPT and its Friends in Hugging Face** (30 Mar 2023) <details><summary>Yongliang Shen, Kaitao Song, Xu Tan, et al.</summary>Yongliang Shen, Kaitao Song, Xu Tan, Dongsheng Li, Weiming Lu, Yueting Zhuang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.17580)
[![citation](https://img.shields.io/badge/citation-413-blue.svg?paper=d1120d67b700e4dfe8b39eb1e48fbdea4e1a0c43)](https://www.semanticscholar.org/paper/d1120d67b700e4dfe8b39eb1e48fbdea4e1a0c43)
[![Code](https://img.shields.io/github/stars/microsoft/JARVIS.svg?style=social&label=Star)](https://github.com/microsoft/JARVIS)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/microsoft/HuggingGPT)

+ **Visual ChatGPT: Talking, Drawing and Editing with Visual Foundation Models** (8 Mar 2023) <details><summary>Chenfei Wu, Shengming Yin, Weizhen Qi, et al.</summary>Chenfei Wu, Shengming Yin, Weizhen Qi, Xiaodong Wang, Zecheng Tang, Nan Duan</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.04671)
[![citation](https://img.shields.io/badge/citation-337-blue.svg?paper=af997821231898a5f8d0fd78dad4eec526acabe5)](https://www.semanticscholar.org/paper/af997821231898a5f8d0fd78dad4eec526acabe5)
[![Code](https://img.shields.io/github/stars/microsoft/JARVIS.svg?style=social&label=Star)](https://github.com/moymix/TaskMatrix)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/microsoft/visual_chatgpt)

+ **AutoGPT: build & use AI agents**\
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://news.agpt.co/)
[![Code](https://img.shields.io/github/stars/Significant-Gravitas/AutoGPT.svg?style=social&label=Star)](https://github.com/Significant-Gravitas/AutoGPT)


# 📍 Multimodal Understanding with LLMs
## Multiple modalities
+ **Mirasol3B: A Multimodal Autoregressive model for time-aligned and contextual modalities**  (9 Nov 2023)<details><summary>[CVPR 2024] AJ Piergiovanni, Isaac Noble, Dahun Kim, et al.</summary>AJ Piergiovanni, Isaac Noble, Dahun Kim, Michael S. Ryoo, Victor Gomes, Anelia Angelova</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.05698)
[![citation](https://img.shields.io/badge/citation-0-blue.svg?paper=a4e7199e725b34ae5ddd574057f60ebb1a2011b7)](https://www.semanticscholar.org/paper/Mirasol3B%3A-A-Multimodal-Autoregressive-Model-for-Piergiovanni-Noble/a4e7199e725b34ae5ddd574057f60ebb1a2011b7)
`text, video, audio`


## Image Understanding

+ **Image Textualization: An Automatic Framework for Creating Accurate and Detailed Image Descriptions** (11 June 2024)<details><summary>Renjie Pi, Jianshu Zhang, Jipeng Zhang et al.</summary> Renjie Pi, Jianshu Zhang, Jipeng Zhang, Rui Pan, Zhekai Chen, Tong Zhang</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.07502)
[![citation](https://img.shields.io/badge/citation-0-blue.svg?paper=da0d382c7fa981ba185ca633868442b75cb76de6)](https://www.semanticscholar.org/paper/91b4f447bb06d081a7947b42df57491a04fa46f9)



+ **T2S-GPT: Dynamic Vector Quantization for Autoregressive Sign Language Production from Text** (11 June 2024)<details><summary>[ACL 2024] Aoxiong Yin, Haoyuan Li, Kai Shen et al.</summary> Aoxiong Yin, Haoyuan Li, Kai Shen, Siliang Tang, Yueting Zhuang</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.07119)
[![citation](https://img.shields.io/badge/citation-0-blue.svg?paper=da0d382c7fa981ba185ca633868442b75cb76de6)](https://www.semanticscholar.org/paper/186910d697bf7eb605aa055aee78fd91ce3ce9fe)


+ **Open-World Human-Object Interaction Detection via Multi-modal Prompts** (11 June 2024)<details><summary>Jie Yang, Bingliang Li, Ailing Zeng et al.</summary>Jie Yang, Bingliang Li, Ailing Zeng, Lei Zhang, Ruimao Zhang</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.07119)
[![citation](https://img.shields.io/badge/citation-0-blue.svg?paper=da0d382c7fa981ba185ca633868442b75cb76de6)](https://www.semanticscholar.org/paper/186910d697bf7eb605aa055aee78fd91ce3ce9fe)


+ **Commonsense-T2I Challenge: Can Text-to-Image Generation Models Understand Commonsense?** (11 June 2024)<details><summary>Xingyu Fu, Muyu He, Yujie Lu et al.</summary>Xingyu Fu, Muyu He, Yujie Lu, William Yang Wang, Dan Roth</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.07221v1)
[![citation](https://img.shields.io/badge/citation-0-blue.svg?paper=da0d382c7fa981ba185ca633868442b75cb76de6)](https://www.semanticscholar.org/paper/f0acf2a2293d963c3786e83bb198c75612adc446)

+ **InternVL: Scaling up Vision Foundation Models and Aligning for Generic Visual-Linguistic Tasks** (21 Dec 2023)<details><summary>Zhe Chen, Jiannan Wu, Wenhai Wang, et al.</summary>Zhe Chen, Jiannan Wu, Wenhai Wang, Weijie Su, Guo Chen, Sen Xing, Muyan Zhong, Qinglong Zhang, Xizhou Zhu, Lewei Lu, Bin Li, Ping Luo, Tong Lu, Yu Qiao, Jifeng Dai</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.14238)
[![citation](https://img.shields.io/badge/citation-10-blue.svg?paper=6a33e58ef961a3a0a5657518b2be86395eb7c8d0)](https://www.semanticscholar.org/paper/6a33e58ef961a3a0a5657518b2be86395eb7c8d0)
[![Code](https://img.shields.io/github/stars/OpenGVLab/InternVL.svg?style=social&label=Star)](https://github.com/OpenGVLab/InternVL)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://internvl.opengvlab.com/)

+ **LLaMA-VID: An Image is Worth 2 Tokens in Large Language Models** (28 Nov 2023)\
Yanwei Li, Chengyao Wang, Jiaya Jia\
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.17043)
[![citation](https://img.shields.io/badge/citation-5-blue.svg?paper=486c2df78cbb770a90a55f7fa3fe19102fba2c24)](https://www.semanticscholar.org/paper/486c2df78cbb770a90a55f7fa3fe19102fba2c24)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://llama-vid.github.io/)
[![Code](https://img.shields.io/github/stars/dvlab-research/LLaMA-VID.svg?style=social&label=Star)](https://github.com/dvlab-research/LLaMA-VID)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](http://103.170.5.190:7864/)

+ **CogVLM: Visual Expert for Pretrained Language Models** (6 Nov 2023)<details><summary>Weihan Wang, Qingsong Lv, Wenmeng Yu, et al.</summary>Weihan Wang, Qingsong Lv, Wenmeng Yu, Wenyi Hong, Ji Qi, Yan Wang, Junhui Ji, Zhuoyi Yang, Lei Zhao, Xixuan Song, Jiazheng Xu, Bin Xu, Juanzi Li, Yuxiao Dong, Ming Ding, Jie Tang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.03079)
[![citation](https://img.shields.io/badge/citation-N/A-blue.svg?paper=3bf842dec99016da2d309ea8cbd7e25343032317)](https://www.semanticscholar.org/paper/3bf842dec99016da2d309ea8cbd7e25343032317)
[![Code](https://img.shields.io/github/stars/THUDM/CogVLM.svg?style=social&label=Star)](https://github.com/THUDM/CogVLM)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](http://36.103.203.44:7861/)

+ **MiniGPT-v2: large language model as a unified interface for vision-language multi-task learning** (14 Oct 2023)<details><summary>Jun Chen, Deyao Zhu, Xiaoqian Shen, et al.</summary>Jun Chen, Deyao Zhu, Xiaoqian Shen, Xiang Li, Zechun Liu, Pengchuan Zhang, Raghuraman Krishnamoorthi, Vikas Chandra, Yunyang Xiong, Mohamed Elhoseiny</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.09478)
[![citation](https://img.shields.io/badge/citation-97-blue.svg?paper=1ddbd08ad8cf22a5c66c4242194c4286328533bf)](https://www.semanticscholar.org/paper/1ddbd08ad8cf22a5c66c4242194c4286328533bf)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://minigpt-v2.github.io/)
[![Code](https://img.shields.io/github/stars/Vision-CAIR/MiniGPT-4.svg?style=social&label=Star)](https://github.com/Vision-CAIR/MiniGPT-4)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/Vision-CAIR/MiniGPT-v2)

+ **OphGLM: Training an Ophthalmology Large Language-and-Vision Assistant based on Instructions and Dialogue** (21 Jun 2023)<details><summary>Weihao Gao, Zhuo Deng, Zhiyuan Niu, et al.</summary>Weihao Gao, Zhuo Deng, Zhiyuan Niu, Fuju Rong, Chucheng Chen, Zheng Gong, Wenze Zhang, Daimin Xiao, Fang Li, Zhenjie Cao, Zhaoyi Ma, Wenbin Wei, Lan Ma</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.12174)
[![citation](https://img.shields.io/badge/citation-7-blue.svg?paper=0f8d12775a4685575f1489796b5dee9e11fbdfb5)](https://www.semanticscholar.org/paper/0f8d12775a4685575f1489796b5dee9e11fbdfb5)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://minigpt-v2.github.io/)
[![Code](https://img.shields.io/github/stars/ML-AILab/OphGLM.svg?style=social&label=Star)](https://github.com/ML-AILab/OphGLM)


+ **InternLM-XComposer: A Vision-Language Large Model for Advanced Text-image Comprehension and Composition** (26 Sep 2023)<details><summary>Pan Zhang, Xiaoyi Dong, Bin Wang, et al.</summary> Pan Zhang, Xiaoyi Dong, Bin Wang, Yuhang Cao, Chao Xu, Linke Ouyang, Zhiyuan Zhao, Haodong Duan, Songyang Zhang, Shuangrui Ding, Wenwei Zhang, Hang Yan, Xinyue Zhang, Wei Li, Jingwen Li, Kai Chen, Conghui He, Xingcheng Zhang, Yu Qiao, Dahua Lin, Jiaqi Wang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.15112)
[![citation](https://img.shields.io/badge/citation-48-blue.svg?paper=c1e450284e7d6cac1855330a1197df8537df653f)](https://www.semanticscholar.org/paper/c1e450284e7d6cac1855330a1197df8537df653f)
[![Code](https://img.shields.io/github/stars/InternLM/InternLM-XComposer.svg?style=social&label=Star)](https://github.com/InternLM/InternLM-XComposer)

+ **[LaVIT] Unified Language-Vision Pretraining in LLM with Dynamic Discrete Visual Tokenization** (9 Sep 2023)<details><summary>Yang Jin, Kun Xu, Kun Xu, et al.</summary>Yang Jin, Kun Xu, Kun Xu, Liwei Chen, Chao Liao, Jianchao Tan, Quzhe Huang, Bin Chen, Chenyi Lei, An Liu, Chengru Song, Xiaoqiang Lei, Di Zhang, Wenwu Ou, Kun Gai, Yadong Mu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.04669)
[![citation](https://img.shields.io/badge/citation-5-blue.svg?paper=bcac614f9774488447221ebb4f16f05e3975ec1e)](https://www.semanticscholar.org/paper/bcac614f9774488447221ebb4f16f05e3975ec1e)
[![Code](https://img.shields.io/github/stars/jy0205/LaVIT.svg?style=social&label=Star)](https://github.com/jy0205/LaVIT)
`tokenizer`

+ **Qwen-VL: A Versatile Vision-Language Model for Understanding, Localization, Text Reading, and Beyond** (24 Aug 2023)<details><summary>Jinze Bai, Shuai Bai, Shusheng Yang, et al.</summary>Jinze Bai, Shuai Bai, Shusheng Yang, Shijie Wang, Sinan Tan, Peng Wang, Junyang Lin, Chang Zhou, Jingren Zhou</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.12966)
[![citation](https://img.shields.io/badge/citation-69-blue.svg?paper=fc6a2f7478f68adefd69e2071f27e38aa1647f2f)](https://www.semanticscholar.org/paper/fc6a2f7478f68adefd69e2071f27e38aa1647f2f)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://github.com/QwenLM/Qwen-VL/blob/master/TUTORIAL.md)
[![Code](https://img.shields.io/github/stars/QwenLM/Qwen-VL.svg?style=social&label=Star)](https://github.com/QwenLM/Qwen-VL)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://modelscope.cn/studios/qwen/Qwen-VL-Chat-Demo/summary)

+ **VisionLLM: Large Language Model is also an Open-Ended Decoder for Vision-Centric Tasks** (18 May 2023)<details><summary>[NeurIPS 2023] Wenhai Wang, Zhe Chen, Xiaokang Chen, et al.</summary>Wenhai Wang, Zhe Chen, Xiaokang Chen, Jiannan Wu, Xizhou Zhu, Gang Zeng, Ping Luo, Tong Lu, Jie Zhou, Yu Qiao, Jifeng Dai</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.11175)
[![citation](https://img.shields.io/badge/citation-134-blue.svg?paper=42a30dc5470f54ec249f25d3c31e05d7c376c8e3)](https://www.semanticscholar.org/paper/42a30dc5470f54ec249f25d3c31e05d7c376c8e3)
[![Code](https://img.shields.io/github/stars/OpenGVLab/VisionLLM.svg?style=social&label=Star)](https://github.com/OpenGVLab/VisionLLM)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://github.com/OpenGVLab/InternGPT)

+ **InstructBLIP: Towards General-purpose Vision-Language Models with Instruction Tuning** (11 May 2023)<details><summary>Wenliang Dai, Junnan Li, Dongxu Li, et al.</summary>Wenliang Dai, Junnan Li, Dongxu Li, Anthony Meng Huat Tiong, Junqi Zhao, Weisheng Wang, Boyang Li, Pascale Fung, Steven Hoi</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.06500)
[![citation](https://img.shields.io/badge/citation-474-blue.svg?paper=8bd6a2a89503be083176f2cc26fabedb79238cbd)](https://www.semanticscholar.org/paper/8bd6a2a89503be083176f2cc26fabedb79238cbd)
[![Code](https://img.shields.io/github/stars/QwenLM/Qwen-VL.svg?style=social&label=Star)](https://github.com/QwenLM/Qwen-VL)

+ **MiniGPT-4: Enhancing Vision-Language Understanding with Advanced Large Language Models** (20 Apr 2023)<details><summary>Deyao Zhu, Jun Chen, Xiaoqian Shen, et al.</summary>Deyao Zhu, Jun Chen, Xiaoqian Shen, Xiang Li, Mohamed Elhoseiny</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.10592)
[![citation](https://img.shields.io/badge/citation-649-blue.svg?paper=ca6a2bc279be5a3349a22bfd6866ed633d18734b)](https://www.semanticscholar.org/paper/ca6a2bc279be5a3349a22bfd6866ed633d18734b)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://minigpt-4.github.io/)
[![Code](https://img.shields.io/github/stars/Vision-CAIR/MiniGPT-4.svg?style=social&label=Star)](https://github.com/Vision-CAIR/MiniGPT-4)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/Vision-CAIR/MiniGPT-v2)

+ **Visual Instruction Tuning** (17 Apr 2023)<details><summary>[NeurIPS 2023 (Oral)] Liu, Haotian, et al.</summary>Haotian Liu, Chunyuan Li, Qingyang Wu, Yong Jae Lee</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.08485)
[![citation](https://img.shields.io/badge/citation-N/A-blue.svg?paper=1a8eb2cae1833df3bf12fe3b41b03d60b4a4a98d)](https://www.semanticscholar.org/paper/1a8eb2cae1833df3bf12fe3b41b03d60b4a4a98d)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://llava-vl.github.io/)
[![Code](https://img.shields.io/github/stars/haotian-liu/LLaVA.svg?style=social&label=Star)](https://github.com/haotian-liu/LLaVA)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://llava.hliu.cc/)


## Video Understanding



+ **Video-XL: Extra-Long Vision Language Model for Hour-Scale Video Understanding**  (22 Sep 2024)<details><summary>Yan Shu, Peitian Zhang, Zheng Liu, et al.</summary>Yan Shu, Peitian Zhang, Zheng Liu, Minghao Qin, Junjie Zhou, Tiejun Huang, Bo Zhao</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.14485)
[![citation](https://img.shields.io/badge/citation-0-blue.svg?paper=ad6f68db45aaebc0e61b342d03da4c2702ce5697)](https://www.semanticscholar.org/paper/Video-XL%3A-Extra-Long-Vision-Language-Model-for-Shu-Zhang/ad6f68db45aaebc0e61b342d03da4c2702ce5697)
[![Code](https://img.shields.io/github/stars/VectorSpaceLab/Video-XL.svg?style=social&label=Star)](https://github.com/VectorSpaceLab/Video-XL/tree/main)



+ **Oryx MLLM: On-Demand Spatial-Temporal Understanding at Arbitrary Resolution** (19 Sep 2024)<details><summary>Zuyan Liu, Yuhao Dong, Ziwei Liu, et al.</summary>Zuyan Liu, Yuhao Dong, Ziwei Liu, Winston Hu, Jiwen Lu, Yongming Rao</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.12961)
[![citation](https://img.shields.io/badge/citation-0-blue.svg?paper=85c514db4e90e1fd4200d858353f27a3cc2c29ad)](https://www.semanticscholar.org/paper/Oryx-MLLM%3A-On-Demand-Spatial-Temporal-Understanding-Liu-Dong/85c514db4e90e1fd4200d858353f27a3cc2c29ad)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://oryx-mllm.github.io/)
[![Code](https://img.shields.io/github/stars/Oryx-mllm/Oryx.svg?style=social&label=Star)](https://github.com/Oryx-mllm/Oryx?tab=readme-ov-file)



+ **VideoLLaMA 2: Advancing Spatial-Temporal Modeling and Audio Understanding in Video-LLMs**  (25 Apr 2024)<details><summary>Zesen Cheng, Sicong Leng, Hang Zhang, et al.</summary>Zesen Cheng, Sicong Leng, Hang Zhang, Yifei Xin, Xin Li, Guanzheng Chen, Yongxin Zhu, Wenqi Zhang, Ziyang Luo, Deli Zhao, Lidong Bing</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.07476)
[![citation](https://img.shields.io/badge/citation-0-blue.svg?paper=7115e1f6cdd91ef09737d5a13664d9489fe27e08)](https://www.semanticscholar.org/paper/VideoLLaMA-2%3A-Advancing-Spatial-Temporal-Modeling-Cheng-Leng/7115e1f6cdd91ef09737d5a13664d9489fe27e08)
[![Code](https://img.shields.io/github/stars/DAMO-NLP-SG/VideoLLaMA2.svg?style=social&label=Star)](https://github.com/DAMO-NLP-SG/VideoLLaMA2)

+ **PLLaVA: Parameter-free LLaVA Extension from Images to Videos for Video Dense Captioning**  (25 Apr 2024)<details><summary>Lin Xu, Yilin Zhao, Daquan Zhou, et al.</summary>Lin Xu, Yilin Zhao, Daquan Zhou, Zhijie Lin, See Kiong Ng, Jiashi Feng</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://pllava.github.io/)
[![citation](https://img.shields.io/badge/citation-0-blue.svg?paper=9d29da83aba362c728c36f4dea9dde678ae3e2b2)](https://www.semanticscholar.org/paper/PLLaVA-%3A-Parameter-free-LLaVA-Extension-from-Images-Xu-Zhao/9d29da83aba362c728c36f4dea9dde678ae3e2b2)
[![Code](https://img.shields.io/github/stars/magic-research/PLLaVA.svg?style=social&label=Star)](https://github.com/magic-research/PLLaVA?tab=readme-ov-file)

+ **MovieChat: From Dense Token to Sparse Memory for Long Video Understanding**  (3 Dec 2023) \
Enxin, Song, et al. \
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2307.16449)
[![citation](https://img.shields.io/badge/citation-16-blue.svg?paper=6f9b7c8cde1be2e62a503c31cac883c6d44c9d0d)](https://www.semanticscholar.org/paper/6f9b7c8cde1be2e62a503c31cac883c6d44c9d0d)
[![Code](https://img.shields.io/github/stars/rese1f/MovieChat.svg?style=social&label=Star)](https://github.com/rese1f/MovieChat)

+ **LLaMA-VID: An Image is Worth 2 Tokens in Large Language Models**  (28 Nov 2023) \
Yanwei, Li, et al. \
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.17043)
[![citation](https://img.shields.io/badge/citation-5-blue.svg?paper=486c2df78cbb770a90a55f7fa3fe19102fba2c24)](https://www.semanticscholar.org/paper/486c2df78cbb770a90a55f7fa3fe19102fba2c24)
[![Code](https://img.shields.io/github/stars/dvlab-research/LLaMA-VID.svg?style=social&label=Star)](https://github.com/dvlab-research/LLaMA-VID)

+ **Video-Bench: A Comprehensive Benchmark and Toolkit for Evaluating Video-based Large Language Models** (27 Nov 2023)\
Ning, Munan, et al. \
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.16103)
[![citation](https://img.shields.io/badge/citation-1-blue.svg?paper=b037bb09aa162d8a543e64ec777ca0edc732d2af)](https://www.semanticscholar.org/paper/b037bb09aa162d8a543e64ec777ca0edc732d2af)
[![Code](https://img.shields.io/github/stars/PKU-YuanGroup/Video-Bench.svg?style=social&label=Star)](https://github.com/PKU-YuanGroup/Video-Bench)

+ **PG-Video-LLaVA: Pixel Grounding Large Video-Language Models** (22 Nov 2023)\
Munasinghe, Shehan, et al. \
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.13435)
[![citation](https://img.shields.io/badge/citation-1-blue.svg?paper=4edbb942c2d20a6f5a4e3caa763a9761be953231)](https://www.semanticscholar.org/paper/4edbb942c2d20a6f5a4e3caa763a9761be953231)
[![Code](https://img.shields.io/github/stars/mbzuai-oryx/Video-LLaVA.svg?style=social&label=Star)](https://github.com/mbzuai-oryx/Video-LLaVA)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://mbzuai-oryx.github.io/Video-LLaVA/)

+ **Video-LLaVA: Learning United Visual Representation by Alignment Before Projection** (16 Nov 2023)\
Lin, Bin, et al. \
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.10122)
[![citation](https://img.shields.io/badge/citation-19-blue.svg?paper=107fb6eec2febbae12db29bf3e311aaf5680027c)](https://www.semanticscholar.org/paper/107fb6eec2febbae12db29bf3e311aaf5680027c)
[![Code](https://img.shields.io/github/stars/PKU-YuanGroup/Video-LLaVA.svg?style=social&label=Star)](https://github.com/PKU-YuanGroup/Video-LLaVA)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/LanguageBind/Video-LLaVA)

+ **Chat-UniVi: Unified Visual Representation Empowers Large Language Models with Image and Video Understanding** (14 Nov 2023)\
Jin, Peng, et al. \
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.08046)
[![citation](https://img.shields.io/badge/citation-11-blue.svg?paper=aad3d2e690f6c73f04a14622ceff51464bbc560e)](https://www.semanticscholar.org/paper/aad3d2e690f6c73f04a14622ceff51464bbc560e)
[![Code](https://img.shields.io/github/stars/PKU-YuanGroup/Chat-UniVi.svg?style=social&label=Star)](https://github.com/PKU-YuanGroup/Chat-UniVi)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/Chat-UniVi/Chat-UniVi)


+ **Video-LLaMA: An Instruction-tuned Audio-Visual Language Model for Video Understanding** (5 Jun 2023)\
Zhang, Hang, Xin Li, and Lidong Bing. EMNLP 2023's demo track. \
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.02858)
[![citation](https://img.shields.io/badge/citation-176-blue.svg?paper=5d321194696f1f75cf9da045e6022b2f20ba5b9c)](https://www.semanticscholar.org/paper/5d321194696f1f75cf9da045e6022b2f20ba5b9c)
[![Code](https://img.shields.io/github/stars/DAMO-NLP-SG/Video-LLaMA.svg?style=social&label=Star)](https://github.com/DAMO-NLP-SG/Video-LLaMA)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/DAMO-NLP-SG/Video-LLaMA)

+ **AntGPT: Can Large Language Models Help Long-term Action Anticipation from Videos?** (31 Jul 2023)\
Zhao, Qi, et al.\
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2307.16368)
[![citation](https://img.shields.io/badge/citation-6-blue.svg?paper=6024f320e0a5b9b8fc29b86903aa9a96956b26dd)](https://www.semanticscholar.org/paper/6024f320e0a5b9b8fc29b86903aa9a96956b26dd)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://brown-palm.github.io/AntGPT/)

+ **Valley: Video Assistant with Large Language model Enhanced ability** (12 Jun 2023)\
Luo, Ruipu, et al.\
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.07207)
[![citation](https://img.shields.io/badge/citation-42-blue.svg?paper=4c4d176c6e28f48041f215d563f6ee8633534cff)](https://www.semanticscholar.org/paper/4c4d176c6e28f48041f215d563f6ee8633534cff)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://valley-vl.github.io/)
[![Code](https://img.shields.io/github/stars/RupertLuo/Valley.svg?style=social&label=Star)](https://github.com/RupertLuo/Valley)

+ **Video-ChatGPT: Towards Detailed Video Understanding via Large Vision and Language Models** (8 Jun 2023)\
Muhammad Maaz, Hanoona Rasheed, Salman Khan, et al.\
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.05424)
[![citation](https://img.shields.io/badge/citation-107-blue.svg?paper=bf7025a2e5dbb3c09deae02a1aa98a256ca559e2)](https://www.semanticscholar.org/paper/bf7025a2e5dbb3c09deae02a1aa98a256ca559e2)
[![Code](https://img.shields.io/github/stars/mbzuai-oryx/Video-ChatGPT.svg?style=social&label=Star)](https://github.com/mbzuai-oryx/Video-ChatGPT)

+ **VideoChat: Chat-Centric Video Understanding** (10 May 2023)\
Li, KunChang, et al. \
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.06355)
[![citation](https://img.shields.io/badge/citation-133-blue.svg?paper=d48cb91b9e555194f7494c4d4bb9815021d3ee45)](https://www.semanticscholar.org/paper/d48cb91b9e555194f7494c4d4bb9815021d3ee45)
[![Code](https://img.shields.io/github/stars/OpenGVLab/Ask-Anything.svg?style=social&label=Star)](https://github.com/OpenGVLab/Ask-Anything)

+ **VideoLLM: Modeling Video Sequence with Large Language Models** (22 May 2023)\
Chen, Guo, et al.\
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.13292)
[![citation](https://img.shields.io/badge/citation-33-blue.svg?paper=f9bfc6d9ba1665b73af3323d46c7642b852759ef)](https://www.semanticscholar.org/paper/f9bfc6d9ba1665b73af3323d46c7642b852759ef)
[![Code](https://img.shields.io/github/stars/cg1177/VideoLLM.svg?style=social&label=Star)](https://github.com/cg1177/VideoLLM)

+ **Learning video embedding space with Natural Language Supervision** (25 Mar 2023)\
Uppala, Phani Krishna, Shriti Priya, and Vaidehi Joshi.\
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.14584)
[![citation](https://img.shields.io/badge/citation-1-blue.svg?paper=4e54a45d2118b61ae1baec07308af3fdd2c48759)](https://www.semanticscholar.org/paper/4e54a45d2118b61ae1baec07308af3fdd2c48759)


  
## 3D Understanding
+ **LL3DA: Visual Interactive Instruction Tuning for Omni-3D Understanding, Reasoning, and Planning** (30 Nov 2023)<details><summary>[CVPR2024]Sijin Chen, Xin Chen, Chi Zhang, et al. </summary>[CVPR 2024] Sijin Chen, Xin Chen, Chi Zhang, Mingsheng Li, Gang Yu, Hao Fei, Hongyuan Zhu, Jiayuan Fan, Tao Chen</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.18651)
[![citation](https://img.shields.io/badge/citation-1-blue.svg?paper=fc53f8f3a84f1fc4993689d8f98cf6551d07a22d)](https://www.semanticscholar.org/paper/fc53f8f3a84f1fc4993689d8f98cf6551d07a22d)
[![Code](https://img.shields.io/github/stars/Open3DA/LL3DA.svg?style=social&label=Star)](https://github.com/Open3DA/LL3DA)

+ **LiDAR-LLM: Exploring the Potential of Large Language Models for 3D LiDAR Understanding** (21 Dec 2023)\
Senqiao Yang*, Jiaming Liu*, Ray Zhang, et al.\
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.14074)
[![citation](https://img.shields.io/badge/citation-6-blue.svg?paper=5edf706467dc76cd09319592d18db0ad4e1fb64d)](https://www.semanticscholar.org/paper/5edf706467dc76cd09319592d18db0ad4e1fb64d)

+ **3D-LLM: Injecting the 3D World into Large Language Models** (24 Jul 2023)<details><summary>[NeurIPS 2023 Spotlight] Yining Hong, Haoyu Zhen, Peihao Chen, et al.</summary>Yining Hong, Haoyu Zhen, Peihao Chen, Shuhong Zheng, Yilun Du, Zhenfang Chen, Chuang Gan</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2307.12981)
[![citation](https://img.shields.io/badge/citation-48-blue.svg?paper=7637ed79d30d0139901175ae4abedd822c217ab4)](https://www.semanticscholar.org/paper/7637ed79d30d0139901175ae4abedd822c217ab4)
[![Code](https://img.shields.io/github/stars/UMass-Foundation-Model/3D-LLM.svg?style=social&label=Star)](https://github.com/UMass-Foundation-Model/3D-LLM)

+ **PointLLM: Empowering Large Language Models to Understand Point Clouds** (31 Aug 2023)<details><summary>[NeurIPS 2023 Spotlight] Runsen Xu, Xiaolong Wang, Tai Wang, et al.</summary>Runsen Xu, Xiaolong Wang, Tai Wang, Yilun Chen, Jiangmiao Pang, Dahua Lin</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2308.16911.pdf)
[![citation](https://img.shields.io/badge/citation-31-blue.svg?paper=6bcc6ab9c28805d4067e99b2cdc7524550fe80e1)](https://www.semanticscholar.org/paper/6bcc6ab9c28805d4067e99b2cdc7524550fe80e1)
[![Code](https://img.shields.io/github/stars/OpenRobotLab/PointLLM.svg?style=social&label=Star)](https://github.com/OpenRobotLab/PointLLM)

+ **PointCLIP: Point Cloud Understanding by CLIP** (31 Aug 2023)<details><summary>[CVPR 2022] Renrui Zhang, Ziyu Guo, Wei Zhang,, et al. </summary>Renrui Zhang, Ziyu Guo, Wei Zhang, Kunchang Li, Xupeng Miao, Bin Cui, Yu Qiao, Peng Gao, Hongsheng Li</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2112.02413.pdf)
[![citation](https://img.shields.io/badge/citation-215-blue.svg?paper=f3ce9ba3fcec362b70263a7ed63d9404975496a0)](https://www.semanticscholar.org/paper/f3ce9ba3fcec362b70263a7ed63d9404975496a0)
[![Code](https://img.shields.io/github/stars/ZrrSkywalker/PointCLIP.svg?style=social&label=Star)](https://github.com/ZrrSkywalker/PointCLIP)



## Audio Understanding
+ **Unified-IO 2: Scaling Autoregressive Multimodal Models with Vision, Language, Audio, and Action** (28 Dec 2023)<details><summary>Jiasen Lu, Christopher Clark, Sangho Lee, et al.</summary>Jiasen Lu, Christopher Clark, Sangho Lee, Zichen Zhang, Savya Khosla, Ryan Marten, Derek Hoiem, Aniruddha Kembhavi</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.17172)
[![citation](https://img.shields.io/badge/citation-8-blue.svg?paper=6c64ddd2190909de2c680dd18abc9b92e80c39f9)](https://www.semanticscholar.org/paper/6c64ddd2190909de2c680dd18abc9b92e80c39f9)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://unified-io-2.allenai.org/)
[![Code](https://img.shields.io/github/stars/allenai/unified-io-2.svg?style=social&label=Star)](https://github.com/allenai/unified-io-2)

+ **M2UGen: Multi-modal Music Understanding and Generation with the Power of Large Language Models** (19 Nov 2023)<details><summary>Atin Sakkeer Hussain, Shansong Liu, Chenshuo Sun, et al.</summary>Atin Sakkeer Hussain, Shansong Liu, Chenshuo Sun, Ying Shan</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.11255)
[![citation](https://img.shields.io/badge/citation-N/A-blue.svg?paper=1e84d7c45f70038574fcdb7bc1b20da9b348a092)](https://www.semanticscholar.org/paper/1e84d7c45f70038574fcdb7bc1b20da9b348a092)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://crypto-code.github.io/M2UGen-Demo/)
[![Code](https://img.shields.io/github/stars/shansongliu/M2UGen.svg?style=social&label=Star)](https://github.com/shansongliu/M2UGen)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/M2UGen/M2UGen-Demo)

+ **Qwen-Audio: Advancing Universal Audio Understanding via Unified Large-Scale Audio-Language Models** (14 Nov 2023)<details><summary>Yunfei Chu, Jin Xu, Xiaohuan Zhou, et al.</summary>Yunfei Chu, Jin Xu, Xiaohuan Zhou, Qian Yang, Shiliang Zhang, Zhijie Yan, Chang Zhou, Jingren Zhou</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.07919)
[![citation](https://img.shields.io/badge/citation-14-blue.svg?paper=f90595f99a0c66d2bb6d0f230f17c7cd8c58f44d)](https://www.semanticscholar.org/paper/f90595f99a0c66d2bb6d0f230f17c7cd8c58f44d)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://github.com/QwenLM/Qwen-Audio)

+ **SALMONN: Towards Generic Hearing Abilities for Large Language Models** (20 Oct 2023)<details><summary>Changli Tang, Wenyi Yu, Guangzhi Sun, et al.</summary>Changli Tang, Wenyi Yu, Guangzhi Sun, Xianzhao Chen, Tian Tan, Wei Li, Lu Lu, Zejun Ma, Chao Zhang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.13289)
[![citation](https://img.shields.io/badge/citation-9-blue.svg?paper=f72be31de9f9a09d4410fd38bc717efe43444827)](https://www.semanticscholar.org/paper/f72be31de9f9a09d4410fd38bc717efe43444827)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://huggingface.co/spaces/tsinghua-ee/SALMONN-7B-gradio)
[![Code](https://img.shields.io/github/stars/bytedance/SALMONN.svg?style=social&label=Star)](https://github.com/bytedance/SALMONN)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/tsinghua-ee/SALMONN)

+ **MusicAgent: An AI Agent for Music Understanding and Generation with Large Language Models** (18 Oct 2023)<details><summary>Dingyao Yu, Kaitao Song, Peiling Lu, et al.</summary>Dingyao Yu, Kaitao Song, Peiling Lu, Tianyu He, Xu Tan, Wei Ye, Shikun Zhang, Jiang Bian</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.11954)
[![citation](https://img.shields.io/badge/citation-2-blue.svg?paper=beaf64df85f8204b8cd89a7f46827608e6d16922)](https://www.semanticscholar.org/paper/beaf64df85f8204b8cd89a7f46827608e6d16922)
[![Code](https://img.shields.io/github/stars/microsoft/muzic/tree/main/musicagent.svg?style=social&label=Star)](https://github.com/microsoft/muzic/tree/main/musicagent)

+ **Llark: A multimodal foundation model for music** (11 Oct 2023)<details><summary>Josh Gardner, Simon Durand, Daniel Stoller, et al.</summary>Josh Gardner, Simon Durand, Daniel Stoller, Rachel M. Bittner</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.07160)
[![citation](https://img.shields.io/badge/citation-N/A-blue.svg?paper=86e75cf15a838ed7d672fb114beff727d7210ca5)](https://www.semanticscholar.org/paper/86e75cf15a838ed7d672fb114beff727d7210ca5)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://storage.googleapis.com/music2text-public/index.html)
[![Code](https://img.shields.io/github/stars/spotify-research/llark.svg?style=social&label=Star)](https://github.com/spotify-research/llark)

+ **LauraGPT: Listen, Attend, Understand, and Regenerate Audio with GPT** (7 Oct 2023)<details><summary>Jiaming Wang, Zhihao Du, Qian Chen, et al.</summary>Jiaming Wang, Zhihao Du, Qian Chen, Yunfei Chu, Zhifu Gao, Zerui Li, Kai Hu, Xiaohuan Zhou, Jin Xu, Ziyang Ma, Wen Wang, Siqi Zheng, Chang Zhou, Zhijie Yan, Shiliang Zhang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.04673)
[![citation](https://img.shields.io/badge/citation-13-blue.svg?paper=ffa05cb5504ba08254f498223f613b3ebcf87692)](https://www.semanticscholar.org/paper/ffa05cb5504ba08254f498223f613b3ebcf87692)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://lauragpt.github.io/)

+ **Improving Audio Captioning Models with Fine-grained Audio Features, Text Embedding Supervision, and LLM Mix-up Augmentation** (29 Sep 2023)<details><summary>Shih-Lun Wu, Xuankai Chang, Gordon Wichern, et al.</summary>Shih-Lun Wu, Xuankai Chang, Gordon Wichern, Jee-weon Jung, François Germain, Jonathan Le Roux, Shinji Watanabe</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.17352)
[![citation](https://img.shields.io/badge/citation-2-blue.svg?paper=8f0a24d1678e4d0e584b0932196cd257d5c53c7d)](https://www.semanticscholar.org/paper/8f0a24d1678e4d0e584b0932196cd257d5c53c7d)

+ **Connecting Speech Encoder and Large Language Model for ASR** (25 Sep 2023)<details><summary>Wenyi Yu, Changli Tang, Guangzhi Sun, et al.</summary>Wenyi Yu, Changli Tang, Guangzhi Sun, Xianzhao Chen, Tian Tan, Wei Li, Lu Lu, Zejun Ma, Chao Zhang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.13963)
[![citation](https://img.shields.io/badge/citation-11-blue.svg?paper=5596bd3e26ec2207666ec1ff3db4415d212f14b9)](https://www.semanticscholar.org/paper/5596bd3e26ec2207666ec1ff3db4415d212f14b9)

+ **Can Whisper perform speech-based in-context learning** (13 Sep 2023)<details><summary>Siyin Wang, Chao-Han Huck Yang, Ji Wu, et al.</summary>Siyin Wang, Chao-Han Huck Yang, Ji Wu, Chao Zhang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.07081)
[![citation](https://img.shields.io/badge/citation-8-blue.svg?paper=3a944ddba8b6fbaaac36126fc955f181f8b8b06a)](https://www.semanticscholar.org/paper/3a944ddba8b6fbaaac36126fc955f181f8b8b06a)

+ **Music understanding LLaMA: Advancing text-to-music generation with question answering and captioning** (22 Aug 2023)<details><summary>Shansong Liu, Atin Sakkeer Hussain, Chenshuo Sun, et al.</summary>Shansong Liu, Atin Sakkeer Hussain, Chenshuo Sun, Ying Shan</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.11276)
[![citation](https://img.shields.io/badge/citation-11-blue.svg?paper=a33b437618be733fea7176bd98e18b6362af0838)](https://www.semanticscholar.org/paper/a33b437618be733fea7176bd98e18b6362af0838)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://crypto-code.github.io/MU-LLaMA-Demo/)
[![Code](https://img.shields.io/github/stars/crypto-code/MU-LLaMA.svg?style=social&label=Star)](https://github.com/crypto-code/MU-LLaMA)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/datasets/mu-llama/MusicQA)

+ **On decoder-only architecture for speech-to-text and large language model integration** (8 Jul 2023)<details><summary>Jian Wu, Yashesh Gaur, Zhuo Chen, et al.</summary>Jian Wu, Yashesh Gaur, Zhuo Chen, Long Zhou, Yimeng Zhu, Tianrui Wang, Jinyu Li, Shujie Liu, Bo Ren, Linquan Liu, Yu Wu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2307.03917)
[![citation](https://img.shields.io/badge/citation-24-blue.svg?paper=8e1868f84091272544cb4209c4ccaad7cc88af27)](https://www.semanticscholar.org/paper/8e1868f84091272544cb4209c4ccaad7cc88af27)

+ **AudioPaLM: A Large Language Model That Can Speak and Listen** (22 Jun 2023)<details><summary>Paul K. Rubenstein, Chulayuth Asawaroengchai, Duc Dung Nguyen, et al.</summary>Paul K. Rubenstein, Chulayuth Asawaroengchai, Duc Dung Nguyen, Ankur Bapna, Zalán Borsos, Félix de Chaumont Quitry, Peter Chen, Dalia El Badawy, Wei Han, Eugene Kharitonov, Hannah Muckenhirn, Dirk Padfield, James Qin, Danny Rozenberg, Tara Sainath, Johan Schalkwyk, Matt Sharifi, Michelle Tadmor Ramanovich, Marco Tagliasacchi, Alexandru Tudor, Mihajlo Velimirović, Damien Vincent, Jiahui Yu, Yongqiang Wang, Vicky Zayats, Neil Zeghidour, Yu Zhang, Zhishuai Zhang, Lukas Zilka, Christian Frank</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.12925)
[![citation](https://img.shields.io/badge/citation-69-blue.svg?paper=3efb81de24eb88017d6dbcf22cb4215084223fd8)](https://www.semanticscholar.org/paper/3efb81de24eb88017d6dbcf22cb4215084223fd8)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://google-research.github.io/seanet/audiopalm/examples/)

+ **Hugginggpt: Solving ai tasks with chatgpt and its friends in huggingface** (30 Mar 2023)<details><summary>Yongliang Shen, Kaitao Song, Xu Tan, et al.</summary>Yongliang Shen, Kaitao Song, Xu Tan, Dongsheng Li, Weiming Lu, Yueting Zhuang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.17580)
[![citation](https://img.shields.io/badge/citation-413-blue.svg?paper=d1120d67b700e4dfe8b39eb1e48fbdea4e1a0c43)](https://www.semanticscholar.org/paper/d1120d67b700e4dfe8b39eb1e48fbdea4e1a0c43)
[![Code](https://img.shields.io/github/stars/microsoft/JARVIS.svg?style=social&label=Star)](https://github.com/microsoft/JARVIS)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/microsoft/HuggingGPT)

+ **Sparks of Artificial General Intelligence: Early experiments with GPT-4** (22 Mar 2023)<details><summary>Sébastien Bubeck, Varun Chandrasekaran, Ronen Eldan, et al.</summary>Sébastien Bubeck, Varun Chandrasekaran, Ronen Eldan, Johannes Gehrke, Eric Horvitz, Ece Kamar, Peter Lee, Yin Tat Lee, Yuanzhi Li, Scott Lundberg, Harsha Nori, Hamid Palangi, Marco Tulio Ribeiro, Yi Zhang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.12712)
[![citation](https://img.shields.io/badge/citation-1407-blue.svg?paper=574beee702be3856d60aa482ec725168fe64fc99)](https://www.semanticscholar.org/paper/574beee702be3856d60aa482ec725168fe64fc99)

+ **Listen, Think, and Understand** (18 May 2023)<details><summary>Yuan Gong, Hongyin Luo, Alexander H. Liu, et al.</summary>Yuan Gong, Hongyin Luo, Alexander H. Liu, Leonid Karlinsky, James Glass</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.10790)
[![citation](https://img.shields.io/badge/citation-33-blue.svg?paper=4bb0b12803791764d641a4cef1e0ce39cf049542)](https://www.semanticscholar.org/paper/4bb0b12803791764d641a4cef1e0ce39cf049542)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/yuangongfdu/LTU)

+ **Speechgpt: Empowering large language models with intrinsic cross-modal conversational abilities** (18 May 2023)<details><summary>Dong Zhang, Shimin Li, Xin Zhang, et al.</summary>Dong Zhang, Shimin Li, Xin Zhang, Jun Zhan, Pengyu Wang, Yaqian Zhou, Xipeng Qiu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.11000)
[![citation](https://img.shields.io/badge/citation-76-blue.svg?paper=5cac6430bd379c9d2fe13137dfd6ae7721a2679f)](https://www.semanticscholar.org/paper/5cac6430bd379c9d2fe13137dfd6ae7721a2679f)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://0nutation.github.io/SpeechGPT.github.io/)
[![Code](https://img.shields.io/github/stars/0nutation/SpeechGPT.svg?style=social&label=Star)](https://github.com/0nutation/SpeechGPT)

+ **Audiogpt: Understanding and generating speech, music, sound, and talking head** (25 Apr 2023)<details><summary>Rongjie Huang, Mingze Li, Dongchao Yang, et al.</summary>Rongjie Huang, Mingze Li, Dongchao Yang, Jiatong Shi, Xuankai Chang, Zhenhui Ye, Yuning Wu, Zhiqing Hong, Jiawei Huang, Jinglin Liu, Yi Ren, Zhou Zhao, Shinji Watanabe</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.12995)
[![citation](https://img.shields.io/badge/citation-83-blue.svg?paper=8bc617c9139648d7a92991d70c671230bac7b2e2)](https://www.semanticscholar.org/paper/8bc617c9139648d7a92991d70c671230bac7b2e2)
[![Code](https://img.shields.io/github/stars/AIGC-Audio/AudioGPT.svg?style=social&label=Star)](https://github.com/AIGC-Audio/AudioGPT)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/AIGC-Audio/AudioGPT)



# 📍 Multimodal LLM Safety
## Attack

+ **Jailbreaking gpt-4v via self-adversarial attacks with system prompts.** (20 Jan 2024)<details><summary>Yuanwei Wu, Xiang Li, Yixin Liu, et al.</summary>Yuanwei Wu, Xiang Li, Yixin Liu, Pan Zhou, Lichao Sun</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.09127.pdf)
[![citation](https://img.shields.io/badge/citation-8-blue.svg?paper=18a8b97d75a87e8fef07542d8875d4a62b553744)](https://www.semanticscholar.org/paper/18a8b97d75a87e8fef07542d8875d4a62b553744)
[![Code](https://img.shields.io/github/stars/ThuCCSLab/lm-ssp.svg?style=social&label=Star)](https://github.com/ThuCCSLab/lm-ssp)

+ **Defending chatgpt against jailbreak attack via self-reminders.** (1 Dec 2023)<details><summary>Yueqi Xie, Jingwei Yi, Jiawei Shao, et al.</summary>Yueqi Xie, Jingwei Yi, Jiawei Shao, Justin Curl, Lingjuan Lyu, Qifeng Chen, Xing Xie, Fangzhao Wu</details>
[![citation](https://img.shields.io/badge/citation-32-blue.svg?paper=e762f92273cd96f63b7788c0173b9b6450adedd7)](https://www.semanticscholar.org/paper/e762f92273cd96f63b7788c0173b9b6450adedd7)
[![Code](https://img.shields.io/github/stars/yjw1029/Self-Reminder.svg?style=social&label=Star)](https://github.com/yjw1029/Self-Reminder)

+ **Misusing Tools in Large Language Models With Visual Adversarial Examples** (4 Oct 2023)<details><summary>Xiaohan Fu, Zihan Wang, Shuheng Li, et al.</summary>Xiaohan Fu, Zihan Wang, Shuheng Li, Rajesh K. Gupta, Niloofar Mireshghallah, Taylor Berg-Kirkpatrick, Earlence Fernandes</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.03185.pdf)
[![citation](https://img.shields.io/badge/citation-6-blue.svg?paper=ac5b4df0e398ca48388330ac5c795b6fe708793c)](https://www.semanticscholar.org/paper/ac5b4df0e398ca48388330ac5c795b6fe708793c)

+ **Image Hijacks: Adversarial Images can Control Generative Models at Runtime.** (18 Sep 2023)<details><summary>Luke Bailey, Euan Ong, Stuart Russell, et al.</summary>Luke Bailey, Euan Ong, Stuart Russell, Scott Emmons</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.00236.pdf)
[![citation](https://img.shields.io/badge/citation-22-blue.svg?paper=5bdaadb84db0cbf72aaebda9f55f4288b63c6e9b)](https://www.semanticscholar.org/paper/5bdaadb84db0cbf72aaebda9f55f4288b63c6e9b)
[![Code](https://img.shields.io/github/stars/euanong/image-hijacks.svg?style=social&label=Star)](https://github.com/euanong/image-hijacks)

+ **Universal and Transferable Adversarial Attacks on Aligned Language Models** (27 Jul 2023)<details><summary>Andy Zou, Zifan Wang, Nicholas Carlini, et al.</summary>Andy Zou, Zifan Wang, Nicholas Carlini, Milad Nasr, J. Zico Kolter, Matt Fredrikson</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2307.15043.pdf)
[![citation](https://img.shields.io/badge/citation-309-blue.svg?paper=47030369e97cc44d4b2e3cf1be85da0fd134904a)](https://www.semanticscholar.org/paper/47030369e97cc44d4b2e3cf1be85da0fd134904a)
[![Code](https://img.shields.io/github/stars/llm-attacks/llm-attacks.svg?style=social&label=Star)](https://github.com/llm-attacks/llm-attacks)

+ **Prompt injection attack against llm-integrated applications** (8 Jun 2023)<details><summary>Yi Liu, Gelei Deng, Yuekang Li, et al.</summary>Yi Liu, Gelei Deng, Yuekang Li, Kailong Wang, Tianwei Zhang, Yepang Liu, Haoyu Wang, Yan Zheng, Yang Liu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.05499.pdf)
[![citation](https://img.shields.io/badge/citation-77-blue.svg?paper=db4cf9f6a653d5c15973e836c800ea47743251ae)](https://www.semanticscholar.org/paper/db4cf9f6a653d5c15973e836c800ea47743251ae)
[![Code](https://img.shields.io/github/stars/LLMSecurity/HouYi.svg?style=social&label=Star)](https://github.com/LLMSecurity/HouYi)

+ **Automatically Auditing Large Language Models via Discrete Optimization** (8 Mar 2023)<details><summary>Erik Jones, Anca Dragan, Aditi Raghunathan, et al.</summary>Erik Jones, Anca Dragan, Aditi Raghunathan, Jacob Steinhardt</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.04381.pdf)
[![citation](https://img.shields.io/badge/citation-64-blue.svg?paper=2f94f03fdac62d05f0f416b7b3855d1f597afee9)](https://www.semanticscholar.org/paper/2f94f03fdac62d05f0f416b7b3855d1f597afee9)
[![Code](https://img.shields.io/github/stars/ejones313/auditing-llms.svg?style=social&label=Star)](https://github.com/ejones313/auditing-llms)

+ **Poisoning Web-Scale Training Datasets is Practical** (20 Feb 2023)<details><summary>Nicholas Carlini, Matthew Jagielski, Christopher A. Choquette-Choo, et al.</summary>Nicholas Carlini, Matthew Jagielski, Christopher A. Choquette-Choo, Daniel Paleka, Will Pearce, Hyrum Anderson, Andreas Terzis, Kurt Thomas, Florian Tram  r</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2302.10149.pdf)
[![citation](https://img.shields.io/badge/citation-61-blue.svg?paper=2cf43a61d0937ad25f23eaef7c90253ab799b3c7)](https://www.semanticscholar.org/paper/2cf43a61d0937ad25f23eaef7c90253ab799b3c7)

+ **Exploiting programmatic behavior of llms: Dual-use through standard security attacks.** (11 Feb 2023)<details><summary>Daniel Kang, Xuechen Li, Ion Stoica, et al.</summary>Daniel Kang, Xuechen Li, Ion Stoica, Carlos Guestrin, Matei Zaharia, Tatsunori Hashimoto</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2302.05733.pdf)
[![citation](https://img.shields.io/badge/citation-94-blue.svg?paper=0cf694b8f85ab2e11d45595de211a15cfbadcd22)](https://www.semanticscholar.org/paper/0cf694b8f85ab2e11d45595de211a15cfbadcd22)

+ **Ignore previous prompt: Attack techniques for language models** (17 Nov 2022)\
F  bio Perez, Ian Ribeiro (NeurIPS 2022 Workshop)\
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2211.09527.pdf)
[![citation](https://img.shields.io/badge/citation-151-blue.svg?paper=9716a2876d08fce9d8e5c5ba4d7b1a9af44806d6)](https://www.semanticscholar.org/paper/9716a2876d08fce9d8e5c5ba4d7b1a9af44806d6)
[![Code](https://img.shields.io/github/stars/agencyenterprise/PromptInject.svg?style=social&label=Star)](https://github.com/agencyenterprise/PromptInject)



## Defense and Detect
+ **Detecting and correcting hate speech in multimodal memes with large visual language model.** (12 Nov 2023)\
Minh-Hao Van, Xintao Wu\
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.06737.pdf)
[![citation](https://img.shields.io/badge/citation-5-blue.svg?paper=60f4dc690ea42fb77b04fc685e9d9c3a1e209319)](https://www.semanticscholar.org/paper/60f4dc690ea42fb77b04fc685e9d9c3a1e209319)

+ **Detecting Pretraining Data from Large Language Models** (3 Nov 2023)<details><summary>Weijia Shi, Anirudh Ajith, Mengzhou Xia, et al.</summary>Weijia Shi, Anirudh Ajith, Mengzhou Xia, Yangsibo Huang, Daogao Liu, Terra Blevins, Danqi Chen, Luke Zettlemoyer</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.16789.pdf)
[![citation](https://img.shields.io/badge/citation-20-blue.svg?paper=3422d5e0cdfdc935d6a84a1e3d3f96659265fe3a)](https://www.semanticscholar.org/paper/3422d5e0cdfdc935d6a84a1e3d3f96659265fe3a)
[![Code](https://img.shields.io/github/stars/swj0419/detect-pretrain-code.svg?style=social&label=Star)](https://github.com/swj0419/detect-pretrain-code)

+ **Jailbreak and guard aligned language models with only few in-context demonstrations** (10 Oct 2023)\
Zeming Wei, Yifei Wang, Yisen Wang\
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.06387.pdf)
[![citation](https://img.shields.io/badge/citation-43-blue.svg?paper=6b135e922a0c673aeb0b05c5aeecdb6c794791c6)](https://www.semanticscholar.org/paper/6b135e922a0c673aeb0b05c5aeecdb6c794791c6)

+ **Smoothllm: Defending large language models against jailbreaking attacks.** (5 Oct 2023)<details><summary>Alexander Robey, Eric Wong, Hamed Hassani, et al.</summary>Alexander Robey, Eric Wong, Hamed Hassani, George J. Pappas</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.03684.pdf)
[![citation](https://img.shields.io/badge/citation-46-blue.svg?paper=8cf9b49698fdb1b754df2556576412a7b44929f6)](https://www.semanticscholar.org/paper/8cf9b49698fdb1b754df2556576412a7b44929f6)
[![Code](https://img.shields.io/github/stars/arobey1/smooth-llm.svg?style=social&label=Star)](https://github.com/arobey1/smooth-llm)

+ **A Watermark for Large Language Models** (6 Jun 2023)<details><summary>John Kirchenbauer, Jonas Geiping, Yuxin Wen, et al. (ICML 2023)</summary>John Kirchenbauer, Jonas Geiping, Yuxin Wen, Jonathan Katz, Ian Miers, Tom Goldstein</details>[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2301.10226.pdf)
[![citation](https://img.shields.io/badge/citation-199-blue.svg?paper=cb5b71a622aff47014d4f28a958679629a8b6363)](https://www.semanticscholar.org/paper/cb5b71a622aff47014d4f28a958679629a8b6363)
[![Code](https://img.shields.io/github/stars/BrianPulfer/LMWatermark.svg?style=social&label=Star)](https://github.com/BrianPulfer/LMWatermark)

+ **Unsafe Diffusion: On the Generation of Unsafe Images and Hateful Memes From Text-To-Image Models** (23 May 2023)<details><summary>Yiting Qu, Xinyue Shen, Xinlei He, et al. (ACM CCS 2023)</summary>Yiting Qu, Xinyue Shen, Xinlei He, Michael Backes, Savvas Zannettou, Yang Zhang</details>[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.13873.pdf)
[![citation](https://img.shields.io/badge/citation-29-blue.svg?paper=c9e548d72f5ad72215025602be36f72042219baf)](https://www.semanticscholar.org/paper/c9e548d72f5ad72215025602be36f72042219baf)
[![Code](https://img.shields.io/github/stars/YitingQu/unsafe-diffusion.svg?style=social&label=Star)](https://github.com/YitingQu/unsafe-diffusion)

+ **TRAK: Attributing Model Behavior at Scale** (3 Apr 2023)<details><summary>Sung Min Park, Kristian Georgiev, Andrew Ilyas, et al.</summary>Sung Min Park, Kristian Georgiev, Andrew Ilyas, Guillaume Leclerc, Aleksander Madry</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.14186.pdf)
[![citation](https://img.shields.io/badge/citation-32-blue.svg?paper=4f2ae5fa2dc74af9c36ee57b359a4b3241006a92)](https://www.semanticscholar.org/paper/4f2ae5fa2dc74af9c36ee57b359a4b3241006a92)
[![Code](https://img.shields.io/github/stars/MadryLab/trak.svg?style=social&label=Star)](https://github.com/MadryLab/trak)

+ **Poisoning Web-Scale Training Datasets is Practical** (20 Feb 2023)<details><summary>Nicholas Carlini, Matthew Jagielski, Christopher A. Choquette-Choo, et al.</summary>Nicholas Carlini, Matthew Jagielski, Christopher A. Choquette-Choo, Daniel Paleka, Will Pearce, Hyrum Anderson, Andreas Terzis, Kurt Thomas, Florian Tram  r</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2302.10149.pdf)
[![citation](https://img.shields.io/badge/citation-61-blue.svg?paper=2cf43a61d0937ad25f23eaef7c90253ab799b3c7)](https://www.semanticscholar.org/paper/2cf43a61d0937ad25f23eaef7c90253ab799b3c7)

+ **Mitigating Inappropriate Degeneration in Diffusion Models** (9 Nov 2022)<details><summary>Patrick Schramowski, Manuel Brack, Bj?rn Deiseroth, et al. (CVPR 2023)</summary>Patrick Schramowski, Manuel Brack, Bj?rn Deiseroth, Kristian Kersting</details>[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2211.05105.pdf)
[![citation](https://img.shields.io/badge/citation-76-blue.svg?paper=0231f2aed9a96cb516242fb57f2cb63f5651c4d8)](https://www.semanticscholar.org/paper/0231f2aed9a96cb516242fb57f2cb63f5651c4d8)
[![Code](https://img.shields.io/github/stars/ml-research/safe-latent-diffusion.svg?style=social&label=Star)](https://github.com/ml-research/safe-latent-diffusion)



## Alignment
+ **Direct Preference Optimization: Your Language Model is Secretly a Reward Model** (13 Dec 2023)<details><summary>Rafael Rafailov, Archit Sharma, Eric Mitchell, et al.</summary>Rafael Rafailov, Archit Sharma, Eric Mitchell, Stefano Ermon, Christopher D. Manning, Chelsea Finn</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.18290.pdf)
[![citation](https://img.shields.io/badge/citation-450-blue.svg?paper=0d1c76d45afa012ded7ab741194baf142117c495)](https://www.semanticscholar.org/paper/0d1c76d45afa012ded7ab741194baf142117c495)

+ **Raft: Reward ranked fine tuning for generative foundation model alignment** (1 Dec 2023)<details><summary>Hanze Dong, Wei Xiong, Deepanshu Goyal, et al. (Transactions on Machine Learning Research (TMLR))</summary>Hanze Dong, Wei Xiong, Deepanshu Goyal, Yihan Zhang, Winnie Chow, Rui Pan, Shizhe Diao, Jipeng Zhang, Kashun Shum, Tong Zhang</details>[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.06767.pdf)
[![citation](https://img.shields.io/badge/citation-116-blue.svg?paper=3ab661db57d924f4ff1706e05ac807873ca00e0a)](https://www.semanticscholar.org/paper/3ab661db57d924f4ff1706e05ac807873ca00e0a)

+ **Better aligning text-to-image models with human preference** (22 Aug 2023)<details><summary>Xiaoshi Wu, Keqiang Sun, Feng Zhu, et al. (ICCV 2023)</summary>Xiaoshi Wu, Keqiang Sun, Feng Zhu, Rui Zhao, Hongsheng Li</details>[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.14420.pdf)
[![citation](https://img.shields.io/badge/citation-44-blue.svg?paper=14c3cf58192774b9b6fc6188df99efd6ab5fc739)](https://www.semanticscholar.org/paper/14c3cf58192774b9b6fc6188df99efd6ab5fc739)
[![Code](https://img.shields.io/github/stars/tgxs002/align_sd.svg?style=social&label=Star)](https://github.com/tgxs002/align_sd)


## Datasets
+ **Goat-bench: Safety insights to large multimodal models through meme-based social abuse.** (7 Jan 2024)<details><summary>Hongzhan Lin, Ziyang Luo, Bo Wang, et al.</summary>Hongzhan Lin, Ziyang Luo, Bo Wang, Ruichao Yang, Jing Ma</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.01523.pdf)
[![citation](https://img.shields.io/badge/citation-4-blue.svg?paper=d98aa44f79fe798ad5ff0cac6e7bf32ee30bd156)](https://www.semanticscholar.org/paper/d98aa44f79fe798ad5ff0cac6e7bf32ee30bd156)
[![Code](https://img.shields.io/github/stars/isXinLiu/MLLM-Safety-Collection.svg?style=social&label=Star)](https://github.com/isXinLiu/MLLM-Safety-Collection)

+ **Tovilag: Your visual-language generative model is also an evildoer.** (13 Dec 2023)<details><summary>Xinpeng Wang, Xiaoyuan Yi, Han Jiang, et al. (EMNLP 2023 Oral)</summary>Xinpeng Wang, Xiaoyuan Yi, Han Jiang, Shanlin Zhou, Zhihua Wei, Xing Xie</details>[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](http://export.arxiv.org/abs/2312.11523)
[![citation](https://img.shields.io/badge/citation-1-blue.svg?paper=10280c290825fc0b0c884e988f4f1dedb80e4e80)](https://www.semanticscholar.org/paper/10280c290825fc0b0c884e988f4f1dedb80e4e80)
[![Code](https://img.shields.io/github/stars/victorup/ToViLaG.svg?style=social&label=Star)](https://github.com/victorup/ToViLaG)

+ **Figstep: Jailbreaking large vision-language models via typographic visual prompts.** (13 Dec 2023)<details><summary>Yichen Gong, Delong Ran, Jinyuan Liu, et al.</summary>Yichen Gong, Delong Ran, Jinyuan Liu, Conglei Wang, Tianshuo Cong, Anyu Wang, Sisi Duan, Xiaoyun Wang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.05608.pdf)
[![citation](https://img.shields.io/badge/citation-7-blue.svg?paper=b78b5ce5f21f46d8149824463f8eebd6103d49aa)](https://www.semanticscholar.org/paper/b78b5ce5f21f46d8149824463f8eebd6103d49aa)
[![Code](https://img.shields.io/github/stars/ThuCCSLab/FigStep.svg?style=social&label=Star)](https://github.com/ThuCCSLab/FigStep)

+ **Query-relevant images jailbreak large multi-modal models.** (29 Nov 2023)<details><summary>Xin Liu, Yichen Zhu, Yunshi Lan, et al.</summary>Xin Liu, Yichen Zhu, Yunshi Lan, Chao Yang, Yu Qiao</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.17600.pdf)
[![citation](https://img.shields.io/badge/citation-N/A-blue.svg?paper=74423a9ee66085e74cd2b2e42303f28359c74eb6)](https://www.semanticscholar.org/paper/74423a9ee66085e74cd2b2e42303f28359c74eb6)
[![Code](https://img.shields.io/github/stars/isXinLiu/MM-SafetyBench.svg?style=social&label=Star)](https://github.com/isXinLiu/MM-SafetyBench)

+ **Dress: Instructing large vision-language models to align and interact with humans via natural language feedback.** (16 Nov 2023)<details><summary>Yangyi Chen, Karan Sikka, Michael Cogswell, et al.</summary>Yangyi Chen, Karan Sikka, Michael Cogswell, Heng Ji, Ajay Divakaran</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.10081.pdf)
[![citation](https://img.shields.io/badge/citation-9-blue.svg?paper=391eaeb1092c2b145ff0e5a2fa61637a42921fce)](https://www.semanticscholar.org/paper/391eaeb1092c2b145ff0e5a2fa61637a42921fce)

+ **Beavertails: Towards improved safety alignment of llm via a human-preference dataset** (7 Nov 2023)<details><summary>Jiaming Ji, Mickel Liu, Juntao Dai, et al. (NeurIPS 2023)</summary>Jiaming Ji, Mickel Liu, Juntao Dai, Xuehai Pan, Chi Zhang, Ce Bian, Chi Zhang, Ruiyang Sun, Yizhou Wang, Yaodong Yang</details>[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2307.04657.pdf)
[![citation](https://img.shields.io/badge/citation-56-blue.svg?paper=92930ed3560ea6c86d53cf52158bc793b089054d)](https://www.semanticscholar.org/paper/92930ed3560ea6c86d53cf52158bc793b089054d)
[![Code](https://img.shields.io/github/stars/GaryYufei/AlignLLMHumanSurvey.svg?style=social&label=Star)](https://github.com/GaryYufei/AlignLLMHumanSurvey)

+ **Can pre-trained vision and language models answer visual information-seeking questions?** (17 Oct 2023)<details><summary>Yang Chen, Hexiang Hu, Yi Luan, et al. (EMNLP 2023)</summary>Yang Chen, Hexiang Hu, Yi Luan, Haitian Sun, Soravit Changpinyo, Alan Ritter, Ming-Wei Chang</details>[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2302.11713.pdf)
[![citation](https://img.shields.io/badge/citation-19-blue.svg?paper=f890b4dfe915174b23db909b07c515d465eaeff2)](https://www.semanticscholar.org/paper/f890b4dfe915174b23db909b07c515d465eaeff2)
[![Code](https://img.shields.io/github/stars/edchengg/infoseek_eval.svg?style=social&label=Star)](https://github.com/edchengg/infoseek_eval)

+ **Can language models be instructed to protect personal information?** (3 Oct 2023)<details><summary>Yang Chen, Ethan Mendes, Sauvik Das, et al.</summary>Yang Chen, Ethan Mendes, Sauvik Das, Wei Xu, Alan Ritter</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.02224.pdf)
[![citation](https://img.shields.io/badge/citation-14-blue.svg?paper=2403c8e72a90d9c778970fc0812ecdcc58800c5d)](https://www.semanticscholar.org/paper/2403c8e72a90d9c778970fc0812ecdcc58800c5d)
[![Code](https://img.shields.io/github/stars/ethanm88/llm-access-control.svg?style=social&label=Star)](https://github.com/ethanm88/llm-access-control)

+ **Safetybench: Evaluating the safety of large language models with multiple choice questions** (13 Sep 2023)<details><summary>Zhexin Zhang, Leqi Lei, Lindong Wu, et al.</summary>Zhexin Zhang, Leqi Lei, Lindong Wu, Rui Sun, Yongkang Huang, Chong Long, Xiao Liu, Xuanyu Lei, Jie Tang, Minlie Huang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.07045.pdf)
[![citation](https://img.shields.io/badge/citation-13-blue.svg?paper=9b9a4fa3ed510fc6eb1bf831979235f3d9f8b556)](https://www.semanticscholar.org/paper/9b9a4fa3ed510fc6eb1bf831979235f3d9f8b556)
[![Code](https://img.shields.io/github/stars/thu-coai/SafetyBench.svg?style=social&label=Star)](https://github.com/thu-coai/SafetyBench)

+ **Safety assessment of chinese large language models** (20 Apr 2023)<details><summary>Hao Sun, Zhexin Zhang, Jiawen Deng, et al.</summary>Hao Sun, Zhexin Zhang, Jiawen Deng, Jiale Cheng, Minlie Huang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.10436.pdf)
[![citation](https://img.shields.io/badge/citation-33-blue.svg?paper=59fc49dfd81b92661437eaf7e339c0792ccd8755)](https://www.semanticscholar.org/paper/59fc49dfd81b92661437eaf7e339c0792ccd8755)
[![Code](https://img.shields.io/github/stars/thu-coai/Safety-Prompts.svg?style=social&label=Star)](https://github.com/thu-coai/Safety-Prompts)


## 3D, Video and Audio Safety

+ **Not My Voice! A Taxonomy of Ethical and Safety Harms of Speech Generators** (25 Jan 2024)\
Wiebke Hutiri, Oresiti Papakyriakopoulos, Alice Xiang\
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.01708)
[![citation](https://img.shields.io/badge/citation-N/A-blue.svg?paper=Not-My-Voice!-A-Taxonomy-of-Ethical-an)
)](https://www.semanticscholar.org/paper/Not-My-Voice!-A-Taxonomy-of-Ethical-an)
)

+ **Adv3D: Generating 3D Adversarial Examples in Driving Scenarios with NeRF** (4 Sep 2023)\
Leheng Li, Qing Lian, Ying-Cong Chen\
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.01351)
[![citation](https://img.shields.io/badge/citation-2-blue.svg?paper=daa6a6b2c495d002d72075c6203c98061d1e35f9)](https://www.semanticscholar.org/paper/daa6a6b2c495d002d72075c6203c98061d1e35f9)
[![Code](https://img.shields.io/github/stars/EnVision-Research/Adv3D.svg?style=social&label=Star)](https://github.com/EnVision-Research/Adv3D)

+ **Deepfake Video Detection Using Generative Convolutional Vision Transformer** (13 Jul 2023)\
Deressa Wodajo, Solomon Atnafu, Zahid Akhtar\
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2307.07036)
[![citation](https://img.shields.io/badge/citation-0-blue.svg?paper=86301139cc02eb53247e63fca91b916348591505)](https://www.semanticscholar.org/paper/86301139cc02eb53247e63fca91b916348591505)
[![Code](https://img.shields.io/github/stars/erprogs/GenConViT.svg?style=social&label=Star)](https://github.com/erprogs/GenConViT)

+ **M2TR: Multi-modal Multi-scale Transformers for Deepfake Detection** (19 Apr 2022)\
Junke Wang, Zuxuan Wu, Wenhao Ouyang, Xintong Han, Jingjing Chen, Ser-Nam Lim, Yu-Gang Jiang\
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2104.09770)
[![citation](https://img.shields.io/badge/citation-132-blue.svg?paper=21e0858665cddf51689fc680f72ec4e00b68ae04)](https://www.semanticscholar.org/paper/21e0858665cddf51689fc680f72ec4e00b68ae04)
[![Code](https://img.shields.io/github/stars/wangjk666/M2TR-Multi-modal-Multi-scale-Transformers-for-Deepfake-Detection.svg?style=social&label=Star)](https://github.com/wangjk666/M2TR-Multi-modal-Multi-scale-Transformers-for-Deepfake-Detection)


# 📍 Related Surveys
## LLM


+ **MM-LLMs: Recent Advances in MultiModal Large Language Models** (24 Jan 2024)<details><summary>Duzhen Zhang, Yahan Yu, Chenxing Li</summary>Duzhen Zhang, Yahan Yu, Chenxing Li, Jiahua Dong, Dan Su, Chenhui Chu, Dong Yu</details>[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.13601)
[![citation](https://img.shields.io/badge/citation-4-blue.svg?paper=a050c9b0c321839e4427ab9defa3463be7825ac4)](https://www.semanticscholar.org/paper/a050c9b0c321839e4427ab9defa3463be7825ac4)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://mm-llms.github.io/)


+ **A Survey on Multimodal Large Language Models** (23 Jun 2023)<details><summary>Shukang Yin, Chaoyou Fu, Sirui Zhao, et al.</summary>Shukang Yin, Chaoyou Fu, Sirui Zhao, Ke Li, Xing Sun, Tong Xu, Enhong Chen</details>[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.13549)
[![citation](https://img.shields.io/badge/citation-114-blue.svg?paper=ebedc4d7a2356090904baba4104ef0832bc236df)](https://www.semanticscholar.org/paper/ebedc4d7a2356090904baba4104ef0832bc236df)
[![Code](https://img.shields.io/github/stars/BradyFU/Awesome-Multimodal-Large-Language-Models.svg?style=social&label=Star)](https://github.com/BradyFU/Awesome-Multimodal-Large-Language-Models)


+ **Multimodal Large Language Models: A Survey** (22 Nov 2023)<details><summary>[IEEE BigData 2023] Jiayang Wu, Wensheng Gan, Zefeng Chen, et al.</summary>Jiayang Wu, Wensheng Gan, Zefeng Chen, Shicheng Wan, Philip S. Yu</details>[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.13165)
[![citation](https://img.shields.io/badge/citation-14-blue.svg?paper=52941cadbd340344f3e0a6f50719fe55b3de5088)](https://www.semanticscholar.org/paper/52941cadbd340344f3e0a6f50719fe55b3de5088)


+ **A Survey of Large Language Models** (31 Mar 2023)<details><summary>Wayne Xin Zhao, Kun Zhou, Junyi Li, et al.</summary>Wayne Xin Zhao, Kun Zhou, Junyi Li, Tianyi Tang, Xiaolei Wang, Yupeng Hou, Yingqian Min, Beichen Zhang, Junjie Zhang, Zican Dong, Yifan Du, Chen Yang, Yushuo Chen, Zhipeng Chen, Jinhao Jiang, Ruiyang Ren, Yifan Li, Xinyu Tang, Zikang Liu, Peiyu Liu, Jian-Yun Nie, Ji-Rong Wen</details>[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.18223)
[![citation](https://img.shields.io/badge/citation-875-blue.svg?paper=c61d54644e9aedcfc756e5d6fe4cc8b78c87755d)](https://www.semanticscholar.org/paper/c61d54644e9aedcfc756e5d6fe4cc8b78c87755d)
[![Code](https://img.shields.io/github/stars/RUCAIBox/LLMSurvey.svg?style=social&label=Star)](https://github.com/RUCAIBox/LLMSurvey?tab=readme-ov-file#timeline-of-llms)


## Vision


+ **State of the Art on Diffusion Models for Visual Computing** (11 Oct 2023)<details><summary>Ryan Po, Wang Yifan, Vladislav Golyanik, et al.</summary>Ryan Po, Wang Yifan, Vladislav Golyanik, Kfir Aberman, Jonathan T. Barron, Amit H. Bermano, Eric Ryan Chan, Tali Dekel, Aleksander Holynski, Angjoo Kanazawa, C. Karen Liu, Lingjie Liu, Ben Mildenhall, Matthias Nießner, Björn Ommer, Christian Theobalt, Peter Wonka, Gordon Wetzstein</details>[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.07204)
[![citation](https://img.shields.io/badge/citation-27-blue.svg?paper=6487ec82f6d8082a5b402a5416ea03009acb1679)](https://www.semanticscholar.org/paper/6487ec82f6d8082a5b402a5416ea03009acb1679)
[![Code](https://img.shields.io/github/stars/CroitoruAlin/Diffusion-Models-in-Vision-A-Survey.svg?style=social&label=Star)](https://github.com/CroitoruAlin/Diffusion-Models-in-Vision-A-Survey)

+ **Diffusion Models in Vision: A Survey** (10 Sep 2022)<details><summary>[TPAMI 2023] Florinel-Alin Croitoru, Vlad Hondru, Radu Tudor Ionescu, et al. </summary>Florinel-Alin Croitoru, Vlad Hondru, Radu Tudor Ionescu, Mubarak Shah</details>[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2209.04747)
[![citation](https://img.shields.io/badge/citation-371-blue.svg?paper=efa1647594b236361610a20d507127f0586a379b)](https://www.semanticscholar.org/paper/efa1647594b236361610a20d507127f0586a379b)
[![Code](https://img.shields.io/github/stars/CroitoruAlin/Diffusion-Models-in-Vision-A-Survey.svg?style=social&label=Star)](https://github.com/CroitoruAlin/Diffusion-Models-in-Vision-A-Survey)










