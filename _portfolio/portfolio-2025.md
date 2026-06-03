---
title: "SkyGPT Revisited"
excerpt: "This project evaluates and optimizes the SkyGPT framework, a physics-informed generative model designed for probabilistic solar forecasting. [Final Report](https://drive.google.com/file/d/1CT8Mi-VFRB4X8Ct3NKapmp9PWd7xMMp_/view?usp=sharing) **authors: Tiranut Kanjanatunyarut and Wachirawit Piyaprapapan ** #SeniorY2025"
collection: portfolio
---

This project evaluates and optimizes the SkyGPT framework, a physics-informed generative model designed for probabilistic solar forecasting. While initial evaluations of the baseline
model indicated suboptimal reconstruction quality, this study demonstrates that these limitations were primarily due to insufficient latent capacity and training instability rather than inherent flaws in the discrete latent modeling approach. The primary focus is the systematic optimization of the Vector-Quantized Variational Autoencoder (VQ-VAE) module. Results indicate that a larger codebook, deeper residual layers, and stabilized quantization via Exponential Moving Averages (EMA) are critical for preserving cloud boundaries and motion textures. The optimized model achieved a validation Peak Signal-to-Noise Ratio (PSNR) of 37.32 dB, significantly outperforming earlier baseline configurations. Integration into the full SkyGPT pipeline demonstrates stable temporal forecasting with a validation PSNR of 30.53 dB. Qualitative analysis reveals that while the framework can at capturing complex dynamics in partly cloudy conditions, performance limitations persist in overcast scenarios due to pixel-wise loss averaging. This work contributes a rigorous, reproducible benchmark that clarifies the architectural requirements for high-fidelity cloud-motion modeling.



Report: [Final Report](https://drive.google.com/file/d/1os0f5Gu62VuERjk9XOgM4BMrtgLJdjlY/view?usp=sharing) 

Presentation: [Presentation](https://drive.google.com/file/d/1BGr-gwqgQyi9NgbUHcFw4nhp5xorQIei/view?usp=sharing)
  
Year: SeniorY2025

Authors: 
- **Tiranut Kanjanatunyarut**
- **Wachirawit Piyaprapapan**

