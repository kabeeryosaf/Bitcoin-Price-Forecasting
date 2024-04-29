# Bitcoin Price Forecasting with Linear Regression

Welcome to the repository of our Bitcoin price forecasting project. This project aims to predict Bitcoin prices using linear regression, a powerful machine learning technique. We'll be using the `coin_Bitcoin.csv` dataset, focusing on creating a target column by averaging the low and high prices, and applying linear regression to find the error.

## Table of Contents

- [About the Project](#about-the-project)
- [Getting Started](#getting-started)
- [Data Preparation](#data-preparation)
- [Linear Regression Model](#linear-regression-model)
- [Error Calculation](#error-calculation)
- [Divide Data into Training and Testing](#divide-data-into-training-and-testing)
- [Draw the Linear Regression Line](#draw-the-linear-regression-line)
- [Custom Linear Regression Implementation](#custom-linear-regression-implementation)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## About the Project

This project is designed to provide a practical approach to Bitcoin price forecasting using linear regression. By following a step-by-step process, we aim to demonstrate the application of linear regression in predicting financial markets.

### Built With

- [Python](https://www.python.org/)
- [Pandas](https://pandas.pydata.org/)
- [NumPy](https://numpy.org/)
- [Scikit-learn](https://scikit-learn.org/)
- [Matplotlib](https://matplotlib.org/)

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

- Python 3.6+
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

### Installation

1. Clone the repo
```
git clone https://github.com/kabeeryosaf/Bitcoin-Price-Forecasting-Using-Regression.git
```

2. Navigate to the project directory
```
cd Bitcoin-Price-Forecasting-Using-Regression
```

3. Install the required packages
```
pip install pandas numpy scikit-learn matplotlib
```

## Data Preparation

We start by preparing our data. The `coin_Bitcoin.csv` dataset is used, and a target column is created by averaging the low and high prices. The open and close columns are dropped as they are considered contributions to the same value.

## Linear Regression Model

Using Scikit-learn, we apply a linear regression model to our dataset. This model will help us predict Bitcoin prices based on the features we've selected.

## Error Calculation

After applying the linear regression model, we calculate the mean absolute and mean squared error to evaluate the model's performance.

## Divide Data into Training and Testing

To ensure the model's effectiveness, we divide the dataset into training and testing sets with a 70-30 ratio. This allows us to validate the model's predictions on unseen data.

## Draw the Linear Regression Line

Using Matplotlib, we visualize the linear regression line estimated by our model. This visualization helps us understand the relationship between the features and the target variable.

## Custom Linear Regression Implementation

As a challenge, we implement the linear regression model from scratch. This includes calculating the mean absolute and mean squared error without using any libraries.

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact

Mail - chkabeer20@gmail.com

Project Link: [https://github.com/kabeeryosaf/Bitcoin-Price-Forecasting-Using-Regression](https://github.com/yourusername/Bitcoin-Price-Forecasting-Using-Regression)
