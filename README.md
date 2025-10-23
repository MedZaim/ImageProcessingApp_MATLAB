# 🖼️ ImageProcessingApp – MATLAB Image Processing Application

### 📚 Project Overview
**ImageProcessingApp** is a MATLAB-based application developed using **App Designer** that provides an interactive graphical interface for performing various **image processing and analysis** operations.  
It was created as part of the *“Traitement d’Images”* course at **Université Sidi Mohamed Ben Abdellah – Fès**, under the supervision of **Pr. Hamid Tairi**, by **Mohamed Zaim** (Master MLAIM 2024/2025).

---

### 🎯 Objectives
- Build an **interactive MATLAB GUI** for experimenting with image processing techniques.  
- Implement core **spatial**, **frequency**, and **morphological** filters.  
- Allow real-time **visualization and comparison** of results.  
- Strengthen understanding of **image enhancement, filtering, and feature detection**.

---

### ⚙️ Features

#### 🧩 1. Spatial Transformations
- Grayscale conversion  
- Image inversion  
- Contrast shifting  
- Binarization (thresholding)  
- Image division and arithmetic operations  
- Histogram equalization  

#### 🎨 2. Spatial Filters
- Mean filters (3×3, 5×5)  
- Gaussian filters (3×3, 5×5)  
- Conic and pyramidal filters  
- Median filtering  

#### 🌐 3. Frequency Domain Filters
- Ideal Low-Pass & High-Pass filters  
- Butterworth Low-Pass & High-Pass filters  

#### ✏️ 4. Edge Detection
- Gradient, Sobel, Prewitt, Roberts, Laplacian operators  

#### 🧭 5. Corner Detection
- Harris detector  
- Susan method  
- Electrostatic model  

#### ⚙️ 6. Mathematical Morphology
- Erosion  
- Dilation  
- Opening  
- Closing  
- Custom structuring elements (4/8-connectivity, lines, etc.)

#### 💥 7. Noise Addition
- Gaussian noise  
- Salt & pepper noise  

#### 🧰 8. Utility Options
- Load / Save / Reset image  
- Dual display (original & processed image)  
- Histogram visualization  

---

### 🧑‍💻 Technologies Used
- **MATLAB R2023b+**
- **App Designer**
- **Image Processing Toolbox**

---

### 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/ImageProcessingApp_matlab.git
   ```
2. Open MATLAB.
3. Launch `app1.mlapp` or load the provided `.m` file (`code_app.txt`) in App Designer.
4. Click **Run** ▶️ to start the graphical application.
5. Load an image and explore available filters and operations!

---

### 📸 Example Interface
*(Include a screenshot of the app’s main window here)*  
`![App Interface](screenshot.png)`

---

### 🧪 Sample Operations
| Operation | Description |
|------------|-------------|
| **Gaussian 5×5 Filter** | Smooths image and reduces noise. |
| **Sobel Edge Detection** | Highlights object contours. |
| **Harris Corners** | Detects feature points in complex images. |
| **Morphological Opening** | Removes small objects from binary images. |

---

### 🧾 Author & Supervision
- 👨‍💻 **Developed by:** *Mohamed Zaim*  
- 🎓 **Master:** Machine Learning et Intelligence Multimédia (MLAIM)  
- 🧑‍🏫 **Supervised by:** *Pr. Hamid Tairi*  
- 🏫 **University:** Université Sidi Mohamed Ben Abdellah – Fès, Faculté des Sciences Dhar El Mahraz  
- 📅 **Academic Year:** 2024 / 2025  

---

### 📜 License
This project is released under the **MIT License**.  
Feel free to use, modify, and distribute with attribution.
