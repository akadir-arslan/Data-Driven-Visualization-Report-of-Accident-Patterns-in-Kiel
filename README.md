# Visualization of Accident Patterns in Kiel

## Project Overview

This project explores accident patterns in Kiel, Germany, using data provided by the municipality of Kiel. The primary goal is to identify interesting patterns in the accident data and provide visualizations and interpretations to help the municipality take measures to improve road safety.

The project includes four visualizations that analyze different aspects of accident data, such as the number of accidents per district, accident severity distribution, the impact of light conditions, and the distribution of accident types over time. Each visualization is accompanied by a brief description, interpretation, key findings, and recommendations for improving road safety.

## Data

The following geo datasets were used in this project:

- **accidents.geojson**: Contains data on accidents in Kiel between 2016 and 2022. Each record represents an accident and includes fields such as accident type, severity, light conditions, and the coordinates of the accident.
- **districts.geojson**: Contains polygons and other information about the districts of Kiel.
- **roads.geojson**: Represents road segments in Kiel. Note that a single road is often composed of multiple segments.

**Note:** I did not share the datasets in this repository!

## Tools and Libraries

This project was developed using Python with the following libraries:

- `geopandas`: Used for handling geospatial data.
- `matplotlib`: Used for static visualizations.
- `seaborn`: Used for advanced data visualization.
- `pandas`: Used for data manipulation and analysis.
- `altair`: Used for creating interactive visualizations.
- `IPython`: Used to enhance interactivity in Jupyter Notebooks.

## Visualizations

### 1. Map of Kiel with Number of Accidents per District
An interactive map that visualizes the number of accidents per district in Kiel. The map also provides information on the percentage of total accidents that occurred in each district.

### 2. Distribution of Accident Severity and Impact of Light Conditions
This visualization shows the distribution of accident severity in Kiel and highlights the impact of light conditions on accident severity.

### 3. Distribution of Accident Types and Most Common Year of Occurrence
This visualization examines how different types of accidents are distributed and identifies the most common year for each accident type.

### 4. Time Series Analysis of Accidents Over the Years
This visualization presents a time series analysis showing how the number of accidents in Kiel has changed over the years.

## Recommendations

Based on the visualizations, the following recommendations are provided for the municipality of Kiel:

1. Focus on improving road safety in the seven central districts where accidents are concentrated.
2. Enhance road lighting, especially in twilight conditions, to reduce accident severity.
3. Investigate the high accident rates in 2016 and analyze potential changes in road conditions or regulations that may have contributed to this spike.
4. Analyze the decline in accidents after 2018 to identify effective measures that can be expanded to other areas of Kiel.
5. Share the findings with the public and promote awareness among drivers, especially regarding the most common accident types and locations.

## How to Run

To run this project, you will need to have Python installed along with the following libraries:

```bash
pip install geopandas matplotlib seaborn pandas altair jupyterlab
