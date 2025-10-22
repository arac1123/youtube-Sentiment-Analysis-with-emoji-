# youtube-Sentiment-Analysis-with-emoji-
(bert deberta)
- This project explores how emoji sequences and their positions in text affect sentiment analysis of social media comments.
= We focus on YouTube comments that contain at least two consecutive emojis and investigate how emoji semantics and placement influence model performance.
= Our framework enhances traditional sentiment analysis models (BERT, RoBERTa, DeBERTa) by integrating emoji2vec embeddings and positional features, achieving better understanding of complex emotional expressions.

## Method
- Pretraining on ELCo
  - Masked Language Modeling on emoji–text pairs
  - Learn semantic relationships between emoji sequences and phrases.
- Textual Entailment Pretraining
  - Construct premise–hypothesis pairs from real YouTube comments
  - Train the model to recognize whether an emoji combination matches the sentence emotion.
- Fine-tuning for Sentiment Classification
  - Use Kaggle YouTube Comments dataset
  - Add emoji2vec embeddings and emoji position as features.

## 🧠 Models Used
- Bert
- Roberta
- Deberta

## Result
<img width="899" height="374" alt="image" src="https://github.com/user-attachments/assets/63a6d304-8c03-42f9-b8c5-e0a3547cae36" />
