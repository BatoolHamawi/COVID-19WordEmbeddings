# COVID-19 Arabic Word Embeddings
 
We built a word vectors model exploiting our whole COVID-19 dataset collected from January 2020 to April 2020 [link](https://github.com/SarahAlqurashi/COVID-19-Arabic-Tweets-Dataset). By removing retweets and duplicated tweets, we ended with 2,821,940 tweets. We consider two noticeable word embeddings generation methods: word2vec, and FastText.
Using these pre-trained word embeddings models that are domain-specific (COVID-19) would be more accurate than using other generic pre-trained word embeddings in AI tasks. 



# COVID19 Twitter Word2Vec models  
We release four embedding models 

| Model | Vocabularies No.| Vec-Size | Download |
| ------------- | ------------- |------------- |------------- |
| Word2Vec-Twitter-SkipGram | 262,715 | 200  | [Download URL](https://drive.google.com/file/d/1Ds5Bl0jCkHbmOKckuW3uFvnncav_0uO_/view?usp=sharing)|
| Word2Vec-Twitter-CBOW | 262,715 | 200  | [Dwonload URL](https://drive.google.com/file/d/1ybI-WCNH-W17_v9X2oUAjIQNO8IOCapm/view?usp=sharing)|
| Word2Vec-Twitter-SkipGram | 262,715 | 300  | [Download URL](https://drive.google.com/file/d/1ycEpVys1qx_iCKJ5EiybLm5WQsJv0Hxu/view?usp=sharing)|
| Word2Vec-Twitter- CBOW | 262,715 | 300  | [Dwonload URL](https://drive.google.com/file/d/1VYeLsFhecETzQQGMaIVMG2aXBIZA9yVf/view?usp=sharing)|

# COVID19 Twitter FastText models  
We release two embedding models 


| Model | Vocabularies No.| Vec-Size | Download |
| ------------- | ------------- |------------- |------------- |
| FastText-Twitter-SkipGram | 262,715 | 200  | [Download URL](https://drive.google.com/file/d/1XpJotgk7Y6XX6wIuHTUNM0hC7qmeg8xC/view?usp=sharing)|
| FastText-Twitter-SkipGram | 262,715 | 300  | [Download URL](https://drive.google.com/file/d/1XgFTZp-Abv5-Op9cNLO25eJSuQO2nHer/view?usp=sharing) |

****************
# Word Embeddings in 2D using T-SNE
Here is the T-SNE visualisation of the word embedding in 2D. It was done using "Embedding Projector" with 3500 iterations and 15 perplexity.

- T-SNE visualisation of Model trianed by Continous Bag of word with a dimension of 300 
![Tsne_CBOW300](https://user-images.githubusercontent.com/18370351/111040683-3f078780-8445-11eb-8aa0-32161978ab90.jpg)

- T-SNE visualisation of FastText Model trained with a dimension of 300 
![Tsne_modelSkipGramFast300](https://user-images.githubusercontent.com/18370351/111040850-3b283500-8446-11eb-87df-d2b12ffd558c.jpg)

***************************************************************************
## How to use 
These models were built using [gensim](https://radimrehurek.com/gensim/models/fasttext.html) Python library. 
For loading and using one of the models, you should install the `gensim` and `nltk` :
- install `gensim` >= 3.4 and `nltk` >= 3.2 using either `pip` or `conda`

>> pip install gensim nltk
> 
>> conda install gensim nltk

### [Code sample](https://github.com/BatoolHamawi/COVID-19WordEmbeddings/blob/main/WordEmbeddingsVector.ipynb)
******************************************

# References
- We built our word embeddings [The Word2Vec-Twitter-Skipgram with dimension 200](https://drive.google.com/file/d/1Ds5Bl0jCkHbmOKckuW3uFvnncav_0uO_/view?usp=sharing) in our paper [COVID-19: What Are Arabic Tweeters Talking About?](https://link.springer.com/chapter/10.1007%2F978-3-030-66046-8_35), to determine the number of topics.
 
If you are going to use this model, please cite this work using the following bibtext: 
```cite
@inproceedings{hamoui2020covid,
  title={COVID-19: What Are Arabic Tweeters Talking About?},
  author={Hamoui, Btool and Alashaikh, Abdulaziz and Alanazi, Eisa},
  booktitle={International Conference on Computational Data and Social Networks},
  pages={425--436},
  year={2020},
  organization={Springer}
}
```
- The rest of word embeddings models were built to be used with classification algorithm in our paper
[Eating Garlic Prevents COVID-19 Infection: Detecting Misinformation on the Arabic Content of Twitter](https://arxiv.org/abs/2101.05626)
If you are going to use our pre-trained models, please cite this work using the following bibtext: 
```cite
@article{alqurashi2021eating,
  title={Eating Garlic Prevents COVID-19 Infection: Detecting Misinformation on the Arabic Content of Twitter},
  author={Alqurashi, Sarah and Hamoui, Btool and Alashaikh, Abdulaziz and Alhindi, Ahmad and Alanazi, Eisa},
  journal={arXiv preprint arXiv:2101.05626},
  year={2021}
}
```
