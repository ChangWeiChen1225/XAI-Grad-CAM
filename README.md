# XAI-Grad-CAM
1D and 2D Grad-CAM effectively captured key features of the main sleep signals of REMs and sleep spindle. Notably, 1D Grad-CAM exhibited superior precision on accuracy and straightforwardness in visualization.


## Dataset
**DREAMS dataset**

9 excerpts of 30 minutes in which REMs were annotated by an expert
<img width="1908" height="591" alt="image" src="https://github.com/user-attachments/assets/acab5b11-8140-4e8c-95fe-5858e238e7e9" />


## Algorithm workflow
<img width="594" height="256" alt="image" src="https://github.com/user-attachments/assets/cc5263f7-5397-45c3-adf1-4f4dde0fd285" />


## Methodology
**Sliding window**
<img width="1113" height="572" alt="image" src="https://github.com/user-attachments/assets/476e973c-236c-4d81-9ea0-1acbcdbcd4a9" />

**Synthetic Minority Oversampling Technique (SMOTE)**
<img width="1082" height="490" alt="image" src="https://github.com/user-attachments/assets/2498561d-86af-4487-9fd7-946cf849f63f" />

**Wavelet Transform Coherence (WTC)**
<img width="1918" height="527" alt="image" src="https://github.com/user-attachments/assets/9c66f3f7-b702-4bfc-bee7-75efe79fdd36" />

** 2-Dimensional Convolution Neural Network (2D-CNN)**
<img width="1490" height="627" alt="image" src="https://github.com/user-attachments/assets/0b8d463c-6a29-4256-9134-6d6a30952582" />

**1-Dimensional Convolution Neural Network (1D-CNN)**
<img width="608" height="353" alt="image" src="https://github.com/user-attachments/assets/ece4e7fc-2125-4790-83a4-652535f9b729" />

**Gradient Class Activation Map (Grad-CAM)**
<img width="605" height="424" alt="image" src="https://github.com/user-attachments/assets/c8c178f5-6384-417c-a476-16d95ec770f5" />


## Results
**REMs detection and sleep spindle detection using 10fold-CV and LOSO-CV**
<img width="975" height="310" alt="image" src="https://github.com/user-attachments/assets/24d37df9-bfd4-460e-a72c-6ae1ed3d4dd2" />

**One-dimensional Grad-CAM for REM**
<img width="758" height="296" alt="image" src="https://github.com/user-attachments/assets/48cae303-cbd2-431d-8de4-90b0f77d2dca" />

**Two-dimensional Grad-CAM for REM**
<img width="835" height="297" alt="image" src="https://github.com/user-attachments/assets/94c89dd6-eab5-4f77-953a-392b2ef5f27b" />

**One-dimensional Grad-CAM for sleep spindle**
<img width="778" height="307" alt="image" src="https://github.com/user-attachments/assets/47eef66c-2858-4a55-a9f9-d7d65089075d" />

**Two-dimensional Grad-CAM for sleep spindle**
<img width="852" height="330" alt="image" src="https://github.com/user-attachments/assets/c4ab8e8a-e9ff-47b5-bf0d-9e58c8683bc1" />

