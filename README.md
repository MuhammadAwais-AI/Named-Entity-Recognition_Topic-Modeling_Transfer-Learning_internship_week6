# Week 6: Advanced NLP - Named Entity Recognition, Topic Modeling & Classification

This project is part of my Data Science Internship Week 6.  
I worked on a News Dataset to perform NLP tasks.

## Tasks Completed
1. **Text Preprocessing + NER**: Cleaned text and extracted PERSON, ORG, LOCATION using spaCy
2. **LDA Topic Modeling**: Found 5 topics from 30k+ news articles
3. **Visualization**: Bar Chart for categories + WordCloud for topics
4. **Text Classification**: TF-IDF + Logistic Regression Baseline
5. **Evaluation**: 60% Accuracy + Confusion Matrix

## Project Structure
|-----------notebook
               |-----> Named-Entity-Recognition_Topic-Modeling_Transfer-Learning.
               
|-----------data
              |------> bbc_news_data.
              
|-----------README.md

|-----------requirements.txt


## How to Run
1. `pip install -r requirements.txt`
2. `python -m spacy download en_core_web_sm`
3. Open `notebooks/week6_advanced_nlp.ipynb`

## Results
Achieved 60% accuracy on news category classification using TF-IDF + Logistic Regression.

## Author
Muhammad Awais khan - AI/ML intren
