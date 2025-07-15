# 🎬 Movie Recommender System

This is a content-based Movie Recommender System built with **Python**, **Streamlit**, and **machine learning** techniques. It recommends movies based on similarity with the one selected by the user.

---

## 🚀 Features

- 🔍 Recommends 5 similar movies based on the selected movie
- 🎞️ Displays movie posters using **TMDB API**
- ⚙️ Built using **cosine similarity** on TF-IDF/CountVectorized data
- 📦 Hosted on **Streamlit Cloud**
- 🧠 Trained on a dataset from **Kaggle** (processed and saved using `.pkl` files)

---

## 🛠️ Tech Stack

- Python
- Streamlit
- Scikit-learn
- Pandas, NumPy
- Pickle (for storing preprocessed data)
- Git LFS (for handling large `.pkl` files)

---

## 🧾 Files in This Repository

| File | Description |
|------|-------------|
| `streamlit_app.py` | Main file to run the app |
| `similarity.pkl` | Precomputed cosine similarity matrix (via LFS) |
| `movies_dict.pkl` | Preprocessed movie dataset dictionary |
| `.gitattributes` | Git LFS tracking configuration |
| `requirements.txt` | Python dependencies for deployment |
| `README.md` | Project description |

---

## 🔧 How to Run Locally

### 1. Clone the repository
```bash
git clone https://github.com/sonall99/Movie-Recommender-System.git
cd Movie-Recommender-System
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the app
```bash
streamlit run streamlit_app.py
```


