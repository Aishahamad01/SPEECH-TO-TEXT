# **Speech-to-Text for Swahili**

## 📌 Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Environment Setup](#environment-setup)
- [Preprocessing](#preprocessing)
- [How to Use](#how-to-use)
- [Contribuors](#contributors)
- [License](#license)
- [Acknowledgments](#acknowledgments)

---

## 🚀 Overview
This project focuses on developing a speech-to-text model for Swahili, a widely spoken language in East Africa. By leveraging state-of-the-art Natural Language Processing (NLP) techniques, the goal is to build an accurate and reliable transcription system for Swahili speech data.  

---

## 📊 Dataset
We use the **Swahili speech dataset** from **Harvard's Dataverse**, which contains diverse audio samples in Swahili. The dataset undergoes preprocessing to ensure high-quality input for model training. 

---

## Preprocessing Steps

1. **Noise Reduction:** Improve speech clarity by eliminating background noise.
2. **Segmentation:** Break audio into manageable segments.
3. **Feature Extraction:** Extract Mel spectrograms and other key features for model training.

---

## Model Training

The project fine-tunes multiple **pre-trained models** to optimize transcription performance for Swahili:

1. **Whisper-Base**: A robust ASR model by OpenAI.

2. **HuBERT:** A self-supervised learning model for speech representation.

3. **Bidirectional Recurrent Neural Networks (RNNs):** Used to capture long-term dependencies in speech sequences.

---

## Evaluation Metrics

The models' performance is assessed using:
- **Word Error Rate (WER)**
- **Character Error Rate (CER)**
- **Overall Transcription Accuracy**

---

### Goal

The ultimate objective is to build a **reliable Swahili speech-to-text system** that enhances research in **underrepresented languages** and improves **accessibility & communication technologies** for Swahili speakers.

---


## Contributors

- **Aisha Hamad**

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgments

- **My Supervisor**: Dr. Nirav Bhatt for his guidance.
- **Hugging Face**: For providing the `transformers` and `datasets` libraries..

---
