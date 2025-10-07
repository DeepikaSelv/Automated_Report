# Automated_Report
# Automated Report Generation with Charts

This project is designed to automate the generation of reports using various data formats such as PDF, CSV, Excel, and text files. It leverages advanced data processing techniques, including data merging, cleaning, standardization, KPI computation, and automatic chart generation. The application also provides insights using a language model and features an advanced OCR model for text extraction.

## Features

- **Data Ingestion**: Supports ingestion from PDF, CSV, Excel, and text files.
- **Data Preprocessing**: Includes cleaning, standardization, and merging of datasets.
- **KPI Computation**: Computes key performance indicators from the ingested data.
- **Insights Generation**: Utilizes LLM insights for data analysis.
- **Automatic Chart Generation**: Generates charts based on the processed data.
- **Executive Summary Generation**: Creates summaries of the analysis results.
- **Report Exporting**: Exports reports in PDF, Excel, and CSV formats.
- **Dynamic Updates**: Allows for real-time updates to reports.
- **Advanced OCR Model**: Extracts text from images and PDFs.
- **Streamlit UI**: Provides an interactive user interface for report generation.

## Project Structure

- `src/main.py`: Entry point of the application.
- `src/config.py`: Configuration settings, including API key input location.
- `src/ui/streamlit_app.py`: Streamlit user interface for interaction.
- `src/api/server.py`: API server for handling requests.
- `src/ingestion/`: Modules for data ingestion from various formats.
- `src/ocr/`: OCR engine and models for text extraction.
- `src/preprocessing/`: Data cleaning, standardization, and merging functions.
- `src/analysis/`: Functions for KPI computation and insights generation.
- `src/charts/`: Chart generation functions and templates.
- `src/export/`: Modules for exporting reports in different formats.
- `src/utils/`: Utility functions for authentication and I/O operations.
- `tests/`: Unit tests for various modules.
- `notebooks/`: Jupyter notebook demonstrating the workflow.
- `docs/`: Documentation for the architecture.
- `examples/`: Sample input data formats.
- `scripts/`: Scripts to run the Streamlit app and API server.
- `.env.example`: Example environment variables.
- `requirements.txt`: Required Python dependencies.
- `Dockerfile`: Docker image definition.
- `LICENSE`: Licensing information.

## Instructions to Run the Project

1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Create a virtual environment and activate it.
4. Install the required dependencies using:
   ```
   pip install -r requirements.txt
   ```
5. Copy `.env.example` to `.env` and input your API key in the appropriate location.
6. To run the Streamlit UI, execute:
   ```
   bash scripts/run_streamlit.sh
   ```
7. To run the API server, execute:
   ```
   bash scripts/run_api.sh
   ```

Make sure to have the necessary permissions and configurations set up for the API key in the `src/config.py` file.
