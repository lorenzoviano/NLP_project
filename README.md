# Natural Language Processing Projects

This repository contains six projects, each exploring a major aspect of Natural Language Processing (NLP). The projects are implemented as Jupyter notebooks and provide hands-on demonstrations of key NLP concepts, datasets, and techniques.

## Project Overview

1. **Tokenization and N-gram Language Modelling**  
This project explores foundational text preprocessing, implementing custom tokenizers and constructing word and sentence tokenization pipelines. Using publicly available text corpora, it builds and evaluates statistical language models, including unigram, bigram, and trigram models. Techniques such as Laplace smoothing are applied to mitigate data sparsity, and perplexity is used to measure model performance. 

- *Motivation:* Tokenization and language modeling are essential in applications such as speech recognition, predictive text, and information retrieval.  
- *Techniques & Libraries:* Custom tokenization, NLTK, statistical modeling, Laplace smoothing, perplexity calculation.  
- *Dataset:* Sample news or Wikipedia corpus.

<br>

2. **POS Tagging and Neural Language Modeling**  
   This notebook covers the implementation of rule-based and statistical POS taggers (e.g., using the Viterbi algorithm) and introduces neural language models. The project compares traditional POS tagging methods to modern neural network approaches using Keras or PyTorch, allowing for hands-on experience with sequence prediction.  
   
- *Motivation:* POS tagging underpins syntactic parsing, text-to-speech, and machine translation, while neural language models form the basis for state-of-the-art NLP systems.  
- *Techniques & Libraries:* NLTK, Viterbi decoding, RNNs with Keras/PyTorch.  
- *Dataset:* Annotated POS corpora, such as the Penn Treebank.

<br>

3. **Morphology and Syntax**  
   Focusing on the structure of words and sentences, this project covers stemming, lemmatization, and morphological analysis. It includes parsing tasks using dependency and constituency parsing, extracting grammatical relations and tree structures from raw sentences. 

- *Motivation:* Morphological and syntactic analysis is crucial for applications in grammar checking, machine translation, and information extraction.  
- *Techniques & Libraries:* NLTK or spaCy for parsing, regular expressions for stemming, visualization of parse trees.  
- *Dataset:* Manually constructed sentences or sample sentences from established NLP corpora.

<br>

4. **Semantics and Discourse**  
   This notebook explores the computation of meaning at the word and sentence level, including word sense disambiguation and vector space representations (e.g., word embeddings). It covers semantic similarity computations, as well as basic discourse analysis—such as identifying coreference and coherence relations.  

- *Motivation:* Semantic and discourse analysis power applications like search engines, chatbots, and reading comprehension systems.  
- *Techniques & Libraries:* Word2Vec, spaCy or Gensim for embeddings, cosine similarity, basic coreference algorithms.  
- *Dataset:* Word similarity datasets (e.g., WordSim-353), sample narrative texts.

<br>

5. **Machine Translation**  
   This project implements a basic machine translation pipeline, including data preprocessing, sentence alignment, word/phrase translation modeling, and scoring using BLEU. The project may use parallel corpora, such as aligned English–French sentence pairs, and explores statistical approaches before discussing the limits of rule-based methods.  

- *Motivation:* Machine translation is fundamental to cross-lingual communication, content localization, and international information access.  
- *Techniques & Libraries:* Sentence alignment, statistical translation models, BLEU scoring with NLTK or SacreBLEU.  
- *Dataset:* Parallel corpora (e.g., Europarl or simple sample datasets).

<br>

6. **Question Answering**  
   The final project builds a question answering system that retrieves and extracts answers from text passages. It employs information retrieval techniques (TF-IDF, ranking) and rule-based or basic machine learning methods for answer extraction, with evaluation on sample QA pairs.  

- Motivation:* QA systems drive search assistants, customer support bots, and information retrieval from large documents.  
- Techniques & Libraries:* Scikit-learn for TF-IDF, ranking, simple extraction algorithms.  
- Dataset:* Custom or open-domain question–answer sets.

<br>

---

Each project is self-contained and includes code, detailed explanations, and example outputs to illustrate core NLP principles, with real-world applications and motivation discussed for each task.
