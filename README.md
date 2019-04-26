# embeddings-word2vec Readme
This program demonstrates the use of word2vec word embeddings. 

Based on <a href="https://www.kaggle.com/pierremegret/gensim-word2vec-tutorial">https://www.kaggle.com/pierremegret/gensim-word2vec-tutorial</a>

<a href="https://colab.research.google.com/github/fmcooper/embeddings-word2vec/blob/master/embeddings-word2vec.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

******************************

1) Program use
2) Google Drive access

******************************

## 1) Program use

You will need to have a Google account to access colab. If you have never used colab before take a look <a href="https://colab.research.google.com/notebooks/welcome.ipynb">here</a>. After this, simply click on the following button to open this program in a new colab instance: 
<a href="https://colab.research.google.com/github/fmcooper/embeddings-word2vec/blob/master/embeddings-word2vec.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

The following variables are available to change: 
* ``NUM_TESTING`` should be a positive integer. If in testing mode then this program will run over the first ``NUM_TESTING`` characters of the sample text
* ``TESTING`` may be set as ``True`` or ``False``. Indicates whether we are in testing mode. 
* Result file locations may also be set. Please see Results section.


## 2) Google Drive access

In order to save the model both during and after training, this program will ask you for google drive access. 

```
from google.colab import drive
drive.mount('/content/gdrive')
```

Please edit this line:

```
DATA_PATH = '/content/gdrive/My Drive/Colab/embeddings-word2vec/data/simpsons_script_lines.csv'
```

To point at the data provided in this repository.
