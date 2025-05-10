# 🎬 Movie Sentiment Analysis with RNN (IMDB Dataset)

This project implements a Recurrent Neural Network (RNN) using Keras and TensorFlow to perform sentiment analysis on the IMDB movie reviews dataset. It classifies reviews as either **positive** or **negative**, helping understand audience sentiment based on text input.

---

## 🧠 Model Overview

- **Architecture**: Simple RNN layers with embedding
- **Dataset**: IMDB movie reviews (50,000 labeled reviews)
- **Output**: Binary classification (Positive / Negative)
- **Frameworks**: TensorFlow, Keras, NumPy, scikit-learn

---

## 📁 Project Structure

```
RNN_movie_imdb/
│
├── venv/                         # Virtual environment (excluded via .gitignore)
├── main.py                       # Main execution script
├── embedding.ipynb               # Embedding preprocessing & visualization
├── prediction.ipynb              # Prediction testing & analysis
├── rnn_model.ipynb               # Model training notebook
├── rnn_model_imdb.h5             # Saved RNN model file
├── simple_rnn_imdb.h5            # Alternate/simple model version
├── requirements.txt              # Python dependencies
└── .gitignore                    # Git ignore rules
```

---

## 🚀 How to Run

1. **Clone the repository**

```bash
git clone https://github.com/yourusername/RNN_movie_imdb.git
cd RNN_movie_imdb
```

2. **Create a virtual environment**

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. **Install dependencies**

```bash
pip install -r requirements.txt
```

4. **Run the model**

You can run the full model pipeline using the notebook or Python script:

```bash
python main.py
```

Or explore training and predictions in the provided `.ipynb` files.

---

## 📊 Example

> Input:  
> `"This movie was an emotional rollercoaster with stunning performances!"`  
> Output:  
> `Positive (Sentiment Score: 0.93)`

---

## 📦 Dependencies

- `tensorflow`
- `keras`
- `numpy`
- `pandas`
- `scikit-learn`
- `matplotlib`
- `jupyter`

See `requirements.txt` for full list.

---

## 📌 Notes

- The `.h5` model files are saved versions of trained models.
- Virtual environment (`venv/`) is excluded from version control using `.gitignore`.
- This is a basic RNN version — consider upgrading to LSTM or GRU for better performance.

---

## 📜 License

MIT License © [Your Name]
