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


Tokens: ['NLP', 'techniques', 'are', ...]/n
After Stopwords: ['NLP', 'techniques', 'used', ...]/n
After Stemming: ['NLP', 'techniqu', 'use', ...]

Task 2:Named Entity Recognition (NER) with SpaCy/n
NER detects entities like people, places, dates./n
Example Sentence:/n
"Barack Obama won the Nobel Peace Prize in 2009."/n
Entities:/n
Barack Obama → PERSON/n
Nobel Peace Prize → WORK_OF_ART/n
2009 → DATE

Task3 : Scaled Dot-Product Attention/n
Steps: Q·Kᵀ → Scale by √d → Softmax → Multiply by V/n
Purpose: Finds how much attention each word should pay to others/n
Result:
Attention Weights: Shows focus of each word/n
Output: Weighted sum of values (V)/n

Task4 : Sentiment Analysis with Transformers/n
Tool: HuggingFace pipeline("sentiment-analysis")/n
Input:/n
"Despite the high price, the MacBook performance is outstanding."/n
Output:/n
Label: POSITIVE/n
Confidence: ~0.999/n

