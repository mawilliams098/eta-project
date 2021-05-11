# Exploratory Text Analysis Final Project 

Box Link to code and data: https://virginia.app.box.com/folder/136685843394?s=8q9j7zk0jww2z00pkgzptexga1lvhoxw

The file structure for this project is as follows: 

* `create_tables.ipynb`: This notebook contains the code to create the initial F2-F4 `DOC`, `LIB`, `TOKEN`, and `VOCAB` tables. 

* `create_models.ipynb`:  This notebook contains the code for PCA, LDA, word2vec, and sentiment analysis. 

* `/F2-F4_tables`  
    - `DOC.csv`
    - `LIB.csv`
    - `TOKEN.csv`
    - `VOCAB.csv`

* `/model_data`
    - `BUTLER-EMBEDDINGS.csv`: word2vec terms and embeddings 
    - `CHAPMAN-EMBEDDINGS.csv`: word2vec terms and embeddings
    - `DCM.csv`: PCA table of documents and components
    - `LOADINGS.csv`: PCA components and word counts ("loadings")
    - `PHI.csv`: Table of term strings and associated topic distributions 
    - `TOPICS.csv`: Table of document and topic concentrations
    - `SENTIMENTS.csv`: Sentiment and emotionl values as features in VOCAB table

* `/source_files`: Original text downloaded from Project Gutenberg
    - `100-iliad-butler.txt`
    - `200-odyssey-butler.txt`
    - `300-iliad-chapman.txt`
    - `400-odyssey-chapman.txt`

* `/visualizations`: All visualizations that appear in `create_models.ipynb`
    - `butler_polarity`
    - `butler_sentiment`
    - `chapman_polarity`
    - `chapman_sentiment`
    - `lda_heatmap`
    - `lda_kde`
    - `pca0_1.png`
    - `pca1_2.png`
    - `pca2_3.png`
    - `pca3_4.png`
    - `tnse_butler.png`
    - `tsne_chapman.png`


