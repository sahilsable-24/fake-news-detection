# Fake News Detection

A machine learning project that detects fake news using various
classification algorithms. This repository includes: - A dataset
(`fake_news_data.csv`) - A Jupyter notebook for model training and
evaluation (`Fake_News_Detection.ipynb`) - Preprocessing steps, feature
extraction, and performance analysis

## 📁 Project Structure

    ├── Fake_News_Detection.ipynb   # Main Jupyter notebook
    ├── fake_news_data.csv          # Dataset used for training/testing
    ├── README.md                   # Project documentation

## 🚀 Features

-   Text preprocessing (cleaning, tokenization, stopword removal)
-   TF-IDF vectorization
-   Machine learning models:
    -   Logistic Regression
    -   Support Vector Machine (SVM)
-   Accuracy, confusion matrix, and classification report

## 🧠 How It Works

1.  The dataset is loaded and cleaned.
2.  Text is converted into numerical form using TF-IDF.
3.  The dataset is split into training and testing sets.
4.  Multiple machine learning models are trained.
5.  Model performance is compared.

## 🛠️ Requirements

Install required libraries:

``` bash
pip install numpy pandas scikit-learn matplotlib
```

## 📊 Results

The notebook evaluates all models and prints: - Accuracy score -
Precision, recall, F1-score - Confusion matrix

## ▶️ Running the Project

1.  Clone the repository:

``` bash
git clone https://github.com/sahilsable-24/fake-news-detection.git
```

2.  Open the notebook:

``` bash
jupyter notebook Fake_News_Detection.ipynb
```

## 🤝 Contributing

Pull requests are welcome!

## 📜 License

MIT License
