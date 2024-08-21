# Google Play Store App Analytics

This repository contains a comprehensive analysis of the Android app market using data from the Google Play Store. The analysis compares thousands of apps available on the platform, examining factors like ratings, size, reviews, pricing, and more. The data was originally scraped from the Google Play Store by Lavanya Gupta in 2018.

## About the Dataset

**Data Source:**  
The data used in this analysis is sourced from Kaggle. It includes information about various apps available on the Google Play Store, including their reviews, ratings, size, price, and more. The original dataset can be found [here](https://www.kaggle.com/lava18/google-play-store-apps).

## Project Structure

### 1. Data Cleaning and Preparation
- **Removing Unnecessary Columns:**  
  The columns `Last_Updated` and `Android_Version` were dropped as they were not relevant to the analysis.
  
- **Handling NaN Values:**  
  Rows with missing values in the `Rating` column were removed.
  
- **Removing Duplicates:**  
  Duplicate entries in the dataset were identified and removed.

### 2. Exploratory Data Analysis (EDA)
- **Highest Rated Apps:**  
  Identified the highest-rated apps and discussed potential issues with relying solely on ratings.
  
- **Largest Apps by Size:**  
  Analyzed the size of the largest apps and speculated on possible size limitations.
  
- **Apps with Most Reviews:**  
  Listed the apps with the highest number of reviews and checked if any paid apps were among the top 50.

### 3. Data Visualization
- **Content Ratings Distribution:**  
  Visualized the distribution of apps across different content ratings using pie and donut charts.
  
- **Installations Analysis:**  
  Converted the `Installs` column to numeric format and analyzed the distribution of installation counts across apps.
  
- **Revenue Estimation:**  
  Estimated the potential revenue of paid apps by multiplying price by the number of installs and identified the top 10 highest-grossing paid apps.

- **Category Analysis:**  
  Used bar charts to analyze the competition and popularity across different app categories.
  
- **Genres Analysis:**  
  Explored the distribution of apps across different genres and visualized the top genres using a bar chart.

- **Free vs. Paid Apps:**  
  Created grouped bar charts to compare the number of free and paid apps in each category.

### 4. Advanced Analysis
- **Downloads Analysis by App Type:**  
  Used box plots to compare the number of downloads between free and paid apps.
  
- **Revenue Analysis by Category:**  
  Visualized the potential revenue for paid apps across different categories and analyzed pricing strategies.

## Technologies Used

- **Pandas**: Data manipulation and analysis.
- **Plotly Express**: Interactive data visualizations.
- **Python**: Programming language for data processing and visualization.

## How to Use

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Prathamesh326/Google-Play-Store-App-Analytics.git
   ```
2. **Install Dependencies:**
   Ensure you have the required Python packages by installing them via pip:
   ```bash
   pip install pandas plotly
   ```
3. **Run the google colab Notebook:**
   Open the notebook and run the cells to see the analysis in action.

## Conclusion

This analysis provides insights into the Android app market by investigating various aspects of apps available on the Google Play Store. From app ratings to revenue estimates, this project covers a wide range of topics that can help developers, marketers, and data enthusiasts understand the dynamics of the app market.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License.
