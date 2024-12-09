# Exploratory-Analysis-on-New-York-Airbnb-

## 📍 **Project Overview**

This project demonstrates my ability to perform **Exploratory Data Analysis (EDA)** and build a **Predictive Model** using a real-world dataset. The goal was to predict the prices of Airbnb listings in **New York City**, leveraging various features such as location, number of reviews, availability, and minimum nights.

Using **machine learning** techniques, I built a **linear regression model** to predict prices, visualized key patterns, and provided actionable insights into the factors that drive Airbnb pricing in different neighborhoods.

![image](https://github.com/user-attachments/assets/13ccbe17-e1d3-4e99-a71b-364d8b9a87bd)


## 🚀 **Key Achievements**

- **Exploratory Data Analysis (EDA)**: Cleaned the data, identified missing values, and visualized key features such as price distribution, reviews, and availability.
- **Correlation Analysis**: Analyzed correlations between features and identified significant relationships that influence pricing.
- **Predictive Modeling**: Developed a linear regression model to predict prices based on features like availability, number of reviews, and neighborhood group.
- **Data Visualization**: Created insightful and professional plots to communicate key findings and model performance.

## 📊 **Technologies Used**
- **Programming Languages**: R
- **Packages**: `ggplot2`, `dplyr`, `readxl`, `corrplot`, `openxlsx`
- **Libraries for Data Visualization**: `ggplot2`, `corrplot`
- **Modeling Techniques**: Linear Regression

## 🔍 **How the Model Works**

The project follows these main steps:

### 1. **Data Preprocessing**
- Loaded and cleaned the dataset to remove duplicates and handle missing values.
- Removed irrelevant columns and filtered data based on business logic (e.g., minimum reviews, availability).

### 2. **Exploratory Data Analysis (EDA)**
- Analyzed the distribution of prices and reviewed the correlations between numerical features.
- Visualized key features such as `price`, `number_of_reviews`, and `neighbourhood_group`.

### 3. **Predictive Modeling**
- Built a linear regression model to predict the `price` using features such as `minimum_nights`, `number_of_reviews`, `availability_365`, and `neighbourhood_group`.
- Evaluated the model using **Mean Squared Error (MSE)** to assess the accuracy of predictions.

### 4. **Model Evaluation**
- Visualized **Predicted vs Actual Prices** to evaluate the performance of the model.
- **Mean Squared Error (MSE)** metric: Lower MSE indicates a better-performing model.

## 📈 **Results & Insights**
- The distribution of Airbnb prices follows a right-skewed pattern, with a few high-end listings skewing the data.
- Key features that significantly affect price:
  - **Neighbourhood group**: Listings in central areas (e.g., Manhattan) tend to have higher prices.
  - **Availability**: Listings with fewer available nights tend to have higher prices.

## 🖼 **Sample Visualizations**

### 1. **Price Distribution**
This plot shows the distribution of Airbnb listing prices across New York City.

![Price Distribution](images/price_distribution.png)  
*Description: The distribution of Airbnb prices is skewed, with a few high-end listings inflating the average.*

### 2. **Correlation Heatmap**
The correlation heatmap identifies relationships between numerical features and the target variable, **price**.

![Correlation Heatmap](images/correlation_matrix.png)  
*Description: The correlation matrix shows strong correlations between `number_of_reviews` and `price`, as well as between `availability_365` and `price`.*

### 3. **Predicted vs Actual Prices**
This scatter plot compares the predicted prices from our model to the actual prices.

![Predicted vs Actual Prices](images/predicted_vs_actual.png)  
*Description: This plot illustrates how well the model predicts Airbnb prices. The closer the points are to the diagonal line, the better the model's performance.*

### 4. **Price vs. Number of Reviews**
This scatter plot visualizes the relationship between `number_of_reviews` and `price`.

![Price vs Reviews](images/price_vs_reviews.png)  
*Description: Listings with more reviews generally have a wider range of prices, but no clear linear relationship is visible.*

### 5. **Price vs. Availability in 365 Days**
This plot shows the relationship between listing price and the number of available days in a year.

![Price vs Availability](images/price_vs_availability.png)  
*Description: Listings with fewer available nights tend to have higher prices, possibly indicating more exclusive or high-demand properties.*

### 6. **Price vs. Minimum Nights**
This scatter plot shows the relationship between price and the minimum number of nights required to book a listing.

![Price vs Minimum Nights](images/price_vs_minimum_nights.png)  
*Description: Listings with a higher price often have higher minimum night requirements, though there are exceptions.*

### 7. **Price by Neighborhood Group**
This bar plot shows the average price in different neighborhood groups across New York City.

![Price by Neighborhood Group](images/price_by_neighbourhood_group.png)  
*Description: Manhattan has the highest average Airbnb prices, followed by Brooklyn, Queens, and other areas.*

### 8. **Price by Neighborhood**
This bar plot shows the price distribution across different neighborhoods in New York City.

![Price by Neighborhood](images/price_by_neighbourhood.png)  
*Description: Different neighborhoods have significant price variations. Listings in Manhattan and popular areas tend to be more expensive.*

## 🏗 **How to Run the Project**

To replicate or extend this project, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/samritiwalia111/Exploratory-Analysis-on-New-York-Airbnb.git
