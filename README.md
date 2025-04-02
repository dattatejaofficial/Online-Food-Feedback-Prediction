# Online Food Feedback Prediction

This project aims to develop a machine learning model that predicts whether a customer will reorder food online based on various demographic and behavioral features. Understanding customer ordering patterns can help food delivery companies optimize their services and enhance customer retention.

## Table of Contents

- [Overview](#overview)
- [Project Structure](#project-structure)
- [Setup Instructions](#setup-instructions)
- [Usage](#usage)
- [Extracted Insights](#extracted-insights)
- [Dependencies](#dependencies)
- [License](#license)

## Overview

The dataset used in this project includes the following features:

- **Age**: Age of the customer.
- **Gender**: Gender of the customer.
- **Marital Status**: Marital status of the customer.
- **Occupation**: Occupation of the customer.
- **Monthly Income**: Monthly income of the customer.
- **Educational Qualifications**: Education level of the customer.
- **Family Size**: Number of family members.
- **Latitude**: Latitude of the customer's location.
- **Longitude**: Longitude of the customer's location.
- **Pin Code**: Postal code of the customer's residence.
- **Feedback**: Feedback rating of the customer's last order.
- **Output**: Target variable indicating whether the customer will order again (1) or not (0).

The objective is to predict the 'Output' variable using the other features.

## Project Structure

The repository contains the following files:

- `online-food-feedback-prediction.ipynb`: A Jupyter Notebook that performs data loading, cleaning, exploratory data analysis, model training, and evaluation.
- `onlinefoods.csv`: A CSV file containing the dataset with all the aforementioned features.

## Setup Instructions

To set up and run the project locally, follow these steps:

1. **Clone the Repository**: Use the following command to clone the repository to your local machine:

   ```bash
   git clone https://github.com/dattatejaofficial/Online-Food-Feedback-Prediction.git
   ```

2. **Navigate to the Project Directory**: Move into the project directory:

   ```bash
   cd Online-Food-Feedback-Prediction
   ```

3. **Create a Virtual Environment** (optional but recommended): Set up a virtual environment to manage project dependencies:

   ```bash
   python3 -m venv env
   ```

   Activate the virtual environment:

   - On Windows:
     ```bash
     .\env\Scripts\activate
     ```
   - On macOS/Linux:
     ```bash
     source env/bin/activate
     ```

4. **Install Dependencies**: Install the required Python packages using pip. The necessary packages are listed in the `requirements.txt` file. If `requirements.txt` is not present, you can manually install the following packages:

   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
   ```

## Usage

To run the analysis:

1. **Ensure the Virtual Environment is Activated**: Make sure your virtual environment is active (refer to the setup instructions above).

2. **Run the Notebook**: Open `online-food-feedback-prediction.ipynb` in the Jupyter interface and execute the cells sequentially to perform the analysis and model development.

## Extracted Insights

The exploratory data analysis and modeling have provided the following insights:

- **Demographic Influences**: Certain demographic factors, such as age, marital status, and monthly income, significantly influence a customer's likelihood to reorder food online.

- **Behavioral Patterns**: Feedback from previous orders plays a crucial role in predicting future ordering behavior, with positive feedback correlating strongly with repeat orders.

- **Model Performance**: The Random Forest Classifier achieved an accuracy of approximately 94.87% in predicting whether a customer will reorder, indicating a high level of reliability.

## Dependencies

The project requires the following Python packages:

- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `seaborn`

These dependencies are essential for data manipulation, modeling, and visualization tasks.
