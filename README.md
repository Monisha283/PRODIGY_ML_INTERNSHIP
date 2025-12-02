# Prodigy_Infotech_ML_Internship_Task
Prodigy Infotech Internship Machine Learning all Task's

**Task 1:** Implement a linear regression model to predict the prices of houses based on their square footage and the number of bedrooms and bathrooms.


**Task 2:** Create a K-means clustering algorithm to group customers of a retail store based on their purchase history.
<br>**Dataset:-** https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python</br>


**Task 3:** Implement a support vector machine (SVM) to classify images of cats and dogs from the Kaggle dataset.
<br>**Dataset:-** https://www.kaggle.com/c/dogs-vs-cats/data</br>


**Task 4:** Develop a hand gesture recognition model that can accurately identify and classify different hand gestures from image or video data, enabling intuitive human-computer interaction and gesture- based control systems.
<br>**Dataset:-** https://www.kaggle.com/gti-upm/leapgestrecog</br>


**Task 5:** Develop a model that can accurately recognize food items from images and estimate their calorie content, enabling users to track their dietary intake and make informed food choices.
<br>**Dataset :-** https://www.kaggle.com/dansbecker/food-101</br>

## Requirements

This repository uses two separate Python environments to manage dependencies for different tasks:

1. **Python 3.14 (`venv`)**  
   - Used for **Task 1 (Linear Regression)** and **Task 2 (K-Means Clustering)**  
   - Install dependencies using:
     ```bash
     python3.14 -m venv venv
     source venv/bin/activate  # Linux/Mac
     venv\Scripts\activate     # Windows
     pip install -r requirements.txt
     ```

2. **Python 3.10 (`tf_venv`)**  
   - Used for **Task 3 (SVM Image Classification)**, **Task 4 (Hand Gesture Recognition)**, and **Task 5 (Food Item Recognition & Calorie Estimation)**  
   - Install dependencies using:
     ```bash
     python3.10 -m venv tf_venv
     source tf_venv/bin/activate  # Linux/Mac
     tf_venv\Scripts\activate     # Windows
     pip install -r requirements_tf.txt
     ```

> **Note:** Virtual environment folders are **not included** in this repository.  
> Use the provided `requirements.txt` and `requirements_tf.txt` to install all necessary packages.

