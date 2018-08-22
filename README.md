# Aggressive Language Identification Using Word Embeddings and Sentiment Features

This notebook presents the code of my participation in the 
<a href=\"https://sites.google.com/view/trac1/shared-task\" target=\"_blank\">
First Shared Task on Aggression Identification</a>. More details about the 
approach can be found in:

Constantin Orǎsan (2018) Aggressive Language Identification Using Word Embeddings 
and Sentiment Features. In *Proceedings of the First Workshop on Trolling, Aggression 
and Cyberbullying (TRAC-2018)*, p. 113 - 119, Santa Fe, USA, August, 25, 
http://aclweb.org/anthology/W18-4414

## Requirements

In order to run this notebook you will need the following software:
* python3.6
* <a href="https://nltk.org">NLTK</a>
* numpy and sklearn
Probably the easiest way to get all these is to install <a href="https://www.anaconda.com/download/">
Anaconda</a>. 

You will also need to obtain the training, development and testing data from the
workshop organisers and store the CSV files in a folder called english (or set the
correct path in the ``path_to_data``).

Download the GloVe vector from https://nlp.stanford.edu/projects/glove/. The current
code assumes you use the 300d vectors. Uncompress the file and update the ``path_to_glove``
variable to point to it. 

Uncompress the ``senti_feats.7z``. This file contains the scores assigned by the
SentiStrength. If you want to process different texts you will need to obtain 
SentiStrength from its author and preprocess the data using the procedure described 
in the notebook. 


