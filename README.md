# Gold Price Prediction Project

This project aims to predict the price of gold using machine learning techniques. The dataset contains historical data about gold prices and other related metrics. A Random Forest Regressor is used as the predictive model for this task.

## Project Structure

1. **Data Import and Exploration**  
   - Load the dataset using `pandas`.
   - Perform exploratory data analysis (EDA) to understand the dataset structure, missing values, and statistical measures.

2. **Data Visualization**  
   - Use heatmaps to identify correlations between features.
   - Analyze the distribution of the target variable (GLD price).

3. **Data Preparation**  
   - Drop irrelevant columns (e.g., `Date`).
   - Split the dataset into features (`X`) and target (`Y`).
   - Divide the data into training and testing sets.

4. **Model Training**  
   - Train a Random Forest Regressor using the training data.

5. **Model Evaluation**  
   - Evaluate the model's performance using the R-squared error metric.
   - Visualize the comparison between actual and predicted values.

6. **Results and Insights**  
   - Use predictions to analyze the model's accuracy and identify areas for improvement.

## Libraries Used

Below are the Python libraries used in the project:

### Data Manipulation and Analysis
- **`numpy`**: For numerical operations and data manipulation.
- **`pandas`**: For loading and handling datasets, and performing EDA.

### Data Visualization
- **`matplotlib.pyplot`**: For plotting graphs and visualizing data trends.
- **`seaborn`**: For creating advanced visualizations, including heatmaps and distribution plots.

### Machine Learning
- **`scikit-learn`**: 
  - `train_test_split`: For splitting the dataset into training and testing sets.
  - `RandomForestRegressor`: For building and training the predictive model.
  - `metrics`: For evaluating the model's performance using R-squared error.

## Steps to Run the Project

1. **Clone the Repository**:  
   ```bash
   git clone <repository_url>
   ```

2. **Install Required Libraries**:  
   Install the necessary Python libraries using `pip`:
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn
   ```

3. **Run the Script**:  
   Execute the script to train the model and visualize the results:
   ```bash
   python gold_price_prediction.py
   ```

## Dataset
The dataset (`gld_price_data.csv`) contains the following columns:
- **Date**: The date of the recorded data.
- **SPX, USO, SLV, EUR/USD**: Features related to market and currency data.
- **GLD**: The target variable representing the gold price.

## Visualizations
1. **Heatmap**: Shows correlations between features.
2. **Distribution Plot**: Displays the distribution of the target variable (GLD price).
3. **Prediction Plot**: Compares actual and predicted values for the GLD price.

## Results
The model achieves a good R-squared score, indicating its accuracy in predicting gold prices based on the features provided.

## Future Improvements
- Experiment with other regression models to improve accuracy.
- Perform feature engineering to derive additional insights from the data.
- Incorporate time-series analysis to capture temporal trends in gold prices.

---
