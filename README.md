## 📝 Minutes of Meeting (NLP)
This project demonstrates how to generate concise meeting minutes using Natural Language Processing (NLP). The process involves text summarization, Named Entity Recognition (NER), Part-of-Speech (POS) tagging, and data visualization to understand the structure and semantics of the input text.

## 🚀 Project Overview
Meetings often produce large volumes of textual data, making it crucial to extract key insights effectively. This project utilizes various NLP techniques to:

Preprocess and analyze meeting transcripts

Generate summary content

Extract action items

Visualize distribution of important linguistic features

## 📁 Files and Structure
Minutes_generation.ipynb – Main Jupyter Notebook containing the full pipeline

README.md – Documentation and project overview

data/ – (Optional) Store input files

outputs/ – (Optional) Store outputs like summaries or graphs

## 🔧 Tools & Libraries Used
Python (pandas, NumPy)

NLP Libraries: spaCy, NLTK, gensim, scikit-learn

Visualization: matplotlib, seaborn

Jupyter Notebook

# 📊 Visualizations
## 📈 Graph 1: Distribution of Summary Lengths
Shows how many words are used in generated summaries to gauge their conciseness.

![image](https://github.com/user-attachments/assets/72819b41-98c0-4feb-9708-989572d77d0a)


## 🧠 Graph 2: POS Tag Distribution
Highlights the frequency of different parts of speech in the processed prompts or summaries.

![image](https://github.com/user-attachments/assets/63ce3e21-9960-439b-bbf9-482238a4ec64)


## 🧾 Graph 3: Named Entity Distribution
Shows how often each type of named entity (PERSON, ORG, DATE, etc.) appears in the text.

![image](https://github.com/user-attachments/assets/8b25662a-38b7-483b-b57f-3d52f5549231)


## 🔑 Graph 4: Top Keywords in Summaries
A TF-IDF-based visualization of the most relevant keywords found across all generated summaries.

![image](https://github.com/user-attachments/assets/60de11db-3963-4f36-b96a-94d7ce76b90b)


## ✅ Graph 5: Most Common Action Items
Displays the top 10 recurring action items extracted from the meeting minutes.

![image](https://github.com/user-attachments/assets/f8310c2e-07af-4dee-bf1d-4c71cf17c9dd)



## 🧠 Future Improvements
Deploy via Streamlit for user-friendly access

Add speech-to-text input functionality

Support multilingual minutes generation

Enhance summarization with transformer-based models

