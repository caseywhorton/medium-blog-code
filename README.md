# medium-blog-code

This repository contains the code that supports my blog posts on various publications, hosted by Medium.

My profile, as well as my blog posts, can be found at https://casey-whorton.medium.com/.

## _Interesting Ways to select Pandas DataFrame Columns_

**Link:** https://towardsdatascience.com/interesting-ways-to-select-pandas-dataframe-columns-b29b82bbfb33

Describes various ways to select columns in a pandas DataFrame. Mixes techniques that use string references and location references as well as conditiona logic to select columns. It's a nice reference when you need to select some subset of columns and it's a little more complicated.

## _Categorical Data, Jaccards Coefficient and Multiprocessing_

**Link:** https://towardsdatascience.com/categorical-data-jaccards-coefficient-and-multiprocessing-b4a7bd5d90f6

Looks at the Jaccard coefficient/metric for measuring similarity between vectors. I use multiprocessing to get through the pairwise comparisons I do in the notebook. A good reference for both of these concepts. The jupyter notebook (.ipynb file) contains the code.

- Dendrogram.png
- Jaccards Metric Introduction.ipynb
- Similarity_Count.png

## _Applying Custom Functions to Groups of data in Pandas_

**Link:** https://towardsdatascience.com/applying-custom-functions-to-groups-of-data-in-pandas-928d7eece0aa

Sometimes, you need to apply a custom function over groups of data, something more than basic statistics. I have come across the need to do this many times, but always manage to forget some of the syntax to get it done.

- apply_custom_functions_to_data_groups.ipynb

## _Easy Logistic Regression with an Analytical Solution_

**Link:** https://towardsdatascience.com/easy-logistic-regression-with-an-analytical-solution-eb4589c2cd2d

Classification of a binary target with an analytical solution instead of importing an algorithm. There is a long-form derivation in the zip file (reads as html).

- Binary Classification Equal Covariances Logistic Regression.ipynb
- binary_classifier_derivation.zip
- index.html

## _Predicting Mixed Targests with Neural Networks and Keras_

**Link:** https://towardsdatascience.com/predicting-mixed-targets-with-neural-networks-and-keras-1dc754ce0c98

Sometimes, you want your neural network to make predictions on more than one target using the same training data. That's what this blog is about.

- keras_mixed_targets.ipynb
