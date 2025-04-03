# Data Pipeline Project

## Overview
This project demonstrates a simple data pipeline that extracts, transforms, and loads (ETL) data into a database. The pipeline processes an `orders.csv` dataset, cleans missing values, and stores it in a structured format using SQL.

## Features
- **Data Extraction**: Extracts the `orders.csv` file from a ZIP archive.
- **Data Cleaning**: Handles missing values and standardizes data.
- **Data Transformation**: Processes relevant columns to prepare data for storage.
- **Data Loading**: Loads cleaned data into a database using SQLAlchemy and SQL scripts.

## File Structure
```
Data Pipeline Project/
│-- DataPipeline.ipynb    # Jupyter Notebook containing the ETL pipeline
│-- DataPipeline.sql      # SQL script for database operations
│-- orders.csv           # Source dataset
│-- archive.zip          # Compressed dataset (optional)
```

## Requirements
Ensure you have the following installed:
- Python 3.x
- Pandas
- SQLAlchemy
- Jupyter Notebook

Install dependencies using:
```bash
pip install pandas sqlalchemy jupyter
```

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/data-pipeline-project.git
   cd data-pipeline-project
   ```
2. Extract `archive.zip` (if needed).
3. Open `DataPipeline.ipynb` in Jupyter Notebook.
4. Run the notebook cells step-by-step.
5. Verify the cleaned data and ensure it is stored in the database.

## SQL Database Integration
The pipeline interacts with a SQL database using `DataPipeline.sql`. Modify connection details in the Jupyter Notebook before execution.

## Contributing
Contributions are welcome! Feel free to fork the repository and submit pull requests.

## Author
Tejas - Data Analyst Enthusiast

## License
This project is for educational purposes.

## Contact
For queries, reach out via GitHub Issues.

