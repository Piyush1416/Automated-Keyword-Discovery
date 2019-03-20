# Automated-Keyword-Discovery
Keywords consist of sequence of one or more words and areconcise representation of important facts in documents. Hence Picking right keyword to represent an document plays key factor in multiple domains including Document Classification.

Key-words can be, utilized to classify a given document, em-ployed in journal articles for indexing, or used as searchqueries in search engines. However, most documents donot contain any assigned keywords, whereas the ones that do are usually restricted to certain keywords and rely on the perception of the curator. Therefore, the importance ofautomatically extracting keywords from documents, a branch of data mining, has been becoming increasingly important in the data driven world of the 21st century.

we will be using Neural Information Processing Systems (NIPS) is one of the top machine learning conferences in the world. This dataset includes the title and abstracts for all NIPS papers to date (ranging from the first 1987 conference to 2016 conference). The dataset is available on kaggle here :- https://www.kaggle.com/benhamner/nips-papers/home

Work Involved in this experiment is as follows:-

1] Data Loading

2] Data Pre-Processing (cleaning data and noise removal)

3] Data Exploration (Understanding the data)

4] Convert data into Word-Vector Representation

5] Based on word Frequencies Pick top words relevant to each topic


I have used Word-Vector representation and then TF-IDF to rank top words and pick most relevant words to a given topic.
The notebook used is attached above.
