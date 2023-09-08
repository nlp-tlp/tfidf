# tfidf
Code for tfidf and topic modelling

The code in this repo was written to allow engineers to explore the impact of parameter selection, such as the number of topics, on the output of tf-idf pipelines. We adapt code from - [Topic extraction via Scikit-learn](https://scikit-learn.org/stable/auto_examples/applications/plot_topics_extraction_with_nmf_lda.html#sphx-glr-auto-examples-applications-plot-topics-extraction-with-nmf-lda-py) web site using ChatGPT.

Users can run the code with one of two provided .txt files

1. An extract of accident reports (documents with multiple sentences)
2. Short text work orders

We encourage users to play with parameters in the pipeline specifically n_features, n_topics, n_top_words.

We demonstrate the results of the output of NMF and LDA models using some easy-to-interpret graphic
