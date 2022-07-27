# U.S.-Patent-Phrase-to-Phrase-Matching-
kaggle competition | silver

In this competition, relevant information will be extracted by matching key phrases in patent documents to determine the semantic similarity between phrases. We introduce the title of each patent code in the external CPC file as the training text in the data processing, and use Groupkfold to split the data into training set and validation set. In the scheme, Bert For Patent + DeBERTa + ELECTRA + Funnel-Transformer multi-model fusion was used, and FGM combat training was added. The final score was 0.868, 1% silver medal.
