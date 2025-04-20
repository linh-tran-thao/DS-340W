# DS 340W Course Project

## Dataset

CO2 Emissions_Canada.csv – This is the dataset that is used by the code files in this repository to train and evaluate the deep learning models predicting vehicle CO₂ emissions.

This dataset was originally published on the website Kaggle.

Link to Kaggle Data: https://www.kaggle.com/datasets/debajyotipodder/co2-emission-by-vehicles

Table

Column | Description
Model | Vehicle drive or body type (e.g., 4WD, AWD, FFV, SWB, LWB, EWB)
Engine Size (L) | Engine displacement in liters
Cylinders | Number of engine cylinders
Transmission | Transmission type: A = Automatic AM = Automated Manual AS = Automatic with Select Shift AV = Continuously Variable M = Manual 3–10 = Gear count
Fuel Type | X = Regular Gasoline Z = Premium Gasoline D = Diesel E = Ethanol (E85) N = Natural Gas
Fuel Consumption City (L/100 km) | Fuel used per 100 km in city driving
Fuel Consumption Hwy (L/100 km) | Fuel used per 100 km in highway driving
Fuel Consumption Comb (L/100 km) | Combined fuel consumption (55% city, 45% highway)
Fuel Consumption Comb (mpg) | Combined fuel consumption in miles per imperial gallon
CO2 Emissions (g/km) | Tailpipe CO₂ emissions for combined driving

##  Code
- ParentPaper_Code.ipynb – This notebook reproduces the analysis and modeling workflow from the original paper. It includes data cleaning, feature selection, and machine learning model for CO₂ emissions prediction using vehicle data.

## Novelty Ideas
🔍 Quantile Regression: Predicts a range of possible CO₂ emission values, capturing uncertainty instead of just a single estimate.

🚨 Super-Polluter Detection: Identifies the top 5% of highest-emitting vehicles using a classification model for targeted action.

🧩 K-Means Clustering: Segments vehicles by emission behavior, revealing patterns across engine size, fuel type, and efficiency.

- Final_Modification.ipynb – This notebook expands on the original paper with novelty ideas.
## Paper

- Linh to Parent Paper 1: https://www.mdpi.com/2071-1050/15/9/7615
- Link to Parent Paper 2: https://www.mdpi.com/2079-9292/12/10/2288
- Link to Parent Paper 3: https://www.nature.com/articles/s41598-025-87233-y



