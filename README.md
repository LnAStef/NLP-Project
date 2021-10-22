# NLP Project - Relation classification and extraction from medical literature

The number of biomedical documents and literature is nowadays increasing rapidly and so does the importance of biomedical text mining tools.
 With the progress in natural language processing (NLP), extracting valuable information from biomedical literature has gained popularity among researchers, and deep learning has boosted the development of effective biomedical text mining models. 
  However, directly applying the advancements in NLP to biomedical text mining might often lead to unsatisfactory results due to a word distribution shift from general domain corpora to biomedical
corpora. 

 In this research, first some of the basic NLP techniques like trimming, stemming, bag of words (BOW) model, Part of Speech (POS) tags, word embeddings will be introduced for the purpose of relation classification in medical literature. Furthermore, a pre-trained language model Bidirectional Encoder Representations from Transformers (BERT) as well as its modification BioBERT designed especially for biomedical text
mining, will be introduced for the purpose of relation extraction. The medical text that will be used as dataset contains labeled chemicals, proteins and the relation between them that should to be predicted.

.code/chemprot/chemprot prepration.ipynb ->  code for CHEMPROT dataset preparation for the Task 1: Binary Relation Classification
.code/corpus-to-graph-ml-master/Task 1 -> models.ipynb -> code for training the models and their evaluation for Task 1: Binary Relation Classification
.code/BERT-RE/Task 2.ipynb -> all code for CHEMPROT dataset preparation as well as model training and evaluation for Task 2: Relation Extraction and Type Classification
