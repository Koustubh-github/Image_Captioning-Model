# 🖼️ Image Captioning with ResNet-50 + LSTM (Flickr8k)

This project implements an image captioning system using an **Encoder–Decoder architecture**, where a **pretrained ResNet-50** model extracts visual features and a **stacked LSTM** generates natural language descriptions. Trained on the **Flickr8k dataset**, the model achieves **BLEU-1 of 65%** and **BLEU-2 of 42%**, outperforming the original benchmark. 🚀

---

## ✨ Key Features
- 🧠 Encoder–Decoder pipeline (ResNet-50 + LSTM)
- 📊 BLEU-1 to BLEU-4 score evaluation
- 🔤 Caption tokenization, padding, and sequence generation
- 📁 Complete preprocessing + feature extraction workflow
- 📈 Training visualization and performance tracking

---

## 📁 Dataset
**Flickr8k Dataset**
- 8,000 images  
- 5 captions per image  
- Publicly available dataset and caption files  

---

## 🛠️ Technologies Used
- Python  
- TensorFlow / Keras  
- ResNet-50 (ImageNet pretrained)  
- LSTM  
- NumPy, Matplotlib, Pickle, tqdm  

---

## 🧩 Model Architecture

### 🔷 Encoder
- Pretrained **ResNet-50**, classification head removed  
- Produces **2048-dimensional** feature vectors  

### 🔶 Decoder
- Embedding layer  
- Stacked LSTM layers  
- Dense layer for next-word prediction  

---

## 📊 Results

| Metric | Score |
|--------|--------|
| ⭐ BLEU-1 | 65% |
| ⭐ BLEU-2 | 42% |
| ⭐ BLEU-3 | 27% |
| ⭐ BLEU-4 | 18% |

> 📈 The model surpasses the reference implementation (BLEU-1: 61%, BLEU-2: 41%).

---
