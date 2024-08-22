# **Height Prediction Model Using Linear Regression**

## **Overview**

This project involves building a simple linear regression model to predict a person's height based on their weight. The model uses historical data on weight and height to learn the relationship between these two variables and make predictions for new data.

## **Table of Contents**

- [**Project Description**](#project-description)
- [**Data**](#data)
- [**Requirements**](#requirements)
- [**Installation**](#installation)

## **Project Description**

The goal of this project is to develop a linear regression model that predicts height based on weight. Linear regression is a statistical method that models the relationship between a dependent variable and one or more independent variables. In this case, the dependent variable is height, and the independent variable is weight.

## **Data**

The dataset used for training the model consists of records of weights and corresponding heights. The data is stored in a CSV file named `height-weight.csv`.

### **Data Columns**

- `Weight` (kg): The weight of the individual.
- `Height` (cm): The height of the individual.

### **Sample Data**

| Weight (kg) | Height (cm) |
|-------------|-------------|
| 60          | 160         |
| 70          | 170         |
| 80          | 180         |
| ...         | ...         |

## **Requirements**

To run the model, you'll need the following Python libraries:

- `numpy`
- `pandas`
- `scikit-learn`
- `matplotlib` (for visualization)

You can install the required packages using pip:

```bash
pip install numpy pandas scikit-learn matplotlib
