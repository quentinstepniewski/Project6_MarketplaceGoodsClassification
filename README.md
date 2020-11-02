# Project6_OpenClassrooms
<p><a href="https://openclassrooms.com/fr/paths/164-data-scientist">Data Scientist path </a>by OpenClassrooms (in partnership with CentraleSupélec)</p>

**Project 6** : Classify marketplace's goods (NLP + Image Classification)

## Project Description:

Implementation of a classification algorithm to assign goods with a category based on their description and picture

* NLP Part:
  * Apply NLP methods to preprocess string data : tokenisation, stopwords,lemmatisation/stemming, Bag of Words/TF-IDF
  * Perform Word Embedding (Doc2Vec, encoding with BERT model)
  * Perform supervised and unsupervised (LDA, NMF, Kmeans) classification
* Image Classification part:
  * Image preprocessing (grayscale, convolutions: median/gaussian blur, histograms equalizer, resizing,...)
  * Feature extraction via ORB + creation of VisualBagOfWord
  * Transfer Learning/ Feature Extraction via VGG16 (ImageNet) CNN model
  * Creation of a CNN from scratch 
  * Unsupervised classification attempt (with observing the classification on 2D with TSNE)
 * Merge both NLP and ImageClassification 
   * Feature extraction of the best models of each part (Doc2Vec and VGG16)
   * Attempt to create emsemble Stacking model 


## Assessed Skills:

* Preprocess string type data into a usable dataset for classification
* Preprocess image into usable data for classification
* Use of dimension-reduction methods
* Graphic representation of high dimension data

