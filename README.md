# E-commerce Sentiment Analyzer using Hugging Face Transformers

## Introduction

1. Development of high-accuracy sentiment analyzer for e-commerce reviews using **Hugging Face Transformers** and **IMDb 50K Review Dataset** from Kaggle.
2. Sentiment classification of movie/customer reviews in real time using **RoBERTa-based sentiment prediction model**.
3. Design of interactive sentiment prediction app using **Gradio framework**.
4. Sentiment prediction of reviews along with visualization of review data, prediction metrics, and sentiment trends.

---

# Highlights

1. Use of IMDb reviews dataset that contained **50,000 reviews**, half of which were positive while the other half were negative.
2. High accuracy of sentiment classification achieved around **88–92%** using a RoBERTa transformer-based model.
3. Generation of various visualization charts as listed below:

   * Bar graph for review sentiment distribution
   * Word cloud of positive reviews
   * Word cloud of negative reviews
   * Confusion Matrix for sentiment classification
   * Confidence score distribution of predictions made
4. Processing and analysis of more than **500 samples** of reviews for evaluation.
5. Creation of web application using **Gradio framework** for sentiment prediction of e-commerce reviews.
6. High accuracy transformer-based architecture of neural network with the ability to understand the context of the review with confidence scores greater than **95%**.

---

# Technologies Used

1. Python
2. Hugging Face Transformers
3. RoBERTa large transformer-based model
4. Gradio
5. Pandas
6. Matplotlib
7. Seaborn
8. WordCloud
9. Sklearn
10. Pytorch

---

# Working Methodology

## Step 1: Collecting Data

1. Importing of the IMDb 50k reviews dataset from Kaggle.
2. Loading of review texts and sentiment labels using pandas library.

---

## Step 2: Data Visualization

1. Plotting bar graphs to see the count of positive vs negative reviews
2. Generating word clouds for:

   * Positive reviews
   * Negative reviews

---

## Step 3: Transformer-based Sentiment Analysis

1. Loading the pretrained RoBERTa-based sentiment model from Hugging Face.

   ```python
   siebert/sentiment-roberta-large-english
   ```

2. Using Hugging face transformers to perform sentiment analysis on the text.

3. Processing of review text up to **512 tokens**.

4. Predicting the following outputs:

   * sentiment
   * confidence

---

## Step 4: Evaluating Model Performance

1. Performing the analysis of around **500 random IMDb reviews** using the model.
2. Computing of following metrics:

   * Accuracy
   * Precision
   * Recall
   * F1 Score
3. Creating a confusion matrix to plot classification results.

---

## Step 5: Creating Gradio Web App

1. Building interactive Gradio application to predict sentiment of input review in real time.
2. Ability to input review text by the user and generating positive/negative sentiment prediction along with confidence percentage in real time.
3. Hosting of web app publicly using following python code:

   ```python
   app.launch(share=True)
   ```

---

# Results

1. High accuracy sentiment classification obtained around **90% overall accuracy**.
2. High confidence predictions obtained where confidence scores were greater than **90-99%** in most cases.
3. Real-time analysis of both types of customer/movie reviews was successfully done.
4. Effective NLP visualizations generated for review sentiment analysis.
5. RoBERTa transformer architecture outperformed TF-IDF-based approaches with respect to contextual understanding.

---

# Possible Applications

1. Analysis of customer review in e-commerce
2. Customer feedback analysis
3. Online reputation management
4. Analysis of social media sentiments
5. Classification of movie reviews/entertainment review sites
6. Business Intelligence systems
7. Monitoring brand sentiment
8. Opinion mining systems
9. AI-driven recommendation engine
10. Live chat integration with NLP transformer

---

# Future Scope

1. Integration with multilingual transformers for multiple languages.
2. Use of Streamlit/Hugging face Spaces for deployment.
3. Adding new categories to sentiment labels like:

   * Happy
   * Angry
   * Neutral
   * Sad
4. Integration with live API's of Amazon, Flipkart, and Twitter review site.
5. Training and fine-tuning own transformer-based architecture for domain specific sentiment prediction.
6. Aspect based sentiment analysis for reviews.

---

# Conclusion

1. A transformer-based sentiment prediction model was designed and developed with ability to perform real-time prediction.
2. Various NLP architectures, visualization libraries, and Gradio framework was integrated to create a robust AI solution.
