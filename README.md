# Sentiment-Analysis
Sentiment Analysis is an analysis of the sentence, text at the document that gives us the opinion of the sentence/text. In this project, it will be implemented a model which inputs a sentence and finds the most appropriate emoji to be used with this sentence. Code is adapted from Andrew Ng's Course 'Sequential Models'.
### Results
![43802983-1fe753e4-9aa0-11e8-9b9e-b87fe91e0c18](https://github.com/abeersethia/Sentiment-Analysis/assets/122032191/a1271dfc-8e55-43d7-acc9-8b0d2b81e94e)

### Dataset
We have a tiny dataset (X, Y) where:

X contains 127 sentences (strings)
Y contains a integer label between 0 and 4 corresponding to an emoji for each sentence

<img width="847" alt="43802586-eac883e6-9a9e-11e8-8f13-6471cc16a3d8" src="https://github.com/abeersethia/Sentiment-Analysis/assets/122032191/e1e3c168-9347-4818-b075-d0f517e31cb2">

### Embeddings
Glove 50 dimension, 40000 words of dictionary file is used for word embeddings. It should be downloaded from https://www.kaggle.com/watts2/glove6b50dtxt (file size = ~168MB))

word_to_index: dictionary mapping from words to their indices in the vocabulary (400,001 words, with the valid indices ranging from 0 to 400,000)
index_to_word: dictionary mapping from indices to their corresponding words in the vocabulary
word_to_vec_map: dictionary mapping words to their GloVe vector representation.

### LSTM
<img width="833" alt="43802664-22c08c8a-9a9f-11e8-83e1-fea4bf334f6e" src="https://github.com/abeersethia/Sentiment-Analysis/assets/122032191/b6a2ee41-04f4-4382-94f1-978ac4565591">

![43803021-416cc59e-9aa0-11e8-8b28-6045dd0ead87](https://github.com/abeersethia/Sentiment-Analysis/assets/122032191/1d8a5af9-eea9-470e-880c-feb6c4f65662)

