### ** 🎭 Mask R-CNN – Real-Time Pose Estimation & Instance Segmentation**  

## 📌 **About the Project**  
This project utilizes **Mask R-CNN** for **pose estimation** and **instance segmentation**, enabling real-time object detection and mask generation. It helps in recognizing multiple objects within a video or image while highlighting their distinct regions.  

## 🚀 **Features**  
- **Real-Time Object Segmentation** – Detect and segment multiple objects dynamically.  
- **Pose Estimation** – Identify human key points for advanced analysis.  
- **Bounding Box & Mask Generation** – Highlight objects with bounding boxes and segmentation masks.  
- **Live Video Processing** – Apply Mask R-CNN to real-time video streams.  

### **🎥 Instance Segmentation in Action**
![Instance Segmentation Output](https://github.com/user-attachments/assets/4392353a-26a3-4db2-8b45-b566f7e6adcb)

### **📌 Pose Estimation Output**
![Pose Estimation Example](https://github.com/user-attachments/assets/9302e0a5-a927-417a-8413-3937ac59c73d)

---

## 🏗 **Tech Stack**  
### 🔹 **Deep Learning Framework**  
- **TensorFlow 2.5** – Deep learning model execution.  
- **Mask R-CNN** – Object segmentation and pose estimation.  

### 🔹 **Computer Vision**  
- **OpenCV** – Real-time video processing.  
- **PixelLib** – Simplified image segmentation.  

### 🔹 **Model & Pretrained Weights**  
- **Mask R-CNN (COCO Dataset)** – Pretrained model for segmentation tasks.  

---

## 🛠 **Setup & Installation**  
1️⃣ **Clone the repository**  
```bash
git clone https://github.com/your-repo/mask-rcnn-segmentation.git
cd mask-rcnn-segmentation
```

2️⃣ **Create a virtual environment**  
```bash
conda create -n mask_rcnn python=3.8 -y
```

3️⃣ **Activate the virtual environment**  
```bash
conda activate mask_rcnn
```

4️⃣ **Install dependencies**  
```bash
pip install -r requirements.txt
```

5️⃣ **Download the Mask R-CNN model weights**  
- Download `mask_rcnn_coco.h5` from the [official repository](https://github.com/matterport/Mask_RCNN/releases) and place it in the project directory.

6️⃣ **Run the project**  
```bash
python segmentation.py
```


