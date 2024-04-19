# Energy Usage Forecasting with Machine Learning

This repository contains a machine learning project aimed at forecasting energy usage in a residential or commercial building. The model is designed to provide accurate predictions by taking into account various factors that influence energy consumption.

## Problem Statement

For approximately 4.5 months, data was collected from a ZigBee wireless sensor network monitoring temperature and humidity levels in a building. Energy consumption data was recorded using m-bus energy meters, and weather information from Chievres Airport, Belgium was integrated into the dataset. The primary objective is to create a machine learning model that can reliably forecast energy usage based on factors like temperature, humidity, illumination, and time of day.

### Key Objectives

- Develop a machine learning model that accurately predicts energy usage.
- Assist building managers, energy firms, and policymakers in optimizing energy consumption, reducing costs, and minimizing environmental impact.
- Identify patterns and trends in energy consumption for informed decision-making.
- Use the model to create regulations and incentives promoting energy efficiency and sustainability.

## Dataset

The dataset used in this project spans approximately 4.5 months and is structured as follows:

- Wireless sensor network data with 10-minute intervals, averaged over 10-minute periods.
- Energy consumption data recorded every 10 minutes.
- Integrated weather data from Chievres Airport, Belgium.
- Random variables for testing regression models and filtering non-predictive features.

## Getting Started

To get started with this project, follow these steps:

1. Clone the repository to your local machine.
2. Install the required dependencies (list them in a requirements.txt file).
3. Explore the Jupyter notebooks in the `notebooks` directory for data analysis, model development, and evaluation.

## Usage

- You can use the provided Jupyter notebooks to:
  - Explore the dataset.
  - Build, train, and evaluate machine learning models for energy usage forecasting.
  - Visualize the results and insights gained from the models.

## Contributing

If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes.
4. Submit a pull request for review.

## License

This project is licensed under the [MIT License](LICENSE.md).

## Acknowledgments

- The project data sources include a ZigBee wireless sensor network, m-bus energy meters, and weather data from Chievres Airport, Belgium.
- The project was inspired by the need to optimize energy consumption, reduce costs, and minimize environmental impact.

---

Please feel free to customize this README to provide more specific details about your project, including installation instructions, usage guidelines, and any additional acknowledgments or references as needed.
