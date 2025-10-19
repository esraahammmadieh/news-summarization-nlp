# Automatic News Summarization using NLP

This project compares **Supervised** and **Unsupervised** approaches for **Extractive Text Summarization** of English news articles.

##  Project Overview
With the massive growth of online news, the goal of this project is to develop an **automatic summarization system** that can efficiently extract key information while preserving the main context.

### Approaches Used:
- **Unsupervised:** TextRank, LSA  
- **Supervised:** Logistic Regression, Random Forest

### Dataset:
- **CNN/Daily Mail Dataset** (from Kaggle)
- Contains ~300k English news articles with human-written summaries.

##  Methodology
1. **Text Preprocessing:** Cleaning, stopword removal, tokenization.
2. **Feature Extraction:** Sentence position, length, keyword frequency, etc.
3. **Model Training:** Logistic Regression & Random Forest.
4. **Evaluation:** ROUGE-1, ROUGE-2, ROUGE-L.


##  Conclusion
Supervised learning methods achieved higher accuracy compared to unsupervised ones.  
TextRank and LSA are still useful when labeled data is unavailable.

##  Authors
- **Arwa Zoukar**  
- **Esraa Hammdieh**  
- **Dunia Houri**  
- **Shaimaa Al-Mosly**

_Fifth year - Artificial Intelligence Specialization_  
_Natural Language Processing Course Project_
