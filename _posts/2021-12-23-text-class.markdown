---
layout: post
title:  Text Classification of Postings in Video Gaming Category
date:   2021-12-23 15:01:35 +0300
image:  '/images/2021-12-23-text-class/2021-12-23-main.jpg'
tags:   [Python, Sklearn, Keras, NLP]
---


## Summary

In this class project, our group **aimed to develop a classification model** that correctly classfies each posting in the video gaming category in Craiglist into a corresponding brand to enhance user experience and the company's key business performance. 

* **Tools / Libraries used:** Python (beautiful soup, pandas, nltk, sklearn, keras, etc.)

* **Dataset:** Web Scrapped / titles and reviews of posts in Craiglist / 3011 rows * 8 columns

* **Analyses Performed:** Web Scrapping, Data Cleaning/Manipulation, Keyword Extraction, Text Representation(Tokenization, Lemmatization, Vectorization), Machine Learning(Naive Bayes, Logistic Regression, Random Forest, SVC, Neural Network), Deep Learning(Recurrent Neural Network), Validation(Confusion Matrix), and Business Insights

## Key Takeaways
* Our best model was gradient boosting, performed 81% accuracy in the test dataset. It was greater than the website's search rate which was 68%.
* It shows that our best model would provide more correct results and minimize information loss on the searches that users performed on the website.
* Therfore, we would expect that our model would contribute to an increase engagement of users with the webiste, leading to growth in retention rate and potentially generating more revenue.
* During the data cleaning process, we were successfully able to categorize each sample into a corresponding brand by using the scoring method. We scored each sample with keywords that were manually extracted and identified the highest score to match with a correct brand. We believe this scoring method would be very effective and scalable for categorization in further analyses.



<br>


## Details of Codes and Model Building Process

<div class="notebook-embedded">
<iframe scrolling="yes" src="https://nbviewer.org/gist/jaylee21/e3b230d13eb3c54663f6163558d96c14" width="100%" data-embed="true" height="500" frameborder="0" allowfullscreen></iframe>
</div>

