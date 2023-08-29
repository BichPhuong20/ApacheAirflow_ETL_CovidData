# ETL Covid-19 Data Pipeline using Apache Airflow
This project focuses on designing, implementing, and managing ETL (Extract, Transform, Load) processes for integrating Covid-19 data from various sources into a PostgreSQL database. Additionally, the project utilizes Apache Airflow to automate ETL workflows.

## Project Overview

### 1. ETL Processes and Data Pipeline:
- Python scripts are developed to extract data from multiple Covid-19 data sources.
- Transformation steps are applied to clean and preprocess the data for consistency.
- The cleaned data is loaded into a PostgreSQL database for easy querying and analysis.

### 2.Data Visualization:
- Power BI is employed to create interactive visualizations of the Covid-19 data.
- Dashboards and reports provide insights into trends, patterns, and impacts of the pandemic.

### 3. Apache Airflow Application:
- Apache Airflow is implemented to automate the ETL workflows.
- Tasks are orchestrated, scheduled, and monitored through Apache Airflow's web interface.

## Project Structure
src/: Contains the Python scripts for ETL processes.
database/: Includes the PostgreSQL database schema and setup instructions.
power_bi/: Houses Power BI files and visualizations.
user_guide/: Contains Apache Airflow setup instructions in docx and video formats.
airflow/: Includes Apache Airflow DAGs and configuration files.
Setup Instructions
Database Setup:

Follow the instructions in database/README.md to set up the PostgreSQL database.
ETL Processes:

Navigate to src/ and follow the guidelines in the script's documentation for data extraction, transformation, and loading.
Power BI Visualization:

Open the Power BI file in the power_bi/ directory to explore the visualizations.
Apache Airflow Application:

Follow the user guide in the user_guide/ directory to set up and manage Apache Airflow.
Place the DAG files from the airflow/ directory into your Apache Airflow DAGs folder.
Contributing
Contributions are welcome! If you'd like to enhance the project or add new features, feel free to create a pull request.

License
This project is licensed under the MIT License.

Please note that this README provides a high-level overview of the project. For detailed setup instructions and specific usage guides, refer to the documentation in the respective directories.
