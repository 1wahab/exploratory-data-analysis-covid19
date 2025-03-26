# COVID-19 Exploratory Data Analysis (EDA) 🌍📊

![Image](https://github.com/user-attachments/assets/bd6ab0e5-fe14-4504-8488-d668635e9343)

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Dataset](#dataset)
- [Folder Structure](#folder-structure)
- [Prerequisites](#prerequisites)
- [Setup](#setup)
- [Usage](#usage)
- [Visualizations](#visualizations)
- [Analysis Insights](#analysis-insights)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Project Overview
This repository contains a comprehensive exploratory data analysis (EDA) of COVID-19 dataset. The analysis includes visualization of confirmed cases, deaths, recoveries, and active cases across different countries and provinces around the world.

## Features
✨ Interactive visualizations of COVID-19 data
✨ Analysis of death ratios across countries
✨ Province-level analysis for specific countries
✨ Time-series analysis of COVID-19 trends
✨ User-friendly Jupyter notebook implementation

## Dataset
The dataset used in this analysis contains COVID-19 data with the following columns:
- Province/State
- Country/Region
- Lat (Latitude)
- Long (Longitude)
- Date
- Confirmed cases
- Deaths
- Recovered cases
- Active cases
- WHO Region

You can find the dataset in the `data/raw/` directory.

## Folder Structure
```
covid-19-eda/
│
├── data/
│   ├── raw/                  # Raw dataset files
│   │   └── covid_19_clean_complete.csv
│   │
│   └── processed/            # Processed datasets
│       ├── covid_19_aggregated.csv
│       └── covid_19_aggregated2.csv
│   
├── notebooks/                # Jupyter notebooks
│   └── EDA_Covid-19.ipynb
│
├── requirements.txt          # Python dependencies
├── .gitignore                # Files to ignore in Git
├── LICENSE                   # Project license
└── README.md                 # Project documentation
```

## Prerequisites
Before you begin, ensure you have installed the following:
- Python 3.7+
- Jupyter Notebook
- Git
- Basic knowledge of Python and data analysis

## Setup
### Step 1: Clone the Repository
```bash
git clone https://github.com/1wahab/covid-19-eda.git
cd covid-19-eda
```

### Step 2: Create a Virtual Environment (Recommended)
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### Step 3: Install Dependencies
```bash
pip install -r requirements.txt
```

## Usage
### Running the Notebook
1. Open Jupyter Notebook:
```bash
jupyter notebook
```

2. Navigate to the `notebooks` directory and open `EDA_Covid-19.ipynb`

### Data Processing
The processed data files in the `data/processed` directory were generated from the raw data using data cleaning and aggregation techniques.

## Visualizations
### Top 10 Countries by Death Ratio
![Image](https://github.com/user-attachments/assets/65a68b29-4a5a-490b-b6d5-d5e80d738050)

### Confirmed Cases and Deaths by Province/State in Australia
![Image](https://github.com/user-attachments/assets/4ad71d8e-ab81-47d3-bbe4-5a3a7c0c9cd1)

### COVID-19 Trends Over Time
![Image](https://github.com/user-attachments/assets/ef5d37df-deb0-4365-83c5-b348e4b16e69)

## Analysis Insights
1. **Death Ratio Variation**: Countries exhibit significant variation in death ratios, likely due to differences in healthcare systems, population demographics, and reporting practices.
2. **Province-Level Disparities**: Within countries like Australia, certain provinces show higher case numbers and death tolls than others.
3. **Temporal Trends**: The data reveals distinct waves of COVID-19 infections over time, with varying peak magnitudes across regions.

## Contributing
Contributions are welcome! Please follow these guidelines:
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- Data source: [Original Data Provider]
- Inspiration from various COVID-19 analysis projects
- The open-source community for providing valuable tools and libraries
