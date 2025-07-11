<div id = "top"></div>

<div align="center">

[![](https://capsule-render.vercel.app/api?type=waving&height=200&color=0:F193b0,100:F050C0&text=Deep%20Learning%20for%20Virtual%20Staining%20of%20Label-Free%20Tissue:%20A%20Survey&fontSize=25&fontAlignY=40&fontColor=FFFFFF)
](#top)

</div>

<div align="center">
  

[![](https://img.shields.io/github/stars/diaoquesang/DL4VS)](https://github.com/diaoquesang/DL4VS)
[![](https://img.shields.io/github/forks/diaoquesang/DL4VS)](https://github.com/diaoquesang/DL4VS)
[![](https://img.shields.io/github/issues/diaoquesang/DL4VS)](https://github.com/diaoquesang/DL4VS/issues)
[![](https://img.shields.io/github/license/diaoquesang/DL4VS)](https://github.com/diaoquesang/DL4VS/blob/main/LICENSE) 
[![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fdiaoquesang%2FDL4VS&label=visitors&countColor=%239797fa&style=flat&labelStyle=none)](https://visitorbadge.io/status?path=https%3A%2F%2Fgithub.com%2Fdiaoquesang%2FDL4VS)

</div>

**🦉 Contributors: [Yifei Sun (22' HDU-ITMO Undergraduate)](https://diaoquesang.github.io/), [Jincheng Li (23' NTU Undergraduate)](https://github.com/li00000011).**

**🎓 DeepWiki: [Generating GitHub Knowledge Base Documentation in One Click](https://deepwiki.com/diaoquesang/DL4VS).**

**📦 Other resources: [1] [Paper List for Medical Anomaly Detection](https://github.com/diaoquesang/Paper-List-for-Medical-Anomaly-Detection), [2] [Bone Suppression in Chest X-Rays: A Deep Survey](https://github.com/diaoquesang/A-detailed-summarization-about-bone-suppression-in-Chest-X-rays), [3] [Paper List for Prototypical Learning](https://github.com/BeistMedAI/Paper-List-for-Prototypical-Learning), [4] [Paper List for Cell Detection](https://github.com/li00000011/Paper-List-for-Cell-Detection), [5] [Medical-AI-Guide](https://github.com/diaoquesang/Medical-AI-Guide/), [6] [Paper List for Medical Reasoning Large Language Models](https://github.com/HovChen/Paper-List-for-Medical-Reasoning-Large-Language-Models).**

### Welcome to join us by contacting: szhsxhsyf@hdu.edu.cn.

<div>
<img src="https://github.com/diaoquesang/Paper-List-for-Medical-Anomaly-Detection/blob/main/logos/HDU.png" height="45px" href="https://www.hdu.edu.cn/">
<img src="https://github.com/diaoquesang/Paper-List-for-Medical-Anomaly-Detection/blob/main/logos/ITMO.jpg" height="45px" href="https://en.itmo.ru/">
<img src="https://github.com/diaoquesang/Paper-List-for-Medical-Anomaly-Detection/blob/main/logos/NTU.jpg" height="45px" href="https://www.ntu.edu.cn/">
</div>


## 📇 Contents
- [**1. Background**](#s1)
- [**2. Related Work**](#s2)
- [**3. Datasets**](#s3)
- [**4. Metrics**](#s4)

## 🧑🏻‍🏫 1. Background <div id = "s1"></div>



Traditional histological staining (e.g., H&E, immunofluorescence) is essential for visualizing tissue structures in pathology but involves complex chemical processes, time-consuming protocols, and labor-intensive workflows. Label-free imaging techniques (e.g., autofluorescence, quantitative phase imaging, Raman microscopy) capture intrinsic optical properties of tissues without exogenous labels, preserving samples and accelerating imaging. However, these methods often lack the diagnostic contrast provided by stains.  

<div align="center">

<img src="https://github.com/user-attachments/assets/590e24eb-da4c-4043-a850-d2b530b1f711" width="90%">

</div>

**Virtual staining** leverages Deep Learning (DL) to computationally transform label-free tissue images into virtually stained counterparts that resemble chemically stained images. This approach:  
- **Eliminates physical staining**, reducing costs, preparation time, and chemical waste.  
- **Enables retrospective analysis** of archived label-free data.  
- **Facilitates multi-stain synthesis** from a single scan.  
- **Preserves tissue integrity** for downstream molecular analysis.  

Recent advances in DL models (e.g., GANs, U-Nets, diffusion models) have demonstrated remarkable accuracy in predicting stain-specific features directly from label-free inputs, paving the way for scalable, stain-free computational pathology.  

<div align="center">

<img src="https://github.com/user-attachments/assets/c92be265-33c6-48f7-9283-44a98afa173c" width="90%">

</div>

## ✍🏻 2. Related Work <div id = "s2"></div>

<div align="center">

|Source|Year|Title|Graph|Code|
|-|-|-|-|-|
|Nature Communications|2025|[Pixel Super-Resolved Virtual Staining of Label-Free Tissue Using Diffusion Models](https://www.nature.com/articles/s41467-025-60387-z)|![image](https://github.com/user-attachments/assets/e44d8ace-6b73-4e3d-baf6-917b86c89fd2)|[:octocat:](https://github.com/Yijie-Zhang/Super-resolved-virtual-staining)|
|Nature Communications|2024|[Virtual Histological Staining of Unlabeled Autopsy Tissue](https://www.nature.com/articles/s41467-024-46077-2)|![image](https://github.com/user-attachments/assets/e54e0668-0ee1-4d37-890d-12bf7e409bf4)|[:octocat:](https://github.com/liyuzhu1998/Autopsy-Virtual-Staining/)|
|Trends in Biotechnology|2024|[Virtual Staining for Histology by Deep Learning](https://www.cell.com/trends/biotechnology/fulltext/S0167-7799(24)00038-6)|![image](https://github.com/user-attachments/assets/ca664665-d15c-4a98-969c-cd20461aea9c)||
|Modern Pathology|2024|[Virtual Staining of Nonfixed Tissue Histology](https://www.sciencedirect.com/science/article/pii/S0893395224000243)|![image](https://github.com/user-attachments/assets/afa8c104-d90d-4dfd-b33e-6b3993e4f91f)||
|Light-Science & Applications|2023|[Deep Learning-Enabled Virtual Histological Staining of Biological Samples](https://www.nature.com/articles/s41377-023-01104-7)|![image](https://github.com/user-attachments/assets/e3fdf413-c8a9-4eda-8e90-a87e47158b26)||
|Nature Biomedical Engineering|2019|[Virtual Histological Staining of Unlabelled Tissue-Autofluorescence Images via Deep Learning](https://www.nature.com/articles/s41551-019-0362-y)|![image](https://github.com/user-attachments/assets/8c9d3ae5-d504-4114-8af8-0bf79e16ec4e)||

</div>

	

## 🔢 3. Datasets <div id = "s3"></div>

## 💯 4. Metrics <div id = "s4"></div>

<div align="center">

|Metric|Full Name|Formula|Purpose|
|-|-|-|-|
|MAE|Mean Absolute Error|$$\frac{1}{n}\sum_{i=1}^{n}\|y_i - \hat{y}_i\|$$|Low-Level Fidelity|
|MSE|Mean Squared Error|$$\frac{1}{n}\sum_{i=1}^{n}(y_i - \hat{y}_i)^2$$|Low-Level Fidelity|
|PSNR|Peak Signal-to-Noise Ratio|$$20 \cdot \log_{10}\left(\frac{\text{MAX}_I}{\sqrt{\text{MSE}}}\right)$$|Low-Level Fidelity|
|SSIM|Structural Similarity Index Measure|$$\frac{(2\mu_y\mu_{\hat{y}} + C_1)(2\sigma_{y\hat{y}} + C_2)}{(\mu_y^2 + \mu_{\hat{y}}^2 + C_1)(\sigma_y^2 + \sigma_{\hat{y}}^2 + C_2)}$$|Structural Integrity|
|MS-SSIM|Multi-Scale SSIM|  ![MS-SSIM Formula](https://latex.codecogs.com/svg.image?\prod_{j=1}^{M}\left&space;[&space;\frac{2\mu_{y_j}\mu_{\hat{y}_j}&space;&plus;&space;C_1}{\mu_{y_j}^2&space;&plus;&space;\mu_{\hat{y}_j}^2&space;&plus;&space;C_1}&space;\right]^{\alpha_j}\cdot&space;\left[&space;\frac{2\sigma_{y_j\hat{y}_j}&plus;C_2}{\sigma_{y_j}^2&space;&plus;&space;\sigma_{\hat{y}_j}^2&space;&plus;&space;C_2}&space;\right]^{\beta_j})|Structural Integrity|
|FID|Fréchet Inception Distance|$$\|\mu_r - \mu_g\|^2 + \text{Tr}(\Sigma_r + \Sigma_g - 2\sqrt{\Sigma_r\Sigma_g})$$|Perceptual Realism|
|IS|Inception Score|$$\exp\left(\mathbb{E}_{\hat{y}} \text{KL}(p(y\|\hat{y}) \| p(y))\right)$$|Perceptual Realism|
|LPIPS|Learned Perceptual Image Patch Similarity|![LPIPS Formula](https://latex.codecogs.com/png.image?\dpi{200}\sum_{l}%20\frac{1}{H_lW_l}\sum_{h,w}%20\|w_l%20\odot%20(\phi_l(y)_{hw}%20-%20\phi_l(\hat{y})_{hw})\|^2_2)|Perceptual Realism|

</div>

## 💞 Citation

```
@misc{sun2025,
  author = {Sun, Yifei and Li, Jincheng},
  title = {Deep Learning for Virtual Staining of Label-Free Tissue: A Survey},
  year = {2025},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{https://github.com/diaoquesang/DL4VS}}
}
```

## 🥰 Star History
[![Star History Chart](https://api.star-history.com/svg?repos=diaoquesang/DL4VS&type=Date)](https://star-history.com/#diaoquesang/DL4VS&Date)

[![](https://capsule-render.vercel.app/api?type=waving&height=200&color=0:F193b0,100:F050C0&text=Back%20to%20Top&section=footer&fontSize=30&fontAlignY=65&fontColor=FFFFFF)
](#top)
