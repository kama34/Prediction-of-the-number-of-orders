<p align="center">
      <img src="https://i.ibb.co/0tnp8Wy/uber-eats-logo-CA3-BA2098-B-seeklogo-com.png">
</p>

<p align="center">
   <img src="https://img.shields.io/badge/Pandas-lavender" alt="Pandas">
   <img src="https://img.shields.io/badge/NumPy-thistle" alt="NumPy">
   <img src="https://img.shields.io/badge/Matplotlib-lightcyan" alt="Matplotlib">
   <img src="https://img.shields.io/badge/ydata_profiling-lavender" alt="ydata_profiling">
   <img src="https://img.shields.io/badge/Scikit_Learn-thistle" alt="Scikit-Learn">
   <img src="https://img.shields.io/badge/PCA-lightcyan" alt="PCA">
</p>

## About

Food delivery companies and systems has skyrocketed in recent years, driven by various factors. The convenience and ease of ordering food from the comfort of one’s home or office have made food delivery a preferred choice for many consumers. With a desire to optimize operational efficiency, reduce costs, and enhance customer satisfaction, food delivery companies have been leveraging machine learning algorithms to predict order cancellation and to forecast their resources such as active couriers. In this project I used machine learning to predict number of orders a courier will deliver.

## Documentation

### Introduction
This project aims to analyze courier activities and predict the total number of deliveries using machine learning techniques. The dataset contains information about couriers' mode of transportation, timestamps, and delivery statistics. Through data profiling, preprocessing, and regression modeling, the goal is to gain insights and build predictive models.

### Overview
The dataset is loaded from a JSON file and undergoes profiling to understand its structure. Categorical features, such as the mode of transportation, are processed using label encoding. Timestamp columns are transformed, and unnecessary columns are dropped. The data is split into features and targets, followed by scaling to ensure feature neutrality.

### Goals and Objectives
- Understand courier activities and patterns.
- Predict the total number of deliveries.
- Identify significant features influencing delivery counts.

### Dataset features description
* courier_id (int) : Courier ID,
* courier_transport (text) : The transport type used by a courier
* total_deliveries (int) : Total number of orders delivered by a courier
* max_unique_pickups (int) : ,
* work_start (Timestamp) : time when the courier started working
* work_finish (Timestamp) : time when the courier finished working
* late_pickups (float) : Percentage of orders that were picked up late from the vendor (during inferencing this feature gets to be the maximum acceptable late pickups)
* late_deliveries (float) : Percentage of orders that were delivered late to client (during inferencing this feature gets to be the maximum acceptable late deliveries)

## Distribute

- [Service Name](Page Link)


## Developers

- [Delevoper Name](GitHub Profile Link)

## License
