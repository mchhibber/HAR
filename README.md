# Human Action Recognition Android App

## Introduction

This is an android app based upon pytorchvideo using a pre-trained PyTorchVideo classification model on Android to see video classification results and latency, updated per second while the video plays on tested videos, videos from the Photos library, or even real-time videos.

## Prerequisites

* PyTorch 1.8.0/1.8.1, torchvision 0.9.1, PyTorchVideo (Optional)
* Python 3.8 or above (Optional)
* Android Pytorch library 1.8.0, torchvision library 1.8.0
* Android Studio 4.0.1 or later

## Quick Start

### 1. Prepare the Model

Place the model alongwith it's classes in `app/src/main/assets` folder as `video_classification.pt` and `classes.txt` respectively.

### 2. Build with Android Studio

Open the project in android studio.

### 3. Run the app

Select an Android emulator or, to test videos from your Camera Roll or live video, select an Android device to run the app. Pre-recorded video are also provided in app.

Some screenshots of the video classification results are as follows:

<img src='https://github.com/mchhibber/Human-Action-Recognition-Android-App/blob/main/images/1.jpeg' width='324' height='648'></img>
<img src='https://github.com/mchhibber/Human-Action-Recognition-Android-App/blob/main/images/2.jpeg' width='324' height='648'></img>
<img src='https://github.com/mchhibber/Human-Action-Recognition-Android-App/blob/main/images/3.jpeg' width='324' height='648'></img>


