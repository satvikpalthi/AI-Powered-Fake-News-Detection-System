# 🤖 AI-Powered Fake News Detection System

## 📌 About the Project

The **AI-Powered Fake News Detection System** is a Python-based Artificial Intelligence and Machine Learning project designed to identify and classify news articles as **REAL or FAKE**.

The system uses Natural Language Processing (NLP) techniques to analyze news content and a trained Machine Learning model to predict whether the information is potentially misleading or genuine.

The main goal of this project is to demonstrate how AI and Machine Learning can be used to analyze information and help people become more aware of fake news.

## 🎯 Objectives

- Detect potentially fake news articles.
- Classify news as REAL or FAKE.
- Apply Machine Learning algorithms to text classification.
- Understand Natural Language Processing (NLP).
- Develop a practical AI-based application.

## ✨ Features

- 📰 Real and Fake News Classification
- 🧠 Machine Learning-Based Prediction
- 🔍 Natural Language Processing
- 📊 Dataset Processing and Analysis
- ⚡ Automated News Detection
- 💻 Interactive User Interface
- 📈 Model Training and Evaluation

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Main Programming Language |
| Pandas | Data Handling |
| NumPy | Numerical Operations |
| Scikit-learn | Machine Learning |
| NLP | Text Processing |
| Streamlit | Web Interface |
| Pickle | Model Storage |

## ⚙️ How It Works

1. The user enters a news headline or article.
2. The system processes the text.
3. NLP techniques convert the text into numerical features.
4. The trained Machine Learning model analyzes the features.
5. The system displays a prediction: REAL or FAKE.

## 📂 Project Structure

```text
AI-Fake-News-Detection/
│
├── app.py
├── train.py
├── requirements.txt
├── README.md
│
├── dataset/
│   └── news.csv
│
├── models/
│   └── fake_news_model.pkl
│
└── utils/
    └── preprocessing.py
```

## 🚀 Installation and Setup

### 1. Clone the Repository

```bash
git clone YOUR_REPOSITORY_URL
```

### 2. Open the Project Folder

```bash
cd AI-Fake-News-Detection
```

### 3. Install Required Libraries

```bash
pip install -r requirements.txt
```

### 4. Train the Machine Learning Model

```bash
python train.py
```

### 5. Run the Application

```bash
streamlit run app.py
```

## 📊 Expected Output

The system will display one of the following predictions:

- ✅ REAL NEWS
- ❌ FAKE NEWS

*Predictions depend on the quality of the training dataset and model. They are not a substitute for independent fact-checking.*

## 🎓 Learning Outcomes

- Understanding Artificial Intelligence and Machine Learning.
- Working with real-world text datasets.
- Learning NLP and text preprocessing.
- Training and evaluating classification models.
- Building Python-based AI applications.

## 🔮 Future Improvements

- Improve prediction accuracy using larger datasets.
- Support multiple languages.
- Add a news credibility analysis feature.
- Develop a more advanced web interface.
- Integrate additional Machine Learning algorithms.

## 👨‍💻 Author

**Satvik Palthi**

AI & Machine Learning Project

## ⭐ Support

If you find this project interesting, consider giving this repository a ⭐ star!

---

**Disclaimer:** This project is developed for educational and research purposes. Model predictions may be incorrect and should not be treated as definitive verification of news authenticity.
