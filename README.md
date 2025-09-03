# Fake News Detection using Machine Learning

##  Overview
This project detects **fake news articles** using **Machine Learning** techniques.  
It applies **Natural Language Processing (NLP)** for text preprocessing and trains models like **Logistic Regression** and **Decision Trees** on a labeled dataset.

---

##  Project Structure
- `fake_News_Detection.ipynb` → Jupyter Notebook with all steps (EDA, preprocessing, modeling).
- `News.csv` → Dataset (if available, otherwise provide Kaggle link).
- `requirements.txt` → List of dependencies.
- `images/` → Visualizations (WordClouds, confusion matrices, etc.).

---

## ⚙ Installation
Clone the repo and install dependencies
```bash
git clone https://github.com/your-username/Fake-News-Detection.git
cd Fake-News-Detection
pip install -r requirements.txt

$$ Dataset

Dataset: Fake News Dataset (Kaggle)

Columns:

  title → Headline of the news

  text → Main article content

  subject → Category of the news

  class → 0 = Fake, 1 = Real

🛠️ Preprocessing

  Removed special characters
  
  Converted to lowercase
  
  Tokenization
  
  Stopword removal
  
  Stemming
  
  TF-IDF Vectorization

🤖 Models Used

  Logistic Regression ✅
  
  Decision Tree Classifier ✅

📈 Results

  Logistic Regression: ~90% accuracy
  
  Decision Tree: ~85% accuracy
  
  Confusion Matrix Example:

🚀 Future Improvements

  Add Random Forest / Naive Bayes / XGBoost
  
  Deploy using Flask / Streamlit
  
  Improve preprocessing (lemmatization, bi-grams)

