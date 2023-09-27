# Interactive_Question_Answering_Model

Deep analysis and exhuastive research on [question answering model using ensembling techniques][https://scholar.google.com/citations?user=CnED4RIAAAAJ&hl=en]


This paper aims to provide an empirical study and comparative analysis of the well-known Deep Learning Models on the Stanford Question Answering Dataset (SQuAD). Keeping in mind the enormous data in the current times, SQuAD Dataset serves as a benchmark for question answering tasks. It aims to solve the issues pertaining machine comprehension and huge context-based question answering tasks. This is a challenging problem in NLP as it requires the model to understand the context and use its reasoning abilities to accurately respond to questions. In this study, Natural Language Processing, Exploratory Data Analysis and Deep Learning Models like Bidirectional LSTMs (BiLSTM), BERT, DistilBERT, BiDAF, Ensemble Learning, Backpropagation neural networks and Optimization techniques have been incorporated for achieving the highest efficiency. Finally, a comparison of each model’s performance based on evaluation metrics like accuracy, precision and F1-score has been done.





  In this project, we explored different models for question
answering on the Squad dataset, including BiLSTM, BIDAF,
BERT, and DistilBERT. We evaluated these models based on
their EM and F1 scores on the train and validation datasets. The
BIDAF model achieved an F1 score of 0.664 on the validation
dataset, which is the highest among the models we tested. The
BiLSTM model performed the worst, with an F1 score of only
0.239. The DistilBERT model achieved an F1 score of 0.754,
which is also relatively high. The BERT model achieved an F1
score of 0.433 on validation dataset and 0.414 on train Dataset.
We then created an ensembling model that chose the answer
with the best F1 score for each question answer pair. This model 
  achieved an F1 score of 0.912 on the train dataset and 0.898 on
the validation dataset, which outperformed all individual
models when ensembled BiLSTM, BIDAF and BERT.
Our Question Answering Model was successful and gave
accurate results. The results demonstrate that the Squad dataset
may be successfully used to answer questions using the BIDAF,
DistilBERT, and ensembling models. On the other hand, BERT
model needed more training to perform better and BiLSTM
struggled in this task. It's crucial to note that the DistilBERT
model outperformed the BERT model in terms of F1 score and
inference time, making it potentially more useful for real-world
applications where speed is a key factor. The ensembling
method was successful in enhancing the performance of
individual models, indicating that merging different models can
frequently produce superior outcomes. Thus, choosing the
appropriate model is essential for getting excellent performance
in question-answering on the Squad dataset, according to the
findings of our study. For this work, BIDAF and DistilBERT
are useful models, and ensembling can boost performance even
more

<img src="accuracy.jpeg" height=200 width=200 style="vertical-align:middle;margin:50 0 ">

![accuracy graph](accuracy.jpeg)










Attached the paper !!
