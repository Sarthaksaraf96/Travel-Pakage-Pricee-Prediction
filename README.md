# Travel-Pakage-Prediction-Price

A machine learning project that Travel Package Price Prediction Model utilizes advanced regression techniques to accurately forecast travel package prices. To facilitate seamless integration, a RESTful API has been constructed using Flask. For enhanced scalability, the model is deployed using Docker. Additionally, various deployment strategies on cloud platforms have been explored to ensure cost efficiency and reliability.

### Output:

![Travel App Price Prediction](https://github.com/Sarthaksaraf96/Travel-Pakage-Prediction-Pricee/assets/132260196/3209165b-4f6c-4f66-aac9-86b4fd2a9506)



## Project Workflow
#### Data Collection and Preparation:
- Dataset Link : [dataset link](https://drive.google.com/file/d/1eQPD_UG5C6YfvduVlX7PckwVwGuBnCBw/view)
- Gather travel package data, including features such as destination, duration, and amenities.
Clean and preprocess the data, handling missing values and encoding categorical variables.

#### Feature Engineering:
- Create new features or transform existing ones to improve model performance.
Use techniques like scaling and normalization to prepare the features for modeling.

#### Model Development:
- Split the data into training and testing sets.
- Develop a machine learning model, such as linear regression or decision tree regression, to predict travel package prices.
- Evaluate the model using metrics like Mean Absolute Error (MAE) or Root Mean Squared Error (RMSE).
- Model Performance :
    - ![Screenshot 2024-04-12 115507](https://github.com/Sarthaksaraf96/Travel-Pakage-Prediction-Pricee/assets/132260196/d1a3b1a0-b3f1-4a74-877e-c29a6e423548)


#### REST API Development:
- Use Flask to create a RESTful API that exposes endpoints for predicting travel package prices.
- Implement data validation and error handling to ensure the API's robustness.

#### Containerization with Docker:
- Dockerize the Flask application to create a lightweight, portable container.
- Used Docker Compose to define and run multi-container Docker applications.

#### Testing and Validation:
- Test the API endpoints to ensure they return the expected results.
- Validate the model's predictions against new data to ensure accuracy and reliability.

#### Model Deployment Option:
- Perfect Statergy to Deploy app On various Cloud Platform
  
#### Monitoring and Maintenance:
- Can be Further monitored and logged to track the API's performance and detect issues.
- Can help to Regularly update and maintain the model and API to incorporate new features and improve performance.
