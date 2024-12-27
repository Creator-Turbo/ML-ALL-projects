# Car Price Prediction

### Table of Contents
- [Demo](#demo)
- [Overview](#overview)
- [Motivation](#motivation)
- [Technical Aspect](#technical-aspect)
- [Installation](#installation)
- [Run](#run)
- [Deployment on Render](#deployment-on-render)
- [Directory Tree](#directory-tree)
- [To Do](#to-do)
- [Bug / Feature Request](#bug--feature-request)
- [Technologies Used](#technologies-used)
- [Team](#team)
- [Credits](#credits)

---

## Demo
This project predicts the price of a car based on its features such as make, model, year, mileage, fuel type, etc.  
**Link to Demo:** [Car Price Prediction](https://steam-review-sentiment-analysis.onrender.com) 

## Car Price Prediction

![Steam Sentiment Analysis](https://i.imgur.com/nN4RaWV.png)


---

## Overview
The Car Price Prediction project utilizes machine learning algorithms to estimate the price of a car based on its attributes. The model is trained on a comprehensive dataset of car features and prices, ensuring accurate predictions.

Key features:

Advanced data preprocessing techniques for numerical and categorical data.
Model training and evaluation for high accuracy.
Interactive web application for user-friendly predictions.


---

## Motivation
Understanding car prices is crucial for both buyers and sellers. This project helps provide accurate price estimates, enabling users to make informed decisions in the automotive market.

---

## Technical Aspect
Training Machine Learning Models:

- Data Collection: Car data with attributes like make, model, year, mileage, etc.

Preprocessing:
- Handling missing values and outliers.
- Encoding categorical features using one-hot encoding.
- Scaling numerical features.

Model Training:
- Algorithms: Linear Regression, Random Forest, Gradient Boosting.
- Hyperparameter tuning using GridSearchCV.

Model Evaluation:
- Metrics: Mean Squared Error (MSE), R-squared score.
- Building and Hosting a Flask Web App:
- Flask-based interface for users to input car details and get price predictions.
- Deployment on platforms like Render or Heroku for public accessibility.

---

## Installation
The Code is written in Python 3.10. If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:

# To clone the repository

```bash

gh repo clone Creator-Turbo/Steam-Review-Sentiment-Analysis

```
# Install dependencies: (all lib)
```bash
pip install -r requirements.txt
```



## Run
To train the Machine leaning models:
 To run the Flask web app locally
```bash
python app.py

```
# Deployment on Render

## To deploy the Flask web app on Render:
Push your code to GitHub.<br>
Go to Render and create a new web service.<br>
Connect your GitHub repository to Render.<br>
Set up the environment variables if required (e.g., API keys, database credentials).<br>
Deploy and your app will be live!



## Directory Tree 
```
.
├── data
│   ├── steam_reviews.csv
├── model
│   ├── sentiment_model.pkl
├── static
│   ├── style.css
├── templates
│   ├── index.html
├── app.py
├── train_model.py
├── requirements.txt
├── README.md

```

## To Do

- Define the project goal,"
 prepare the data, and train the model.
- Set up monitoring tools to track its performance.
- Automate the pipeline, document the process, test the system, and ensure continuous improvement.




## Bug / Feature Request
If you encounter any bugs or want to request a new feature, please open an issue on GitHub. We welcome contributions!




## Technologies Used
Python 3.10<br> 
scikit-learn<br>
TensorFlow <br>
Flask (for web app development)  <br>
Render (for hosting and deployment)  <br>
pandas (for data manipulation) <br>
numpy (for numerical operations)  <br>
matplotlib (for visualizations) <br>



![](https://forthebadge.com/images/badges/made-with-python.svg)


[<img target="_blank" src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/05/Scikit_learn_logo_small.svg/260px-Scikit_learn_logo_small.svg.png" width=170>](https://pandas.pydata.org/docs/)
[<img target="_blank" src="https://miro.medium.com/v2/resize:fit:720/format:webp/0*RWkQ0Fziw792xa0S" width=170>](https://pandas.pydata.org/docs/)
  [<img target="_blank" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSDzf1RMK1iHKjAswDiqbFB8f3by6mLO89eir-Q4LJioPuq9yOrhvpw2d3Ms1u8NLlzsMQ&usqp=CAU" width=280>](https://matplotlib.org/stable/index.html) 
 [<img target="_blank" src="https://icon2.cleanpng.com/20180829/okc/kisspng-flask-python-web-framework-representational-state-flask-stickker-1713946755581.webp" width=170>](https://flask.palletsprojects.com/en/stable/) 
 [<img target="_blank" src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/31/NumPy_logo_2020.svg/512px-NumPy_logo_2020.svg.png" width=200>](https://aws.amazon.com/s3/) 







## Team
This project was developed by:
[![Bablu kumar pandey](https://github.com/Creator-Turbo/images-/blob/main/resized_image.png?raw=true)](ressume_link) |
-|


**Bablu Kumar Pandey**


- [GitHub](https://github.com/Creator-Turbo)  
- [LinkedIn](https://www.linkedin.com/in/bablu-kumar-pandey-313764286/)
* **Personal Website**: [My Portfolio](https://creator-turbo.github.io/Creator-Turbo-Portfolio-website/)



## Credits

Special thanks to the contributors of the scikit-learn library for their fantastic machine learning tools.
