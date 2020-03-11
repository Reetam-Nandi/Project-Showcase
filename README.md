# Improved Product Recommendations

### Project Overview
----------------------------------
##### Problem

How to improve product recommendations for customers visiting dell online product store and increase the sales figures ensuring customer satisfaction.


##### Solution

* We gather customer's activity data from different sites example, flipkart, amazon and google using a browser extension (or Ad Networks if available).
* The gathered data is used to train a machine learning algorithm which then predicts the preference/priority value for all dell products in the store inventory.
* We further improve the predictions by implementing refinement algorithms based on dell's requirements to target the user with specific categories of products
* The final recommendations are shown to the user. Maximum customer satisfaction is achieved as the products are of high specifications in minimum customer budget.
* Now we track the user's interaction with the recommended products and refine the recommendations further based on the actions taken like - product added to cart or products checked out.
* Interactions with a product on dell.com are used to track product recommendation conversion ratio. This ratio is used to manipulate the recommendations and display popular products.
* The customer can provide a feedback in the form of a comment. This comment is run through a sentiment analysis algorithm and the factor is used to improve the predictions.
* We provide a dashboard for the marketing and analysis team to visualise the performance of our recommendation engine and its outcomes.

### Solution Description
----------------------------------

#### Architecture Diagram

The following diagrams show a high level view of data flow in the solution design.
![alt text](/dfd.png "data flow")

![alt text](/analyticsdfd.png "anlytics data flow")
#### Technical Description

##### Technologies and libraries used
 Following are some important technologies and libraries used.

|Technology | Version |
|---|---|
|python|3.6.5|
|Django|3.0|
|nltk|3.4.5|
|numpy|1.17.4|
|pandas|0.25.3|
|psycopg2|2.8.4|
|scikit-learn|0.22|
|scipy|1.3.3|
|sklearn|0.0|
|tensorflow|1.13.1|
|tflearn|0.3.2|
|postgreSQL|12.1 |