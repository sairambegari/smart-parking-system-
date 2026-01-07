# 🚗 Smart Parking Space Detector using YOLO and OpenCV 🅿️  

## 🔍 Overview  
This project utilizes **YOLO (You Only Look Once) and OpenCV** to detect and monitor parking spaces in real-time. It helps optimize parking lot management by identifying vacant and occupied spots with high accuracy.  

## 🛠️ Features  
✅ **Real-time Parking Detection** using YOLOv4/YOLOv8  
✅ **OpenCV for Image Processing**  
✅ **Bounding Boxes & Object Detection** for parked cars  
✅ **Customizable Parking Zone Mapping**  
✅ **Supports Live Camera Feeds & Video Input**  

## 📸 Demo 

<img width="1493" height="816" alt="Screenshot 2025-11-01 073737" src="https://github.com/user-attachments/assets/ba1e6f0f-bc8e-4a19-897e-aeb01c72a3c4" />



## 🏗️ Installation  

### 1️⃣ Clone the Repository  
```sh
git clone https://github.com/prajesdas/Smart-Parking-Space-Detector-using-YOLO-and-OpenCV.git
cd Smart-Parking-Space-Detector-using-YOLO-and-OpenCV
```

### 2️⃣ Install Dependencies  
```sh
pip install -r requirements.txt
```

### 3️⃣ Download YOLO Weights  
- Download YOLOv4 weights from [official YOLO website](https://pjreddie.com/darknet/yolo/) or use a pre-trained YOLOv8 model.  
- Place the weights in the `models/` directory.  

### 4️⃣ Run the Detection Script  
```sh
python detect_parking.py --source video.mp4
```
or for live webcam feed:  
```sh
python detect_parking.py --source 0
```

## 📂 Project Structure  
```
📂 Smart-Parking-Space-Detector  
 ┣ 📂 models/              # YOLO model weights  
 ┣ 📂 data/                # Parking lot images/videos  
 ┣ 📂 utils/               # Helper functions  
 ┣ 📜 detect_parking.py    # Main script for detection  
 ┣ 📜 requirements.txt     # Dependencies  
 ┣ 📜 README.md            # Project documentation  
```

## 🚀 Future Enhancements  
🔹 Integration with a **mobile app** for user-friendly access 📱  
🔹 Adding a **cloud database** to store parking statistics ☁️  
🔹 Implementing **number plate recognition** for security 🔢  

## 🤝 Contributing  
Pull requests are welcome! If you'd like to contribute, please open an issue first to discuss your ideas.  

## 📜 License  
This project is **MIT Licensed**. Feel free to use and modify it.  

## Contact 
https://github.com/bsairam027/smart-parking-system

## Instagram
https://instagram.com/Sairamsai73
