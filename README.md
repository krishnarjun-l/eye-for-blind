# Eye for Blind: Assistive AI for Image-to-Audio Descriptions

## 📌 Project Overview
Eye for Blind is an assistive AI application designed to help visually impaired individuals understand their surroundings. The system takes an image as input and generates a descriptive audio narration of the scene.

## 🧠 Technical Architecture
The model utilizes an **Encoder-Decoder architecture** with Attention mechanisms:
* **Encoder:** A pre-trained **InceptionV3** model used for deep feature extraction from images.
* **Decoder:** A Recurrent Neural Network (RNN) that processes preprocessed captions to generate descriptive text.
* **Audio Integration:** Integrated a Text-to-Speech (TTS) engine to convert generated descriptions into audible speech.

## 📊 Dataset
* **Source:** Kaggle Image Captioning Dataset.
* **Scale:** 40,455 images paired with corresponding text captions.
* **Preprocessing:** Captions were cleaned, tokenized, and padded; images were normalized for InceptionV3 compatibility.
* The dataset is not included in this repository because of its size (thousands of images). It is publicly available on Kaggle:
https://www.kaggle.com/code/quadeer15sh/flickr8k-image-captioning-using-cnns-lstms


## 🛠️ Tech Stack
* **Language:** Python 
* **Deep Learning:** TensorFlow, Keras 
* **Data Processing:** NumPy, Pandas, OpenCV 
* **Visualization:** Matplotlib, Seaborn 
* **Speech:** gTTS (Google Text-to-Speech) 

## 📂 Repository Structure
```
├── Eye_For_Blind_Capstone_Project.ipynb
├── requirements.txt
└── README.md
```


