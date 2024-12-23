## First Model (22.5 kHz, librosa MFCC)
- model_v6_final.ipynb
- model_final.keras
- converted_model_final.tflite
- scaler_final.pkl

## Second Model (16 kHz, manual MFCC, less dropout layers)
- model_v6_final (16kHz).ipynb
- q_model.keras
- q_converted_model.tflite
- q_scaler.pkl

## Audio Test Samples
- sample1.wav      (cough)
- sample2.wav      (non_cough)
- sample3.wav      (mix)

## Data Dir (if you want to try training)
- data/
  - coughs/        (https://www.kaggle.com/datasets/himanshu007121/cough-audio-dataset)
  - not_coughs/    (https://www.kaggle.com/datasets/himanshu007121/cough-audio-dataset)
  - coughvid/      (https://www.kaggle.com/datasets/nasrulhakim86/coughvid-wav)
