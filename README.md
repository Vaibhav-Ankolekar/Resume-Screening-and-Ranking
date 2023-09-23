# Project Setup and Configuration

This repository contains code for the **Resume Screening and Ranking Web App**.

## Prerequisites

Before you begin, make sure you have the following software and dependencies installed on your machine:

- Python v3.9.0
- pip package manager
- Git (for cloning the repository)

## Setup Instructions

Follow the steps below to set up and configure the project environment:

### 1. Clone the Repository

Clone the project repository from GitHub using the following command:

```bash
git clone https://github.com/Vaibhav-Ankolekar/Resume-Screening-and-Ranking.git
```

### 2. Install Virtual Environment

If you don't have `virtualenv` installed, you can install it using pip:

```bash
pip install virtualenv
```

### 3. Create and Activate Virtual Environment

Navigate to your project directory and create a virtual environment named `venv`:

```bash
cd Resume-Screening-and-Ranking
```
```bash
virtualenv venv
```

Activate the virtual environment:

For Windows:

```bash
.\venv\Scripts\activate
```

For macOS and Linux:

```bash
source venv/bin/activate
```

### 4. Install Required Packages

Install the required Python packages from `requirements.txt`:

```bash
pip install -r requirements.txt
```

### 5. Download Spacy Model

Download the Spacy model for language processing:

```bash
python -m spacy download en_core_web_lg
```

### 6. Download Stopwords

Execute the script to download stopwords:

```bash
python downloadStopwords.py
```

### 7. Install MongoDB Driver

Install the `pymongo` package with SRV support:

```bash
pip install pymongo[srv]
```

### 8. Install python-dotenv

Install the `python-dotenv` package for managing environment variables:

```bash
pip install python-dotenv
```

### 9. Copy Configuration Files

Copy the `.env` and `client_secret.json` files provided with the project and paste them into the root folder of the project.

### 10. Run the Application

Run the application:

```bash
python app.py
```

The Resume Screening and Ranking Web App should now be up and running. Access it in your web browser at the specified address (`http://localhost:5000`) and begin using the application.
