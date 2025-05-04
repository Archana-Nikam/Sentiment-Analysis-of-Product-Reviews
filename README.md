
# Sentiment Analysis of Amazon Product Reviews

This project performs sentiment analysis on Amazon product reviews using Python. It includes end-to-end data preprocessing, sentiment classification using TextBlob, and basic data analysis for insights into customer opinions.

---

## Project Notebook

View the full notebook here:  
[Sentiment Analysis.ipynb](https://github.com/Archana-Nikam/Sentiment-Analysis-of-Product-Reviews/blob/main/Sentiment%20Analysis.ipynb)

---

## Dataset

- **Source**: Amazon product reviews dataset (CSV format)
- **Columns Used**: 
  - `reviewText` — actual customer review
  - `overall` — star rating
  - `reviewTime` — date of the review
  - `reviewerName` — name of reviewer (optional for analysis)

---

## Project Goals

- Preprocess raw text data (cleaning, tokenization, stopword removal)
- Analyze word frequencies using NumPy and collections
- Visualize sentiment distribution
- Compare predicted sentiment with actual star ratings
- Build an interpretable pipeline using Pandas, NLTK, TextBlob

---

## Technologies Used

- Python 3
- Pandas — data handling
- Matplotlib / Seaborn — visualizations
- TextBlob — sentiment analysis
- NLTK — stopwords removal
- NumPy — array and frequency operations
- Jupyter Notebook — development and presentation

---

## How It Works

1. **Data Cleaning**  
   - Remove null or duplicate reviews
   - Retain essential columns (`reviewText`, `overall`, etc.)

2. **Text Preprocessing**  
   - Convert to lowercase
   - Remove punctuation and numbers
   - Remove stopwords using NLTK

3. **Tokenization & Word Frequency**  
   - Tokenize each review
   - Count most common words in each sentiment class

4. **Sentiment Classification**  
   - Use `TextBlob` polarity to label each review as:
     - Positive
     - Neutral
     - Negative

5. **Visualization & Analysis**  
   - Plot sentiment distribution
   - Display top words per sentiment
   - Compare predicted sentiment with actual `overall` rating

---

## Sample Output

- Sentiment distribution bar chart
- Top 10 most common words
- Optional comparison: Sentiment vs Star Rating

---

## Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/Archana-Nikam/Sentiment-Analysis-of-Product-Reviews.git
cd Sentiment-Analysis-of-Product-Reviews
