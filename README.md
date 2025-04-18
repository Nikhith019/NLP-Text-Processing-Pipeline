# Neural_Home_Assignment-4

##Student Details

Name : Nikhith Raju Konduru

700# : 700756171

CRN  : 23849

## To run the files clones this repo and run in a python ide with necessary libraries

## Explanation of tasks

Task 1: NLP Preprocessing Pipeline

Steps: Tokenize → Remove Stopwords → Apply Stemming

Example:

Sentence: "NLP techniques are used in virtual assistants like Alexa and Siri."
Tokens: ['NLP', 'techniques', 'are', ...]

After Stopwords: ['NLP', 'techniques', 'used', ...]

After Stemming: ['NLP', 'techniqu', 'use', ...]

Task 2:Named Entity Recognition (NER) with SpaCy

NER detects entities like people, places, dates.

Example Sentence:

"Barack Obama won the Nobel Peace Prize in 2009."

Entities:

Barack Obama → PERSON

Nobel Peace Prize → WORK_OF_ART/

2009 → DATE

Task3 : Scaled Dot-Product Attention/

Steps: Q·Kᵀ → Scale by √d → Softmax → Multiply by V

Purpose: Finds how much attention each word should pay to others

Result:
Attention Weights: Shows focus of each word

Output: Weighted sum of values (V)

Task4 : Sentiment Analysis with Transformers

Tool: HuggingFace pipeline("sentiment-analysis")

Input:

"Despite the high price, the MacBook performance is outstanding."

Output:

Label: POSITIVE

Confidence: ~0.999

