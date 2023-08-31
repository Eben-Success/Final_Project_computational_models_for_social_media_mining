# Project Description

## Building A Personalized Post and Subreddit Recommendation System 

### Department of Computer Science, University of Ghana 

#### DCIT316: Computational Models for Social Media Mining 
![reddit](/reddit.png)

Reddit, a social media platform with over 1.660 billion monthly active users and more than
130,000 subreddits, serves as a massive repository of user-generated content. While this large
number of data offers a rich variety of topics, it also poses a challenge for users trying to find
content that aligns with their interests. This project aims to address this issue by developing a
personalized post and subreddit recommendation system. Leveraging the Reddit Self-Post
Classification Task (RSPCT) dataset, which comprises 1.013 million self-posts across 1013
subreddits.
The study involved several key steps, starting with data acquisition and environment preparation
on the Kaggle platform. Data preprocessing was performed using Pandas and scikit-learn
libraries. The Data preprocessing stage was focused on handling missing values, feature
engineering, and normalization. Natural Language Processing (NLP) techniques were applied for
text analysis, and data visualization was conducted using Seaborn and Matplotlib. The text data
was vectorized using Term Frequency-Inverse Document Frequency (TF-IDF) for machine
learning modeling and evaluation.
Two algorithms were evaluated for the recommendation system: Naïve Bayes and Single Value
Decomposition (SVD) for collaborative filtering. Both models were assessed based on precisionat-k metrics. The study also included an exploratory data analysis to understand user behavior
and subreddit themes better.
From a business perspective, the recommendation system aims to increase user engagement,
thereby creating more opportunities for advertising and monetization. Overall, this study presents
a comprehensive approach to understanding user behavior on Reddit and offers a scalable
solution for personalized content recommendation.

# About the Dataset

About Dataset: The Reddit Self-Post Classification Task (RSPCT) dataset was used for this project. This dataset involves classifying self-posts into their corresponding subreddits. The dataset comprises 1.013 million self-posts from 1013 subreddits, with 1000 examples per subreddit class. Efforts were made to minimize content overlap by carefully selecting a diverse set of subreddits. Additionally, there is manual annotation data for around 3000 subreddits that contributed to dataset creation, including category, subcategory, and reasons for exclusion if applicable. Detailed information about the dataset can be found using this [Link](https://www.kaggle.com/datasets/mswarbrickjones/reddit-selfposts)

# How to Set Up the Project

### Clone the project

```bash
git clone
 ```


### Create a virtual environment using `pip` or `conda`

#### Using `pip`

```bash
pip install virtualenv
```

```bash
virtualenv venv
```

```bash
venv\Scripts\activate
```

```bash
source venv/bin/activate
```

#### Using `conda`

```bash
conda create --name myenv
```

```bash
conda activate myenv
```

#### Install the dependencies using the  `requirements.txt`

```bash
pip install -r requirements.txt
```

