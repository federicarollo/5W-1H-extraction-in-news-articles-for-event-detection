# 5W-1H-extraction-in-news-articles-for-event-detection


data_to_import.csv contains data about the news articles:
- the identifier (id) and the text of the news articles, 
- the name of the newspaper where the news articles have been published and the url of the web page, 
- the category of crime reported in the news articles (column 'activelearning_tag'), obtained by a process of active learning using word embeddings, 
- the answers to the 5W+1H questions (w_what, w_where, w_when, w_who_author, w_who_victim, w_who_other, w_why, h_how).


The Jupyter notebook contains the code to build the Event-Centric Knowledge Graph.
