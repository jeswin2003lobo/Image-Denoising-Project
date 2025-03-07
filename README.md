# 📌 Digital Image Processing: Noise Removal Project

## 📝 Project Description
This project focuses on **Image Restoration & Noise Removal** using various filtering techniques in **Digital Image Processing (DIP)**. The goal is to take a noisy image as input, apply different noise removal techniques, and evaluate the quality of the restored image using performance metrics like **PSNR (Peak Signal-to-Noise Ratio) and SSIM (Structural Similarity Index Measure).**

---

## 🎯 Objectives
✔ **Remove noise** from images using different denoising techniques.  
✔ **Compare performance** of Median Blur, Gaussian Blur, and Non-Local Means Denoising.  
✔ **Measure the quality** of noise removal using PSNR and SSIM.  

---

## 🛠️ Technologies Used
- **Python**  
- **OpenCV** (for image processing)  
- **Matplotlib** (for visualization)  
- **NumPy** (for matrix operations)  
- **scikit-image** (for performance metrics)  

---

## 🔧 Installation & Setup
1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/Image-Denoising-Project.git
   cd Image-Denoising-Project
   ```

2. **Install Required Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Jupyter Notebook**
   ```bash
   jupyter notebook Noise_Removal.ipynb
   ```

---

## 📸 Noise Removal Techniques Used
### 1️⃣ **Median Blur**
- Removes **salt-and-pepper noise** by replacing pixel values with the median of surrounding pixels.

### 2️⃣ **Gaussian Blur**
- Applies a Gaussian filter to smooth the image and reduce noise.

### 3️⃣ **Non-Local Means Denoising**
- Uses a more advanced noise removal approach to preserve image details.

---

## 📊 Performance Evaluation
The quality of noise removal is measured using **PSNR (Peak Signal-to-Noise Ratio)** and **SSIM (Structural Similarity Index Measure).**

| Technique | PSNR  | SSIM  |
|-----------|-------|-------|
| **Median Blur** | 18.34 | 0.3922 |
| **Gaussian Blur** | 20.48 | 0.6656 |
| **Non-Local Means Denoising** | 19.73 | 0.4681 |

Higher PSNR and SSIM values indicate better quality restoration.

---

## 📂 Project Structure
```
Image-Denoising-Project/
│── images/                # Sample input and output images
│── Noise_Removal.ipynb    # Jupyter Notebook with implementation
│── requirements.txt       # List of dependencies
│── README.md              # Project documentation
```

---

## 🚀 How to Contribute
1. Fork the repository.
2. Create a new branch: `git checkout -b feature-branch`
3. Commit changes: `git commit -m 'Added a new feature'`
4. Push to the branch: `git push origin feature-branch`
5. Submit a pull request.

---

## 📌 Authors
👤 **Jeswin Lobo**  
📧 Contact: [22j23.jeswin@sjec.ac.in](mailto:22j23.jeswin@sjec.ac.in)  
🔗 GitHub: [Jeswin2003lobo](https://github.com/Jeswin2003lobo) 

## 👤 **Shashank Rao U**  
📧 Contact: [22j46.shashank@sjec.ac.in](mailto:22j46.shashank@sjec.ac.in)  
🔗 GitHub: [Shashankraou](https://github.com/Shashankraou) 
---

## 📜 License
This project is licensed under the **MIT License**.
