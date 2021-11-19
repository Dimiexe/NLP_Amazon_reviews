# NLP_Amazon_reviews

The aim of this projet is to develope an NLP pipeline that gets amazon review texts as input and predicts their user rating. The approach followed here makes no shortcuts by employing readily available models (like pretrained hagging face models, pretrained embeddings etc.) and the entire pipeline is shown. That is of course intentional, as another reason of this project is to familiarise myself with NLP concepts and their usage. The data used in this project can be downloaded [here](http://snap.stanford.edu/data/amazon/productGraph/categoryFiles/reviews_Apps_for_Android_5.json.gz).


The entire project is in one jupyter notebook file writen in python 3.8. Prerequisite modules include:
* nltk, gensim
* pandas, numpy, matplotlib, seaborn
* scikit-learn, imbalanced-learn
