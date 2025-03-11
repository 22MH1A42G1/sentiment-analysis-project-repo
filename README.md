## Sentiment Analysis on Review Dataset  

### Overview  
This project involves analyzing a dataset of customer reviews using Python and various data visualization techniques. The dataset consists of textual reviews and corresponding sentiment labels (1 for positive, 0 for negative). The analysis includes data exploration, handling duplicates, generating a word cloud, and visualizing word frequency.  

### Dataset  
- **File:** `Reviews.csv`  
- **Columns:**  
  - `review`: The textual review provided by the customer.  
  - `class`: Sentiment label (1 = Positive, 0 = Negative).  
- **Total Entries:** 4,321  
- **No missing values or null entries detected.**  

### Features & Analysis  
1. **Data Exploration:**  
   - Display first and last 10 rows of data using `data.head()` and `data.tail()`.  
   - Check data types using `data.info()`.  
   - Identify duplicate entries using `data.duplicated()`.  

2. **Text Analysis & Visualization:**  
   - **Word Cloud:** Generates a word cloud to visualize frequently occurring words in the reviews.  
   - **Word Frequency Bar Chart:** Analyzes the occurrence of selected words (`good`, `great`, `amazing`, `bad`, `not bad`) to understand sentiment distribution.  

### Dependencies  
To run this analysis, install the required Python libraries:  
```bash
pip install pandas seaborn matplotlib wordcloud
```

### How to Use  
1. Load the dataset in Google Colab or a local Jupyter Notebook.  
2. Execute the provided Python script to explore the data and generate visualizations.  
3. Observe insights from the word cloud and frequency analysis to understand customer sentiment.  

### Results & Insights  
- Positive words like **"good"**, **"great"**, and **"amazing"** appear frequently in the dataset.  
- Negative words like **"bad"** occur less often, indicating a generally positive sentiment among the reviews.  
- The word cloud visualization highlights key terms that shape customer opinions.  

### Future Improvements  
- Apply Natural Language Processing (NLP) techniques for deeper sentiment analysis.  
- Implement machine learning models to predict sentiment more accurately.  
- Expand the dataset to analyze trends over time.  

---

**Author:** Indana Aditya  
**LinkedIn:** [Indana Aditya](https://www.linkedin.com/in/aditya-indana-899734216)  
**GitHub:** [Indana Aditya](https://github.com/22MH1A42G1/)