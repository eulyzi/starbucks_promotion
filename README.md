# Data Analysis for Starbucks Promotion Experiment: A Customer Decision Perspective


### Table of Contents

1. [Introduction](#description)
2. [Installation](#installation)
3. [Requirements](#Requirements)
4. [File Descriptions](#files)
5. [Instructions](#instructions)
6. [Summary](#summarys)
7. [Licensing](#licensing)
8. [Acknowledgements](#acknowledgements)




## Introduction<a name="description"></a>

<img src="images/hans-vivek-gfLlvYFD7NE-unsplash.jpg">

Photo by <a href="https://unsplash.dogedoge.com/@oneshotespresso?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Hans Vivek</a> on <a href="https://unsplash.dogedoge.com/s/photos/starbucks?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>

Marketing promotions have been used to boost sales and increase profits. As time goes by, consumers nowadays are exposed to tons of messages every day and their expectations are higher too. For retailers, it becomes more and more important to understand their customers and choose suitabe promotion strategies to attract their attentions and lead to a target behavior.

For this project  I analyzed a promotion experiment dataset from Starbucks and I intended to better understand:
1. Consumer Attention: How to reach different consumers groups?
2. Consumer Response: Can we predict consumers response to different promotion offers?
3. Loyal Consumer: Can we distinguish customers with more loyalty?


  

## Installation <a name="installation"></a>

Clone this GIT repository:

```
git clone https://github.com/eulyzi/starbucks_promotion.git
```

## Requirements <a name="Requirements"></a>

Python 3.6+ and modules in `requirements.txt` are recommended.

## File Descriptions <a name="files"></a>

There are 2 main parts of the project:
 - `cleaning.ipynb` shows how the dataset is cleaned.
 - `analysis.ipynb` diplays exploratory data analysis and  machine learning models to predict the behavior of customers in different stage.
 - `requirements.txt` required modules.
 
Besides these parts.
- `data` folder is used to save dataset.
- `images` folder is used to save picture used by `README.md`

### Instructions <a name="instructions"></a>

`*.ipynb` files can be open by `Jupyter Notebook`.
Run `cleaning.ipynb` firstly and then `analysis.ipynb`.

### Summary <a name="summarys"></a>

 - Firstly, this project analyzed a Starbucks promotion experiment from a customer decision perspective. The promotion offer process is divided into view stage and engage stage. Exploratory data analysis and machine learning models are built to analyze and predict conversion rate in each stage and the f1 score estimators show good results.
- Secondly, this project also tries to find loyal customers who are like to pay less attention to promotion infomation.
- Thirdly, this project reveals that there can be a trade-off between promotion and direct-buy behavior. 
- Finally, to get a better promotion impact and profit increase, further research direction can be financial anaylsis and loyalty degree study.


## Licensing <a name="licensing"></a>

Apache 2.0.

## Acknowledgements <a name="acknowledgements"></a>

The dataset is provided by [Stackbucks](https://www.starbucks.com/) and [Uddacity Data Scientist Nanodegree Program](https://www.udacity.com/course/data-scientist-nanodegree--nd025) .
