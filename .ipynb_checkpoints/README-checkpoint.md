# 🌌 Digital Image Processing: Astronomical Image Denoising

## 📋 Project Description

This mini-project focuses on **Image Restoration & Noise Removal** techniques specifically applied to **astronomical images**, particularly those captured by the **Hubble Space Telescope**. The goal is to simulate **salt-and-pepper noise** (common in space imaging due to cosmic rays) and restore the image quality using various denoising algorithms. The effectiveness of each technique is evaluated using standard image quality metrics: **PSNR (Peak Signal-to-Noise Ratio)** and **SSIM (Structural Similarity Index Measure)**.

---

## 🌟 Problem Statement

Astronomical images often get degraded due to sensor limitations and cosmic interference. Salt-and-pepper noise is particularly common due to high-energy particles hitting the imaging sensor. Although many public datasets are already denoised, simulating such noise and applying restoration techniques is crucial in developing resilient algorithms for deep-space research.

---

## 🚀 Real-World Relevance

* ✨ Enhances clarity in deep-space imaging used by astrophysicists.
* 🔬 Preserves scientific fidelity in astronomical observations.
* 🚀 Improves automated analysis of celestial phenomena by reducing artifacts.

---

## 🪨 Dataset Used

Images are sourced from the [ESA/Hubble Space Telescope Archive](https://esahubble.org/images/), which provides high-quality views of galaxies, nebulae, and other celestial bodies. We manually introduce **salt-and-pepper noise** to simulate raw unprocessed captures from deep space.

---

## 🔧 Technologies Used

* **Python 3.x**
* **OpenCV** – Image processing and denoising filters
* **NumPy** – Array operations
* **Matplotlib** – Visualization
* **scikit-image** – For SSIM and PSNR metrics

---

## 🔢 Techniques Implemented

* Median Filter
* Non-Local Means (NLM)
* Wavelet Denoising
* Bilateral Filter
* Hybrid Filters: Median + NLM, Bilateral + Wavelet

---
## 📷 Output Preview

### Original and Noisy Images
Below are the original and noisy images for H1 and H2:

- **H1 Original**:
  ![H1 Original](results/H-1 (Potential future star-forming regions)_denoised_grid.png)

- **H1 Noisy**:
  ![H1 Noisy](results/H-1\ \(Potential\ future\ star-forming\ regions\)_noisy.png)

- **H2 Original**:
  ![H2 Original](results/H-2\ \(Active\ star\ formation\)_original.png)

- **H2 Noisy**:
  ![H2 Noisy](results/H-2\ \(Active\ star\ formation\)_noisy.png)

### Denoised Images (Grid)
Below is a grid showing the results of various denoising methods applied to the noisy images:

- **H1 Denoised Images**:
  ![H1 Denoised](results/H-1\ \(Potential\ future\ star-forming\ regions\)_denoised_grid.png)

- **H2 Denoised Images**:
  ![H2 Denoised](results/H-2\ \(Active\ star\ formation\)_denoised_grid.png)
## Evaluation Results
Here are the evaluation results for the denoising methods (PSNR and SSIM):
## 📊 Performance Evaluation (H1)

| Method              | PSNR      | SSIM      |
| ------------------- | --------- | --------- |
| Median + NLM        | **31.31** | **0.760** |
| Median Filter       | 28.67     | 0.582     |
| Wavelet Filter      | 26.60     | 0.517     |
| Bilateral + Wavelet | 26.16     | 0.556     |
| Bilateral Filter    | 25.60     | 0.519     |
| Non-Local Means     | 21.94     | 0.344     |

## 📊 Performance Evaluation (H2)

| Method              | PSNR      | SSIM      |
| ------------------- | --------- | --------- |
| Median + NLM        | **31.28** | **0.848** |
| Median Filter       | 28.76     | 0.589     |
| Wavelet Filter      | 26.31     | 0.509     |
| Bilateral + Wavelet | 25.91     | 0.546     |
| Bilateral Filter    | 25.44     | 0.506     |
| Non-Local Means     | 21.16     | 0.254     |

---

## 📂 Project Structure

---
Astronomical-Image-Denoising/
├── images/                     # Original images
│   ├── H-1 (Potential future star-forming regions).jpg
│   ├── H-2 (Active star formation).jpg
├── results/                    # Processed images and output
│   ├── H-1_original.png
│   ├── H-1_noisy.png
│   ├── H-1_denoised_grid.png
│   ├── H-1_evaluation.csv
│   ├── H-2_original.png
│   ├── H-2_noisy.png
│   ├── H-2_denoised_grid.png
│   ├── H-2_evaluation.csv
├── Noise_Removal.ipynb         # Main code
└── README.md                   # Documentation (to be updated with links to the results)

---

## 🔄 How to Run

```bash
git clone https://github.com/your-username/Astronomical-Image-Denoising.git
cd Astronomical-Image-Denoising
jupyter notebook Noise_Removal.ipynb
```

## 👨‍💼 Team Members

* 👤 Jeswin Lobo (4SO22CD023)
  📧 Email: [22j23.jeswin@sjec.ac.in](mailto:22j23.jeswin@sjec.ac.in)
  👤 GitHub: [Jeswin2003lobo](https://github.com/Jeswin2003lobo)

* 👤 Shashank Rao U (4SO22CD046)
  📧 Email: [22j46.shashank@sjec.ac.in](mailto:22j46.shashank@sjec.ac.in)
  👤 GitHub: [Shashankraou](https://github.com/Shashankraou)

---

## 📝 License

This project is licensed under the **MIT License**.


