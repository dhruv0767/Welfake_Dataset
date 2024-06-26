### README.md
# Natural Language Processing Project: Fake News Classification

## Project Overview
This project is focused on classifying news articles as "fake" or "real" using various Natural Language Processing techniques. Our goal was to analyze the effectiveness of different NLP models and techniques in distinguishing between authentic and deceptive content. The project includes extensive data preprocessing, feature extraction, model building, and evaluation using a dataset of labeled news items.

## Dataset
The dataset consists of 72,134 news articles categorized into real (35,028) and fake (37,106) news items.

## Key Results
- Best performance achieved with Random Forest using TF-IDF and quantitative linguistic features, achieving 94.4% accuracy.
- Deep Learning models explored include LSTM and BERT-based classifiers.

## Repository Contents
- `NLTK_Feature_Extraction.ipynb` - Feature extraction using NLTK
- `TFIDF_Visualizations.ipynb` - Visualizations using TF-IDF vectorization
- `POS_Featuresets.ipynb` - Part of Speech tagging and analysis
- `IST664_NLP_Final_Report.pdf` - Detailed project report and analysis

## Models and Techniques
- **Vectorization**: Bag of Words, TF-IDF, BERT Embeddings
- **Classifiers**: Naive Bayes, Logistic Regression, Random Forest, SVM
- **Deep Learning**: LSTM, DistilBERT
- **Visualization**: Word clouds, histograms, dimensionality reduction with UMAP and GLoVE

## License
Distributed under the MIT License. See `LICENSE` for more information.

## Acknowledgments
- Dataset provided by Kaggle: [Fake News Classification](https://www.kaggle.com/datasets/saurabhshahane/fake-news-classification)
- IEEE paper on fake news detection that inspired this project: [IEEE Xplore](https://ieeexplore.ieee.org/document/9395133)
