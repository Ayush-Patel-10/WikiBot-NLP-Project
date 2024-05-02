# WikiBot: Summarizing Wikipedia Articles

## Overview

As you know there are a lot of articles on Wikipedia and they are lengthy, which in turn takes a long time to read. To make it easy for the user to read the relevant context of these articles, we introduce WikiBot. WikiBot leverages Wikipedia's vast information to deliver relevant summaries of the articles quickly. This project uses sophisticated web scraping and natural language processing (NLP) techniques for data extraction and summarization, enhancing how users interact with information. We also made a content-based recommendation mechanism that suggests related articles. 

## Features

### Data Collection
- Scraped and cleaned over 50,000 Wikipedia articles to build a comprehensive dataset for model training.

### Summarization Models
- Implemented various summarization models, including TextRank, LDA, NMF, T5, and BART.
- Achieved a high ROUGE score of 0.88 with our LDA model, demonstrating its effectiveness in distilling essential information.

### Recommending Articles
- We have enhanced WikiBot with a sophisticated recommendation engine that utilizes Latent Dirichlet Allocation (LDA) for topic modeling. This feature identifies key topics within user inquiries and suggests related articles based on the top words from those topics.



