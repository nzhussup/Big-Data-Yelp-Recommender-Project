# Big-Data-Recommender-Project
University big data project. Analysing Yelp dataset and developing recommendation algorithms

![PySpark](https://img.shields.io/badge/PySpark-EE4C2C?style=for-the-badge&logo=apache-spark&logoColor=white)
![Spark ML](https://img.shields.io/badge/Spark%20ML-4CAF50?style=for-the-badge&logo=apache-spark&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3776AB?style=for-the-badge&logo=python&logoColor=white)

# Team Q Project (Yelp Dataset)

## Purpose of the project

The project aims to develop 2 recommender algorithms for Yelp:

1. **Content-Based Recommender (NLP):**
   - Create a personalized recommendation system using NLP sentiment prediction models.
   - Improve review evaluation efficiency and provide tailored suggestions based on textual content.

2. **Collaborative Filtering Recommender (ALS):**
   - Implement collaborative filtering with the ALS algorithm for user-item interaction analysis.
   - Enhance recommendations by identifying patterns and similarities among users and businesses.


Building a recommender algorithm is crucial for Yelp's success. It enhances user experience by providing personalized suggestions, increasing engagement, and optimizing revenue through targeted advertising. This technology not only sets Yelp apart in a competitive market but also offers valuable data-driven insights and ensures ethical data usage, building trust with users.


## Getting Started

### Dependencies

* Code wrote on: macOS Ventura Version 13.5.1
* Libraries: PySpark, FindSpark, Matplotlib, Seaborn, WordCloud, Textblob, NLTK, Scikit-learn

```bash
!pip install pyspark, findspark, matplotlib, seaborn, wordcloud, textblob, nltk, sklearn
```


### Executing program

* Paste your own spark path

```python
path = "your path"
findspark.init(path)
```

* Configure SparkSession to your own preferences
* Press "Run All"

### Data

Used files from Yelp dataset:

* business.json
* review.json


## Authors

Contributors names and contact info

* Nurzhanat Zhussup
* Markus Grain
* Philipp Meissner


## License

[Yelp_License](https://s3-media0.fl.yelpcdn.com/assets/srv0/engineering_pages/f64cb2d3efcc/assets/vendor/Dataset_User_Agreement.pdf)
