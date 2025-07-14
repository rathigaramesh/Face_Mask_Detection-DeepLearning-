# Face_Mask_Detection-DeepLearning-
🎯 Objective: Train a deep learning model to classify whether a person is wearing a mask or not, based on image input.
📌 Highlights:
📦 Dataset: Two classes — with mask and without mask
🧠 Model: MobileNetV2 (Transfer Learning from ImageNet)
📐 Image Size: Resized to 224x224 pixels
🔄 Data Augmentation to increase diversity and reduce overfitting
🧪 Dataset Split: 75% Training / 25% Testing
🧮 One-hot encoding for labels
🧰 Custom head with pooling, dense layers, dropout, and softmax
⚙️ Optimizer: Adam (LR = 1e-4)
📊 Loss Function: Binary Crossentropy
📈 Training: 20 Epochs with accuracy/loss plots
🧪 The model performed well on the test set, showing strong precision, recall, and accuracy across both classes.
💾 The trained model is saved in .h5 format for future deployment — perfect for real-time applications like video-based mask detection.
🔧 Tech Stack:
tensorflow==1.14.0
keras==2.3.1
opencv-python==4.2.0.32
scikit-learn==0.23.1
numpy==1.18.2
matplotlib==3.2.1
pillow==7.2.0
imutils==0.5.3
scipy==1.4.1
argparse==1.1
