TASK 1- MOVIE GENRE CLASSIFICATION Goal: Predict movie genres from plot summaries using multi-label classification.

->Steps:
1. Mount Google Drive (Colab)
2. Import Libraries
3. Load Data Files (train_data.txt, test_data.txt, solution.txt)
4. Clean Plot Text (lowercase, remove special chars)
5. Convert Genre Strings to Binary Format using MultiLabelBinarizer
6. TF-IDF Vectorization on Plots
7. Train One-vs-Rest Classifier using Logistic Regression
8. Evaluate on Test Data (accuracy, classification report)
   
->Libraries Used: TfidfVectorizer, LogisticRegression, OneVsRestClassifier, MultiLabelBinarizer, pandas

-> Dataset Link: https://www.kaggle.com/datasets/hijest/genre-classification-dataset-imdb
