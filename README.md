# Next Word Prediction using LSTM

This repository contains an LSTM-based deep learning model for predicting the next word in a given text sequence. The model is trained on Shakespeare's *Hamlet* and is deployed using a **Streamlit** web application.

## 🚀 Features
- Predicts the next word based on the input text using an LSTM model.
- Uses **tokenizer.pickle** for text processing.
- Web interface powered by **Streamlit**.
- Pre-trained model **next_word_lstm.h5** included.

---

## 📂 Repository Structure

```
word_prediction/
│── hamlet.txt               # Dataset (Shakespeare's Hamlet)
│── next_word_lstm.h5        # Trained LSTM model
│── tokenizer.pickle         # Tokenizer for text processing
│── training.ipynb           # Notebook for training and saving the model
│── word_app.py              # Streamlit app for prediction
│── screenshots/             # Folder containing website screenshots
│── README.md                # Documentation (this file)
```

---

## 🛠 Installation & Setup

1️⃣ **Clone the Repository:**
```bash
git clone https://github.com/your-username/word_prediction.git
cd word_prediction
```

2️⃣ **Create a Virtual Environment (Optional but Recommended):**
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3️⃣ **Install Dependencies:**
```bash
pip install -r requirements.txt  # Create this file if needed
```

4️⃣ **Run the Streamlit App:**
```bash
streamlit run word_app.py
```

---

## 🏗 Training the Model
If you want to train the model from scratch, open `training.ipynb` and run all the cells. The notebook includes:
- Data preprocessing
- Tokenization
- LSTM model training
- Saving the trained model and tokenizer

---

## 📊 How It Works
1. Enter a partial sentence (e.g., *"To be or not to"*).
2. Click **"Predict Next Word"**.
3. The model suggests the next most likely word.

---

## 🖼 Screenshots
Here are some previews of the Streamlit web app:

![Screenshot 1](screenshots/screenshot1.png)
![Screenshot 2](screenshots/screenshot2.png)

*(Add more screenshots as needed)*

---

## 📌 To-Do List
- [ ] Improve model accuracy with larger datasets.
- [ ] Deploy online using **Streamlit Cloud** or **Hugging Face Spaces**.
- [ ] Enhance UI/UX of the web app.

---

## 🤝 Contributing
Feel free to fork this repo, improve it, and submit a pull request!

---

⭐ **If you found this project useful, give it a star!** ⭐

