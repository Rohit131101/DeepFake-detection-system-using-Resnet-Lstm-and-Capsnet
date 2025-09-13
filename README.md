# DeepFake Detection System using ResNet, LSTM, and CapsNet

This project is a hybrid deep learning system that combines Convolutional Neural Networks (ResNet), Recurrent Neural Networks (LSTM), and Capsule Networks (CapsNet) to detect DeepFake videos. The system processes videos frame-by-frame and uses spatial-temporal and capsule feature extraction to classify videos as real or fake.

## 🔍 Features

- Hybrid architecture combining ResNet50, LSTM, and Capsule Networks
- Real-time video frame extraction and classification
- Flask-based web interface for uploading and analyzing videos
- Clean UI with HTML, CSS, and JavaScript
- Visual performance plots for model evaluation

---

## 📁 Project Structure
- ├── model_training.py # Script for training the hybrid deep learning model
- ├── inference.py # Script for running inference on input videos
- ├── app.py # Flask app to host the frontend
- ├── static/ # Static assets for the web interface
- │ ├── style.css # Custom styles
- │ └── script.js # Frontend interactivity scripts
- ├── templates/ # HTML templates for Flask
- │ └── index.html # Main user interface
- ├── model/ # Directory for storing trained models
- │ └── hybrid_model.h5 # Saved Keras hybrid model
- └── utils/ # Utility scripts


---

## 🧠 Dependencies

Ensure Python 3.8+ is installed. Install the required libraries using:

```bash
pip install -r requirements.txt
```
If requirements.txt is not available, you can install the main packages manually
```
pip install numpy pandas opencv-python flask tensorflow keras matplotlib scikit-learn pillow
```
🛠️ Setup Instructions

setup:
-   clone_command: git clone https://github.com/Rohit131101/DeepFake-detection-system-using-Resnet-Lstm-and-Capsnet.git
-   run_app: python app.py
-   train_model: python model_training.py
-   inference: python inference.py --input path_to_video.mp4
-   url: http://127.0.0.1:5000/
