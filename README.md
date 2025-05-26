# 🦠 Malaria Parasite Detection using CNNs

An intelligent diagnostic tool that uses **Convolutional Neural Networks (CNNs)** to detect malaria parasites in blood smear images—enhancing early diagnosis, treatment, and saving lives in high-risk regions.

## 📖 Overview

This project automates the identification of malaria-infected cells in microscopic blood smear images. It leverages **deep learning (CNNs)** and computer vision techniques to classify cells as either infected or uninfected. With a simple, efficient model built using **TensorFlow/Keras** and image preprocessing via **OpenCV**, this tool supports healthcare providers in regions where timely diagnostics are critical.

## 🧠 Key Features

* 🔍 **Automated Detection of Malaria Parasites**
* 📊 **Binary Classification: Infected vs Uninfected**
* 🧬 **CNN architecture optimized for medical image classification**
* 🏥 **Real-world impact for healthcare workers and remote clinics**

## 🛠️ Tech Stack

* **Deep Learning**: TensorFlow, Keras
* **Image Processing**: OpenCV
* **Notebook Interface**: Jupyter (.ipynb)

## 🌍 Impact

* Enables **faster, more accurate malaria diagnosis**
* Reduces **mortality and misdiagnosis** in under-resourced areas
* Supports **accessible and scalable healthcare solutions**

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/malaria-cnn-detector.git
cd malaria-cnn-detector
```

### 2. Install Requirements

```bash
pip install -r requirements.txt
```

### 3. Run the Notebook

Open the `malaria.ipynb` notebook in Jupyter and run all cells to train/test the model or use the pretrained version.

---

## 📁 Dataset

The dataset used consists of blood smear images categorized into:

* `Parasitized` (with malaria parasite)
* `Uninfected` (without parasite)

📦 You can download the dataset from: [NIH Malaria Dataset](https://www.kaggle.com/datasets/iarunava/cell-images-for-detecting-malaria)

## 📈 Model Performance

* **Accuracy**: \~95% (depends on training configuration)
* **Metrics**: Confusion Matrix, Precision, Recall, F1-Score

## 🤝 Contribute

You’re welcome to improve the architecture, add real-time camera inference, build a GUI, or deploy this as a mobile or web app for field diagnosis.

---

## 📫 Contact

For collaboration or questions, reach out via pshanmukhapriyasravani@gmail.com
