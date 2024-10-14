Uber Pickups Data Analysis

  Overview: This project analyzes Uber pickup data in NYC from April to September 2014. We cleaned, visualized, and applied machine learning to predict ride demand based on location and time.

Dataset

  The dataset includes monthly Uber pickup data for 2014 (April-September), which we cleaned by:

- Removing duplicates
- Renaming columns
- Engineering features like `rush_hour` classification and ride `count`.

Data Visualization

  We employed various data visualization techniques to explore the dataset:

- Histograms: Displayed the number of Uber rides ordered per month, hour and per weekday.
- Scatterplots: Visualized latitude and longitude data organized by Uber vehicle type (base).
- Interactive Heatmaps: Created using Folium, with interactive elements via ipywidgets to display ride density over NYC.
- Boxplot, FacetGrid, Violin Plot: These plots were used to compare Uber rides during rush hours and non-rush hours and show distribution patterns.

Machine Learning

  We utilized Random Forest Regression to predict Uber demand based on time and location. The model grouped data by date, time, and location to forecast pickups.

Results

  The analysis provided insights into ride patterns and demand fluctuations throughout the week, highlighting peak times and rush-hour effects. The machine learning model was able to predict ride demand with reasonable accuracy based on location and time.

Tools

- Pandas, Matplotlib, Seaborn for data handling and visualization.
- Folium for interactive maps.
- Scikit-learn for machine learning.
