# Project Setup and Configuration

This repository contains code for **Resume Screening and Ranking Web App**.

## Prerequisites

- Python v3.9.0
- pip package manager

## Setup Instructions

Follow the steps below to set up and configure the project environment:

### 1. Install Virtual Environment

If you don't have `virtualenv` installed, you can install it using pip:

```bash
pip install virtualenv
```

### 2. Create and Activate Virtual Environment

Create a virtual environment named `venv` and activate it:

```bash
virtualenv venv
```

For Windows:

```bash
.\venv\Scripts\activate
```

For macOS and Linux:

```bash
source venv/bin/activate
```

### 3. Install Required Packages

Install the required packages from `requirements.txt`:

```bash
pip install -r requirements.txt
```

### 4. Download Spacy Model

Download the Spacy model:

```bash
python -m spacy download en_core_web_lg
```

### 5. Download Stopwords

Execute the script to download stopwords:

```bash
py downloadStopwords.py
```

### 6. Install MongoDB Driver

Install the `pymongo` package with SRV support:

```bash
pip3 install pymongo[srv]
```

### 7. Install python-dotenv

Install the `python-dotenv` package for managing environment variables:

```bash
pip install python-dotenv
```

### 8. Copy Configuration Files

Copy the `.env` and `client_secret.json` files and paste them into the root folder of the project.

### 9. Run the Application

Run the application:

```bash
py app.py
```
