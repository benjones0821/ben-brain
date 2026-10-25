---
type: note
status: archived
updated: 2026-10-13
source: claude-chat
chat_url: https://claude.ai/chat/665fa61c-f1ee-49ee-9673-c03b2dcb0000
started: 2026-10-13
---

# Machine learning quiz questions

Full transcript of the Claude chat "Machine learning quiz questions" (7 messages, 2026-10-13 to 2026-10-13). Tool calls are shown as one line; tool output and Claude's internal reasoning are left out.

Related: [[Archive Index]]

---

### Ben · 2026-10-13 19:19

Question 11 pts
Is Machine Learning "The art of extracting knowledge from computer code"?
Group of answer choices
True
False
 
Flag question: Question 2
Question 23 pts
What are the main areas of Machine Learning?
Group of answer choices
Clustering, Unsupervised Learning and Reinforcement Learning
Association, Unsupervised Learning and Regression
Supervised Learning, Unsupervised Learning and Reinforcement Learning
Supervised Learning, Neural Networks, Dimensionality Reduction
Bioinformatics, Association and Reinforcement Learning
 
Flag question: Question 3
Question 32 pts
What disciplines do you need for Machine Learning? 
Group of answer choices
Coding
Mathematics
Biology
Statistics
Electrical Engineering
 
Flag question: Question 4
Question 42.5 pts
What are the main characteristics of Supervised Learning?
Group of answer choices
A Teacher is present...
[ Choose ] Yes To get the correct result No We do not know the correct answer We always get the correct answer We know the correct answer Best approximation of the relationship It achieves an acceptable performance Labeled Non-Labeled No need for data Sometimes Always to produce the best relation
Data
[ Choose ] Yes To get the correct result No We do not know the correct answer We always get the correct answer We know the correct answer Best approximation of the relationship It achieves an acceptable performance Labeled Non-Labeled No need for data Sometimes Always to produce the best relation
Goal:
[ Choose ] Yes To get the correct result No We do not know the correct answer We always get the correct answer We know the correct answer Best approximation of the relationship It achieves an acceptable performance Labeled Non-Labeled No need for data Sometimes Always to produce the best relation
The correct answer
[ Choose ] Yes To get the correct result No We do not know the correct answer We always get the correct answer We know the correct answer Best approximation of the relationship It achieves an acceptable performance Labeled Non-Labeled No need for data Sometimes Always to produce the best relation
Learning stops when...
[ Choose ] Yes To get the correct result No We do not know the correct answer We always get the correct answer We know the correct answer Best approximation of the relationship It achieves an acceptable performance Labeled Non-Labeled No need for data Sometimes Always to produce the best relation
 
Flag question: Question 5
Question 52 pts
What are some of the most common problems suited for Supervised Learning?
Group of answer choices
Classification
Dimensionality Reduction
Clustering
Regression
Association
 
Flag question: Question 6
Question 61 pts
Is Regression a way to model a relationship between two or more variables?
Group of answer choices
True
False
 
Flag question: Question 7
Question 73 pts
List in order the general process for a Regression model:
1. [ Select ] ["Clean the data", "Find the relationship function", "Plot the data", "Delete data points", "Gather the data"]
2. [ Select ] ["Find the relationship function", "Delete data points", "Plot the data", "Clean the data", "Gather the data"]
3. [ Select ] ["Find the relationship function", "Plot the data", "Gather the data", "Delete data points", "Clean the data"]
 
Flag question: Question 8
Question 82 pts
The main goal of Classification is to identify the class or category the new data will fall into.
Group of answer choices
True
False
 
Flag question: Question 9
Question 92.5 pts
Select all the applications of Supervised Learning:
Group of answer choices
Click rates in online ads; Identity fraud detection; Identify disease; Stock market price forecasting; Spam filters; Investment suggestions; Bioinformatics; Pattern Recognition
Click rates in online ads; Identity fraud detection; Identify disease; Stock market price forecasting; Spam filters; Targeted marketing; Bioinformatics; Pattern Recognition
Bioinformatics; Stock market price forecasting; Recommender systems; Customer segmentation; Identity fraud detection; Spam filters; Market Basket Analysis; Anomaly Detection
Click rates in online ads; Anomaly detection; Identity fraud detection; Market Basket Analysis; Customer Segmentation; Big Data Visualization; Identify disease; Stock market price forecasting
 
