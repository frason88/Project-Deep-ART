# Project-Deep-ART
<p align="center"><img src="https://github.com/frason88/Project-Deep-ART/blob/main/demo.gif?raw=true" width="400px" height="200px"/></p>

## Introduction:
The creation of art is among the highest forms of expression of the human mind and imagination. The ability to communicate imagination sets us apart from all other beings. 
Painting, being an expression of visual language, has attracted and connected the brilliant human minds since the dawn of civilization - from early drawings on walls of caves to 
paper or glass paintings of modern times, from charcoals in prehistoric times to water, oil, or pastel colors of today. We have traveled a long way, and have finally reached a 
stage where not only humans but computers, another brilliant creation of human minds, is creating paintings. For an enthusiast of arts, identifying the paintings of her favorite 
artists is not that difficult, given years of careful practice and research. Given a painting, she can easily identify if it was painted by a painter she is passionate about. But 
can a computer do the same? Can a machine without emotions identify who the genius is behind a mind-blowing painting?

## Dataset Information:
The dataset is taken from the “Best Artworks of All Time” which has a Collection of Paintings of the 50 Most Influential Artists of All Time. 
This dataset contains three files:
1. artists.csv: a dataset of information for each artist
2. images.zip: a collection of images (full size), divided into folders and sequentially numbered
3. resized.zip: same collection but images have been resized and extracted from a folder structure

## Deep-ART Gallery:
AR Art Museum embarks on the theme of practical education and comprises an AR museum.
As the deadly Covid-19 pandemic swept across the world, it induced a paranormal amount of fear, anxiety, and depression in people. But the world also starts to see a surge in the 
usage of new technology. New ways of education came forward. But with this, the real-life practical experience came to decline. Students started feeling boredom seeing 2-D images 
and text. Educational trips to museums and other destinations came to halt. AR deepArt Museum is a small step to curb this problem as it provides the user with a virtual 3-D 
museum in their real environment containing 3-D models of various different artist domains to experience. 

[Link to AR-Gallery](https://console.echoar.xyz/webar?key=odd-butterfly-1790&entry=6870315e-d174-4dc4-bd01-afc0bc0c3342)

<p align="center"><img src="https://github.com/frason88/Project-Deep-ART/blob/main/AR-Gallery.JPG?raw=true" width="400px" height="200px"/></p>

## Evaluation Metrics:  
1. Confusion Metrics 
<p align="center"><img src="https://github.com/frason88/Project-Deep-ART/blob/main/confusion_matrix.png?raw=true" width="300px" height="300px"/></p>

2. Classification Report
<p align="center"><img src="https://github.com/frason88/Project-Deep-ART/blob/main/classification_report.jpg?raw=true" width="400px" height="200px"/></p>

## Predictions:
The final model could identify the artists with an approximate accuracy of 99% on training set and 87% on cross-validation set.

## Instruction to run this code
- Requirements: Python 3, Numpy, Matplotlib, Tensorflow and Keras
- Download the dataset from link provided above
- Modify the input file paths and point to your local directory where data the downloaded data is stored
- The model is deployed as a web-application on Heroku cloud - https://deep-artist.herokuapp.com/


## Contributors 
- [Shrikrithika Nagarajan](https://www.behance.net/shri_sthrii)
- [Frason Francis](https://github.com/frason88)
- [Cindy Su](https://github.com/cindy-MP-2020?tab=repositories)








