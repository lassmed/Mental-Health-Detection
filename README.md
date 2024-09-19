
report : [pfa.pdf](https://github.com/user-attachments/files/17064125/pfa.pdf)
## Social Media Mental Health Detection

This repository contains the implementation of our end-of-year project focused on detecting mental health issues using social media data. The project aims to classify mental health conditions such as depression, anxiety, ADHD, and borderline personality disorder (BPD) based on user-generated content on Reddit.

### Project Overview

Social media platforms like Reddit provide a vast amount of user-generated content, which can be analyzed to gain insights into users' mental health. This project leverages deep learning techniques to identify patterns indicative of mental health conditions. The objective is to develop predictive models that can accurately classify posts into one of the four targeted mental health categories.

### Methodology

- *Data Collection & Preparation*: We used the publicly available "Reddit Mental Health Dataset" which includes posts from various subreddits. The data was preprocessed using standard NLP techniques like tokenization, lemmatization, and removal of stopwords.
- *Modeling Approaches*: We experimented with several deep learning models including CNN, BiLSTM, and hybrid CNN-BiLSTM architectures. Additionally, we implemented transformer models like BERT and RoBERTa to capture the contextual nuances of the text.
- *Evaluation Metrics*: The models were evaluated using accuracy, precision, recall, and F1-score to determine their effectiveness in classifying mental health conditions.

### Key Features

- *CRISP-DM Framework*: The project follows the CRISP-DM methodology, ensuring a structured approach from data understanding to deployment.
- *Advanced NLP Techniques*: Implementation of state-of-the-art NLP techniques including word embeddings, n-gram analysis, and TF-IDF.
- *Deep Learning Models*: Use of multiple deep learning models to analyze textual data and improve detection accuracy.

### Results

Our models demonstrated promising results, with the CNN-BiLSTM model achieving the highest accuracy for most classes. Detailed model performance metrics are provided in the report.

### How to Use

1. Clone the repository.
2. Install the required libraries listed in requirements.txt.
3. Run the Jupyter notebooks in the notebooks directory for data preprocessing, model training, and evaluation.
4. Check the results folder for detailed evaluation metrics and model outputs.

### Conclusion

This project highlights the potential of using deep learning for mental health detection on social media. By identifying early signs of mental health issues, we aim to contribute to better mental health awareness and intervention strategies.

