# 🧑‍⚕️ ISIC 2024 - Skin Cancer Detection with 3D Total Body Photography (TBP) 🩺
## 🚀 Kaggle Challenge Overview
In this competition, we aim to develop algorithms to identify histologically confirmed skin cancer from single-lesion crops in 3D Total Body Photos (TBP). These images are similar to smartphone photos commonly used in telehealth. The objective is to build a binary classification model that aids in early skin cancer detection, especially in areas with limited access to specialized care.

## 🔍 Model Versions
### Version 1: Basic CNN
* 🖼️ Data: Only used image data.
* ⚙️ Model: Basic CNN after balancing the data.
* 📊 AUC Curve: 60.
* 📝 Result: Initial results, but not optimal.
### Version 2: VGG16 + ResNet
* 🖼️ Data: Only used image data.
* ⚙️ Model: VGG16 combined with ResNet for better feature extraction.
* 📊 AUC Curve: 70.
* 📝 Result: Some improvement, but still needed fine-tuning.
### Version 3: EfficientNet + Tabular Data
* 🖼️ Data: Combined image data with tabular features from the dataset.
* 📝 Inspiration: Took ideas from a starter notebook provided in the competition.
* ⚙️ Model: EfficientNet architecture with advanced data augmentation.
* 📊 AUC Curve: 92.
* 💡 Best Result: Achieved the best score of 0.1367/2 after submission! 📈
* 🏆 Leaderboard Screenshot (coming soon)
This version incorporates the AUC curve improvements, highlighting the progression of the model's performance over time!
### 🌍 Global Ranking
Position: 2200 out of 3000 participants from around the world 🌐.
![image](https://github.com/user-attachments/assets/8d383f52-81f8-49fa-a804-78d264e424e6)
