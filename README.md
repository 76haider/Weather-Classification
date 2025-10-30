# Weather Classification using Decision Trees

A machine learning project that classifies weather conditions based on meteorological data using Decision Tree algorithms.

## 📋 Project Overview

This project demonstrates supervised classification to predict weather conditions using various meteorological measurements:
- Temperature (°C)
- Dew Point Temperature (°C)
- Relative Humidity (%)
- Wind Speed (km/h)
- Visibility (km)
- Pressure (kPa)

## 🎯 Objectives

- Build a classification pipeline to predict weather conditions
- Analyze the impact of model complexity on performance
- Identify optimal model parameters to prevent overfitting
- Provide a reusable framework for weather prediction

## 📊 Dataset

The dataset contains 2,208 hourly weather observations with 8 columns. Original data had 35 weather classes, which were processed to 17 classes by grouping rare conditions.

**Most Common Weather Conditions:**
- Cloudy (584 samples)
- Snow (395 samples)
- Clear (279 samples)
- Mostly Cloudy (244 samples)
- Mainly Clear (200 samples)

## 🛠️ Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/weather-classification.git
cd weather-classification
