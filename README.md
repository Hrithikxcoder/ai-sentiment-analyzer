ML-Based Sentiment Analyzer (Improved Version)
Overview
This project is a medium-level machine learning sentiment analyzer made for the Fundamentals of AI practical.
It classifies sentences into three categories:

Positive
Negative
Neutral
This improved version includes:

Model accuracy calculation
Probability scores for each class
Loop-based user input
Flowchart and architecture diagram
Clean Jupyter Notebook implementation
Features (Updated)
✔️ Machine learning–based sentiment classification
✔️ Uses CountVectorizer (Bag of Words)
✔️ Uses Multinomial Naive Bayes
✔️ Displays probabilities for all classes
✔️ Evaluates accuracy on a small test dataset
✔️ Easy, understandable logic for viva and external exam

Dataset
A custom dataset containing 15 sentences:

5 Positive
5 Negative
5 Neutral
All sentences are manually labeled.

Flow Diagram
┌────────────────────────┐ │ User Input │ │ (Sentence/Statement) │ └────────────┬───────────┘ │ ▼ ┌────────────────────────┐ │ Text Preprocessing │ │ - Lowercasing │ │ - Tokenization │ └────────────┬───────────┘ │ ▼ ┌────────────────────────┐ │ Feature Extraction │ │ CountVectorizer │ │ (Bag of Words Model) │ └────────────┬───────────┘ │ ▼ ┌─────────────────────────┐ │ ML Model Training │ │ Multinomial Naive Bayes │ └────────────┬────────────┘ │ ▼ ┌─────────────────────────┐ │ Prediction │ │ - Sentiment Label │ │ - Class Probabilities │ └────────────┬────────────┘ │ ▼ ┌──────────────────────────┐ │ Output │ │ Positive/Negative/Neutral│ │ + Probabilities │ └──────────────────────────┘

Model Accuracy
A small test dataset was used to check accuracy:

Model accuracy on test set: XX.XX % True labels: [...] Predicted labels: [...]

(Exact accuracy depends on variations.)

Example Output
Enter a sentence: I am happy today

Predicted Sentiment: positive Class probabilities: negative : 0.05 neutral : 0.10 positive : 0.85

How to Run
Install library
pip install scikit-learn

Run the script
python sentiment_analyzer.py

File Structure
ai-sentiment-analyzer/ │ ├── sentiment_analyzer.ipynb ├── sentiment_analyzer.py ├── requirements.txt └── README.md

Screenshots
ai-sentiment-analyzer-test1 ai-sentiment-analyzer-test2 ai-sentiment-analyzer-test3
Author
HRITHIK ROSHAN
B.Tech CSE – Fundamentals of AI ML
