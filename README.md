# Next-Gen Info Retrieval with LlamaIndex and Google Gemini

This project focuses on developing a next-generation information retrieval system using **LlamaIndex** and **Google Gemini** to efficiently search and retrieve relevant data from various sources such as PDFs and databases.

## Project Structure

- **Data**: Contains the dataset used for information retrieval experiments.
- **Experiments**: Directory for conducting and storing experimental results.
- **QAWithPDF**: Core module for handling Question and Answer (QA) retrieval from PDF documents.
- **QApplication.egg-info**: Metadata and distribution information for the application.
- **__pycache__**: Compiled Python files to optimize runtime.
- **build/lib/QAWithPDF**: Built libraries for the QA module.
- **dist**: Distribution files generated for deployment.
- **logs**: Contains logs generated during experiments and usage.
- **notebook**: Jupyter notebooks for experimentation and exploratory analysis.
- **storage**: Persistent storage for data, results, or intermediary files.
- **.gitignore**: Specifies files and directories to be ignored by Git.
- **StreamlitApp.py**: A web app for the retrieval system built using Streamlit for user interaction.
- **exception.py**: Custom exception handling module.
- **logger.py**: Module for logging errors and events during execution.
- **requirements.txt**: List of dependencies required to run the project.
- **setup.py**: Setup script for installing the package.
- **template.py**: Utility module for handling templates.

## Features

- **QA Retrieval from PDF**: Uses LlamaIndex to process PDF documents and retrieve answers based on queries.
- **Streamlit App**: A web interface for running and interacting with the retrieval system.
- **Efficient Search**: Combines the power of LlamaIndex and Google Gemini for quick and accurate information retrieval.
- **Custom Logging**: Logs execution and events for better tracking and debugging.
- **Custom Exceptions**: Gracefully handles errors and exceptions.

## Installation

1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd <repository_name>


2. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the setup:
   ```bash
   python setup.py install
   ```

## Running the Application

To start the **Streamlit** application, use the following command:
```bash
streamlit run StreamlitApp.py
```

## Directory Overview

- **Data**: Stores input datasets, including PDFs.
- **Experiments**: Houses experiments related to information retrieval techniques.
- **logs**: Execution logs for monitoring and debugging purposes.
- **notebook**: Jupyter notebooks for interactive development and experimentation.

## Logging

- **logger.py** is configured to log important events and errors during the retrieval process.
- You can check the logs in the `logs/` directory for details.

## Error Handling

- **exception.py** provides custom error classes to handle different error scenarios gracefully.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```

This README gives an overview of the project structure, explains key modules, and provides instructions on how to set up and run the application. You can further customize it as needed based on specific project details.
