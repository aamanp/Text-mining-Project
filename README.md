# Text-mining-Project
Detection of Cyberbulling in Tweets
In this project we are going to work with a dataset from online social media.

One of the biggest problems on the internet today is the presence of negative attitudes towards certain groups in relation to their ethnicity, gender, religion or political ideology. In this exercise we will work with a real, manually tagged dataset from the [Kaggle] platform (https://www.kaggle.com/datasets/andrewmvd/cyberbullying-classification/data). Originally, each document in the dataset was assigned one of the following categories:
- *religion
- *age
- *ethnicity
- *gender
- *other_cyberbullying
- *not_cyberbullying


The initial objective of the dataset was to use it to train a model capable of detecting the type of hate content present on the internet according to the target group. In this case, a function `load_prepare_data()` has been generated that changes the categories of the dataset, obtaining at the end 2 categories with value 1 or 0, indicating whether the tweet has hate content.
