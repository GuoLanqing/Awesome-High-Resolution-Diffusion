# Awesome Diffusion Models in High-Resolution Synthesis [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
Collection of recent diffusion-based high-resolution (e.g., $>1024^2$) image and video synthesis works. Questions and discussions are most welcome! Upcoming works will be updated on a regular basis, feel free to contact me to add... :thumbsup:

## Papers and Codes

### Tuning-Free Algorithm

* `NeurIPS 2023` Training-free Diffusion Model Adaptation for Variable-Sized Text-to-Image Synthesis [[Paper]](https://arxiv.org/abs/2306.08645)

* `ICML2023` MultiDiffusion: Fusing Diffusion Paths for Controlled Image Generation [[Paper]](https://arxiv.org/abs/2302.08113) [[Code]](https://github.com/omerbt/MultiDiffusion)

* `ICLR2024` ScaleCrafter: Tuning-Free Higher-Resolution Visual Generation with Diffusion Models [[Paper]](https://arxiv.org/pdf/2310.07702.pdf) [[Code]](https://yingqinghe.github.io/scalecrafter/)
  
* `Arxiv2023` HiDiffusion: Unlocking High-Resolution Creativity and Efficiency in Low-Resolution Trained Diffusion Models [[Paper]](https://arxiv.org/abs/2311.17528)

* `Arxiv2023` DemoFusion: Democratising High-Resolution Image Generation With No $$$ [[Paper]](https://arxiv.org/abs/2311.16973) [[Code]](https://github.com/PRIS-CV/DemoFusion) [[Webpage]](https://ruoyidu.github.io/demofusion/demofusion.html)

* `CVPR2024 Oral` FreeU: Free Lunch in Diffusion U-Net [[Paper]](https://arxiv.org/abs/2309.11497) [[Code]](https://github.com/ChenyangSi/FreeU) [[Webpage]](https://chenyangsi.top/FreeU/)
  
* `Arxiv2024` FouriScale: A Frequency Perspective on Training-Free High-Resolution Image Synthesis [[Paper]](https://arxiv.org/abs/2403.12963) [[Code]](https://github.com/LeonHLJ/FouriScale)

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

* `ICLR2024` SDXL: Improving Latent Diffusion Models for High-Resolution Image Synthesis [[Paper]](https://arxiv.org/abs/2307.01952)[[Code]](https://github.com/Stability-AI/generative-models)
  
* `ICLR2024` Matryoshka Diffusion Models [[Paper]](https://arxiv.org/abs/2310.15111)

* `ICLR2024` [Patch-DM] Patched Denoising Diffusion Models For High-Resolution Image Synthesis [[Paper]](https://arxiv.org/abs/2308.01316)[[Code]](https://github.com/mlpc-ucsd/patch-dm?tab=readme-ov-file)
  
* `Arxiv2024` FiT: Flexible Vision Transformer for Diffusion Model [[Paper]](https://arxiv.org/abs/2402.12376)[[Code]](https://github.com/whlzy/FiT)
  
* `Arxiv2024` Scalable High-Resolution Pixel-Space Image Synthesis with Hourglass Diffusion Transformers [[Paper]](https://arxiv.org/abs/2401.11605)[[Code]](https://github.com/crowsonkb/k-diffusion) [[Webpage]](https://crowsonkb.github.io/hourglass-diffusion-transformers/)


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