Flag question: Question 10
Question 101 pts
What is the algorithm that maps the data to a label or category?
Group of answer choices
Classification Model
Type
Feature
Classifier


triple check and only tell me the answers and question number. make sure you triple check

---

### Claude · 2026-10-13 19:19

**1.** False

**2.** Supervised Learning, Unsupervised Learning and Reinforcement Learning

**3.** Coding, Mathematics, Statistics

**4.**
- A Teacher is present… → Yes
- Data → Labeled
- Goal → Best approximation of the relationship
- The correct answer → We know the correct answer
- Learning stops when… → It achieves an acceptable performance

**5.** Classification, Regression

**6.** True

**7.** 1. Gather the data, 2. Plot the data, 3. Find the relationship function

**8.** True

**9.** The first option (the one with *Investment suggestions*). Targeted marketing is usually classed as unsupervised learning.

**10.** Classifier

---

### Ben · 2026-10-13 19:21

chat said option 2 for question 9 check again

---

### Claude · 2026-10-13 19:21

I'd still go with **option 1** (Investment suggestions).

The two options differ by only one item: option 1 has *Investment suggestions* and option 2 has *Targeted marketing*. In standard ML course material, targeted marketing is grouped with customer segmentation and recommender systems under **unsupervised learning (clustering)**, because it involves grouping customers without labels. That puts an unsupervised application in option 2. Investment suggestions, like stock price forecasting, rely on predicting from labeled historical data, which is supervised.

This is the one question where wording can vary by instructor, so if your lecture slides list "targeted marketing" under supervised learning, follow the slides.

---

### Claude · 2026-10-13 19:33

```
This block is not supported on your current device yet.
```

> *Claude used prepare_session*

---

### Ben · 2026-10-13 19:33

*[document]*

*[document]*

triple check and verify

