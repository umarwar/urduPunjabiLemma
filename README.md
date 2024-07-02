# urduPunjabiLemma
This project aims to develop a Deep Learning-based Bilingual Lemmatizer for Urdu and 
Punjabi. The lemmatizer was developed using Python and deep learning frameworks 
like TensorFlow and Keras. The Deep Learning-based Lemmatizer consists of modules for data collection, 
preprocessing, feature extraction, model training, model evaluation, bilingual integration.<br>
The lemmatizer was released as a pip package and also be made available as a 
web portal. The pip package will make it easy for developers to integrate the lemmatizer 
into their own projects. The web portal will allow users to lemmatize Urdu and Punjabi 
text online

# Dataset
This lemmatizer utilizes a manually developed dataset consisting of Urdu and Punjabi (Shahmukhi script) verbs and nouns. The dataset includes:
<ul>
  <li>Urdu Verbs</li>
  <li>Urdu Nouns</li>
  <li>Punjabi Verbs</li>
  <li>Punjabi Nouns</li>
</ul>
The dataset is freely available and can be accessed on Kaggle https://www.kaggle.com/datasets/malaikabasharat/urdu-punjabi-merged-dataset

# Deployment
<ul>
  <li>Web Portal</li>
  The web portal will allow users to lemmatize Urdu and Punjabi text online.
  <li>Pip Package</li>
  The pip package will make it easy for developers to integrate the lemmatizer into their own projects.
</ul>

<b>!!How to install urdupunjabilemma through pip package?</b><br>
<ol>
  <li>pip install urdupunjabilemma</li>
  <li>import urdupunjabilemma as upl</li>
  <li>upl.lemmatize("your word")</li>
</ol>

<b>!!Getting version error while using the package? try this:</b><br>
<ol>
  <li>pip uninstall keras tensorflow</li>
  <li>pip install tensorflow</li>
</ol>

