# 📱 Android Image Classification App

Real-time Image Classification Android application built using CameraX and TensorFlow Lite.

This application captures live camera frames and performs on-device image classification using a MobileNet TFLite model.

---

## 🚀 Features

- 📷 Real-time camera preview using CameraX  
- 🤖 On-device image classification (TensorFlow Lite Task Library)  
- ⚡ Fast inference (CPU / GPU / NNAPI support)  
- 🎯 Displays Top-3 predictions with confidence scores  

## 🏗 Tech Stack

- Kotlin  
- CameraX  
- TensorFlow Lite Task Vision  
- ViewBinding  
- CardView  
- MobileNet V1 Quantized Model  

## 🧠 Model Information

Model used:

mobilenet_v1_1.0_224_quantized_1_metadata_1.tflite

- Input size: 224 x 224  
- Quantized model (optimized for mobile devices)  
- Lightweight and fast inference  

## 📷 Application Flow

1. Request camera permission  
2. Start CameraX preview  
3. Capture frame using ImageAnalysis  
4. Convert ImageProxy to Bitmap  
5. Resize image to 224x224  
6. Run TensorFlow Lite inference  
7. Display classification results  

