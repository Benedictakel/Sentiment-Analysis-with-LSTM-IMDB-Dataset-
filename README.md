# 🎬 Sentiment Analysis with LSTM (IMDB Dataset)

This project implements an **LSTM-based deep learning model** to perform **sentiment analysis** on movie reviews from the IMDB dataset, classifying them as **positive or negative**.



## 📑 Table of Contents

* [Introduction](#introduction)
* [Dataset](#dataset)
* [Model Architecture](#model-architecture)
* [Technologies Used](#technologies-used)
* [Installation](#installation)
* [Usage](#usage)
* [Project Structure](#project-structure)
* [Results](#results)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)



## 📝 Introduction

**Sentiment analysis** is a key NLP task with applications in product reviews, social media monitoring, and customer feedback analysis. This project trains an **LSTM (Long Short-Term Memory) network** to classify IMDB movie reviews as positive (1) or negative (0), learning from the sequence of words in each review.



## 📚 Dataset

* **Dataset:** [IMDB Large Movie Review Dataset]()
* **Description:** 50,000 movie reviews, equally divided into 25,000 for training and 25,000 for testing, with binary sentiment labels:

  * **0:** Negative
  * **1:** Positive



## 🏗️ Model Architecture

* **Embedding Layer:** Converts words to dense vectors
* **LSTM Layer:** Captures sequential dependencies in text data
* **Dense Layer:** Final output layer with Sigmoid activation for binary classification

The architecture enables the model to learn contextual representations of words for accurate sentiment classification.



## ✨ Features

✅ Data loading and preprocessing (tokenization, padding)

✅ LSTM-based neural network model

✅ Binary classification (positive or negative sentiment)

✅ Model evaluation with accuracy and loss plots

✅ Prediction on custom user-inputted reviews



## 🛠️ Technologies Used

* **Python 3**
* **TensorFlow / Keras**
* `numpy`
* `matplotlib`
* `seaborn`
* **Jupyter Notebook**



## ⚙️ Installation

1. **Clone the repository**

```bash
git clone https://github.com/yourusername/Sentiment-Analysis-with-LSTM-IMDB-Dataset.git
cd Sentiment-Analysis-with-LSTM-IMDB-Dataset
```

2. **Create and activate a virtual environment (optional)**

```bash
python -m venv venv
source venv/bin/activate  # For Linux/Mac
venv\Scripts\activate     # For Windows
```

3. **Install dependencies**

```bash
pip install -r requirements.txt
```

4. **Launch Jupyter Notebook**

```bash
jupyter notebook
```



## ▶️ Usage

1. Open `Sentiment_Analysis_LSTM_IMDB.ipynb` in Jupyter Notebook.
2. Run cells sequentially to:

   * Import libraries and load the IMDB dataset
   * Preprocess text (tokenize and pad sequences)
   * Build and compile the LSTM model
   * Train the model and visualize accuracy and loss
   * Evaluate the model on test data
   * Make predictions on custom input reviews



## 📁 Project Structure

```
Sentiment-Analysis-with-LSTM-IMDB-Dataset/
 ┣ data/
 ┃ ┗ (IMDB dataset downloaded via Keras)
 ┣ Sentiment_Analysis_LSTM_IMDB.ipynb
 ┣ requirements.txt
 ┗ README.md
```



## 📈 Results

* **Test Accuracy:** *e.g. 87% (sample value)*
* **Loss:** *e.g. 0.30 (sample value)*


The model accurately classifies movie reviews as positive or negative, demonstrating the capability of LSTM networks in NLP tasks.



## 📊 Example Prediction

```python
review = "The movie was fantastic! Brilliant acting and a thrilling plot."
prediction = model.predict(preprocess(review))
print("Positive" if prediction > 0.5 else "Negative")
```



## 🤝 Contributing

Contributions are welcome to:

* Improve model performance with **Bidirectional LSTM or GRU layers**
* Add attention mechanisms for interpretability
* Deploy as an API for web or mobile sentiment analysis integration

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add YourFeature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a pull request



## 📄 License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.



## 📬 Contact

**Ugama Benedicta Kelechi**
[LinkedIn](www.linkedin.com/in/ugama-benedicta-kelechi-codergirl-103041300) | [Email](mailto:ugamakelechi501@gmail.com) | [Portfolio](#)



### ⭐️ If you find this project useful, please give it a star!


