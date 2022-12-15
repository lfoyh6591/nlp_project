# nlp_project

## Objects
Apply texttiling method for topic segmentation to Korean text data.  


Imporvement texttiling method by using sentence embedding with pretrained SBERT models 
and setting cosine similarities to similarity scores.


## File explanation
### execution
Execute only korean_texttiling.ipynb for the result.

#### 1. texts
Korean text data in the texts folder from AIHUB  
Preprocessed by fetch_data.ipynb  
link : https://aihub.or.kr/aihubdata/data/view.do?currMenu=115&topMenu=100&aihubDataSe=realm&dataSetSn=543

#### 2. textiling.py
Modified nltk's texttiligng source code for Korean text and improvement.
link : https://www.nltk.org/_modules/nltk/tokenize/texttiling.html

#### 3. segmentation.py
nltk's segmentation source code for evaluation metric.
link : https://www.nltk.org/_modules/nltk/metrics/segmentation.html

#### 4. fetch_data.ipynb
Used to load data from AIHUB and preprocess data.

#### 5. korean_texttiling.ipynb
Used to expriment

