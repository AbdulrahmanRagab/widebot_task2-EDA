1-Tasks
Data Concatenation: Combine data from multiple sources related to arts and culture, media, and sports.
Data Selection: Choose relevant features and labels for topic classification.
Topic Selection: Select topics "Art & Culture," "Media," and "Sports" for classification.
Data Preprocessing: Prepare the data for model training by performing tokenization, stop word removal, etc.
Data Filtering: Reduce the dataset size while maintaining its diversity and representativeness.
Data Shuffling: Randomize the order of samples in the dataset.
Model Creation: Build a machine learning model for topic classification.
Model Training: Train the model on the preprocessed and shuffled data.
Model Evaluation: Assess the model's performance using appropriate evaluation metrics.


-- ploted numeric values to check distribution


-- Word Frequency Analysis
As part of the data exploration and preparation process, I performed a Word Frequency Analysis on the text data in the dataset. Word Frequency Analysis helps us understand the distribution of words and their occurrences within the text, providing valuable insights into the most common words used in each topic category ("Art & Culture," "Media," and "Sports").

Methodology
Tokenization: The text data was tokenized, i.e., broken down into individual words or tokens.

Stop Words Removal: Common stop words such as "the," "is," "and," etc., were removed from the tokenized data. Stop words are words that do not add much meaning to the text and are often removed in text analysis to focus on the significant words.

Word Count Calculation: We calculated the frequency of each word in the text data to determine how often each word appears.


-- Text Cleaning Process
The text cleaning process involved the following steps:

Removing Special Characters: We removed any special characters, symbols, or punctuation marks from the text data. These characters may not contribute significantly to the text's meaning and can be safely removed.

Converting to Lowercase: We converted all the text to lowercase to ensure that words are not treated differently based on their casing during analysis.

Tokenization: The text was tokenized, which means breaking down the text into individual words or tokens. This allows us to analyze the text on a word-by-word basis.

Stop Words Removal: Common stop words such as "the," "is," "and," etc., were removed from the tokenized text. Stop words are often removed to focus on the more meaningful words during analysis.

Lemmatization or Stemming (Optional): Depending on the specific requirements of the analysis, we might have applied lemmatization or stemming to reduce words to their base or root form. This step can help in standardizing the text and grouping similar words together.


-- N-gram Analysis
In the N-gram analysis, we considered various values of N (such as unigrams, bigrams, trigrams, etc.) to capture different word sequences


-- As part of the data preprocessing and analysis, I calculated the number of characters in each comment, excluding spaces. This metric helps us understand the length of each comment and provides insights into the distribution of comment lengths within the dataset.

Methodology
Text Preprocessing: Before counting the characters, we preprocessed the text data by removing any leading or trailing spaces to ensure accurate character count.

Character Count: I then calculated the number of characters in each comment, excluding spaces. This was achieved by counting the number of non-space characters in the comment string.


-- howing the most common words for each topic class is a valuable step in understanding the dominant themes and content within each category. This analysis provides insights into the key words that distinguish one topic class from another and can aid in feature selection for the topic classification model.

Methodology
Topic Labeling: Before identifying the most common words for each topic class, we labeled the comments in the dataset according to their respective topics ("Art & Culture," "Media," and "Sports").

Text Preprocessing: We preprocessed the text data by cleaning the comments and removing stop words, as described earlier.

Word Frequency Calculation: We calculated the frequency of each word in the comments belonging to each topic class.

Most Common Words: We identified the most common words for each topic class based on their frequency. These words are the ones that appear most frequently in the comments of a specific topic class compared to others.