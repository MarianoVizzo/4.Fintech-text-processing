<div id="header" align="center">
    <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExN3V1Z3RpbDM2OXBubTg4aTJkNWdtMnBqbXFqamI5YWJteW16Nms2NyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/l2SpXaJA67JaSqSxq/giphy.gif" width="400" />
    <h1 align="center"> PROJECT: TEXT PROCESSING WITH K-MEANS, BERT & CLASSIFICATION MODELS </h1>
</div>

---

## A. CHARACTERISTICS OF THE PROJECT

### CONTEXT
- This project applies **Natural Language Processing (NLP)** techniques to analyze a corpus of academic and professional documents related to the Fintech sector.  
- The goal is to **identify, cluster and classify documents** as *relevant* or *irrelevant* for building the theoretical framework of a Master’s Final Project.  
- The focus is on **predicting investment decisions of digital wallet users** in the context of Argentine and Latin American Fintech.

### OBJECTIVES
**1.** Apply clustering techniques (K-Means) to group similar documents.  
**2.** Generate embeddings with **BERT** to capture semantic context.  
**3.** Train and evaluate predictive classification models (Logistic Regression, Random Forest, SVM, Gradient Boosting, KNN).  
**4.** Apply **topic modeling (LDA)** to identify latent themes.  
**5.** Build a methodological pipeline to process text data for research purposes.

---

## B. DATA SETS
- Corpus compiled from reliable sources such as **Google Scholar, ResearchGate, ScienceDirect, Deloitte Insights, PwC, World Bank, IMF**.  
- Data includes **academic papers, reports, and publications** on Fintech, financial inclusion, investment, and machine learning.  
- Documents were downloaded in PDF format and preprocessed into structured DataFrames.

---

## C. PROJECT PIPELINE

<div id="header" align="center">
    <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExem4zamFrZXEydjB5Znk1aXZmOHN2YzRkOXJ1aW84M2d2aTVkMWVoZCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/coxQHKASG60HrHtvkt/giphy.gif" width="300" />  
</div>

**1)** **Exploratory Data Analysis (EDA)**: word frequencies, histograms, length distributions.  
**2)** **Clustering**: TF-IDF vectorization + K-Means to group texts.  
**3)** **Embeddings with BERT**: creation of contextual word vectors.  
**4)** **Classification Models**: Logistic Regression, Random Forest, SVM, Gradient Boosting, KNN.  
**5)** **SMOTE**: balancing classes for better prediction performance.  
**6)** **Topic Modeling with LDA**: extracting latent themes from the corpus.  

---

## D. HOW TO READ/USE THE FILES?

**1)** 📄 **Report (PDF):**  
   `VIZZO_Actividad de Evaluación_Procesamiento de datos de texto.pdf`  
   → Contains the full academic report with analysis, results, and conclusions.

**2)** 💻 **Notebook (Colab):**  
   `TP_Procesamiento_de_textos_Mariano_Vizzo.ipynb`  
   → Contains Python code for preprocessing, clustering, embeddings, training and evaluation.

**3)** ⚙️ **Execution Requirements:**  
   - Python 3.10+  
   - Main libraries: `pandas`, `numpy`, `scikit-learn`, `nltk`, `gensim`, `transformers`, `torch`, `matplotlib`, `seaborn`, `wordcloud`

---

## E. ABOUT THE PROJECT
- Developed as part of the Master’s program in **Financial Data Management and Analysis (UBA)**.  
- Course: *Models Based on Unstructured Data*.  
- Professor: **Dr. Javier Ignacio García Fronti**.  
- Author: **Mariano Vizzo**.  

---
