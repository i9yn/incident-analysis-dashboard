# Incident Analysis Dashboard

This is an interactive dashboard built with **Dash** and **Plotly** to visualize incident data. It allows users to filter incidents by various categories and generate dynamic heatmaps to identify trends and hotspots.

## Key Features
- Dynamic filtering by Assignment Group, Category, Service, Issue, Location, and Month.
- On-demand heatmap generation to visualize relationships between different data fields.
- Detailed incident data viewing by clicking on a heatmap cell.
- Exporting filtered data to a CSV file.

---

## Technologies Used
- **Python**: The core language for the application logic.
- **Pandas**: Used for data loading, cleaning, and manipulation.
- **Dash**: The framework used to create the interactive web application.
- **Plotly**: The library used for creating the interactive heatmaps and other visualizations.

---

## How to Run Locally

1. **Clone the repository**:
   ```bash
   git clone [https://github.com/i9yn/incident-analysis-dashboard.git](https://github.com/i9yn/incident-analysis-dashboard.git)
Navigate to the project directory:

Bash

cd incident-analysis-dashboard
Install the required libraries:

Bash

pip install pandas dash plotly openpyxl
Prepare the data: This application requires an Excel file named cleaned_month_shortened.xlsx to function. You must provide your own dataset that matches the structure of the original data and save it with the same file name in the project directory.

Run the application:

Bash

python your_main_dashboard_file.py
Note: Replace your_main_dashboard_file.py with the actual name of your main Python script.

Contact
Author: IBRAHIM ALSAWYAN

GitHub: i9yn
