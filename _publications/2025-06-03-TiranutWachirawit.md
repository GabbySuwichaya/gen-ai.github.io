---
title: "SkyGPT Revisited"
collection: publications
category: seniorproj
permalink: /publication/2025-TiranutWachirawit
excerpt: 'This project evaluates and optimizes the SkyGPT framework, a physics-informed generative model designed for probabilistic solar forecasting.'
date: 2025-06-03
venue: 'Senior Project 499 at Chulalongkorn University by Tiranut Kanjanatunyarut and Wachirawit Piyaprapapan' 
paperurl: 'https://gabbysuwichaya.github.io/gen-ai.github.io/files/SeniorProjects/2025/499.pdf' 
slidesurl: 'http://gabbysuwichaya.github.io/gen-ai.github.io/files/SeniorProjects/2025/Slide.pdf'
---

This project evaluates and optimizes the SkyGPT framework, a physics-informed generative model designed for probabilistic solar forecasting. While initial evaluations of the baseline
model indicated suboptimal reconstruction quality, this study demonstrates that these limitations were primarily due to insufficient latent capacity and training instability rather than inherent flaws in the discrete latent modeling approach. The primary focus is the systematic optimization of the Vector-Quantized Variational Autoencoder (VQ-VAE) module. Results indicate that a larger codebook, deeper residual layers, and stabilized quantization via Exponential Moving Averages (EMA) are critical for preserving cloud boundaries and motion textures. The optimized model achieved a validation Peak Signal-to-Noise Ratio (PSNR) of 37.32 dB, significantly outperforming earlier baseline configurations. Integration into the full SkyGPT pipeline demonstrates stable temporal forecasting with a validation PSNR of 30.53 dB. Qualitative analysis reveals that while the framework can at capturing complex dynamics in partly cloudy conditions, performance limitations persist in overcast scenarios due to pixel-wise loss averaging. This work contributes a rigorous, reproducible benchmark that clarifies the architectural requirements for high-fidelity cloud-motion modeling.

Authors: 
- **Tiranut Kanjanatunyarut**
- **Wachirawit Piyaprapapan**

You can cite their work with the following bibtex

```
@techreport{suwandee2026solar,
  author      = {Tiranut Kanjanatunyarut and Wachirawit Piyaprapapan},
  title       = {SkyGPT Revisited},
  institution = {Chulalongkorn University},
  year        = {2025},
  type        = {Senior Project Report},
  note        = {Advisor: Dr. Suwichaya Suwanwimolkul}
}
```
or 

```
Kanjanatunyarut, Tiranut, and Wachirawit Piyaprapapan. SkyGPT Revisited. Advisor: Dr. Suwichaya Suwanwimolkul. Chulalongkorn University, 2025. Senior Project Report. 
```

Year: SeniorY2025

[Senior project report](https://gabbysuwichaya.github.io/gen-ai.github.io/files/SeniorProjects/2025/499.pdf)   
 
[Slide](https://gabbysuwichaya.github.io/gen-ai.github.io/files/SeniorProjects/2025/Slide.pdf)  




