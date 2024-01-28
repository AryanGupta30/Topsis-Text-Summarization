# Topsis-Text-Summarization

In this assignment we had to apply topsis to find the best pre-trained model for Text-Summarization

The dataset was taken from hugging face

The original dataset was having 12500 rows. I reduced the size of rows for the sake of simplicity and reducing training time.

# 4 parameters for Text Summarization

## 1. Bleu Score : 
BLEU, or the Bilingual Evaluation Understudy, is a score for comparing a candidate translation of text to one or more reference translations. Although developed for translation, it can be used to evaluate text generated for a suite of natural language processing tasks.

## 2. Semantic Coherence :
Semantic coherence is maximized when the most probable words in a given topic frequently co-occur together, and it's a metric that correlates well with human judgment of topic quality

## 3.Factual Accuracy :
Information that is factually accurate means that it is free from errors or inaccuracies concerning the details, events, or data presented

## 4.Content Coverage :
Content coverage assesses the extent to which the generated summary covers important information from the dialogue. Higher content coverage indicates better coverage of relevant information.

# 5 Pretrained Model 
1.facebook/bart-large-cnn
2.t5-large
3.sshleifer/distilbart-cnn-12-6
4.google/pegasus-large
5.allenai/led-large-16384-arxiv

# Topsis
The results were stored in evaluation_results.csv

On this csv file Topsis was performed and Models were ranked

The result with topsis was stored in Topsis.csv

The Graph of each model and its topsis score is as follows 

<img width="617" alt="image" src="https://github.com/AryanGupta30/Topsis-Text-Summarization/assets/100289349/f3f346bc-d0ec-4e62-95ad-e4642e48ce20">


