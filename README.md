# BachelorThesis

Song lyrics were provided by the [Wasabi Research Group](http://wasabihome.i3s.unice.fr/)

## Meta Data Enriching

The lyrical dataset was enriched with meta data in [enrich_metadata.ipynb](enrich_metadata.ipynb)

Information about Song Genres were taken from the [WasabiDataset](https://github.com/micbuffa/WasabiDataset)
Some additional Genre assignments were done manually
Further information about publication dates were obtained from the Website of the [Million Song Dataset](http://millionsongdataset.com/sites/default/files/AdditionalFiles/tracks_per_year.txt)

The resulting enriched lyrical Dataset 'songs_enriched' was used for Word Embeddings Training and LDA Topic Modeling

## Word Embeddings Training

Word2Vec and FastText embeddings were trained in [word_embeddings.ipynb](word_embeddings.ipynb)  
GloVe embeddings were trained with the downloadable implementation of the follwing website: https://nlp.stanford.edu/projects/glove/  
"Compass Embeddings" were trained with the implementation found in the following public repository:  https://github.com/valedica/twec  

## LDA Topic Modeling

LDA topic model was applied in [topic_modeling.ipynb](topic_modeling.ipynb)

## WordClouds

WordClouds for every genre were created in [wordclouds.ipynb](wordclouds.ipynb)
