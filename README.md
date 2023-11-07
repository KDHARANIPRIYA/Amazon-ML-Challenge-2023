## PRODUCT LENGTH PREDICTION
[ Amazon-ML-Challenge-2023 ]
The Amazon ML Challenge 2023 focused on predicting the length dimension of a product using machine learning techniques. The challenge aimed to address the time-consuming and error-prone task of manually measuring product lengths, especially for large catalogs with millions of products.

### Dataset
The dataset provided for the challenge included product title, description, bullet points, product type ID, and product length for over 2.2 million products. The goal was to train a machine learning model on this data and use it to predict the length of products in a separate test set.
{The dataset provided consists of two files, train.csv and test.csv, containing 2.2 million and 734,736 product records, respectively.} 
The data contains the following columns:

_PRODUCT_ID_: Represents a unique identification of a product
_TITLE_: Represents the title of the product
_DESCRIPTION_: Represents the description of the product
_BULLET_POINTS_: Represents the bullet points about the product
_PRODUCT_TYPE_ID_: Represents the product type
_PRODUCT_LENGTH_: Represents the length of the product

### Task
Participants are required to build a machine learning model that can predict the length of a product from the given metadata. The evaluation metric used for this hackathon is the mean absolute percentage error (MAPE), and the score is calculated using the following formula:

_**score = max(0, 100*(1 - metrics.mean_absolute_percentage_error(actual, predicted)))**_


