# Airports Flight Price Visualization

This project fetches flight prices from an origin airport to multiple destinations using the **Amadeus API**, processes the data, and generates a CSV ready for visualization in **Kepler.gl**.

## 🚀 Overview
- Randomly selects a subset of airports from `airports.csv`.
- Fetches the cheapest available flight from the origin airport (`MXP`) to each destination for a date 30 days from today.
- Assigns each flight a **price bucket** and **color** for visualization.
- Saves results to `airports_with_prices.csv`.

## 📊 Data
- Input CSV: `airports.csv`
- Kaggle dataset source: https://www.kaggle.com/datasets/samvelkoch/global-airports-iata-icao-timezone-geo?resource=download
- Output CSV: `airports_with_prices.csv` (ready for Kepler.gl)
