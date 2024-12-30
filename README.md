
**Description:**

This project aims to analyze the obtained dataset which contains the properties of soil and weather conditions in
order to recommend the best crop for farmers to grow, so that they can get bountiful harvest and avoid loss of crops due to growing unsuitable crops. This will also determine what kind of soil is needed to grow which crop, which can be an indicator of what fertilizers and others product the farmers may need to use if they wanted to grow any specific crop.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## **Dataset:**
The datasets being used in our project are from the following two sources:


1.   
https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset
2.   https://data.mendeley.com/datasets/8v757rr4st/1

Both of these datasets are not in the same format (i.e Number of Columns, Column Names etc) and as such transformation of dataset is required in order to incorporate both of them for the use of the project.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
**Dataset # 1(Kaggle Dataset):**

The first dataset we obtained from kaggle had the following columns:


*   N: Nitrogen content in soil.
*   P: Phosphorus content in soil.
*   K: Potassium content in soil.
*   temperature: Average temperature.
*   humidity: Average humidity.
*   ph: Soil pH value
*   rainfall: Rainfall amount.
*   label: Target crop type.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Dataset # 2(Mendeley Dataset):**

The second dataset we obtained from mendeley has the following columns:

*   **Soilcolor**: Describes the color of the soil (e.g., "Yellowish brown", "red").
*   **Ph**: Soil pH value, indicating soil acidity or alkalinity.
*   **K**: Potassium content in the soil.
*   **P**: Phosphorus content in the soil.
*   **N**: Nitrogen content in the soil.
*   **Zn**: Zinc content in the soil (a micronutrient).
*   **S**: Sulfur content in the soil (a secondary nutrient).
*   **QV2M-W, QV2M-Sp, QV2M-Su, QV2M-Au**: Specific humidity at 2 meters for Winter, Spring, Summer, and Autumn, respectively.
*   **T2M_MAX-W, T2M_MAX-Sp, T2M_MAX-Su, T2M_MAX-Au**: Maximum temperature at 2 meters for each season.
*   **T2M_MIN-W, T2M_MIN-Sp, T2M_MIN-Su, T2M_MIN-Au**: Minimum temperature at 2 meters for each season.
*   **PRECTOTCORR-W, PRECTOTCORR-Sp, PRECTOTCORR-Su, PRECTOTCORR-Au**: Corrected total precipitation(rainfall) for each season.
*   **WD10M**: Wind direction at 10 meters.
*   **GWETTOP**: Surface soil moisture.
*   **CLOUD_AMT**: Cloud cover amount.
*   **WS2M_RANGE**: Wind speed range at 2 meters.

This dataset contained comprehensive data obtained from NASA's cloud infrastructure. But in order to use it in our project, We will need to transform this data to match with the data set obtained from Kaggle.

