## Predicting intoxication with smart phone accelerometer data
**Authors:** [Peter Eusebio](https://github.com/Pete-Best/), [Lola Johnston](https://github.com/lolajohnston/), [Yannik Kumar](https://github.com/yannikkumar/)

**Date:** June 2020

GitHub repository for a final project in a Machine Learning course at the University of Chicago: https://github.com/Pete-Best/predicting_intoxication

Accelerometer data was used to predict TAC levels of 13 research subjects.  The data was provided by the [UCI Machine Learning Database](https://archive.ics.uci.edu/ml/datasets/Bar+Crawl%3A+Detecting+Heavy+Drinking).  The project is based on Killian, J.A., Passino, K.M., Nandi, A., Madden, D.R. and Clapp, J., [Learning to Detect Heavy Drinking Episodes Using Smartphone Accelerometer Data](http://ceur-ws.org/Vol-2429/paper6.pdf). In Proceedings of the 4th International Workshop on Knowledge Discovery in Healthcare Data co-located with the 28th International Joint Conference on Artificial Intelligence (IJCAI 2019) (pp. 35-42).

- **eda.ipynb** explores the accelerometer and TAC data.

- **join_together.ipynb** joins the accelerometer and TAC data from the [UCI Machine Learning Database](https://archive.ics.uci.edu/ml/datasets/Bar+Crawl%3A+Detecting+Heavy+Drinking).  Its output is fed into feature_extraction.ipynb.

- **feature_extraction.ipynb** extracts features from the accelerometer data to be used for predicting TAC.

- **feedforward_networks.ipynb** builds feedforward neural networks to predict TAC using the explanatory data.

- **recurrent_and_convolutional_networks.ipynb** builds RNNs and CNNs to predict TAC using the explanatory data.

- **modeling_sklearn.ipynb** uses a variety of classifiers to predict TAC using the explanatory data.
