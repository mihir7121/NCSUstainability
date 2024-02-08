<p align="center">
<img src="https://github.com/rushildpatel/NCSUstainability/blob/master/public/images/logo.png" alt="drawing" width="400"/>
</p>

# NCSUstainability
\#SAVE every last bite, \#GIVE every last bite! 
All in one solution for food throughout the campus.

## Problem Statement
NC State University faces a sustainability challenge with significant food wastage due to inaccurate attendance predictions, unsustainable expiration tracking, and inefficient leftover management. The current practices result in overproduction, environmental impact, and resource wastage. A solution incorporating data analytics and smart inventory tracking is crucial to optimize food resources, minimize waste, and enhance campus sustainability.

## Proposed solution
We propose a two-fold solution to optimize operations at Clark Dining Hall @NC State and Tuffy's Diner, a fast-food chain. 

Firstly, leveraging real-life data collected from both establishments, we utilize advanced machine learning techniques to accurately forecast footfall and predict the necessary food quantities needed to meet demand effectively.

Secondly, we implement a smart inventory management system designed to efficiently utilize expiring goods, thereby minimizing waste and maximizing resource utilization. This integrated approach ensures both precision in meeting customer demand and optimization of inventory management processes.

## Technology Used

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Embedded JavaScript (EJS)](https://img.shields.io/badge/EJS-090909?style=for-the-badge&logo=ejs&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)


## Features
Our approach encompasses several key features:

1. Exploratory data analysis (EDA) conducted on the raw data collected from Clark Dining Hall and Tuffy's Diner, providing crucial insights into the underlying patterns and characteristics of customer behavior.

2. Data analysis of the refined dataset, enabling informed decision-making and uncovering valuable insights such as top-selling items and peak hours of activity.

3. Implementation of ARIMA time series forecasting to predict future trends, enhancing our ability to anticipate fluctuations in customer traffic and demand.

4. Integration of a smart inventory management system that effectively monitors expiration dates and alerts users to expiring or soon-to-expire goods. This proactive approach ensures timely utilization of inventory and minimizes wastage.


## Usage
### Installation
````
npm install
````
### Configure Environment Variables
Create a .env file in the root directory and add the following:
````
USER=your_mongo_username
PASSWORD=your_mongo_password
PORT=5000
SECRET=your_passport_session_secret
````
### Run the app
````
node app
````

App will be running on http://localhost:5000
