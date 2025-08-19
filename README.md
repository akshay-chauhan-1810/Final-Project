# Final Project- Secure Voice - Speech-based verification 

This project implements a **speech verification system** that determines whether audio samples belong to the **same speaker** or **different speakers**.

It uses the **LibriSpeech `train-clean-100` dataset** for training and evaluation.  
The main notebook is [`project_main.ipynb`](project_main.ipynb), which contains data processing, model training, and verification steps.

---

## Quick Start

1. **Run online**: Click the "Open in Colab" in .ipynb main file
2. **Run locally**:
   ```bash
   git clone https://github.com/akshay-chauhan-1810/Final-Project.git
   jupyter notebook project_main.ipynb

---
## Features

- One-to-one speaker verification
- Preprocessing of the **LibriSpeech** audio dataset
- Feature extraction (MFCCs / spectrograms)
- Model training for speaker verification
- Evaluation on test audio samples

---

## Dataset

- **LibriSpeech `train-clean-100`**  
  - [Download Here](https://www.openslr.org/12)  
  - Audio files are `.flac` format, sampled at 16 kHz.  
  - Place the dataset in a folder structure like:
data/
└── LibriSpeech/
    └── train-clean-100/
        └── <speaker_id>/
            └── <chapter_id>/
                └── <audio_file>.flac

