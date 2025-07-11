# 🚗 Accident Detection System using Deep Learning

This project is a real-time accident detection system built using deep learning and computer vision. It processes dashcam or webcam footage to classify whether a road accident has occurred.

---

## ✨ Features

- 🚘 Detects accidents in real-time from video frames
- 🎯 Trained deep learning model using ResNet18
- 📦 Includes preprocessing scripts for frame extraction and image enhancement
- 🧠 Jupyter notebooks for model training, evaluation, and selection
- 🛑 Can be integrated into emergency response systems (like auto-alerts)

---

## 🗂️ Project Structure

```
Accident_Detection_System/
├── Accident_Prediction.py              # Main prediction script
├── accident_classifier_resnet18.pth    # Trained PyTorch model
├── image_processing.ipynb              # Preprocessing logic
├── Accident_Classifier_Model_Selection.ipynb  # Model comparison
├── Locked_Model.ipynb                  # Final locked model
├── unified_data/                       # Image/video dataset
├── requirements.txt                    # Environment dependencies
├── .gitignore
└── README.md
```

---

## ⚙️ Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/AmanSingh-layman/Accident_Detection_System.git
   cd Accident_Detection_System
   ```

2. **Create and activate a virtual environment**:
   ```bash
   python -m venv .venv
   .venv\Scripts\activate     # On Windows
   ```

3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

---

## 🚀 Usage

Run the main script for real-time prediction:

```bash
python Accident_Prediction.py
```

You can also explore the notebooks:
- `image_processing.ipynb`: Preprocessing frames
- `Accident_Classifier_Model_Selection.ipynb`: Model selection and accuracy comparison
- `Locked_Model.ipynb`: Final evaluation results

---

## 📌 Requirements

- Python 3.8+
- PyTorch
- OpenCV
- NumPy, Pandas, Matplotlib
- Jupyter (for notebooks)

All dependencies are listed in `requirements.txt`

---

## 👨‍💻 Author

**Aman Singh**  

