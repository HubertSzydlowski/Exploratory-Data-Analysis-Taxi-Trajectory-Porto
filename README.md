# Exploratory Data Analysis: Taxi Trajectory Porto

## **🧑‍💻 Author**

### Hubert Szydłowski

---

## 🎯 Project Objective
The main goal of this project is to prepare the data for future modeling through Exploratory Data Analysis (EDA).

---

## 📂 Dataset Description

- **Dataset name**: `train.csv`  
- **Source**: [Kaggle - Taxi Trajectory Data Set](https://www.kaggle.com/datasets/crailtap/taxi-trajectory)  
- **Domain**: Transportation  
- **Description**: The dataset contains trajectory data for all 442 taxis operating in Porto, Portugal, over a full year from July 1, 2013 to June 30, 2014.

---

## 📊 Dataset Structure

- **Number of records**: 1,710,670  
- **Number of variables**: 9

---

## 🧾 Variable Descriptions:

- `TRIP_ID` *(string)* – Unique identifier of each trip.  
- `CALL_TYPE` *(char)* – Method of taxi request:  
  - `A` – dispatched from central  
  - `B` – picked up at a taxi stand  
  - `C` – hailed from the street  
- `ORIGIN_CALL` *(integer)* – Identifier for the client’s phone number (only for `CALL_TYPE = A`).  
- `ORIGIN_STAND` *(integer)* – Identifier of the taxi stand (only for `CALL_TYPE = B`).  
- `TAXI_ID` *(integer)* – Unique identifier of the driver.  
- `TIMESTAMP` *(integer)* – Start time of the trip (Unix timestamp).  
- `DAY_TYPE` *(char)* – Type of the day:  
  - `A` – normal day/weekend  
  - `B` – holiday/special day  
  - `C` – day before a holiday  
- `MISSING_DATA` *(boolean)* – Indicates if any GPS data is missing.  
- `POLYLINE` *(string)* – List of GPS coordinates (every 15 seconds), representing the trip's trajectory.

---

## 🧠 Analysis Summary

During the analysis:
- Missing data was identified and its impact on the dataset evaluated.
- Data was cleaned to ensure reliability for future modeling.
- Variable distributions and inter-variable relationships were examined.
- It was observed that the dataset's analytical potential may be limited due to weak correlations.
- Tools like correlation matrices were effectively used to identify variable relationships.
