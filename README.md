# AIML Development Position – Project Portfolio

Welcome to the repository containing project implementations for the AIML Development Position Test by **Palak Jagtap**. This includes a collection of AI/ML-driven tools and models across automation, video editing, deep learning, and computer vision.

## 📁 Repository Contents

### ✅ Task 1: Code Automation Tools
1. **Text to 3D Model**  
   - Generates a simple 3D house from text using `trimesh` and `numpy`.  
   - Output: `house.obj` (can be imported into SketchUp/Blender).

2. **Text to Animation**  
   - Creates a sine wave animation using `matplotlib`.  
   - Output: `sine_wave.gif`.

3. **Text to Editable Infographics**  
   - Generates an interactive bar chart from text-based data using `plotly`.  
   - Output: `infographic.html`.

---

### 🎬 Task 2: Video Editing via Text Commands
A video processing pipeline using:
- **ffmpeg** (video trimming, subtitles),
- **OpenCV** (frame extraction),
- **MiDaS** model (depth estimation via `torch`, `torchvision`).

Features:
- Trim video segments.
- Add subtitles.
- Extract frames.
- Generate depth maps per frame.

---

### 🧠 Task 3: Model Fine-Tuning

#### A. LLM-Based fine tuning on  Medical QA System
- Originally intended for LLaMA 70B, downsized due to computational constraints.
- Focused on:
  - QA dataset curation.
  - Lighter transformer fine-tuning.
  - Partial performance improvement observed.

#### B. Indian Food Recognition (GoogLeNet Fine-Tuning)
- Dataset: Subset of **80 Indian Cuisines** from Kaggle.
- Classes: Butter Chicken, Chapati, Daal Baati Churma, Kachori, Palak Paneer, Ras Malai, Shrikhand.
- Binary classifier to detect Indian dishes.
- Model: GoogLeNet (Inception v1), pretrained on ImageNet.
- Output models:  
  - `fine_tuned_indian_food_model.pth` (5 epochs)  
  - `fine_tuned_indian_food_model02.pth` (30 epochs)

**Planned Future Improvements**:
- Add unknown class (non-Indian dishes)
- Multi-class support
- Evaluation metrics (accuracy, precision, etc.)
- Augmentations and ResNet/EfficientNet trials

---

### 🌊 Task c : MiDaS for Depth Estimation
- Fine-tuned MiDaS Large model using NYU Depth V2 dataset.
- Depth maps generated with moderate quality.
- Limitations due to resource constraints and model complexity.

---

## 🚀 Getting Started

To run or explore the Jupyter notebooks in this repository:

> **🟢 Click the button below to open in Google Colab (Recommended):**  
> [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/)

Or:
1. Upload `.ipynb` files directly to [Google Colab](https://colab.research.google.com/).
2. Use GPU runtime (`Runtime > Change runtime type > GPU`).
3. Install required libraries via `!pip install`.

---

## 📧 Contact

**Palak Jagtap**  
📧 palak_j@bt.iitr.ac.in  
🔗 [GitHub: PAlakj02/stick-dot](https://github.com/PAlakj02/stick-dot)

---

## 📝 License

This repository is for demonstration and evaluation purposes only.

