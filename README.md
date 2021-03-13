# COVID-19 Arabic Word Embeddings
 
We built a word vectors model exploiting our whole COVID-19 dataset collected from January 2020 to April 2020 [link](https://github.com/SarahAlqurashi/COVID-19-Arabic-Tweets-Dataset). By removing retweets and duplicated tweets, we ended with 2,821,940 tweets. We consider two noticeable word embeddings generation methods: word2vec, and FastText.
Using these pre-trained word embeddings models that are domain-specific (COVID-19) would be more accurate than using other generic pre-trained word embeddings in AI tasks. 

# Citation 
If you are qoing to use our pre-trained models, please cite this work using the following bibtext: 
```cite
@article{alqurashi2021eating,
  title={Eating Garlic Prevents COVID-19 Infection: Detecting Misinformation on the Arabic Content of Twitter},
  author={Alqurashi, Sarah and Hamoui, Btool and Alashaikh, Abdulaziz and Alhindi, Ahmad and Alanazi, Eisa},
  journal={arXiv preprint arXiv:2101.05626},
  year={2021}
}
```
# COVID19 Twitter Word2Vec models  
We release four embedding models 
- Model trained by Skipgram algorithm with a dimension of 200 [Download URL](https://drive.google.com/file/d/1Ds5Bl0jCkHbmOKckuW3uFvnncav_0uO_/view?usp=sharing)
- Model trianed by Continous Bag of word with a dimension of 200 [Dwonload URL](https://drive.google.com/file/d/1ybI-WCNH-W17_v9X2oUAjIQNO8IOCapm/view?usp=sharing)
- Model trained by Skipgram algorithm with a dimension of 300 [Download URL](https://drive.google.com/file/d/1ycEpVys1qx_iCKJ5EiybLm5WQsJv0Hxu/view?usp=sharing)
- Model trianed by Continous Bag of word with a dimension of 300 [Dwonload URL](https://drive.google.com/file/d/1VYeLsFhecETzQQGMaIVMG2aXBIZA9yVf/view?usp=sharing)

| Model | Vocabularies No.| Vec-Size | Download |
| ------------- | ------------- |------------- |------------- |
| Word2Vec-Twitter-SkipGram | 262,715 | 200  | [Download URL] (https://drive.google.com/file/d/1Ds5Bl0jCkHbmOKckuW3uFvnncav_0uO_/view?usp=sharing)|
| Word2Vec-Twitter-CBOW | 262,715 | 200  | [Dwonload URL](https://drive.google.com/file/d/1ybI-WCNH-W17_v9X2oUAjIQNO8IOCapm/view?usp=sharing)|
| Word2Vec-Twitter-SkipGram | 262,715 | 300  | [Download URL](https://drive.google.com/file/d/1ycEpVys1qx_iCKJ5EiybLm5WQsJv0Hxu/view?usp=sharing)|
| Word2Vec-Twitter- CBOW | 262,715 | 300  | [Dwonload URL](https://drive.google.com/file/d/1VYeLsFhecETzQQGMaIVMG2aXBIZA9yVf/view?usp=sharing)|

# COVID19 Twitter FastText models  
We release two embedding models 
- Model trained by Skipgram algorithm with a dimension of 200 [Download URL](https://drive.google.com/file/d/1XpJotgk7Y6XX6wIuHTUNM0hC7qmeg8xC/view?usp=sharing)
- Model trained by Skipgram algorithm with a dimension of 300 [Download URL](https://drive.google.com/file/d/1XgFTZp-Abv5-Op9cNLO25eJSuQO2nHer/view?usp=sharing)
