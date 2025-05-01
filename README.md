# 🌌 Digital Image Processing: Astronomical Image Denoising

## 📝 Project Description
This mini-project focuses on **Image Restoration & Noise Removal** techniques specifically applied to **astronomical images**, particularly those captured by the **Hubble Space Telescope**. The goal is to simulate **salt-and-pepper noise** (common in space imaging due to cosmic rays) and restore the image quality using various denoising algorithms. The effectiveness of each technique is evaluated using standard image quality metrics: **PSNR (Peak Signal-to-Noise Ratio)** and **SSIM (Structural Similarity Index Measure)**.

---

## 🌟 Problem Statement
Astronomical images often get degraded due to sensor limitations and cosmic interference. Salt-and-pepper noise is particularly common due to high-energy particles hitting the imaging sensor. Although many public datasets are already denoised, simulating such noise and applying restoration techniques is crucial in developing resilient algorithms for deep-space research.

---

## 🚀 Real-World Relevance
- ✨ Enhances clarity in deep-space imaging used by astrophysicists.
- 🔬 Preserves scientific fidelity in astronomical observations.
- 🚀 Improves automated analysis of celestial phenomena by reducing artifacts.

---

## 🪨 Dataset Used
Images are sourced from the [ESA/Hubble Space Telescope Archive](https://esahubble.org/images/), which provides high-quality views of galaxies, nebulae, and other celestial bodies. We manually introduce **salt-and-pepper noise** to simulate raw unprocessed captures from deep space.

---

## 🔧 Technologies Used
- **Python 3.x**
- **OpenCV** – Image processing and denoising filters
- **NumPy** – Array operations
- **Matplotlib** – Visualization
- **scikit-image** – For SSIM and PSNR metrics

---

## 🔢 Techniques Implemented

### ✅ Median Filter
- Best for removing impulsive salt-and-pepper noise.

### ✅ Non-Local Means (NLM)
- Uses neighborhood similarity to preserve edges while denoising.

### ✅ Wavelet Denoising
- Works in frequency domain for multi-resolution noise suppression.

### ✅ Bilateral Filter
- Smoothens while preserving edges.

### ✅ Hybrid Techniques
- Combination of Median + NLM, and Bilateral + Wavelet yielded the best results.

### ❌ Wiener Filter
- Statistical filter with low performance for this noise type.

---

## 📊 Performance Evaluation

### 🔹 Image: h1
| Method               | PSNR       | SSIM     |
|----------------------|------------|----------|
| Median + NLM         | **31.29**  | **0.761** |
| Median Filter        | 28.66      | 0.582    |
| Wavelet Filter       | 26.65      | 0.520    |
| Bilateral + Wavelet  | 26.16      | 0.558    |
| Bilateral Filter     | 25.61      | 0.521    |
| Non-Local Means      | 21.96      | 0.350    |
| Wiener Filter        | 18.10      | 0.137    |

### 🔹 Image: h2
| Method               | PSNR       | SSIM     |
|----------------------|------------|----------|
| Median + NLM         | **31.29**  | **0.850** |
| Median Filter        | 28.78      | 0.591    |
| Wavelet Filter       | 26.48      | 0.519    |
| Bilateral + Wavelet  | 26.03      | 0.552    |
| Bilateral Filter     | 25.55      | 0.510    |
| Non-Local Means      | 21.22      | 0.256    |
| Wiener Filter        | 18.15      | 0.134    |

---

## 📂 Project Structure
```
Astronomical-Image-Denoising/
│── images/                  # Input noisy and restored Hubble images
│── Noise_Removal.ipynb      # Main implementation
│── README.md                # Documentation
```

---

## 🔄 How to Run
```bash
git clone https://github.com/your-username/Astronomical-Image-Denoising.git
cd Astronomical-Image-Denoising
jupyter notebook Noise_Removal.ipynb
```

---

## 👨‍💼 Team Members
- 👤 Jeswin Lobo (22J23)  
  📧 Email: 22j23.jeswin@sjec.ac.in  
  👤 GitHub: [Jeswin2003lobo](https://github.com/Jeswin2003lobo)

- 👤 Shashank Rao U (22J46)  
  📧 Email: 22j46.shashank@sjec.ac.in  
  👤 GitHub: [Shashankraou](https://github.com/Shashankraou)

---

## 📝 License
This project is licensed under the **MIT License**.

---

## 📅 Submission Note
- This mini-project submission is as per **Digital Image Processing Assignment Category 2**.
- Evaluation Metrics: Real-World Problem Mapping, Input Relevance, PSNR/SSIM Metrics, Code Quality, README, and Timely Submission.
- We encourage interviewers and recruiters to explore this project for its relevance to **AI in Imaging and Space Data Analysis**.

---

> ✨ **"Don't just treat this as another assignment — treat it as a project you'd proudly showcase in interviews."**


