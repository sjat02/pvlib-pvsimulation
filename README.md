# Physical Model for PV Performance Simulation 
[PVLib Documentation](https://pvlib-python.readthedocs.io/en/stable/index.html)


## Overview

This project focuses on simulating the performance of photovoltaic (PV) systems using a physical model. The simulation is based on data collected from a specific location (59°31’52.54″N 12°37’14.78″E) over a period from September 1, 2021, to August 31, 2022. The project utilizes various Python libraries, including `pvlib`, `numpy`, `pandas`, and `matplotlib`, to analyze and visualize the data.

## Project Structure

The project is organized into several sections within a Jupyter notebook:

1. **Data Import and Preprocessing**:
   - Import necessary libraries.
   - Load and preprocess the PV performance dataset.
   - Set the dataset index to datetime and localize the timezone to UTC.

2. **Data Exploration**:
   - Display the first few rows of the dataset.
   - Check the number of rows and columns.
   - List the data features available in the dataset.

3. **Data Visualization**:
   - Plot irradiance data to understand the dataset better.
   - Focus on key features important for PV modeling, such as Global Horizontal Irradiance (GHI), Diffuse Horizontal Irradiance (DHI), Direct Normal Irradiance (DNI), ambient temperature (`Tamb`), and wind velocity (`WindVel`).

4. **PV System Simulation**:
   - Use the `pvlib` library to simulate PV performance based on the processed data.
   - Visualize the simulation results to gain insights into the PV system's performance.

## Key Features

- **Data Handling**: The project involves loading and preprocessing a CSV file containing PV performance data. The data is indexed by datetime and localized to UTC.
- **Data Analysis**: Basic data exploration is performed to understand the dataset's structure and content. Key features relevant to PV modeling are identified and analyzed.
- **Visualization**: Various plots are generated to visualize the irradiance data, helping to understand the patterns and trends in the dataset.
- **Simulation**: The `pvlib` library is used to simulate the performance of a PV system based on the provided data. The simulation results are visualized to assess the system's efficiency and performance.

## Libraries Used

- **numpy**: For numerical computations.
- **pandas**: For data manipulation and analysis.
- **pvlib**: For PV performance simulation.
- **matplotlib**: For data visualization.
- **pathlib**: For file path manipulations.

## Dataset

The dataset used in this project contains hourly PV performance data, including:
- Year, Month, Day, Hour, Minute
- Ambient Temperature (`Tamb`)
- Cloud Opacity (`Cloudopacity`)
- Diffuse Horizontal Irradiance (DHI)
- Direct Normal Irradiance (DNI)
- Global Horizontal Irradiance (GHI)
- Wind Velocity (`WindVel`)

## Usage

To run this project, ensure you have the required libraries installed. You can install them using pip:

```bash
pip install numpy pandas pvlib matplotlib
```

Clone the repository and open the Jupyter notebook to explore the data and run the simulations.

```bash
git clone https://github.com/sjat02/pvlib-pvsimulation.git
```

## Results

The project provides insights into the performance of PV systems based on the given dataset. The visualizations and simulations help in understanding the impact of various environmental factors on PV performance.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## Acknowledgments

- The `pvlib` community for providing a robust library for PV performance simulation.
- The dataset providers for making the PV performance data available.