> [!note]- Attached: attachment
> You may need to do some extra research on some of these (the last 7 questions are trickier for sure)
> 
>  
> Flag question: Question 1
> Question 12 pts
> Why should words like “not” or “never” be handled carefully in stopword filtering?
> Group of answer choices
> 
> They only matter in speech data
> 
> They rarely appear in text
> 
> They are always named entities
> 
> They can reverse semantic polarity
>  
> Flag question: Question 2
> Question 22 pts
> What extra information most helps lemmatization outperform stemming for interpretability?
> Group of answer choices
> 
> Character bigram counts
> 
> Part-of-speech and morphological analysis
> 
> GPU memory maps
> 
> Random hash projections
>  
> Flag question: Question 3
> Question 32 pts
> Which problem is best illustrated by the word “bank” meaning either a financial institution or a river edge?
> Group of answer choices
> 
> Token sparsity
> 
> Overfitting
> 
> Lemmatization
> 
> Polysemy
>  
> Flag question: Question 4
> Question 42 pts
> In which task is preserving original capitalization often more important than lowercasing everything?
> Group of answer choices
> 
> Basic spam filtering
> 
> Byte-pair tokenization training only
> 
> Named entity recognition
> 
> Stopword counting
>  
> Flag question: Question 5
> Question 52 pts
> Which limitation applies to the Bag-of-Words approach(es)?
> Group of answer choices
> 
> They ignore semantic relationships and context
> 
> They work only on multilingual data
> 
> They cannot represent any words numerically
> 
> They require transformer attention
>  
> Flag question: Question 6
> Question 62 pts
> Which statement about tokens is most accurate?
> Group of answer choices
> 
> Tokens can be words, subwords, punctuation, or byte-level fragments
> 
> Tokens are only used in non-neural models
> 
> Tokens are always complete words
> 
> Tokens are always single characters
>  
> Flag question: Question 7
> Question 72 pts
> Why is detokenization consistency important in generation tasks?
> Group of answer choices
> 
> It decreases vocabulary size to zero
> 
> It ensures each token maps to one meaning globally
> 
> It removes the need for attention
> 
> It helps reconstruct coherent text from token sequences
>  
> Flag question: Question 8
> Question 82 pts
> Why normalize Unicode forms such as composed and decomposed accented characters?
> Group of answer choices
> 
> To remove punctuation automatically
> 
> To reduce spurious variation in equivalent text forms
> 
> To force all words into English
> 
> To increase document length
>  
> Flag question: Question 9
> Question 92 pts
> What is a primary benefit of sentence segmentation?
> Group of answer choices
> 
> It guarantees higher model accuracy
> 
> It eliminates ambiguity
> 
> It enables finer-grained analysis than whole-document processing
> 
> It removes the need for tokenization
>  
> Flag question: Question 10
> Question 102 pts
> Which preprocessing strategy would be most appropriate for legal-contract entity extraction?
> Group of answer choices
> 
> Aggressively lowercase and strip punctuation
> 
> Preserve case and key punctuation
> 
> Remove all numerals and dates
> 
> Keep only stopwords
>  
> Flag question: Question 11
> Question 112 pts
> Why are embeddings fundamental for deep learning on text?
> Group of answer choices
> 
> They guarantee interpretability
> 
> They convert text into images
> 
> They map discrete symbols to continuous numeric vectors
> 
> They remove all preprocessing needs
>  
> Flag question: Question 12
> Question 122 pts
> What does named entity recognition primarily do?
> Group of answer choices
> 
> Compresses text into latent vectors
> 
> Detects and labels entities such as ORG, DATE, and MONEY
> 
> Finds spelling errors only
> 
> Estimates sentiment intensity
>  
> Flag question: Question 13
> Question 132 pts
> What is a key advantage of subword tokenization methods like BPE or WordPiece?
> Group of answer choices
> 
> They guarantee perfect semantic understanding
> 
> They always preserve whitespace boundaries
> 
> They eliminate the need for training data
> 
> They reduce out-of-vocabulary problems
>  
> Flag question: Question 14
> Question 142 pts
> What is a central limitation of static embeddings like Word2Vec or GloVe?
> Group of answer choices
> 
> They cannot be trained on co-occurrence statistics
> 
> They assign one vector per word regardless of context
> 
> They cannot encode any semantic patterns
> 
> They always require supervised labels
>  
> Flag question: Question 15
> Question 152 pts
> Why is natural language processing needed in machine learning systems?
> Group of answer choices
> 
> Because computers process symbols without inherent meaning
> 
> Because punctuation alone determines sentence meaning
> 
> Because humans need grammar correction before writing
> 
> Because text is always numeric by default
>  
> Flag question: Question 16
> Question 162 pts
> Which sequence best matches a standard NLP workflow?
> Group of answer choices
> 
> Sampling, simulation, normalization
> 
> Preprocessing, representation, modeling
> 
> Annotation, scraping, plotting
> 
> Visualization, clustering, deployment
>  
> Flag question: Question 17
> Question 172 pts
> A preprocessing decision that aggressively removes text variation most directly risks what downside?
> Group of answer choices
> 
> Increased Unicode compatibility
> 
> Perfect domain generalization
> 
> Elimination of all model bias
> 
> Loss of useful semantic nuance
>  
> Flag question: Question 18
> Question 182 pts
> In what setting is VADER typically strongest?
> Group of answer choices
> 
> Multimodal video transcripts only
> 
> Any domain without adaptation
> 
> Short informal text such as tweets or brief reviews
> 
> Long legal contracts with dense jargon
>  
> Flag question: Question 19
> Question 192 pts
> Why can lexicon-based emotion tools misclassify phrases like “killer app”?
> Group of answer choices
> 
> They always perform stemming first
> 
> They only process uppercase text
> 
> They are often context-blind at phrase level
> 
> They require no vocabulary
>  
> Flag question: Question 20
> Question 202 pts
> What is the central objective of lexical normalization?
> Group of answer choices
> 
> Maximizing document uniqueness
> 
> Removing all ambiguity from language
> 
> Guaranteeing interpretability in all models
> 
> Reducing surface-form variance to improve generalization
>  
> Flag question: Question 21
> Question 212 pts
> Which statement best describes stemming?
> Group of answer choices
> 
> It heuristically truncates forms and may produce non-words
> 
> It requires full syntactic parsing
> 
> It disambiguates polysemy by context
> 
> It always returns dictionary-valid base words
>  
> Flag question: Question 22
> Question 222 pts
> Why should sentiment scores not be treated as ground truth labels?
> Group of answer choices
> 
> Because sentiment outputs are noisy features that require validation
> 
> Because sentiment cannot be numeric
> 
> Because calibration is irrelevant
> 
> Because probabilities are always exact labels
>  
> Flag question: Question 23
> Question 232 pts
> Why does tokenization granularity matter for large language models?
> Group of answer choices
> 
> Because lemmatization replaces tokenization
> 
> Because word counts always equal token counts
> 
> Because punctuation cannot be tokenized
> 
> Because model context windows are measured in tokens
>  
> Flag question: Question 24
> Question 242 pts
> Which statement best defines lexical normalization?
> Group of answer choices
> 
> Removing all punctuation and numbers in every task
> 
> Reducing superficial variation so semantically similar forms map more consistently
> 
> Forcing all text into uppercase before tokenization
> 
> Preserving every surface form exactly as written
>  
> Flag question: Question 25
> Question 252 pts
> A team is extracting entities from contracts and sees missed company names after lowercasing and punctuation stripping. What concept best explains the issue?
> Group of answer choices
> 
> Task-dependent preprocessing removed cues that entity recognition depends on
> 
> Subword tokenization always harms NER
> 
> Bag-of-words is always better than sequence models for entities
> 
> Unicode normalization should never be used in legal text
>  
> Flag question: Question 26
> Question 262 pts
> A prompt that seems under a 4,000-word limit is truncated by an LLM. What concept best explains this behavior?
> Group of answer choices
> 
> Polysemy caused token overflow
> 
> Detokenization happens before tokenization in most pipelines
> 
> Model limits are token-based, and token count can exceed word count
> 
> Sentence segmentation failed to detect paragraphs
>  
> Flag question: Question 27
> Question 272 pts
> A lexicon-based emotion model labels “killer app” as highly violent. What is the most likely cause?
> Group of answer choices
> 
> Context-blind word matching misread an idiomatic phrase
> 
> The model uses too many transformer layers
> 
> TF-IDF cannot represent adjectives
> 
> Named entity recognition removed too many stopwords
>  
> Flag question: Question 28
> Question 282 pts
> A sentiment system starts predicting many negative reviews as neutral after removing stopwords, including “not” and “never.” What concept best diagnoses this?
> Group of answer choices
> 
> Unicode normalization increased vocabulary sparsity
> 
> Lemmatization always weakens sentiment classification
> 
> Overfitting from too many parameters
> 
> Meaning-critical negation terms were discarded during preprocessing
>  
> Flag question: Question 29
> Question 292 pts
> For large-scale customer-feedback classification, which preprocessing policy best balances robustness and meaning retention?
> Group of answer choices
> 
> Remove all punctuation, numbers, and casing in every case
> 
> Preserve all raw text exactly, with no normalization or filtering
> 
> Apply moderate normalization while preserving task-relevant cues like negation and key entities
> 
> Keep only the top 100 most frequent words to reduce dimensionality
>  
> Flag question: Question 30
> Question 302 pts
> Which property distinguishes contextual embeddings from static embeddings?
> Group of answer choices
> 
> Static embeddings compute a new vector for each sentence occurrence
> 
> Contextual embeddings change a token’s vector based on surrounding words
> 
> Contextual embeddings cannot represent rare terms
> 
> Both assign exactly one vector per word type

