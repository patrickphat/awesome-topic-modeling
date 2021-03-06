<div align="center">

# Awesome Topic Modeling
![img](https://user-images.githubusercontent.com/45748186/168281978-755d8647-db3e-4235-a6fd-25dd63faa271.png)

<br>*All methods, libraries and resources for exploring topics from large datasets* ✨

</div>

# 📚 Introduction
Topic Models are a collection of machine learning models that explores topics in a large set of documents 

# 🏛️ Classical Topic Models 
This part includes classical topic models, which heavily based on statistical models and com

- Latent Dirichlet Allocation (LDA) [[Paper](https://www.jmlr.org/papers/volume3/blei03a/blei03a.pdf)] [[Video](http://videolectures.net/mlss09uk_blei_tm/)] [[Article](https://medium.com/analytics-vidhya/topic-modeling-using-lda-and-gibbs-sampling-explained-49d49b3d1045#id_token=eyJhbGciOiJSUzI1NiIsImtpZCI6ImIxYTgyNTllYjA3NjYwZWYyMzc4MWM4NWI3ODQ5YmZhMGExYzgwNmMiLCJ0eXAiOiJKV1QifQ.eyJpc3MiOiJodHRwczovL2FjY291bnRzLmdvb2dsZS5jb20iLCJuYmYiOjE2NTI2ODUwMTMsImF1ZCI6IjIxNjI5NjAzNTgzNC1rMWs2cWUwNjBzMnRwMmEyamFtNGxqZGNtczAwc3R0Zy5hcHBzLmdvb2dsZXVzZXJjb250ZW50LmNvbSIsInN1YiI6IjExODIzMDc2NzA3OTg0Mjk5NzEzMyIsImVtYWlsIjoicGF0cmlja25ld3llbkBnbWFpbC5jb20iLCJlbWFpbF92ZXJpZmllZCI6dHJ1ZSwiYXpwIjoiMjE2Mjk2MDM1ODM0LWsxazZxZTA2MHMydHAyYTJqYW00bGpkY21zMDBzdHRnLmFwcHMuZ29vZ2xldXNlcmNvbnRlbnQuY29tIiwibmFtZSI6IlRydW9uZy1QaGF0IE5ndXllbiIsInBpY3R1cmUiOiJodHRwczovL2xoMy5nb29nbGV1c2VyY29udGVudC5jb20vYS0vQU9oMTRHaTZYTHhURzFhRm9rckhvMGQ3YnIwT0pSZVdKdDdvSVFhQnNuTllvZz1zOTYtYyIsImdpdmVuX25hbWUiOiJUcnVvbmctUGhhdCIsImZhbWlseV9uYW1lIjoiTmd1eWVuIiwiaWF0IjoxNjUyNjg1MzEzLCJleHAiOjE2NTI2ODg5MTMsImp0aSI6IjA1ZWRmZTQ0YWY4YWViNjI1MWQxYmYwOTQwMTFhMTMyMmUyYjRlN2IifQ.F5Tj6EBifpjWZnvCBWxPkXStUR4-6EPxz2WiwNQXH26STbH1Eq6sost2KxkfvjIzA5JgGBeEyjeIWUHuTm2EdUcwfoyF30qaTDKrE6l4XYBTsaNeirMQrvM47yYS7M2Bjso9Ajvi0VVowvD6wFnvBOe0H9VpIr2X3EaxiRDxIeNquxUo5djnD6ZBhMTY5e85ClBlHOEwAvEqsO6NbhTl5sAxaQTL2R1qK7w4SK5Ft4GrUh9O3J1DoY96_4SS7H84BQayNUpqfwx9rZrESQxekgaJzNbLT1QYmD-bx9FExsUbLIDrrYmykIs9C1wlKSDqJU5xc5yesseXOumQNXBSJA)]
- Latent Semantic Analysis (LSA) [[Article](http://lsa.colorado.edu/papers/dp1.LSAintro.pdf)]
- Non-negative Matrix Factorization (NMF) [[Article](https://methods.sagepub.com/base/download/DatasetStudentGuide/non-negative-matrix-factorization-in-news-201://methods.sagepub.com/base/download/DatasetStudentGuide/non-negative-matrix-factorization-in-news-2016)]

# 🤖 Neural Topic Models
This part revolves around topic modelling techniques with the adoption of deep learning models.

- Pre-training is a Hot Topic: Contextualized Document Embeddings Improve Topic Coherence [[Paper](https://aclanthology.org/2021.acl-short.96/)] [[Github](https://github.com/MilaNLProc/contextualized-topic-models)]
- Topic Modeling with Contextualized Word Representation Clusters [[Paper](https://arxiv.org/abs/2010.12626)]
- TopicBERT: Topic-aware BERT for Efficient Document Classification [[Paper](https://arxiv.org/abs/2010.16407)] [[Github](https://github.com/YatinChaudhary/TopicBERT)]
- BERTopic [[Paper](https://arxiv.org/abs/2203.05794)] [[Github](https://github.com/MaartenGr/BERTopic)]

# 🌱 Semi-supervised topic models (SSTM)
SSTM allows users to inject prior knowledge about topics into topic models
- SeededLDA [[Paper](https://www.aclweb.org/anthology/E12-1021.pdf
)] [[Github](https://github.com/koheiw/seededlda)]
- Anchored CorEX [[Paper](https://arxiv.org/pdf/1611.10277.pdf)] [[Github](https://github.com/gregversteeg/corex_topic)]

# ⚡ Dynamic Topic Models (DTM)
DTMs are set of topic models that take into account the evolution of topic through time
- Dynamic Topic Model, David Blei [[Paper](https://dl.acm.org/doi/abs/10.1145/1143844.1143859)] [[Github](https://github.com/blei-lab/dtm)]
- Dynamic Non-negative Matrix Factorization (Dynamic NMF) [[Paper](https://www.cambridge.org/core/journals/political-analysis/article/abs/exploring-the-political-agenda-of-the-european-parliament-using-a-dynamic-topic-modeling-approach/BBC7751778E4542C7C6C69E6BF954E4B)] [[Github](https://github.com/derekgreene/dynamic-nmf)]

# Topic Model Libraries
- OCTIS: Comparing Topic Models is Simple! A python package to optimize and evaluate topic models (accepted at EACL2021 demo track) [[Github](https://github.com/MIND-Lab/OCTIS)]
- Topic modeling using Gensim [[Article](https://www.machinelearningplus.com/nlp/topic-modeling-gensim-python/)]

# Surveys:
- Topic Modelling Meets Deep Neural Networks: A Survey [[Paper](
https://arxiv.org/pdf/2103.00498.pd://arxiv.org/pdf/2103.00498.pdf)]
