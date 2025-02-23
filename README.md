# AI-Based Crowd Detection & Management System  

## 📌 Overview  
This project is an **AI-powered crowd detection and management system** using **YOLOv8, Random Forest, and LSTM**. It predicts **crowd density**, sends **alerts for congestion**, and helps in **staff deployment** for better crowd control.  

---

## 🔥 Features  
✅ **Real-time crowd detection** using **YOLOv8**  
✅ **Heatmap generation** for crowd density visualization  
✅ **Future crowd prediction** using **Random Forest**  
✅ **Automated congestion alerts** when people count exceeds a threshold  
✅ **Staff deployment recommendations** based on predicted crowd trends  
✅ **Preprocessing (Denoising, FPS reduction) for faster processing**  

---

## 🛠️ Tech Stack  
- **Deep Learning:** YOLOv8 (Ultralytics)  
- **Machine Learning:** Random Forest
- **Data Processing:** Pandas, NumPy  
- **Visualization:** Matplotlib, OpenCV  
- **Backend (Optional):** Flask for real-time monitoring  
- **Deployment:** Google Colab / Local Machine  

---

---

## 🚀 Installation & Setup  

### **1️⃣ Install Dependencies**  
Clone the repository and install dependencies:  
```bash
git clone https://github.com/kanakrajarora/Crowd-Management-System.git
cd crowd-detection
pip install -r requirements.txt
```
### **2️⃣ Install YOLOv8 (Ultralytics)**
```bash
pip install ultralytics opencv-python pandas numpy tensorflow keras matplotlib
```
### **3️⃣ Run PBL.ipynb **

### **4️⃣ Upload raw video footage when prompted **


## 📊 Results  
- ✅ **YOLOv8 successfully detects people in real-time**  
- ✅ **Random Forest achieves R² = 0.67** for predicting crowd trends. 
- ✅ **Heatmaps highlight high-density areas** for better management.   
- ✅ **Congestion alerts are triggered when crowd exceeds 30+ people**  

---

## 🚀 Future Enhancements  
- 🔹 **Deploy as a Flask API** for real-time monitoring  
- 🔹 **Optimize YOLO models** for faster inference  
- 🔹 **Improve LSTM** with Transformer-based models

---

## 📝 License  
MIT License © 2024 AI-Based Crowd Management System  

