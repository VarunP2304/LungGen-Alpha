# LungGen
## Synthetic Chest X-Ray Generation via Denoising Diffusion Probabilistic Models

📄 **Zenodo Preprint (DOI):**  
https://zenodo.org/records/18454685

---

## About

**LungGen** is a diffusion-based research project that explores the generation of anatomically realistic and clinically plausible chest X-ray (CXR) images using **Denoising Diffusion Probabilistic Models (DDPMs)** with a U-Net architecture.

This GitHub repository hosts **supplementary materials** associated with the LungGen preprint, including generated samples, reference images, preprocessing examples, and a visualization of the diffusion process.

> ⚠️ This repository is intended for **research transparency and qualitative evaluation**.  
> It does **not** provide a full training or inference pipeline.

---

## Motivation

Medical imaging research faces persistent challenges such as:
- Limited access to large-scale and diverse datasets
- Privacy and regulatory constraints on patient data
- Dataset bias and underrepresentation

LungGen investigates **privacy-preserving synthetic data generation** as a potential approach to mitigate these challenges in chest X-ray analysis.

---

## Method Summary

- **Model:** Denoising Diffusion Probabilistic Model (DDPM)
- **Backbone:** U-Net
- **Training Data:** NIH Chest X-ray dataset (preprocessed)
- **Output Resolution:** 256 × 256 grayscale images
- **Generation Process:** Progressive denoising from Gaussian noise


---

## Included Artifacts

### Research Paper
- **LungGen_Research_Paper.pdf**  
  Full preprint describing the model architecture, training methodology, evaluation setup, and qualitative analysis.

### Synthetic X-Ray Samples
- **X-Ray_Generated_Sample*.png**  
  Synthetic chest X-ray images generated at **256×256 resolution** using the trained DDPM model.

### Reference and Preprocessing Examples
- **original_nih_dataset*.png**  
  Representative samples from the NIH Chest X-ray dataset.
- **preprocessed.png**  
  Example of preprocessing applied prior to model training.

### Diffusion Process Visualization
- **DDPM_256.mp4**  
  Video demonstrating the progressive denoising process, showing how image quality improves across training epochs.

---

## Evaluation Notes

The LungGen study includes:
- Quantitative image similarity metrics
- Structured qualitative evaluation by board-certified radiologists

Downstream classification or diagnostic performance evaluation is **not included** in this release.

---

## Privacy and Ethics

- No patient-identifiable information is included
- Synthetic images are generated from learned data distributions
- Original NIH dataset samples are shared only as representative examples
- All dataset usage follows original licensing and citation policies

---

## Dataset Reference

NIH Chest X-ray Dataset  
National Institutes of Health (NIH)

---

## License

This repository is released under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license.

You are free to use, share, and adapt the materials for academic and research purposes with appropriate attribution.

---

## Citation

If you use this work, please cite:
Varun P, Pratham Vinayak Raykar, Mervin Sumith Sequeira, Suhan N, & Sharathchandra N R.
LungGen: Synthetic Chest X-Ray Generation via Denoising Diffusion Probabilistic Models.
Zenodo, 2026. https://doi.org/10.5281/zenodo.18454685


---

## Authors

- Varun P  
- Pratham Vinayak Raykar  
- Mervin Sumith Sequeira  
- Suhan N  
- Sharathchandra N R  

Affiliation: Sahyadri College of Engineering & Management, Mangalore

---

## Future Work

- Higher-resolution image synthesis
- Conditional diffusion-based generation
- Expanded qualitative and clinical validation
- Public release of training code where feasible




