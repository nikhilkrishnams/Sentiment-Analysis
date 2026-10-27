# Sentiment-Analysis

Emotion Classification

Loading and Preprocessing

I loaded the dataset and cleaned the text by converting it to lowercase removing special charactersand filtering out stopwords

Cleaning: Removes unnecessary characters like punctuation from the text

Stopwords Removal: Removes common words like the is and and to focus more on useful words

Tokenization: Splits the text into individual words for further processing

These steps help reduce unwanted words and make the text easier for the models to process.

Feature Extraction

I used TfidfVectorizer to convert the cleaned text into numerical features. TF-IDF (Term Frequency-Inverse Document Frequency) gives more importance to words based on how frequently they appear in a text compared to other texts in the dataset.

Model Development & Evaluation

I trained two models Naive Bayes and Support Vector Machine (SVM) for emotion classification.

Naive Bayes is a simple and fast model, while SVM works well with text data having many features.

I compared both models using Accuracy and F1-score.

Naive Bayes gave an accuracy of 89.81%, while SVM gave 93.94%. The F1-score was also higher for SVM.

From the results, SVM performed better than Naive Bayes in classifying the emotions.
