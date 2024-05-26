# Bike Index Project

![Bike Index](https://raw.githubusercontent.com/sorzkode/BikeIndexProject/master/assets/bIndex.png)

---

Author: **Mister Riley**  
GitHub: [https://github.com/sorzkode/](https://github.com/sorzkode/)  
Kaggle: [https://www.kaggle.com/code/misterriley/bikeindexeda](https://www.kaggle.com/code/misterriley/bikeindexeda)  
License: [MIT License](https://en.wikipedia.org/wiki/MIT_License)

---

## Overview

In this project, we will leverage Python to gain hands-on experience in performing the ETL (Extract, Transform, Load) process and some basic EDA (Exploratory Data Analysis). The project will guide you step by step, suitable for complete beginners or seasoned data professionals. This is the first project in an end-to-end data series that will focus on Data Analytics, Data Science, and Data Engineering.

---

## Data Used

We will extract data from [Bike Index](https://bikeindex.org) using their API (Application Programming Interface), which outputs data in JSON (JavaScript Object Notation) format.

---

## Assumptions

This project assumes that you are on a Windows machine that meets the system requirements of each application we will be utilizing.

---

## Setup

### Bike Index Setup

#### Creating an Account

Bike Index is an online bicycle registration and recovery platform that helps cyclists register and track their bikes, aiding in the recovery of stolen bicycles through a community-driven database and collaboration with law enforcement.

1. Visit the [Bike Index website](https://bikeindex.org/).
2. Click the [SIGN UP](https://bikeindex.org/users/new) button.
3. Fill out the form and click `SIGN UP`.
4. Verify your email.

#### Creating an API Token

1. Visit the [Bike Index website](https://bikeindex.org/).
2. Click the [LOG IN](https://bikeindex.org/session/new) button.
3. Read the [API V3 Documentation](https://bikeindex.org/documentation/api_v3).
4. Click [Add an Application](https://bikeindex.org/oauth/applications).
5. Click the [NEW APPLICATION](https://bikeindex.org/oauth/applications/new) button.
6. Give your application a name. For this project, I'm using the generic `bearer` as a name.
7. Enter a Redirect URI. For this project, I'm using [https://bikeindex.org/documentation/authorize](https://bikeindex.org/documentation/authorize).
8. Click the `SUBMIT` button.
9. Copy your API token and keep it safe. The token is listed under `SECRECT: your_token_string`.

**Example:**

![Bike Index Secret](https://github.com/sorzkode/BikeIndexProject/blob/main/examples/BikeIndexSecret.png?raw=true)

---

## Requirements

- [Python 3](https://www.python.org/downloads/)
- [Requests](https://pypi.org/project/requests/)
- [JSON](https://docs.python.org/3/library/json.html)
- [Pandas](https://pypi.org/project/pandas/)
- [Matplotlib](https://pypi.org/project/matplotlib/)

---

## Setting up and Running .ipynb Files in VS Code

1. **Install Jupyter Extension**: Open VS Code and go to the Extensions view by clicking on the square icon in the sidebar. Search for "Jupyter" and install the extension provided by Microsoft.
   
2. **Open .ipynb File**: Once the extension is installed, open your .ipynb file in VS Code.

3. **Select Kernel**: At the top right corner of the notebook editor, you'll see a dropdown menu. Make sure to select a Python interpreter that has the necessary dependencies installed.

4. **Run Cells**: You can run individual cells by clicking the "Run Cell" button that appears on the left side of each cell, or by using the keyboard shortcut `Shift + Enter`.

5. **Run All Cells**: To run all cells in the notebook, go to the "Run" menu and select "Run All Cells" or use the keyboard shortcut `Ctrl + Enter`.

---






