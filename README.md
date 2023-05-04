# a_whatsapp_group_analysis
This repository contains an analysis of a WhatsApp group chat using exploratory data analysis, sentiment analysis, and topic modeling. <br>
The analysis is originally presented in the following article:
https://medium.com/@barklight/cracking-the-conversation-973839be5b88

## Data
The chat data used in this analysis is contained in `whatsapp_chat.txt`
> Please note that the message has been encrypted for privacy reasons.

## Lexicon
* [ID-Stopwords](https://github.com/masdevid/ID-Stopwords) - Used to remove common words that do not contribute to the overall meaning of the messages.
* [InSet (Indonesia Sentiment Lexicon)](https://github.com/fajri91/InSet) - Used to perform sentiment analysis on the messages.
* [Kamus Alay (Colloquial Indonesian Lexicon)](https://github.com/nasalsabila/kamus-alay) - Used to identify and clean up slang words in the messages.
> All the lexicons used in this analysis are specifically designed for handling natural language processing (NLP) tasks in Bahasa Indonesia
