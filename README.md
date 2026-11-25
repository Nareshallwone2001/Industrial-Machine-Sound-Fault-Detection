# MachinePulse AI

## Industrial Machine Sound-Based Fault Detection Using Deep Learning — CNN & Autoencoder

### Project Overview
MachinePulse AI detects abnormal industrial machine sounds using deep learning and audio signal processing.

### Key Features
- Normal and abnormal sound classification
- Interactive audio upload
- Waveform visualization
- Mel Spectrogram visualization
- Model performance dashboard
- Gradio web application

### Technologies Used
Python, TensorFlow, Keras, CNN, Autoencoder, Librosa, NumPy, Pandas, Matplotlib and Gradio.

### Dataset
MIMII Pump Sound Dataset

- Total samples: 519
- Normal samples: 381
- Abnormal samples: 138

### Model Performance

| Model | Test Accuracy |
|---|---|
| CNN | 96.15% |
| Autoencoder | 78.21% |

The application uses CNN for classification. The Autoencoder is included for experimental comparison.

### Run Locally

    pip install -r requirements.txt
    python app.py

### Application Modules
1. Welcome Hub
2. Sound Intelligence Lab
3. Insights Dashboard
4. Project Explorer

### Deployment
- Local deployment: Completed
- Cloud deployment: In progress

### Disclaimer
This is an educational deep learning prototype, not a safety-certified industrial monitoring system.
