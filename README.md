# Computer Vision Assignments

This repository contains a collection of **computer vision projects** ranging from **classical image processing** techniques to **state-of-the-art deep learning and transformer-based models**. Each assignment emphasizes both theoretical understanding and practical implementation.

---

## 📁 Assignments

### 🚗 Assignment 1: Lane Boundary Detection
**Objective:**  
Detect lane boundaries in ground-level road images using classical computer vision techniques.

**Techniques Used:**
- Gaussian blurring and adaptive thresholding  
- Canny edge detection  
- Region masking  
- Hough Line Transform  

**Key Highlights:**
- Performed **heatmap-based hyperparameter tuning** for edge detection  
- Implemented **image segregation logic** to dynamically select edge detection strategies  
- Designed the pipeline to handle varying lighting and road conditions  

---

### 🧬 Assignment 2: PatchCamelyon Image Classification
**Objective:**  
Classify tumor vs. non-tumor tissue images from the **PatchCamelyon dataset**.

**Models & Methods:**
- Fine-tuned pretrained **ResNet** and **VGG** architectures  
- Conducted extensive **ablation studies** on:
  - Data augmentation techniques  
  - Optimizers and learning rate schedulers  
  - Loss functions  
  - Number of trainable layers  
  - Input image resolutions  
- Developed a **custom PyTorch CNN** combining:
  - Inception blocks  
  - Residual connections  

**Results:**
- Achieved **91% accuracy** on the test dataset  

---

### 🌫️ Assignment 3: Object Detection on Foggy Cityscapes
**Objective:**  
Evaluate and improve object detection performance under adverse weather conditions using the **Foggy Cityscapes dataset**.

**Models Used:**
- **Deformable DETR**  
- **Grounding DINO** (via Hugging Face Transformers)

**Evaluation Strategy:**
- **Qualitative analysis:** Visual overlays of predicted vs. ground-truth bounding boxes  
- **Quantitative analysis:**
  - Mean Average Precision (mAP)  
  - Class-wise Average Precision  
  - Performance under varying IoU and confidence thresholds (using `pycocotools`)  

**Advanced Experiments:**
- Fine-tuned **Deformable DETR** to improve mAP  
- Explored **soft prompt tuning** to enhance Grounding DINO’s detection and generalization  

---

## 🛠️ Tools & Technologies
- Python  
- OpenCV  
- PyTorch  
- Hugging Face Transformers  
- NumPy, Matplotlib  
- pycocotools  

---

## 📌 Summary
These projects demonstrate a progression from **traditional image processing pipelines** to **modern transformer-based computer vision models**, emphasizing:
- Robust CV system design  
- Model evaluation and ablation studies  
- Practical application of state-of-the-art frameworks  

---

## 📫 Contact
If you have any questions or would like to collaborate, feel free to reach out!
