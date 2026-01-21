# UNIT 11: Introduction to Natural Language Processing (NLP)

## 11.1 What is NLP?

**Natural Language Processing (NLP)** is a branch of AI and Machine Learning that allows computers to **understand, interpret, and generate human language**.

### Example Applications:

- Chatbots (like Siri, Alexa)  
- Spam detection in emails  
- Sentiment analysis (positive/negative reviews)  
- Language translation (Google Translate)  

---

## 11.2 Challenges in NLP

- Ambiguity in human language  
- Slang, abbreviations, and typos  
- Different languages and dialects  
- Sarcasm and sentiment detection  

---

## 11.3 NLP Workflow

Steps to process and analyze text:

1. **Text Collection** → Gather raw text data  
2. **Text Preprocessing** → Clean and prepare text  
3. **Feature Extraction** → Convert text into numerical form  
4. **Model Training** → Train ML/DL models  
5. **Evaluation** → Evaluate model performance  

---

## 11.4 Text Preprocessing Techniques

### 11.4.1 Tokenization
Split text into words, sentences, or tokens  

**Example:**  
Text: "I love machine learning."
Tokens: ["I", "love", "machine", "learning"]

pgsql
Copy code

### 11.4.2 Stop Words Removal
Remove common words that do not add meaning  

**Example:** "the", "is", "and"

### 11.4.3 Stemming
Reduces words to their root form  

**Example:** "running", "runs" → "run"

### 11.4.4 Lemmatization
Reduces words to dictionary form  

**Example:** "better" → "good"

### 11.4.5 Lowercasing
Convert all text to lowercase for uniformity  

---

## 11.5 Feature Extraction in NLP

Machine learning models require numerical input, so text must be converted.

### 11.5.1 Bag of Words (BoW)
- Represent text as frequency of words  
- Ignores grammar and word order  

### 11.5.2 TF-IDF (Term Frequency – Inverse Document Frequency)
Gives importance to words based on frequency and uniqueness  

**Formula:**  

TF-IDF = TF * log(TotalDocuments / DocumentsContainingTerm)

yaml
Copy code

### 11.5.3 Word Embeddings
- Represent words as **dense vectors**  
- Captures **context and meaning**  

**Popular Methods:**
- Word2Vec  
- GloVe  
- FastText  

---

## 11.6 NLP Tasks

- **Text Classification** – Spam detection, sentiment analysis  
- **Named Entity Recognition (NER)** – Identify names, places, organizations  
- **Part-of-Speech (POS) Tagging** – Identify nouns, verbs, adjectives  
- **Machine Translation** – Translate between languages  
- **Text Summarization** – Generate summaries of text  

---

## 11.7 Applications of NLP

- Chatbots & virtual assistants  
- Email filtering & spam detection  
- Sentiment analysis for social media  
- Automatic translation  
- Question-answering systems  

---

## 11.8 Advantages of NLP

- ✅ Automates text analysis  
- ✅ Can process huge volumes of data  
- ✅ Improves communication with machines  

---

## 11.9 Limitations of NLP

- ❌ Difficult to understand context  
- ❌ Ambiguity and sarcasm  
- ❌ Requires large datasets for accuracy  
- ❌ Language-specific challenges  

---

## 🎯 Exam-Oriented Questions

1. Define NLP.  
2. List common NLP challenges.  
3. Explain **tokenization**, **stemming**, and **lemmatization**.  
4. What is **TF-IDF**?  
5. Name three NLP applications.  
6. Difference between **BoW** and **Word Embeddings**.
