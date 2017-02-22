# A-Game-of-Vectors

creating word vectors using 'A game of thrones' dataset of all five books and word2vec.This repository contains the code for the blog-post by [Vyom Sharma](https:vyomshm.github.io) entitled "Word Vectors from Game of Thrones"

### About the dataset

The 'data' folder contains 5 text files each containing one of the 5 books by [George R. Martin](http://www.georgerrmartin.com/) , in no specific order.These files are completely unedited containing all of the text in the original books including acknowledgements, index, forewords etc.

The folder 'clean' within the 'data' folder contains the cleaned up data. The books have been re-named in the order of the entire series:

1) A game of throne
2) A clash of kings
3) A storm of swords
4) A feast for crows
5) A dance with dragons

### The kaggle dataset 

The kaggle dataset contains three data files dowloaded from [here](https://www.kaggle.com/mylesoneill/game-of-thrones). I included this datset her beacuse i plan on using this for another one of my blog post where i will try to replicate the character-death predictions in the 'character-predictions.csv'. These predictions were made using a SVM( support vector machine)

This dataset combines three sources of data, all of which are based on information from the book series.

1)Firstly, there is battles.csv which contains Chris Albon's "The War of the Five Kings" Dataset, which can be found [here]( https://github.com/chrisalbon/war_of_the_five_kings_dataset). Its a great collection of all of the battles in the series.

2)Secondly we have character-deaths.csv from Erin Pierce and Ben Kahle. This dataset was created as a part of their Bayesian Survival Analysis which can be found [here](http://allendowney.blogspot.com/2015/03/bayesian-survival-analysis-for-game-of.html)

3)Finally we have a more comprehensive character dataset with character-predictions.csv. This comes from the team at A Song of Ice and Data who scraped it from http://awoiaf.westeros.org/ . It also includes their predictions on which character will die, the methodology of which can be found here: https://got.show/machine-learning-algorithm-predicts-death-game-of-thrones
What insights about the complicated political landscape of this fantasy world can you find in this data?

## Of course, it goes without saying that this dataset contains spoilers ;)