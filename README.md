# Awesome Diffusion Models in High-Resolution Synthesis [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
Collection of recent diffusion-based high-resolution (e.g., $>1024^2$) image and video synthesis works. Questions and discussions are most welcome! Upcoming works will be updated on a regular basis, feel free to contact me to add... :thumbsup:

## Papers and Codes

- [📍 Image Generation](#-image-generation)
  - [Tuning-Free Algorithm](#tuning-free-image)
  - [Fine-Tuning Algorithm](#tuning-image)
  - [Training from Scratch Algorithm](#training-from-scratch-image)
  - [Super Resolution Algorithm](#super-resolution-image)
  - [Datasets](#dataset-image)
  - [Metrics](#metric-image)
- [📍 Video Generation](#video-generation)
  - [Tuning-Free Algorithm](#tuning-free-video)
  - [Fine-Tuning Algorithm](#tuning-video)
  - [Training from Scratch Algorithm](#training-from-scratch-video)
  - [Super Resolution Algorithm](#super-resolution-video)
  - [Datasets](#dataset-video)
  - [Metrics](#metric-video)

### 🔅 Tuning-Free Algorithm

+ **ResMaster: Mastering High-Resolution Image Generation via Structural and Fine-Grained Guidance** (24 June 2024)<details><summary>Shuwei Shi, Wenbo Li, Yuechen Zhang, et al.</summary> Shuwei Shi, Wenbo Li, Yuechen Zhang, Jingwen He, Biao Gong, Yinqiang Zheng</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.16476)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://sites.google.com/view/minedreamer/main)
[![Code](https://img.shields.io/github/stars/Shuweis/ResMaster.svg?style=social&label=Star)](https://github.com/Shuweis/ResMaster)

+ **DiffuseHigh: Training-free Progressive High-Resolution Image Synthesis through Structure Guidance** (26 June 2024)<details><summary>Linjiang Huang, Rongyao Fang, Aiping Zhang, et al.</summary> Linjiang Huang, Rongyao Fang, Aiping Zhang, Guanglu Song, Si Liu, Yu Liu, Hongsheng Li</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.18459)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://yhyun225.github.io)
[![Code](https://img.shields.io/github/stars/yhyun225/DiffuseHigh.svg?style=social&label=Star)](https://github.com/yhyun225/DiffuseHigh)

+ **FouriScale: A Frequency Perspective on Training-Free High-Resolution Image Synthesis** (19 Mar 2024)<details><summary>Linjiang Huang, Rongyao Fang, Aiping Zhang, et al.</summary> Linjiang Huang, Rongyao Fang, Aiping Zhang, Guanglu Song, Si Liu, Yu Liu, Hongsheng Li</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.12963)
[![Code](https://img.shields.io/github/stars/LeonHLJ/FouriScale.svg?style=social&label=Star)](https://github.com/LeonHLJ/FouriScale)

+ **`ECCV‘24` Make a Cheap Scaling: A Self-Cascade Diffusion Model for Higher-Resolution Adaptation** (16 Feb 2024)<details><summary> Lanqing Guo, Yingqing He, Haoxin Chen, et al.</summary> Lanqing Guo, Yingqing He, Haoxin Chen, Menghan Xia, Xiaodong Cun, Yufei Wang, Siyu Huang, Yong Zhang, Xintao Wang, Qifeng Chen, Ying Shan, Bihan Wen</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.10491)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://guolanqing.github.io/Self-Cascade/)
[![Code](https://img.shields.io/github/stars/GuoLanqing/Self-Cascade.svg?style=social&label=Star)](https://github.com/GuoLanqing/Self-Cascade/)
[![citation](https://img.shields.io/badge/citation-1-blue.svg?paper=9ced6e814457eae83f5415364e266143defc81d1)](https://www.semanticscholar.org/paper/MultiDiffusion%3A-Fusing-Diffusion-Paths-for-Image-Bar-Tal-Yariv/9ced6e814457eae83f5415364e266143defc81d1)

+ **`CVPR‘24` DemoFusion: Democratising High-Resolution Image Generation With No $$$** (15 Dec 2023)<details><summary> Ruoyi Du, Dongliang Chang, Timothy Hospedales, et al.</summary> Ruoyi Du, Dongliang Chang, Timothy Hospedales, Yi-Zhe Song, Zhanyu Ma</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.07702)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://ruoyidu.github.io/demofusion/demofusion.html)
[![Code](https://img.shields.io/github/stars/PRIS-CV/DemoFusion.svg?style=social&label=Star)](https://github.com/PRIS-CV/DemoFusion)
[![citation](https://img.shields.io/badge/citation-1-blue.svg?paper=9ced6e814457eae83f5415364e266143defc81d1)](https://www.semanticscholar.org/paper/MultiDiffusion%3A-Fusing-Diffusion-Paths-for-Image-Bar-Tal-Yariv/9ced6e814457eae83f5415364e266143defc81d1)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://replicate.com/lucataco/demofusion)


+ **`CVPR‘24` Chenyang Si, Ziqi Huang, Yuming Jiang, Ziwei Liu** (20 Sep 2023)<details><summary> Chenyang Si, Ziqi Huang, Yuming Jiang, et al.</summary> Chenyang Si, Ziqi Huang, Yuming Jiang, Ziwei Liu</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.11497)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://chenyangsi.top/FreeU/)
[![Code](https://img.shields.io/github/stars/ChenyangSi/FreeU.svg?style=social&label=Star)](https://github.com/ChenyangSi/FreeU)
[![citation](https://img.shields.io/badge/citation-1-blue.svg?paper=9ced6e814457eae83f5415364e266143defc81d1)](https://www.semanticscholar.org/paper/MultiDiffusion%3A-Fusing-Diffusion-Paths-for-Image-Bar-Tal-Yariv/9ced6e814457eae83f5415364e266143defc81d1)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/ChenyangSi/FreeU)

+ **`ICLR‘24` ScaleCrafter: Tuning-Free Higher-Resolution Visual Generation with Diffusion Models** (11 Oct 2023)<details><summary> Yingqing He, Shaoshu Yang, Haoxin Chen, et al.</summary> Yingqing He, Shaoshu Yang, Haoxin Chen, Xiaodong Cun, Menghan Xia, Yong Zhang, Xintao Wang, Ran He, Qifeng Chen, Ying Shan</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.07702)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://yingqinghe.github.io/scalecrafter/)
[![Code](https://img.shields.io/github/stars/YingqingHe/ScaleCrafter.svg?style=social&label=Star)](https://github.com/YingqingHe/ScaleCrafter)
[![citation](https://img.shields.io/badge/citation-1-blue.svg?paper=9ced6e814457eae83f5415364e266143defc81d1)](https://www.semanticscholar.org/paper/MultiDiffusion%3A-Fusing-Diffusion-Paths-for-Image-Bar-Tal-Yariv/9ced6e814457eae83f5415364e266143defc81d1)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://replicate.com/cjwbw/scalecrafter)


+ **`NeurIPS’23` Training-free Diffusion Model Adaptation for Variable-Sized Text-to-Image Synthesis** (26 Oct 2023)<details><summary>Zhiyu Jin, Xuli Shen, Bin Li, et al.</summary> Zhiyu Jin, Xuli Shen, Bin Li, Xiangyang Xue</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.08645)
[![citation](https://img.shields.io/badge/citation-1-blue.svg?paper=166b8c2ee52794c46615c5c52d0390d896b79794)](https://www.semanticscholar.org/paper/Training-free-Diffusion-Model-Adaptation-for-Jin-Shen/166b8c2ee52794c46615c5c52d0390d896b79794)


+ **`ICML‘23` MultiDiffusion: Fusing Diffusion Paths for Controlled Image Generation** (16 Feb 2023)<details><summary>Omer Bar-Tal, Lior Yariv, Yaron Lipman, et al.</summary> Omer Bar-Tal, Lior Yariv, Yaron Lipman, Tali Dekel</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2302.08113)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://multidiffusion.github.io)
[![Code](https://img.shields.io/github/stars/omerbt/MultiDiffusion.svg?style=social&label=Star)](https://github.com/omerbt/MultiDiffusion)
[![citation](https://img.shields.io/badge/citation-1-blue.svg?paper=9ced6e814457eae83f5415364e266143defc81d1)](https://www.semanticscholar.org/paper/MultiDiffusion%3A-Fusing-Diffusion-Paths-for-Image-Bar-Tal-Yariv/9ced6e814457eae83f5415364e266143defc81d1)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/weizmannscience/MultiDiffusion)


+ **HiDiffusion: Unlocking High-Resolution Creativity and Efficiency in Low-Resolution Trained Diffusion Models** (29 Nov 2023)<details><summary>Shen Zhang, Zhaowei Chen, Zhenyu Zhao, et al.</summary> Shen Zhang, Zhaowei Chen, Zhenyu Zhao, Yuhao Chen, Yao Tang, Jiajun Liang</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.17528)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://hidiffusion.github.io)
[![Code](https://img.shields.io/github/stars/megvii-research/HiDiffusion.svg?style=social&label=Star)](https://github.com/megvii-research/HiDiffusion)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://colab.research.google.com/drive/1EiBn9lSnPZTU4cikRRaBBexs429M-qty?usp=drive_link)
  

### Fine-Tuning Algorithm
* `ICCV2023` DiffFit: Unlocking Transferability of Large Diffusion Models via Simple Parameter-Efficient Fine-Tuning [[Paper]](https://arxiv.org/abs/2304.06648)

* `Arxiv2023` Any-Size-Diffusion: Toward Efficient Text-Driven Synthesis for Any-Size HD Images [[Paper]](https://arxiv.org/abs/2308.16582)

* `Arxiv2024` Make a Cheap Scaling: A Self-Cascade Diffusion Model for Higher-Resolution Adaptation [[Paper]](https://arxiv.org/abs/2402.10491) [[Code]](https://github.com/GuoLanqing/Self-Cascade/)


### Training from Scratch Algorithm

**Cascaded Model**

* `JMLR2022` [CDM] Cascaded Diffusion Models for High Fidelity Image Generation [[Paper]](https://arxiv.org/abs/2106.15282)
[[Webpage]](https://cascaded-diffusion.github.io/)

* `Arxiv2023` LaVie: High-Quality Video Generation with Cascaded Latent Diffusion Models [[Paper]](https://arxiv.org/abs/2309.15103) [[Code]](https://github.com/Vchitect/LaVie)
  
* `Arxiv2023` Show-1: Marrying Pixel and Latent Diffusion Models for Text-to-Video Generation [[Paper]](https://arxiv.org/abs/2309.15818) [[Code]](https://github.com/showlab/Show-1)
  
* `ICLR2024` Relay Diffusion: Unifying diffusion process across resolutions for image synthesis [[Paper]](https://arxiv.org/abs/2309.03350) [[Code]](https://github.com/THUDM/RelayDiffusion)


**End-to-End Model**
* `Arxiv2023` Simple diffusion: End-to-end diffusion for high resolution images [[Paper]](https://arxiv.org/abs/2301.11093)

* `Arxiv2023` On the Importance of Noise Scheduling for Diffusion Models [[Paper]](https://arxiv.org/abs/2301.10972)

* `Arxiv2023` ∞-Diff: Infinite Resolution Diffusion with Subsampled Mollified States [[Paper]](https://arxiv.org/abs/2303.18242)

* `ICLR2024` SDXL: Improving Latent Diffusion Models for High-Resolution Image Synthesis [[Paper]](https://arxiv.org/abs/2307.01952) [[Code]](https://github.com/Stability-AI/generative-models)
  
* `ICLR2024` Matryoshka Diffusion Models [[Paper]](https://arxiv.org/abs/2310.15111)

* `ICLR2024` [Patch-DM] Patched Denoising Diffusion Models For High-Resolution Image Synthesis [[Paper]](https://arxiv.org/abs/2308.01316) [[Code]](https://github.com/mlpc-ucsd/patch-dm?tab=readme-ov-file)
  
* `Arxiv2024` FiT: Flexible Vision Transformer for Diffusion Model [[Paper]](https://arxiv.org/abs/2402.12376)[[Code]](https://github.com/whlzy/FiT)
  
* `Arxiv2024` Scalable High-Resolution Pixel-Space Image Synthesis with Hourglass Diffusion Transformers [[Paper]](https://arxiv.org/abs/2401.11605) [[Code]](https://github.com/crowsonkb/k-diffusion) [[Webpage]](https://crowsonkb.github.io/hourglass-diffusion-transformers/)


### Super Resolution Algorithm
* `Arxiv2023` [StableSR] Exploiting Diffusion Prior for Real-World Image Super-Resolution [[Paper]](https://arxiv.org/abs/2305.07015) [[Code]](https://github.com/IceClear/StableSR)
  
* `Arxiv2023` [PromptSR] Image Super-Resolution with Text Prompt Diffusion [[Paper]](https://arxiv.org/abs/2311.14282) [[Code]](https://github.com/zhengchen1999/PromptSR)
  
* `Arxiv2023` TIP: Text-Driven Image Processing with Semantic and Restoration Instructions [[Paper]](https://arxiv.org/abs/2312.11595)
  
* `CVPR2024` Scaling Up to Excellence: Practicing Model Scaling for Photo-Realistic Image Restoration In the Wild [[Paper]](https://arxiv.org/abs/2401.13627) [[Code]](https://github.com/Fanghua-Yu/SUPIR) [[Webpage]](https://supir.xpixel.group/)


## Metrics

* FID / KID (Fre ́chet Inception Distance) [[Ref]](https://en.wikipedia.org/wiki/Fréchet_inception_distance)
* IS (Inception Score) [[Ref]](https://proceedings.neurips.cc/paper/2016/file/8a3363abe792db2d8761d6403605aeb7-Paper.pdf)
* patch-FID (pFID) / patch-KID (pKID): use cropped local patches [[Ref]](https://arxiv.org/abs/2204.07156)
* sFID / sKID: use the features before the global average pooling [[Ref]](https://arxiv.org/abs/2103.03841)

