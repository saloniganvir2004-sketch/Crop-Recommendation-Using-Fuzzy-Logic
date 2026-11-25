# Fuzzy Logic-Based Crop Recommendation System

## Project Overview

This project implements a Fuzzy Logic-Based Crop Recommendation System using Python and the Scikit-Fuzzy library.

The system evaluates environmental conditions and recommends suitable crops using fuzzy membership functions and a rule-based inference mechanism.

## Input Parameters

- Temperature (0–50°C)
- Humidity (0–100%)
- Rainfall (0–300)

## Fuzzy Membership Functions

Each input parameter is classified into three linguistic categories:

- Low
- Medium
- High

## Recommended Crops

The system recommends three crops:

- Wheat
- Maize
- Rice

## Implemented Techniques

1. Fuzzy input and output variable definition.
2. Triangular membership function generation.
3. Fuzzy rule construction.
4. Mamdani-style fuzzy inference.
5. Centroid defuzzification.
6. Crop recommendation based on calculated output.

## Technologies Used

- Python
- NumPy
- Pandas
- Scikit-Fuzzy
- Google Colab

## Project Structure

Crop-Recommendation-Using-Fuzzy-Logic/
├── Crop_Recommendation_Fuzzy_Logic.ipynb
├── README.md
└── requirements.txt

## Execution

1. Open the notebook in Google Colab.
2. Upload the required Crop_recommendation.csv file.
3. Execute the notebook cells sequentially.
4. Enter temperature, humidity, and rainfall values.
5. Observe the recommended crop.

