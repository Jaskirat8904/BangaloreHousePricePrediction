# BangaloreHousePricePrediction
Predicts property prices using ML (XGBoost, Random Forest) and DL (Neural Networks). Processes Bangalore real estate data, compares model performance, and offers interactive price estimates via web interface. Built with Python, Pandas, Scikit-learn, TensorFlow, and JavaScript. Helps buyers/sellers gauge market values.
![image](https://github.com/user-attachments/assets/85564b3a-33bc-42e4-8a93-ac8d7309641a)
This data science project series walks through step by step process of how to build a real estate price prediction website. We will first build a model using sklearn and linear regression using banglore home prices dataset from kaggle.com. Second step would be to write a python flask server that uses the saved model to serve http requests. Third component is the website built in html, css and javascript that allows user to enter home square ft area, bedrooms etc and it will call python flask server to retrieve the predicted price. During model building we will cover almost all data science concepts such as data load and cleaning, outlier detection and removal, feature engineering, dimensionality reduction, gridsearchcv for hyperparameter tunning, k fold cross validation etc. Technology and tools wise this project covers,

Python
Numpy and Pandas for data cleaning
Matplotlib for data visualization
Sklearn for model building
Jupyter notebook, visual studio code and pycharm as IDE
Python flask for http server
HTML/CSS/Javascript for UI
