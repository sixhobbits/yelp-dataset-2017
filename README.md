# Yelp Dataset Challenge: Our paper, tutorials, and blog posts

This repository and related resources, to which we link below, forms our submission to the 2017 Yelp Dataset Challenge. 

With new advances in machine learning and artificial intelligence, there has been a surge of talk about *Democratizing* AI. (For example, see [https://news.microsoft.com/features/democratizing-ai/](https://news.microsoft.com/features/democratizing-ai/)). It is important that everyone benefits from advances in this area, and not only huge corporations.

As part of this process, we believe that new research should be as accessible as possible, to as many people as possible. Therefore, instead of presenting our work in a single format, targetted at a specific audience, we instead present it in many formats, with different target audiences, including academics, beginners, and programmers. 

Much of the presented research is related to authorship attribution. This is an interesting task with many practical applications (for example, detecting fake reviews, or deanonymising criminals online). However, many of the methods we use are generalizable to other text classification tasks, and, more broadly, to most machine learning tasks. We therefore present work not only related to authorship attribution, our field of interest, but also some introductory materials on machine learning and data visualisation in general.

Specifically, our submission consists of the following:

* For the academic community, we present [a research paper](https://github.com/sixhobbits/authorship-attribution/blob/master/Authorship%20Attribution%20Yelp%20Reviews.pdf) in which we detail our experiments on different methods for authorship attribution tasks. We relate our experiments on the Yelp dataset to previous work done on Authorship Attribution, and provide the first results on new datasets that we created as subsets from the Yelp reviews. We hope that others will use this data to compare future Authorship Attribution systems to ours.
* For those just starting out in their machine learning journey, we present [a tutorial](https://github.com/sixhobbits/authorship-attribution/blob/master/Yelp%20Reviews%20-%20Authorship%20Attribution.ipynb) that consists of runnable code and clear explanations in a Jupyter Notebook, showing how classification tasks work, and explaining each step. Note that although this tutorial shows a similar experiment to the ones discussed in the research paper, it uses a slightly different subset of the Yelp dataset where examples are broken down per review instead of concatenated by author. 
* Also for the budding ML engineer or researcher, we also present [a blog post](http://www.developintelligence.com/blog/2017/03/predicting-yelp-star-ratings-review-text-python/) in which we show how to predict the rating of a review given its text. This is closely related to sentiment analysis tasks, and we therefore discuss this in that context.
* For those who want to venture deeper into machine learning, we present a thorough [introduction to using Keras](http://www.developintelligence.com/blog/2017/06/practical-neural-networks-keras-classifying-yelp-reviews/). We again tackle the rating-prediction task, and show how to train Keras models using a powerful cloud GPU instance from AWS. We take a highly practical approach, and show how to package the resulting models and use them for real-world tasks after training.
* For those who want to get started with data science and data visualisation, we present [another blog post](http://www.developintelligence.com/blog/2017/02/analyzing-4-million-yelp-reviews-python-aws-ec2-instance/) showing how to carry out basic analysis on the Yelp reviews using an AWS cloud machine. We look at how to create some basic plots with Matplotlib and (spoiler alert) find out that negative reviews tend to be longer than positive ones.

The code we used for the experiments in the paper can also be found in the other Jupyter Notebook files in this repository. However, these files are not well-strucutred nor well documented, and we do not recommend them as a learning experience. 

We would like to thank Yelp and everyone involved in the Dataset challenge for providing this opportunity and dataset, with which we have a lot of fun over the last several months.

