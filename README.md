# 📧 Spam Text Filtering with Naive Bayes

This project demonstrates how to build a **spam text message classifier** using the **Naive Bayes algorithm**. It leverages natural language processing (NLP) techniques to clean and process text data, and uses machine learning to classify SMS messages as either "spam" or "ham" (not spam).

---

## 📂 Project Structure

- `Spam_Text_Filtering_with_Naive_Bayes_.ipynb`: Main Jupyter Notebook containing the full code for preprocessing, modeling, training, evaluation, and visualization.

---

## 🚀 Features

- Preprocessing of raw SMS text (stopword removal, stemming, tokenization)
- Vectorization using **TF-IDF**
- Classification using **Multinomial Naive Bayes**
- Performance evaluation (accuracy, precision, recall, confusion matrix)
- Visualizations for insights into the dataset and model results

---

## 🧠 Technologies Used

- Python
- Jupyter Notebook
- Pandas
- Numpy
- Matplotlib / Seaborn
- Scikit-learn
- NLTK

---

## 📊 Dataset

The dataset used is a collection of SMS messages labeled as **spam** or **ham**. It contains two columns:

- `label`: The class of the message (spam or ham)
- `message`: The text of the SMS

> Note: The dataset is loaded directly in the notebook and assumed to be in a file named `spam.csv`.

---

## 🧪 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/spam-text-filtering-naive-bayes.git
   cd spam-text-filtering-naive-bayes
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Launch the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

4. Open `Spam_Text_Filtering_with_Naive_Bayes_.ipynb` and run all the cells.

---

## 📈 Results

- Achieved high accuracy in classifying messages
- Clear visualizations of model performance
- Demonstrated effectiveness of simple NLP techniques in spam filtering

---

## 📌 TODO

- Add support for deep learning models (e.g., LSTM)
- Deploy as a web app using Flask/Streamlit
- Add tests and pipeline

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