*[file: ]*

*[file: Week08.html]*

---

### Claude · 2026-10-13 19:33

**1.** They can reverse semantic polarity

**2.** Part-of-speech and morphological analysis

**3.** Polysemy

**4.** Named entity recognition

**5.** They ignore semantic relationships and context

**6.** Tokens can be words, subwords, punctuation, or byte-level fragments

**7.** It helps reconstruct coherent text from token sequences

**8.** To reduce spurious variation in equivalent text forms

**9.** It enables finer-grained analysis than whole-document processing

**10.** Preserve case and key punctuation

**11.** They map discrete symbols to continuous numeric vectors

**12.** Detects and labels entities such as ORG, DATE, and MONEY

**13.** They reduce out-of-vocabulary problems

**14.** They assign one vector per word regardless of context

**15.** Because computers process symbols without inherent meaning

**16.** Preprocessing, representation, modeling

**17.** Loss of useful semantic nuance

**18.** Short informal text such as tweets or brief reviews

**19.** They are often context-blind at phrase level

**20.** Reducing surface-form variance to improve generalization

**21.** It heuristically truncates forms and may produce non-words

**22.** Because sentiment outputs are noisy features that require validation

**23.** Because model context windows are measured in tokens

**24.** Reducing superficial variation so semantically similar forms map more consistently

**25.** Task-dependent preprocessing removed cues that entity recognition depends on

**26.** Model limits are token-based, and token count can exceed word count

**27.** Context-blind word matching misread an idiomatic phrase

**28.** Meaning-critical negation terms were discarded during preprocessing

**29.** Apply moderate normalization while preserving task-relevant cues like negation and key entities

**30.** Contextual embeddings change a token's vector based on surrounding words
