🧠 Skin Disease Classification using Deep Learning

📌 Objective

The objective of this project is to develop a deep learning model that can classify different types of skin diseases from images using Convolutional Neural Networks (CNN) and transfer learning.

📊 Dataset

- Dataset: HAM10000 Skin Disease Dataset
- Number of Classes: 7
- Data Type: Dermatoscopic images
- Source: Kaggle / Medical dataset

⚙️ Technologies Used

- Python
- TensorFlow / Keras
- OpenCV
- NumPy & Pandas
- Matplotlib

🔍 Project Workflow

1. Data Loading from Google Drive
2. Data Preprocessing (cleaning, filtering missing data)
3. Data Augmentation (rotation, zoom, flip)
4. Dataset Splitting (Training & Testing)
5. Model Development using MobileNetV2
6. Model Training and Validation
7. Evaluation using classification metrics
8. Prediction of skin disease from image

🧠 Model Architecture

- Pre-trained MobileNetV2 (Transfer Learning)
- Global Average Pooling Layer
- Dense Layer
- Dropout Layer
- Output Layer (Softmax)

🏋️ Model Training

- Optimizer: Adam
- Loss Function: Categorical Crossentropy
- Metrics: Accuracy

📉 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

📈 Results

The model shows good performance in classifying different skin diseases. Training and validation accuracy improve over epochs, indicating effective learning.

🔮 Prediction

The model can take a single image as input and predict the type of skin disease using trained weights.

💾 Model Saving

The trained model is saved for future use:

skin_disease_model.keras

🚀 Future Improvements

- Use larger dataset for better accuracy
- Apply advanced models like EfficientNet
- Improve model tuning and optimization

👨‍💻 Author

Avdhut Kale
