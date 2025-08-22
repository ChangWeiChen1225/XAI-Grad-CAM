

# XAI-Grad-CAM
- 1D 和 2D Grad-CAM 有效捕捉了 REM 和睡眠主軸等主要睡眠訊號的關鍵特徵。
- 值得一提的是，1D Grad-CAM 在準確性和視覺化直觀性方面表現出卓越的精度。


## 系統簡介
<img width="605" height="424" alt="image" src="https://github.com/user-attachments/assets/c8c178f5-6384-417c-a476-16d95ec770f5" />

- 1D/2D CNN model for REMs and sleep spindle
<img width="1763" height="960" alt="image" src="https://github.com/user-attachments/assets/b7e916e9-92ec-4169-870a-3f49009e78ff" />




## 功能特色
- 利用EOG對REMs睡眠訊號的發生作檢測
- 利用EEG對sleep spindle睡眠訊號的發生作檢測
- 透過1D/2D Grad-CAM可解釋性模型來呈現推論結果

## 環境需求
- Colab
- Kaggle


## 安裝與執行方式
1. 下載這個github專案
```bash
git clone https://github.com/ChangWeiChen1225/XAI-Grad-CAM.git
```
2. 使用Colab或kaggle開啟資料中的.ipynb檔

## 結果呈現
### REMs 視覺化成果
**One-dimensional Grad-CAM for REM**
<img width="758" height="296" alt="image" src="https://github.com/user-attachments/assets/48cae303-cbd2-431d-8de4-90b0f77d2dca" />

**Two-dimensional Grad-CAM for REM**
<img width="835" height="297" alt="image" src="https://github.com/user-attachments/assets/94c89dd6-eab5-4f77-953a-392b2ef5f27b" />

### Sleep spindle 視覺化成果
**One-dimensional Grad-CAM for sleep spindle**
<img width="778" height="307" alt="image" src="https://github.com/user-attachments/assets/47eef66c-2858-4a55-a9f9-d7d65089075d" />

**Two-dimensional Grad-CAM for sleep spindle**
<img width="852" height="330" alt="image" src="https://github.com/user-attachments/assets/c4ab8e8a-e9ff-47b5-bf0d-9e58c8683bc1" />


## 作者
陳政瑋 (國立成功大學生物醫學工程學系)


# XAI-Grad-CAM (English version)
- Both 1D and 2D Grad-CAM effectively capture key features of major sleep signals, such as REM sleep and sleep axes.
- Notably, 1D Grad-CAM demonstrates superior accuracy and intuitive visualization.


## Introduction
<img width="605" height="424" alt="image" src="https://github.com/user-attachments/assets/c8c178f5-6384-417c-a476-16d95ec770f5" />

- 1D/2D CNN model for REMs and sleep spindle
<img width="1763" height="960" alt="image" src="https://github.com/user-attachments/assets/b7e916e9-92ec-4169-870a-3f49009e78ff" />




## Feature
- Detecting the occurrence of REM sleep signals using EOG
- Detecting the occurrence of sleep spindles using EEG
- Presenting inference results using 1D/2D Grad-CAM explainable models

## Requirements
- Colab
- Kaggle


## Installation & Execution
1. Download this github project
```bash
git clone https://github.com/ChangWeiChen1225/XAI-Grad-CAM.git
```
2. Use Colab or Kaggle to open the .ipynb file in the data

## Demo showcase
### REMs Visualization Results
**One-dimensional Grad-CAM for REM**
<img width="758" height="296" alt="image" src="https://github.com/user-attachments/assets/48cae303-cbd2-431d-8de4-90b0f77d2dca" />

**Two-dimensional Grad-CAM for REM**
<img width="835" height="297" alt="image" src="https://github.com/user-attachments/assets/94c89dd6-eab5-4f77-953a-392b2ef5f27b" />

### Sleep spindle visualization results
**One-dimensional Grad-CAM for sleep spindle**
<img width="778" height="307" alt="image" src="https://github.com/user-attachments/assets/47eef66c-2858-4a55-a9f9-d7d65089075d" />

**Two-dimensional Grad-CAM for sleep spindle**
<img width="852" height="330" alt="image" src="https://github.com/user-attachments/assets/c4ab8e8a-e9ff-47b5-bf0d-9e58c8683bc1" />



### Statistics results
**REMs detection and sleep spindle detection using 10fold-CV and LOSO-CV**
<img width="975" height="310" alt="image" src="https://github.com/user-attachments/assets/24d37df9-bfd4-460e-a72c-6ae1ed3d4dd2" />

