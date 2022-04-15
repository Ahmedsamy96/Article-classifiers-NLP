 <h1 align="center">🧠🧾 Article classifiers NLP</h1>

<h3 align="left"> End-to-End NLP pipeline for topics classification using deep learning ( LSTM ).</h3>

<p align="left"> In this project, my goal was to make a text classification by representing NLP-pipeline </p>

1. **Project Idea** 🎭: The project idea is to make a web service that is based on a deep learning model trained for text classification, the classification case is to take an Article Topic and classify this Topic into (ART, ECONOMY, SPORTS), this program can be very useful for many purposes in doing Analytics on user interests to improve websites reach and direct it for the convenient slots of users.

2. **Data Source** 📲: In my case, I've decided to use web scapping to create my own dataset which meets my needs, I've targeted a website of a famous Egyptian news newspaper, and I collected from it using Python code all the data needed to train the model so that each category had 10,000 texts to be trained on, with a total dataset of 30,000 rows.

3. **Data Cleaning** 👨‍🦯: At the first of this process, we have 3 csv files each is about 10000 records.
- Concat them into one csv file.
- Drop duplicates if found.
- Remove spaces in the text.

4. **Data Preprocessing** 🔧🧪 : In this step, I have important processes to apply to my dataframe to be ready as an input for the model.
- Remove punctuation
- Convert all texts to be in lower case.
- Use nltk.tokenize for sentences tokenization.
- Remove stopwords from the tokenized text.
- Apply Stemming on the texts.
- Apply Lemmatization to the texts.
- Save the final processed dataframe to be used in the next step of Model Training.

5. **Model Training** 🏃‍♂️: 

<h3 align="left">Tools & Libraries ✂🛒:</h3>
- jupyter Notebook (python 3)
- BeautifulSoup for web scraping
- NLTK for text processing
- LSTM model - Logistic Regression & Naive Bayes
- Flask for Deployment
