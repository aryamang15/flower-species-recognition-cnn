#  Flower Species Recognition using CNN

An end-to-end Flower Species Recognition system built using a Convolutional Neural Network (CNN). The model classifies flower images into five categories and includes a Tkinter GUI for real-time predictions.

## Features

- Custom CNN built from scratch
- TensorFlow/Keras implementation
- Image preprocessing and data augmentation
- Tkinter desktop GUI
- Real-time flower prediction
- Model saved using Keras format

## Dataset

TensorFlow Flowers Dataset

Classes:
- Daisy
- Dandelion
- Roses
- Sunflowers
- Tulips

Approximately 3,670 images.

## Technologies Used

- Python 3.10
- TensorFlow 2.x
- Keras
- NumPy
- Pillow
- Tkinter

## Model Architecture

- Conv2D (32 filters)
- MaxPooling2D
- Conv2D (64 filters)
- MaxPooling2D
- Flatten
- Dense (128)
- Softmax Output (5 classes)

## Performance

| Metric | Score |
|---------|-------|
| Accuracy | 91% |
| Precision | 90% |
| Recall | 89% |
| F1 Score | 89.5% |

## Project Structure

```
Flower-CNN/
│
├── dataset/
├── model/
│   └── flower_model_v2.keras
├── images/
├── gui.py
├── train.py
├── predict.py
├── requirements.txt
└── README.md
```

## Installation

```bash
git clone https://github.com/yourusername/flower-species-recognition-cnn.git

cd flower-species-recognition-cnn

pip install -r requirements.txt
```

## Train the Model

```bash
python train.py
```

## Run Prediction GUI

```bash
python gui.py
```

## Results

- Validation Accuracy: 91%
- CPU Inference Time: ~0.45 seconds/image
- Model Size: ~8 MB

## Future Improvements

- EfficientNet Transfer Learning
- Flask/FastAPI Web Deployment
- Mobile Application
- Plant Disease Detection
- Explainable AI (Grad-CAM)

## Authors

- Aryaman Giri
- Ranveer Singh Thakur

Department of Computer Engineering

MPSTME, NMIMS Mumbai

## License

MIT License
