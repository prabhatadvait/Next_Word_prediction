# 📝 Next Word Prediction using LSTM & GRU

[![Live App](https://img.shields.io/badge/Streamlit-Live%20Demo-brightgreen?logo=streamlit)](https://nextwordpredictions.streamlit.app/)

A deep learning project that predicts the **next possible word** in a sentence using **LSTM** and **GRU** models.  
The model is trained on the works of **William Shakespeare**, making it capable of generating text in a Shakespearean style.

---

## 🚀 Live Demo
👉 [Try the App Here](https://nextwordpredictions.streamlit.app/)

---

## ✨ Project Overview
- Built a **Next Word Prediction model** using **Recurrent Neural Networks (RNNs)**.  
- Implemented both **LSTM** and **GRU** architectures with **TensorFlow** and **Keras**.  
- Trained on a **large corpus of Shakespeare’s text** (`hamlet.txt`).  
- Deployed with **Streamlit** for an interactive web application.  

---

## 🛠️ Tech Stack
- **Python**  
- **TensorFlow / Keras** (Deep Learning Frameworks)  
- **Streamlit** (Web App Deployment)  
- **Jupyter Notebook** (Experiments & Prototyping)  

---

## 📂 Repository Structure
```
Next_Word_prediction/
│
├── app.py                 # Streamlit app for deployment
├── experiments.ipynb      # Jupyter notebook with training & experiments
├── hamlet.txt             # Training dataset (Shakespeare text)
├── next_word_lstm.h5      # Trained LSTM model
├── tokenizer.pickle       # Saved tokenizer for text preprocessing
├── requirements.txt       # Project dependencies
└── README.md              # Project documentation
```

---

## ⚙️ How It Works
1. **Text Preprocessing**  
   - Tokenized the Shakespeare dataset using `Tokenizer` (Keras).  
   - Converted text sequences into input-output pairs for training.  

2. **Model Training**  
   - Used **LSTM** and **GRU layers** to capture sequential word dependencies.  
   - Optimized with categorical cross-entropy loss.  

3. **Prediction**  
   - Given an input phrase, the model predicts the **most probable next word**.  

4. **Deployment**  
   - The trained model was integrated into a **Streamlit app** for real-time interaction.  

---

## 📦 Installation & Setup
Clone the repository:
```bash
git clone https://github.com/prabhatadvait/Next_Word_prediction.git
cd Next_Word_prediction
```

Install dependencies:
```bash
pip install -r requirements.txt
```

Run the Streamlit app locally:
```bash
streamlit run app.py
```

---

## 🤝 Contributing
Contributions, suggestions, and improvements are welcome!  
- Fork the repo  
- Create a branch  
- Submit a PR 🚀  

---

## 📄 License
This project is licensed under the **MIT License**.  
See the [LICENSE](LICENSE) file for more details.  
