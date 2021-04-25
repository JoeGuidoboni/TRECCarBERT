Learn-to-Retrive-and-Generate for Article Generation

Abstract:
Advances in Natural Language Processing (NLP) and Information Retrieval (IR) models over the past several years have given rise to improvements in text retrieval and generation tasks. We look to leverage one such model, Google's Bidirectional Encoder Representation for Transformers (BERT) for the task of Wikipedia article generation via next-paragraph-prediction. Using a pre-trained implementation of BERT, we fine-tune on top of this model to sequentially predict and retrieve paragraphs from an article's set of paragraphs. Articles are generated continuously, basing the prediction for the next paragraph on the generated article thus far, rather than on the previously retrieved paragraph. This work looks to serve as a basis for further paragraph-level retrieval techniques, as well as text level article generation.
