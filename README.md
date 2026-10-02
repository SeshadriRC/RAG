# RAG - QA

This repository contains a Retrieval Augmented Generation (RAG) application. This application allows you to ingest data and then interact with it through a user-friendly interface.

## Prerequisites

In this project I have used `uv` to install, please feel free to use any package manager to install.

### Install uv (Python package manager):

`curl -LsSf https://astral.sh/uv/install.sh | sh`

### Verify the installation:

`uv --version`

## Clone the repository or Download as zip file

`git clone https://github.com/akash-balakrishnan-22/RAG.git`

## Environment Setup

### Create a Virual Environment

`uv venv`

#### Activate the environment

`source .venv/bin/activate`

#### Install Dependencies

`uv sync`

## Running the Application

### 1. Data Ingestion

Run the data ingestion script to prepare your data:
`uv run ingest.py`

### 2. Start the Application

Add your Groq API key in the .env file
Launch the Streamlit application:
`uv run streamlit run app.py`

## Note:

- Make sure you have the required data files in place before running the ingestion script and change the `config.py` accordingly.
- The application will be available in your browser once Streamlit starts.
- To deactivate the virtual environment simply run `deactivate`.


<img width="828" height="507" alt="image" src="https://github.com/user-attachments/assets/a0b1e88a-b050-4b06-8dfa-6af6f6f6d0d2" />

<img width="1045" height="482" alt="image" src="https://github.com/user-attachments/assets/2cd72929-fce1-4f82-b93e-da1fd85a2b1d" />

<img width="1312" height="682" alt="image" src="https://github.com/user-attachments/assets/48687dcf-a375-4815-b556-5403efe159ff" />


<img width="1227" height="415" alt="image" src="https://github.com/user-attachments/assets/da255479-3adb-48e2-9d3e-3da4aa60998a" />
