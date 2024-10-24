Project Overview
----------------

This project involves the analysis of a financial debt account portfolio through clustering techniques. The goal is to uncover actionable insights and create targeted strategies for each segment, based on customer characteristics and financial behaviors. K-means clustering has been applied to categorize accounts into different risk profiles, enabling strategic decision-making for debt recovery and management.

Table of Contents
-----------------

-   [Prerequisites](#prerequisites)
-   [Installation](#installation)
-   [Data Description](#data-description)
-   [Usage](#usage)
-   [Clustering Process](#clustering-process)
-   [Author](#author)

* * * * *

## Prerequisites
-------------

Before you begin, ensure you have the following:

-   Python 3.8+
-   Libraries: `pandas`, `seaborn`, `matplotlib`, `scikit-learn`

You can install the necessary libraries using:

`pip install pandas seaborn matplotlib scikit-learn`

## Installation
------------

1.  Clone the repository to your local machine:

    `git clone https://github.com/your-repository-link.git`

2.  Navigate to the project directory:

    `cd your-project-directory`

3.  Install the required dependencies:

    `pip install -r requirements.txt`

Data Description
----------------

Two datasets are used for this analysis:

-   **Transaction Data**: Contains details about financial debt accounts, such as balances, payment history, and account status.
-   **Bureau Data**: Includes customer-specific information such as credit lines, defaults, and bankruptcy status.

Example of columns:

-   `Account_Current_Balance`: The current balance of the debt account.
-   `No_of_Satisfied_Credit_Lines`: Number of credit lines satisfied by the customer.
-   `Months_Since_Last_Payment`: Duration since the last payment made by the customer.

## Usage
-----

### 1\. Loading the Data

Modify the file paths for loading your data in the script.

`transaction_data = pd.read_csv('path_to_transaction_data.csv')
bureau_data = pd.read_csv('path_to_bureau_data.csv')`

## Clustering Process
-----
The K-means clustering process is applied to identify unique customer segments with similar financial behaviors. Each cluster is analyzed and labeled based on characteristics such as:

High-risk vs low-risk customers
Non-payers vs regular payers
Active bankruptcies
Arrears ratio
Clusters are then examined individually to provide tailored debt management strategies.

## Author
------

-   [Millie Ellis](https://github.com/milbot1992)
