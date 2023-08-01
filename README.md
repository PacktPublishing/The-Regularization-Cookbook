# The-Regularization-Cookbook

<a href="https://www.amazon.es/Regularization-Cookbook-practical-recipes-robustness-ebook/dp/B0BRSSG5Z6"><img src="https://m.media-amazon.com/images/I/51sCPuArqDL.jpg" alt="The Regularization Cookbook" height="256px" align="right"></a>

This is the code repository for [The Regularization Cookbook](https://www.amazon.es/Regularization-Cookbook-practical-recipes-robustness-ebook/dp/B0BRSSG5Z6), published by Packt.

**Explore practical recipes to improve the functionality of your ML models**

## What is this book about?
Regularization is an infallible way to produce accurate results with unseen data, however, applying regularization is challenging as it is available in multiple forms and applying the appropriate technique to every model is a must. The Regularization Cookbook provides you with the appropriate tools and methods to handle any case, with ready-to-use working codes as well as theoretical explanations.

After an introduction to regularization and methods to diagnose when to use it, you’ll start implementing regularization techniques on linear models, such as linear and logistic regression, and tree-based models, such as random forest and gradient boosting. You’ll then be introduced to specific regularization methods based on data, high cardinality features, and imbalanced datasets. In the last five chapters, you’ll discover regularization for deep learning models. After reviewing general methods that apply to any type of neural network, you’ll dive into more NLP-specific methods for RNNs and transformers, as well as using BERT or GPT-3. By the end, you’ll explore regularization for computer vision, covering CNN specifics, along with the use of generative models such as stable diffusion and Dall-E.

By the end of this book, you’ll be armed with different regularization techniques to apply to your ML and DL models.

This book covers the following exciting features: 
* Diagnose overfitting and the need for regularization
* Regularize common linear models such as logistic regression
* Understand regularizing tree-based models such as XGBoos
* Uncover the secrets of structured data to regularize ML models
* Explore general techniques to regularize deep learning models
* Discover specific regularization techniques for NLP problems using transformers
* Understand the regularization in computer vision models and CNN architectures
* Apply cutting-edge computer vision regularization with generative models

If you feel this book is for you, get your [copy](https://www.amazon.com/dp/1837634084) today!

<a href="https://www.packtpub.com/?utm_source=github&utm_medium=banner&utm_campaign=GitHubBanner"><img src="https://raw.githubusercontent.com/PacktPublishing/GitHub/master/GitHub.png" alt="https://www.packtpub.com/" border="5" /></a>

## Instructions and Navigations
All of the code is organized into folders.

The code will look like the following:
```
# Load data
data = pd.read_csv('Tweets.csv')
data[['airline_sentiment', 'text']].head()
```

**Following is what you need for this book:**
This book is for data scientists, machine learning engineers, and machine learning enthusiasts, looking to get hands-on knowledge to improve the performances of their models. Basic knowledge of Python is a prerequisite.

With the following software and hardware list you can run all code files present in the book (Chapter 1-11.

### Software and Hardware List

| Chapter  | Software required                                                                    | OS required                        |
| -------- | -------------------------------------------------------------------------------------| -----------------------------------|
|  	1-11   | Python 3.9   							                                              | Windows, Mac OS X, and Linux (Any) |


### Related products <Other books you may enjoy>
* Causal Inference and Discovery in Python [[Packt]](https://www.packtpub.com/product/causal-inference-and-discovery-in-python/9781804612989) [[Amazon]](https://www.amazon.in/Causal-Inference-Discovery-Python-learning/dp/1804612987)

* Pretrain Vision and Large Language Models in Python [[Packt]](https://www.packtpub.com/product/pretrain-vision-and-large-language-models-in-python/9781804618257) [[Amazon]](https://www.amazon.in/Pretrain-Vision-Language-Models-Beginners-ebook/dp/B0BFFDF4MQ)

## Get to Know the Author
**Vincent Vandenbussche** After a Ph.D. in Physics, Vincent Vandenbussche has worked for a decade in the industry, deploying ML solutions at scale. He has worked in numerous companies, such as Renault, L’Oréal, General Electric, Jellysmack, Chanel, and CERN.
He also has a passion for teaching: he co-founded a data science boot camp, was an ML lecturer at Mines Paristech engineering school and EDHEC business school and trained numerous professionals in companies like ArcelorMittal and Orange.

## Usage

Clone this repo:
```shell
git clone git@github.com:PacktPublishing/The-Regularization-Cookbook.git
```

Create a virtual environment and install dependencies:
```shell
conda create -n regularization python=3.9
conda activate regularization
pip install -r requirements.txt
```

Then launch jupyter notebook, run and adapt the codes as you want:
```shell
jupyter notebook
```
