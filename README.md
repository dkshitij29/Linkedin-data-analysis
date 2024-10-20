# LinkedIn Data Analysis (Jupyter Notebook Version)

## Overview

This project provides a notebook-based analysis of your LinkedIn connections and messages. By using the data exported from LinkedIn, this tool allows you to gain insights into your professional network, message trends, and communication patterns.

### Features

- **Analyze LinkedIn Connections**: Get insights into the top companies, job roles, and the connection trends over time.
- **Analyze LinkedIn Messages**: Perform sentiment analysis on your messages, track message volume, and identify your most frequent contacts.
- **Visualization**: Interactive plots and charts to better understand your connections and messaging data.

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Data Files](#data-files)
- [Contributing](#contributing)
- [License](#license)

---

## Installation

### Prerequisites

To run this project, ensure you have the following installed:

- [Python 3.x](https://www.python.org/downloads/)
- Jupyter Notebook or JupyterLab
- Required Python packages (listed in `requirements.txt` if available)

### Install the Required Packages

Use the following command to install necessary packages:

```bash
pip install pandas matplotlib seaborn textblob
```

---

## Usage

### Step 1: Export LinkedIn Data

- Go to [LinkedIn Data Export](https://www.linkedin.com/help/linkedin/answer/50191/downloading-your-account-data) and download your **Connections** and **Messages** CSV files.

### Step 2: Place Data Files

- Place the exported CSV files (`Connections.csv` and `messages.csv`) in the `Data/` directory.

### Step 3: Run the Jupyter Notebook

- Open the `test.ipynb` Jupyter Notebook using JupyterLab or Jupyter Notebook:
  ```bash
  jupyter notebook test.ipynb
  ```

- The notebook contains the necessary steps to:
  - Load and clean the CSV data.
  - Perform analysis on connections and messages.
  - Visualize the data using various charts.

---

## Data Files

***Note***: I have not added the csv files as they are my personal data.
The data files used in this project are:

- **`Data/Connections.csv`**: Contains information about your LinkedIn connections (name, job title, company, date connected, etc.).
- **`Data/messages.csv`**: Contains message data including sender, recipient, message content, and date.

---

## Contributing

Contributions are welcome! If you'd like to contribute:

1. Fork the repository.
2. Create a feature branch: `git checkout -b feature-branch-name`.
3. Commit your changes: `git commit -m 'Add a new feature'`.
4. Push the branch: `git push origin feature-branch-name`.
5. Open a pull request.

