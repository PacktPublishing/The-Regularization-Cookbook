
<b><p align='center'>[![Packt Sale](https://static.packt-cdn.com/assets/images/e72907cf-bf2f-4f83-bb58-6cc08a901ff9.jpeg)](https://www.packtpub.com/)</p></b>Get this book on sale at [Packt](https://www.packtpub.com/).

# The Regularization Cookbook

<a href="https://www.packtpub.com/product/the-regularization-cookbook/9781837634088"><img src="https://content.packt.com/B19629/cover_image_small.jpg" alt="The Regularization Cookbook" height="256px" align="right"></a>

This is the code repository for [The Regularization Cookbook](https://www.packtpub.com/product/the-regularization-cookbook/9781837634088), published by Packt.

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

With the following software and hardware list you can run all code files present in the book (Chapter 1-11).

### Software and Hardware List

| Chapter  | Software required                                                                    | OS required                        |
| -------- | -------------------------------------------------------------------------------------| -----------------------------------|
|  	1-11   | Python 3.9   							                                              | Windows, Mac OS X, and Linux (Any) |


### Detailed Chapters Content
<details>
    <summary>
        <a href="chapter_01/chapter_01.ipynb">Chapter 1: An Overview of Regularization</a>
    </summary>

- Introducing regularization
</details>

<details>
    <summary>
        <a href="chapter_02/chapter_02.ipynb">Chapter 2: Machine Learning Refresher</a>
    </summary>

- Loading the data
- Splitting the data
- Preparing quantitative data
- Preparing qualitative data
- Model training
- Model evaluation
- Hyperparameter optimization
</details>

<details>
    <summary>
        <a href="chapter_03/chapter_03.ipynb">Chapter 3: Regularization with Linear Models</a>
    </summary>

- Training a Linear Regression with scikit-learn
- Regularizing with Ridge Regression
- Regularizing with Lasso Regression
- Regularizing with an Elastic Net Regression
- Training a Logistic Regression
- Regularizing a Logistic Regression
- Choosing the Right Regularization
</details>

<details>
    <summary>
        <a href="chapter_04/chapter_04.ipynb">Chapter 4: Regularization with Tree-based Models</a>
    </summary>

- Building a classification tree
- Building a Regression Tree
- Regularizing a decision tree
- Training a Random Forest
- Regularizing a Random Forest
- Training a Boosting model with XGBoost
- Regularizing with XGBoost
</details>

<details>
    <summary>
        <a href="chapter_05/chapter_05.ipynb">Chapter 5: Regularization with Data</a>
    </summary>

- Hashing high cardinality features
- Aggregating features
- Undersampling an imbalanced dataset
- Oversampling an imbalanced dataset
- Resampling imbalanced data with SMOTE
</details>

<details>
    <summary>
        <a href="chapter_06/chapter_06.ipynb">Chapter 6: Deep Learning Reminders</a>
    </summary>

- Training a perceptron
- Training a neural network for regression
- Training a neural network for binary classification
- Training a multiclass classification neural network
</details>

<details>
    <summary>
        <a href="chapter_07/chapter_07.ipynb">Chapter 7: Deep Learning Regularization</a>
    </summary>

- Regularizing a neural network with L2 regularization
- Regularizing a neural network with early stopping
- Regularizing with network architecture
- Regularizing with dropout
</details>

<details>
    <summary>
        <a href="chapter_08/chapter_08.ipynb">Chapter 8: Regularization with Recurrent Neural Networks</a>
    </summary>

- Training a RNN
- Training a GRU
- Regularizing with dropout
- Regularizing with maximum sequence length
</details>

<details>
    <summary>
        <a href="chapter_09/chapter_09.ipynb">Chapter 9: Advanced Regularization in Natural Language Processing</a>
    </summary>

- Regularization using a word2vec embedding
- Data augmentation using word2vec
- Zero-shot inference with pre-trained models
- Regularization with BERT embeddings
- Data augmentation using GPT-3
</details>

<details>
    <summary>
        <a href="chapter_10/chapter_10.ipynb">Chapter 10: Regularization in Computer Vision</a>
    </summary>

- Training a CNN
- Regularizing a CNN with vanilla NN methods
- Regularizing a CNN with transfer learning for object detection
- Semantic segmentation using transfer learning
</details>

<details>
    <summary>
        <a href="chapter_11/chapter_11.ipynb">Chapter 11: Regularization in Computer Vision: Synthetic Image Generation</a>
    </summary>

- Applying image augmentation with Albumentations
- Creating synthetic images for object detection
- Implementing real-time style transfer
</details>

### Related products <Other books you may enjoy>
* Causal Inference and Discovery in Python [[Packt]](https://www.packtpub.com/product/causal-inference-and-discovery-in-python/9781804612989) [[Amazon]](https://www.amazon.com/Causal-Inference-Discovery-Python-learning-ebook/dp/B0C4LKQ1X7)

* Pretrain Vision and Large Language Models in Python [[Packt]](https://www.packtpub.com/product/pretrain-vision-and-large-language-models-in-python/9781804618257) [[Amazon]](https://www.amazon.com/Pretrain-Vision-Language-Models-Beginners/dp/180461825X)

## Get to Know the Author
**Vincent Vandenbussche** After a Ph.D. in Physics, Vincent Vandenbussche has worked for a decade in diverse companies, deploying ML solutions at scale. He has worked in numerous companies, such as Renault, L’Oréal, General Electric, Jellysmack, Chanel, and CERN.
He also has a passion for teaching; he co-founded a data science boot camp, was an ML lecturer at Mines Paristech engineering school and EDHEC business school and trained numerous professionals in companies like ArcelorMittal and Orange.

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

## Feedbacks

For any feedback or typo, please open an issue and describe it.
