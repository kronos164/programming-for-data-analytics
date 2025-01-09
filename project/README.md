# Programming for data analytics

Repository for ATU module assessment 

***

# Wind Speed and Wind Farm Analysis in Ireland

## Project Overview

This project analyzes historical wind speed data across Ireland's weather stations and examines wind farm distribution patterns. The analysis combines meteorological data with wind farm locations to provide insights into Ireland's wind energy landscape.

## Features

- Historical wind speed data analysis from multiple weather stations
- Quarterly (trimester) wind speed pattern analysis
- Geospatial visualization of wind farms and weather stations
- Comparative analysis of recent (2012-2022) vs historical wind patterns
- Wind farm distribution assessment

## Data Sources

**Weather Data**
- Historical wind speed measurements from Met Éireann weather stations
- Station-specific details including location coordinates and operational periods
- Quarterly wind speed aggregations

**Wind Farm Data**
- Wind farm locations as of June 2022
- Operational wind farm details

## Technical Requirements

```python
pandas==1.5.0
geopandas==0.12.0
matplotlib==3.6.0
numpy==1.23.0
```
## Repository Structure

```
programming-for-data-analytics/project/
|
├── HistWindSpeedIreland/                   # Folder wind speed dataframes
├── Images/                                 # Folder sith images used
├── ROI_map/                                # Folder with Ireland's geodata files
├── WindFarmsIreland/                       # Folder with wind farms dataframes
├── Assingment Description.pdf              # PDF file with the assingment description
├── requirements.txt                        # Python dependencies
├── winds-of-ireland.ipynb                  # Jupyter notebook with the project and data analysis
|
```
## Running the Project


### Option 1: On Your Local Machine

**Using Visual Studio Code and Anaconda:**

1. Clone the repository:
   ```shell
   git clone https://github.com/kronos164/programming-for-data-analytics/tree/main/project
   cd programming-for-data-analytics/project/
   ```
2. Install dependencies:
   ```shell
   conda create --name windspeed_env python=3.8
   conda activate windspeed_env
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook:
   - Launch VS Code.
   - Open the repository folder.
   - Start the Jupyter extension and open `winds-of-ireland.ipynb`.
   - Run all cells to analyze the data.

---

### Option 2: Using GitHub Codespaces

1. Open the repository on GitHub and click **"Code" > "Codespaces" > "Create Codespace"**.
2. GitHub Codespaces will automatically set up the environment.
3. Open `winds-of-ireland.ipynb` in the integrated Jupyter environment.
4. Run all cells to process and analyze the weather data.

## Project Structure

**Data Processing**
- Weather station data cleaning and consolidation
- Wind speed measurement standardization
- Temporal aggregation for quarterly analysis

**Analysis Components**
- Historical wind speed trends
- Seasonal variation assessment
- Geographical distribution patterns
- Recent vs historical wind speed comparisons

## Limitations

- Incomplete weather station coverage in some regions
- Uneven spatial distribution of weather stations
- Temporal gaps in historical data
- Measurement consistency variations across stations
- Wind farm data limited to June 2022
- Potential coordinate accuracy issues in geospatial analysis

## Usage

The project utilizes Python notebooks for analysis and visualization. The main analysis components are organized into separate notebook sections covering data collection, processing, analysis, and visualization.

## Data Processing Pipeline

1. Data collection from multiple weather stations
2. Standardization of wind speed measurements
3. Temporal alignment of measurements
4. Quarterly aggregation
5. Integration with wind farm location data
6. Geospatial analysis and visualization

## Author

***

#### About me:

My name is Cainã Oliveira. I hold a Master's degree in Psychology from the [University of Porto](https://www.up.pt/portal/en/) and am currently advancing my education in data analytics through a postgraduate course at the [Atlantic Technological University: ATU](https://www.atu.ie/). Simultaneously, I am pursuing a Master's in Artificial Intelligence at the [International University of Applied Sciences](https://www.iu.org/). My academic journey reflects a strong commitment to integrating the insights of human behaviour with the cutting-edge technologies of AI and data science, aiming to harness these disciplines in innovative and impactful ways.

![IT](https://erp.today/wp-content/uploads/2022/12/Artificial_Intelligence-2048x1024.jpg)