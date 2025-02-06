# **Mobile Price Classification using R**

## **Project Description**

- This project aims to analyze mobile phone features to classify them into different price ranges. By leveraging statistical modeling and hypothesis testing, we explore the impact of features like RAM, battery power, and pixel resolution on pricing. The dataset consists of 2,000 observations collected from Kaggle.

## **Objectives**

- Understand the relationship between mobile features and price.

- Perform statistical tests to determine feature importance.

- Implement R-based data analysis and modeling techniques.

## **Scope of Project**

The project's scope includes:

- Feature analysis and data preprocessing.

- Statistical hypothesis testing (t-tests, ANOVA, Chi-square, Kruskal-Wallis tests).

- Data visualization using histograms, box plots, bar charts, and pie charts.

- Interpretation of statistical results and insights into mobile pricing.

## **Dataset Information**

- Source: Mobile Price Classification Dataset

- Sample Size: Mobile phones released from 2012 to 2016.

- Target Population: All available mobile phones in the market.

- Price Categories: 0 (Low Cost) , 1 (Medium Cost) , 2 (High Cost), 3 (Very High Cost)


## **Environment Setup & Dependencies**

- To set up the environment, install the required R packages:
```bash
install.packages(c("tidyverse", "ggplot2", "dplyr", "ggpubr", "car"))
```
- For virtual environment management:
```bash
install.packages("renv")
renv::init()
```
## **Reproducibility Guide**

- Steps to Run Analysis
Clone this repository:
```bash
git clone https://github.com/yourusername/mobile-price-classification.git
cd mobile-price-classification
```
- Load the dataset into R:
```bash
data <- read.csv("mobile_price_data.csv")
summary(data)
```
- Perform statistical tests:
```bash
t.test(data$battery_power, data$ram)
```
## **Results & Findings**

Key Insights:

- Higher RAM, larger battery power, and better camera specifications contribute to higher price ranges.

- Primary camera and internal memory may not strongly impact mobile phone pricing.

- Network type alone is not a strong predictor of price.

- Dual SIM phones may have different RAM specifications compared to single SIM phones.

- 4G capability influences battery power specifications.

## **Conclusion**

- This project provides useful insights for consumers and the mobile industry by helping people make informed decisions about buying phones. It systematically analyzes key features to understand how factors like RAM and camera quality influence pricing, making it easier for industry professionals and consumers to navigate the mobile market.

## **References**

- Mobile Price Classification Dataset on Kaggle (https://www.kaggle.com/datasets/iabhishekofficial/mobile-price-classification)

