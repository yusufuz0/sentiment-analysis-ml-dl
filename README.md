Sentiment Classification Using Deep Learning and Machine Learning Models 


Technologies Used:

 🐍 Python
 📊 Pandas
 ➗ NumPy
 🔤 re (Regular Expressions)
 🧠 Scikit-learn
 🧪 TensorFlow / Keras
 🤗 Hugging Face Transformers
 💾 joblib
 ☁️ Google Colab
 📁 Google Drive

 
Modeling & Algorithms:

 📉 Logistic Regression
 📊 Naive Bayes
 🔄 LSTM
 🤖 BERT
 📈 TF-IDF
 

In this project, I performed sentiment analysis on a dataset of 40,000 tweets using the Python programming language in the Google Colab environment, integrated with Google Drive. The dataset included three columns: tweet ID, sentiment label, and tweet content. There were 13 different sentiment classes, but some were underrepresented, which negatively affected model performance. To address this, I removed rare classes to create a more balanced dataset.
I used Pandas and NumPy for data cleaning and preprocessing. To reduce noise and remove unnecessary characters from the text, I used the re module. I then converted the text data into numerical vectors using the TF-IDF technique to make it suitable for machine learning models.
For modeling, I first applied classical machine learning models such as Logistic Regression and Naive Bayes. After removing the rare sentiment classes, I observed a significant increase in the accuracy of the Naive Bayes model. Later, I designed an LSTM model using TensorFlow and Keras, which provided better results by capturing the sequential nature of the text. To prevent overfitting, I implemented dropout techniques.
Finally, I trained a BERT model using the Hugging Face Transformers library. In this model, I focused only on the "neutral", "sadness", and "happiness" classes and achieved an accuracy of 68%. Through this project, I gained valuable experience in natural language processing and model training. I improved my skills in critical areas such as data preprocessing, handling imbalanced datasets, and hyperparameter optimization.
