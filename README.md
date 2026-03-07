# Eye for Blind: Assistive AI for Image-to-Audio Descriptions

## 📌 Project Overview
Eye for Blind is an assistive AI application designed to help visually impaired individuals understand their surroundings. The system takes an image as input and generates a descriptive audio narration of the scene.

## 🧠 Technical Architecture
The model utilizes an **Encoder-Decoder architecture** with Attention mechanisms:
* [cite_start]**Encoder:** A pre-trained **InceptionV3** model used for deep feature extraction from images[cite: 22].
* [cite_start]**Decoder:** A Recurrent Neural Network (RNN) that processes preprocessed captions to generate descriptive text[cite: 22].
* [cite_start]**Audio Integration:** Integrated a Text-to-Speech (TTS) engine to convert generated descriptions into audible speech[cite: 23].

## 📊 Dataset
* [cite_start]**Source:** Kaggle Image Captioning Dataset[cite: 21].
* [cite_start]**Scale:** 40,455 images paired with corresponding text captions[cite: 21].
* [cite_start]**Preprocessing:** Captions were cleaned, tokenized, and padded; images were normalized for InceptionV3 compatibility[cite: 22].

## 🛠️ Tech Stack
* [cite_start]**Language:** Python [cite: 16]
* [cite_start]**Deep Learning:** TensorFlow, Keras [cite: 17]
* [cite_start]**Data Processing:** NumPy, Pandas, OpenCV [cite: 17]
* [cite_start]**Visualization:** Matplotlib, Seaborn [cite: 17]
* [cite_start]**Speech:** gTTS (Google Text-to-Speech) [cite: 23]

## 📂 Repository Structure
├── notebooks/          # Eye_For_Blind_Capstone_Project.ipynb
├── data/               # captions.txt (Sample data)
├── requirements.txt    # Project dependencies
└── README.md           # Project documentation