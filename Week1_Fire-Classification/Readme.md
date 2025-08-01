# Week 1: Classification of Fire Types in India Using MODIS Satellite Data

This project focuses on classifying different types of fire incidents in India using MODIS satellite data from 2021 to 2023. The goal is to develop a machine learning model that can accurately predict the type of fire event (e.g., forest fire, agricultural burning, volcanic activity, or other thermal anomalies) based on satellite-captured features.

## Project Structure

- `Classification_of_Fire_Types_in_India_Using_MODIS_Satellite_Data.ipynb`  
  Main Jupyter notebook containing data analysis, visualization, and classification model development.
- `modis_2021_India.csv`  
  MODIS fire detection data for India (2021).
- `modis_2022_India.csv`  
  MODIS fire detection data for India (2022).
- `modis_2023_India.csv`  
  MODIS fire detection data for India (2023).

## Data Source

- Data is sourced from NASA’s FIRMS (Fire Information for Resource Management System).
- Each CSV contains thermal anomaly and active fire detection records for India.

## Key Features

- **Data Exploration:**  
  Visualizations and summary statistics to understand fire incident patterns.
- **Feature Engineering:**  
  Selection and transformation of relevant features for classification.
- **Modeling:**  
  Machine learning models (e.g., XGBoost) to classify fire types.
- **Evaluation:**  
  Performance metrics and visualizations to assess model accuracy.

## How to Run

1. Clone this repository or download the project files.
2. Install required Python packages:
    ```sh
    pip install pandas numpy matplotlib seaborn scikit-learn xgboost
    ```
3. Open the notebook `Classification_of_Fire_Types_in_India_Using_MODIS_Satellite_Data.ipynb` in Jupyter or VS Code.
4. Run the cells sequentially to reproduce the analysis and results.






I am adding the link in the readme file since my Model - best_fire_detection_model.pkl file is **460.1 MB**. Any file larger than 25 MB is not accepted in the Github without LFS.
Students, you can also share the link in the github just like I did. If you don't know how to create the readme file, you can download my readme file and edit it.

Link for the Model:
https://drive.google.com/file/d/1K-CkomnFCIaZVmTCCGRVR1wG75_54EZU/view?usp=share_link






## References

- [NASA FIRMS Documentation](https://earthdata.nasa.gov/earth-observation-data/near-real-time/firms)
- [MODIS Active Fire Product Info (LP DAAC)](https://lpdaac.usgs.gov/products/mod14a1v006/)
- [Understanding MODIS Fire Algorithm](https://modis.gsfc.nasa.gov/data/dataprod/mod14.php)

## Notes

- MODIS NRT (Near Real-Time) data may have slightly lower geolocation accuracy, especially from the Aqua satellite.
- The dataset includes various fire types; accurate classification is crucial for disaster response and