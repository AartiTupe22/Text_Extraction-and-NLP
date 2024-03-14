# Text_Extraction-and-NLP
The OBjective OF this Project is to extract the data From web and and perform text Analysis To compute Variable .

we perform the following Process on extracted data:
Cleaning using Stop Words Lists: Stop words are removed from the text to facilitate sentiment analysis, using predefined lists of common stop words.

Creating a dictionary of Positive and Negative words: A dictionary of positive and negative words is compiled from a master dictionary, excluding stop words.

Extracting Derived variables: Text is tokenized and used to calculate Positive Score, Negative Score, Polarity Score, and Subjectivity Score for sentiment analysis.

Analysis of Readability: Readability is assessed using the Gunning Fox index formula, considering factors like average sentence length and percentage of complex words.

Average Number of Words Per Sentence: The total number of words is divided by the total number of sentences to determine the average number of words per sentence.

Complex Word Count: Words with more than two syllables are counted to assess complexity.

Word Count: Total cleaned words are counted after removing stop words and punctuation.

Syllable Count Per Word: Syllables in each word are counted, handling exceptions like words ending with "es" or "ed".

Personal Pronouns: Personal pronouns such as "I," "we," "my," "ours," and "us" are counted using regex, excluding exceptions like the country name "US."

Average Word Length: The average length of words is calculated by dividing the total number of characters by the total number of words.
