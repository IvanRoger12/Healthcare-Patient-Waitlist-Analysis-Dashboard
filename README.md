# Healthcare Patient Waitlist Analysis Dashboard

## Overview
This project provides an interactive dashboard to visualize and analyze patient waitlists in healthcare settings. The dashboard includes key indicators and trends to support decision-making and resource allocation. 

## Features
- **Patient Waitlist Overview**: Displays total waitlists for the current and previous periods.
- **Case Type Bifurcation**: Visualizes waitlist data by case types (Outpatient, Day Case, Inpatient).
- **Age & Time Analysis**: Median wait times segmented by age groups and time bands.
- **Specialty Insights**: Highlights the top 5 specialties based on patient waitlists.
- **Monthly Trends**: Tracks waitlist trends over time for different case types.

## Data
The dataset used includes:
- **Waitlist counts**: Monthly data for outpatient, inpatient, and day cases.
- **Time bands**: Segmentation of patients by wait time duration.
- **Age profiles**: Patient age categories.
- **Specialty information**: Data grouped by medical specialties.

## Visualization Tools
- Interactive charts and graphs for:
  - Case type distribution.
  - Monthly trends.
  - Wait time by age profiles.
- Highlights of key metrics such as median wait times.

## Technologies Used
- **Power BI/Tableau**: For data visualization.
- **Python/Excel**: For data preprocessing.
- **SQL**: For querying and managing datasets.

## Getting Started
1. **Clone Repository**:
   ```bash
   git clone https://github.com/yourusername/healthcare-waitlist-dashboard.git
   cd healthcare-waitlist-dashboard
Install Dependencies: Ensure you have Python and necessary libraries installed if data preprocessing is required:

bash
Copier le code
pip install -r requirements.txt
Data Preparation: Unzip the provided dataset (Data-Mapping-Bg.zip) and ensure files are placed in the data/ directory.

Run the Dashboard

Open the .pbix
Alternatively, use Python scripts for preprocessing or further analysis.
Folder Structure
bash

healthcare-waitlist-dashboard/
│
├── data/                # Raw data files
├── scripts/             # Data preprocessing scripts
├── visualizations/      # Dashboard files (.pbix or Tableau)
├── README.md            # Project documentation
├── requirements.txt     # Python dependencies
Contributions
Contributions are welcome! Please create a pull request with a detailed description of your changes.








