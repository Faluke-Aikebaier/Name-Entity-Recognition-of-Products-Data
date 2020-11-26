# Name-Entity-Recognition-of-Products-Data

The project is to regognize & extract [Named Entities](https://en.wikipedia.org/wiki/Named-entity_recognition) from several fields on the corpus. Corpus comes as is, so it's up to the data-scientist to decide how to label the data & train the model. There are 119 unique providers which describe their products in a certain way. This helps the labelling process as one can see below. Suggested Named Entities are (at least, depends on the row-data): BRAND, SIZE, COLOR, SIZE, WEIGHT, etc.

The first part of the project, obtaining the entity and entity lists, are omitted due to the lengthy codes. Rather, the saved lists are uploaded. The second part is devoted to train a model with Spacy. One can use the two lists or similar ones, and the function in the code cell 13 in the notebook `ner_train` to create annotations (rule based matching) for Spacy. The model is trained on a local drive, and hence many issues are left for future. Finally the trained model is also uploaded.
 
