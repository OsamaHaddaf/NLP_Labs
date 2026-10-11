# NLP Labs

Jupyter notebooks for a Natural Language Processing course, with all lab tasks completed and executed.

| Lab | Topic | What it covers |
|---|---|---|
| [Lab 1](NLP_Lab1) | Introduction to NLP | What NLP is, why it's hard, the NLP pipeline; loading and exploring the IMDB 50K reviews dataset. |
| [Lab 2](NLP_Lab2) | Text pre-processing & regex | Regular expressions, tokenization, stemming, lemmatization, stop words. Tasks: hashtag analysis of Apple tweets, `re.compile`, `re.split`, spaCy vs NLTK tokenization. |
| [Lab 3](NLP_Lab3) | N-grams | Unigrams/bigrams/trigrams, padding, MLE language models, perplexity. Task: clean ~200K Pakistani tweets, train a bigram model and generate tweets. |
| [Lab 4](NLP_Lab4) | Classification & evaluation | Sentiment analysis with TF-IDF + SVM. Task: Amazon phone reviews with TF-IDF + Naive Bayes (85% accuracy) and a confusion matrix. |
| [Lab 5](NLP_Lab5) | Text representation | TF-IDF, cosine similarity, Word2Vec. Task: Word2Vec on The Simpsons scripts (`most_similar`, `doesnt_match`). |
| [Lab 6](NLP_Lab6) | Deep learning for NLP | PyTorch neural network for Yelp review sentiment. Task: Word2Vec features with a 128→64→32→1 network (73% accuracy). |
| [Lab 7](NLP_Lab7) | Large Language Models | Decoder-only (DistilGPT-2), encoder–decoder (FLAN-T5) and encoder-only (DistilBERT) models with Hugging Face. |

## Requirements

```bash
pip install nltk spacy gensim emoji kagglehub pandas scikit-learn matplotlib torch transformers sentencepiece
python -m spacy download en_core_web_sm
```

Datasets for Labs 2–4 are downloaded automatically from Kaggle with `kagglehub`; Labs 5 and 6 use the files in their `dataset/` folders.
