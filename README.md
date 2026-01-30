# Slogan Generation and Industry Classification

This project applies **neural network–based natural language processing (NLP)** techniques to build two complementary models: a slogan generator and an industry classifier. Using a dataset of business slogans and their associated industries, the project explores how sequence models can both **generate text** and **infer meaning from text**. The focus of the project is on **clear structure, modular design, and interpretability**, with an emphasis on building functional models before progressing to more advanced optimisation.

![LSTM architecture diagram](lstm.png)

*Image source: “LSTM Networks – A Detailed Explanation”, Towards Data Science.*

---

### What’s in this repository

- **Jupyter Notebook:** complete capstone implementation (`neural_network_slogan.ipynb`)  
- **Images:** visuals and reviewer feedback  
- **Dataset:** `slogan-valid.csv`  
- **Requirements:** Python dependencies (`requirements.txt`)  

---

### Project Context

This capstone task focused on applying **sequential modelling techniques to a natural language processing problem**, providing experience with real-world NLP workflows.

The objective was to design a system capable of:

- generating business slogans based on industry category  
- predicting the industry of a business given its slogan  
- combining both models to evaluate whether generated slogans could be correctly classified  

The project required careful preprocessing, modular code design, and clear documentation throughout.

---

### Approach Overview

- Text cleaning and preprocessing  
- Tokenisation and sequence encoding  
- Vocabulary construction and indexing  
- Development of two neural network models:
  - slogan generation model  
  - slogan classification model  
- Modular function design for reuse and clarity  
- Evaluation of generated text and classification behaviour  
- Comparative analysis of generator and classifier outputs  

---

### Key Insights / Findings

- Functional slogan generation was achieved once stable preprocessing and tokenisation pipelines were in place.  
- Classification performance demonstrated that industry-related linguistic patterns were being learned, even with limited training.  
- Generated slogans were often syntactically plausible but semantically inconsistent, highlighting the challenges of small NLP datasets.  
- Passing generated slogans back through the classifier provided useful insight into where generative and discriminative models diverge.  

The project intentionally prioritised **correct structure and end-to-end functionality** over extensive optimisation.

---

### Endorsement

Reviewer feedback highlighted the **high quality and professionalism of the submission**, with particular praise for:

- **Highly readable code** with clear, descriptive variable naming  
- Strong adherence to **clean coding conventions**  
- Effective use of **modular functions** that promote reuse and maintainability  
- Inclusion of **docstrings** explaining function purpose, parameters, and outputs  
- Thoughtful organisation that makes the notebook easy to debug, extend, and maintain  

Overall feedback described the work as **clean, thoughtful, and well-structured**, noting that it demonstrates strong development habits and attention to long-term maintainability.

---

### Current Limitations and Next Steps

While both models are fully functional, performance remains limited by:

- minimal hyperparameter tuning  
- constrained training time  
- dataset size  

A logical next phase would involve a **systematic hyperparameter tuning exercise**, exploring embedding dimensions, sequence length, batch size, and model depth to improve both generation quality and classification accuracy.

These improvements were noted but intentionally not implemented in this iteration.

---

### Skills Demonstrated

**Analysis**
- Text preprocessing and tokenisation  
- Interpretation of model outputs  

**Modelling**
- Neural networks for NLP  
- Sequence-based text generation  
- Text classification models  

**Evaluation**
- Qualitative assessment of generated text  
- Comparative analysis between generator and classifier  

**Tools**
- Python  
- TensorFlow / Keras  
- NumPy  
- pandas  
- Jupyter Notebook  

---

### Requirements / How to Run

Install the required Python dependencies using `requirements.txt`.

---

### Additional reading

The following article was particularly helpful in understanding Long Short-Term Memory (LSTM) architectures and informed both model design and interpretation:

LSTM Networks – A Detailed Explanation, Towards Data Science
https://towardsdatascience.com/lstm-networks-a-detailed-explanation-8fae6aefc7f9/

The architecture diagram used above (lstm.png) is sourced from this article.

---

### Why this project belongs in my portfolio

This project demonstrates my ability to design, structure, and document a complete neural network–based NLP system. Rather than focusing solely on performance metrics, the emphasis is on clean architecture, modular design, and interpretability, reflecting how machine learning systems are developed and maintained in practice.

It complements my earlier deep learning work by extending neural networks into text-based modelling, while also showing awareness of the iterative nature of NLP development.


