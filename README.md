\# 🩺 AI Medical Report Assistant



\## 📌 Project Overview



The \*\*AI Medical Report Assistant\*\* is an end-to-end Deep Learning application that analyzes Chest X-ray images to detect \*\*Pneumonia\*\* or \*\*Normal\*\* conditions. The application uses a \*\*Transfer Learning model\*\* built with TensorFlow and generates an \*\*AI-assisted medical report\*\* using an LLM (OpenRouter GPT-4.1 Mini). A user-friendly Streamlit interface allows users to upload X-ray images, view predictions, and download the generated report.



\---



\## 🚀 Features



\- Upload Chest X-ray images

\- Automatic image preprocessing

\- Pneumonia / Normal classification

\- Confidence score display

\- AI-generated medical report using an LLM

\- Download medical report as a text file

\- Modern Streamlit web interface



\---



\## 📂 Dataset



\*\*Dataset:\*\* Chest X-ray Pneumonia Dataset



\*\*Source:\*\*

https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia



\### Dataset Statistics



\- Train Images: 5,216

\- Validation Images: 16

\- Test Images: 624



\### Classes



\- NORMAL

\- PNEUMONIA



\---



\## 🧠 Deep Learning Model



\- Framework: TensorFlow / Keras

\- Transfer Learning Model: EfficientNetB0 \*(Replace with your actual model if different)\*

\- Output Layer: Sigmoid Activation

\- Loss Function: Binary Crossentropy

\- Optimizer: Adam



\---



\## 📊 Model Evaluation



The model was evaluated using:



\- Accuracy

\- Precision

\- Recall

\- F1-Score

\- ROC Curve

\- AUC Score

\- Validation AUC

\- Confusion Matrix



\---



\## 🤖 LLM Integration



This project integrates \*\*OpenRouter GPT-4.1 Mini\*\* to generate a simple AI-assisted medical report based on the model prediction.



The generated report includes:



\- Findings

\- Impression

\- Recommendation

\- Disclaimer



\---



\## 💻 Technologies Used



\- Python

\- TensorFlow

\- Keras

\- Streamlit

\- NumPy

\- Pillow (PIL)

\- OpenAI Python SDK

\- OpenRouter API



\---



\## 📁 Project Structure



```text

AI\_Medical\_Report\_Assistant/

│

├── app.py

├── README.md

├── requirements.txt

│

├── models/

│   └── pneumonia\_model.h5

│

├── notebooks/

│   └── model\_training.ipynb

│

├── outputs/

│   ├── accuracy\_loss.png

│   ├── confusion\_matrix.png

│   └── roc\_curve.png

│

├── screenshots/

│   ├── home.png

│   ├── upload.png

│   ├── prediction.png

│   └── report.png

│

└── dataset/

```



\---



\## ▶️ Installation



Clone the repository



```bash

git clone <repository-url>

```



Move into the project directory



```bash

cd AI\_Medical\_Report\_Assistant

```



Install the required packages



```bash

pip install -r requirements.txt

```



Run the application



```bash

streamlit run app.py

```



\---



\## 📸 Application Workflow



1\. Upload a Chest X-ray image.

2\. The image is preprocessed.

3\. The TensorFlow model predicts the class.

4\. The confidence score is displayed.

5\. The LLM generates an AI-assisted medical report.

6\. The report can be downloaded.



\---



\## ⚠ Disclaimer



This application is developed for \*\*educational and research purposes only\*\*.



The AI-generated report should \*\*not\*\* replace professional medical diagnosis or clinical judgment.



\---



\## 👨‍💻 Developer



\*\*Name:\*\* Praveen



Project: \*\*AI Medical Report Assistant\*\*



Built using \*\*TensorFlow\*\*, \*\*Streamlit\*\*, and \*\*OpenRouter GPT-4.1 Mini\*\*.

