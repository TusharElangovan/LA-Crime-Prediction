# Crime Severity Prediction in Los Angeles County  

## Project Description  
This project aims to analyze and predict crime severity rates in Los Angeles County using deep learning methods. The motivation behind this project stems from the ongoing social and political discourse around police effectiveness and resource allocation, particularly following movements such as BLM and the aftermath of George Floyd's tragic death.  

The project's primary goal is to provide actionable insights into crime patterns and severity levels across various regions in Los Angeles. With accurate predictions, we hope to assist the LAPD in allocating resources more effectively and addressing citizens' concerns regarding safety and law enforcement operations.  

## Dataset  
The dataset used in this project contains approximately 1 million crime reports from Los Angeles County, spanning the years 2020 to 2024 (sourced from Gostinski, C.). It includes 28 columns with the following key features:  
- **Crime Types**: Robbery, theft, assault, homicide, etc.  
- **Temporal Details**: Date, time, and location of incidents.  
- **Victim Demographics**: Age, gender, and other details.  
- **Incident-Specific Data**: Involvement of weapons, premises of crimes, arrest statuses, etc.  
- **Geographical Details**: Area names and coordinates for spatial analysis.  

This comprehensive dataset allows for a detailed exploration of crime trends, victim profiles, and the efficiency of law enforcement efforts over time.  

## Files Included  
1. **Reports**:  
   - Project report summarizing the findings, analysis, and recommendations for LAPD resource allocation.  

2. **Notebooks**:  
   - `EDA.ipynb`: Contains exploratory data analysis (EDA) and visualizations to understand crime trends, patterns, and victim demographics.  
   - `Model.ipynb`: Implements the deep learning model used to predict crime severity across LA County regions.  

3. **Other Files**:  
   - Preprocessed dataset (if included).  
   - Any additional supporting files or scripts.  

## Tools and Libraries Used  
- **Programming Language**: Python  
- **Libraries for EDA**:  
  - Pandas  
  - NumPy  
  - Matplotlib  
  - Seaborn  
  - Geopandas (for spatial analysis)  
- **Libraries for Modeling**:  
  - TensorFlow/Keras (for deep learning)  
  - Scikit-learn (for preprocessing and evaluation metrics)  
- **Other Tools**: Jupyter Notebook for interactive coding and visualizations.  

## Project Workflow  
1. **Data Exploration and Cleaning**:  
   - Initial exploration of the dataset to understand its structure and identify missing values or anomalies.  
   - Data cleaning and preprocessing to ensure the dataset is ready for analysis.  

2. **Exploratory Data Analysis (EDA)**:  
   - Visualizations to identify trends, patterns, and relationships between crime types, locations, and victim demographics.  
   - Spatial analysis to highlight high-crime areas across LA County.  

3. **Model Development**:  
   - Deep learning model built using TensorFlow/Keras to predict crime severity based on features like crime type, time, location, and demographics.  
   - Hyperparameter tuning to improve model accuracy and performance.  

4. **Evaluation**:  
   - Assess model accuracy using metrics such as Mean Absolute Error (MAE) and R-squared.  
   - Compare predicted crime severity rates with actual data to evaluate model effectiveness.  

5. **Recommendations**:  
   - Insights and recommendations for LAPD to optimize resource allocation and address safety concerns in high-crime areas.  

## How to Use  
1. Clone this repository:  
   ```bash  
   git clone https://github.com/TusharElangovan/LA-Crime-Prediction
2. Download the Notebooks:
   ```bash
   jupyter notebook EDA.ipynb  
   jupyter notebook Model.ipynb  
