# **Amazon ML Challenege 2023**
![AmazonMLChallenge](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fmedia-fastly.hackerearth.com%2Fmedia%2Fhackathon%2Famazon-ml-challenge-2023%2Fimages%2F11bd10ecf6-amazon_ml_challenge_hackerearth.jpg&f=1&nofb=1&ipt=d5908b73bbb0a585180441e20cecf5caac94ab3109dfbe0804cfa83819f066c5&ipo=images)
A team-participation challenge was held on April 21, 2023, 12:00 AM IST–April 23, 2023, where a solution was to be built for the given problem statement. This repository consists of a Jupyter notebook that contains the code we submitted under the name of our team, [TALISMANIC VADERS](https://www.hackerearth.com/challenges/competitive/amazon-ml-challenge-2023/leaderboard/page/6/#) and with an accuracy of _20.42677_, we ranked __290__ among 4898 teams.
# Problem Statement ~
--------
## Product length prediction  
In this hackathon, the goal is to develop a machine learning model that can predict the length dimension of a product. Product length is crucial for packaging and storing products efficiently in the warehouse. Moreover, in many cases, it is an important attribute that customers use to assess the product size before purchasing. However, measuring the length of a product manually can be time-consuming and error-prone, especially for large catalogues with millions of products.

You will have access to the product title, description, bullet points, product type ID, and product length for 2.2 million products to train and test your submissions. Note that there is some noise in the data.

### Task

You are required to build a machine-learning model that can predict product length from catalogue metadata.

### Dataset description

The dataset folder contains the following files: 
```
train.csv: 2249698 x 6
test.csv: 734736 x 5
sample_submission.csv: 734736 x 2
```

The columns provided in the dataset are as follows:

| Column name | Description |
|-------------|-------------|
| PRODUCT_ID | Represents a unique identification of a product |
| TITLE | Represents the title of the product |
| DESCRIPTION | Represents the description of the product |
| BULLET_POINTS | Represents the bullet points about the product |
| PRODUCT_TYPE_ID | Represents the product type |
| PRODUCT_LENGTH | Represents the length of the product |

### Evaluation metric
```score = max( 0 , 100*(1-metrics.mean_absolute_percentage_error(actual,predicted)))```

The dataset can be downloaded from [here](https://s3-ap-southeast-1.amazonaws.com/he-public-data/datasetb2d9982.zip).
