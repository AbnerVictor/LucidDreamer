# LucidDreamer: Towards High-Fidelity Text-to-3D Generation via Interval Score Matching

[Yixun Liang](https://yixunliang.github.io/)$^{\color{red}{\*}}$ [Xin Yang](https://abnervictor.github.io/2023/06/12/Academic-Self-Intro.html)$^{\color{red}{\*}}$, Jiantao Lin, Haodong Li, [Xiaogang Xu](https://xiaogang00.github.io), [Yingcong Chen](https://www.yingcong.me)$^{\**}$

$\color{red}{\*}$: Equal contribution.
\**: Corresponding author.

[Project Page (Coming Soon)]() | [Paper PDF](https://github.com/EnVision-Research/LucidDreamer/blob/main/resources/supplementFiles/LucidDreamer.pdf)

---

<div align=center>
<img src="resources/teaser.jpg" width="95%"/>  
  
Examples of text-to-3D content creations with our framework.
</div>

## 🎏 Abstract

We present a text-to-3D generation framework, named the *LucidDreamer*, to distill high-fidelity textures and shapes from pretrained 2D diffusion models.

<details><summary>CLICK for the full abstract</summary>

> The recent advancements in text-to-3D generation mark a significant milestone in generative models, unlocking new possibilities for creating imaginative 3D assets across various real-world scenarios. While recent advancements in text-to-3D generation have shown promise, they often fall short in rendering detailed and high-quality 3D models. This problem is especially prevalent as many methods base themselves on Score Distillation Sampling (SDS). This paper identifies a notable deficiency in SDS, that it brings inconsistent and low-quality updating direction for the 3D model, causing the over-smoothing effect. To address this, we propose a novel approach called Interval Score Matching (ISM). ISM employs deterministic diffusing trajectories and utilizes interval-based score matching to counteract over-smoothing. Furthermore, we incorporate 3D Gaussian Splatting into our text-to-3D generation pipeline. Extensive experiments show that our model largely outperforms the state-of-the-art in quality and training efficiency.

</details>

## 🚧 Todo

- [ ] Release the training codes
- [ ] Release the guidance documents

Coming soon!

## 📍 Citation 
