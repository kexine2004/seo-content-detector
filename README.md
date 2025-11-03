pandas: Used for data manipulation, reading CSVs, and creating DataFrames (your main data structure).

numpy: Provides fundamental array and mathematical operations, especially used by scikit-learn and for TF-IDF vector handling.

scikit-learn: The machine learning library you used to create the TfidfVectorizer, calculate cosine_similarity, and train the RandomForestClassifier.

textstat: The library you used to calculate the readability scores (flesch_reading_ease, smog_index).

requests: Used in Cell 8 (Real-Time Demo) to fetch the HTML content from the new URLs.

beautifulsoup4: Used in Cell 2 (Extraction) and Cell 8 to parse the HTML and extract the raw body text.

nltk: The Natural Language Toolkit, specifically needed for sent_tokenize (sentence counting) and for its integration with textstat.

tqdm: Used to display the progress bars (.progress_apply) during the data cleaning and feature engineering steps.
