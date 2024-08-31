**Sentiment Analysis using Textblob**

**Objective**: Program to takes a text string as input and outputs a message about the sentiment of the text string, whether it’s “Positive”, “Negative” or “Neutral”.
Libraries: Textblob, Pandas

**Textblob**: Textblob is a python library used to process text data. It gives an easy API to perform Natural Language Processing (NLP) tasks i.e., Identifying parts of speech such as nouns, pronouns, verbs; recognizing people, organization names from the text; translates text from one language to other; language recognition and so on.
It performs many operations. Some of them are:
1.	b.sentiment.polarity : It measures the sentiment of a text. Polarity ranges between 0 and 1. If Polarity is less than 0, then text is Negative; Polarity is greater than 0, then text is Positive; Polarity is equal to 0, then text is Neutral.
2.	b.tags: Recognizes parts of speech for each word in sentence.
3.	b.translate(to='es') : Translates to other languages
4.	b.correct() : Correct the spellings
