# Android CNN Image Classifier using Neural Networks API (NNAPI)

This project demonstrates how to collect images using an Android device, preprocess them in Kotlin, and run a convolutional neural network (CNN) for image classification using Android's **Neural Networks API (NNAPI)** via native code.

> ⚠️ Android does not support running neural networks directly in Kotlin. Instead, we leverage the NNAPI through native C++ code using TensorFlow Lite and Android NDK.

---

## Features

- Capture or load images using Kotlin-based Android UI.
- Preprocess images (resize, normalize) before inference.
- Execute CNN inference using TensorFlow Lite and NNAPI delegate.
- Display the top prediction class and confidence.
- Lightweight and optimized for on-device inference.

---

## Technologies Used

- **Kotlin (UI, image collection)**
- **TensorFlow Lite (model inference)**
- **Android NDK (C/C++ integration)**
- **NNAPI (hardware acceleration)**
- **OpenCV (optional, for image preprocessing)**

---

## Prerequisites

- Android Studio Arctic Fox or newer
- Android device running API 27+ (Oreo or above)
- NDK (Native Development Kit) installed
- TensorFlow Lite model (e.g., MobileNetV1)

---
