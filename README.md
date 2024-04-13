# College Admission Logistic Regression

This project demonstrates the application of logistic regression to predict college admissions based on student scores. It showcases the setup and execution of a machine learning model in a Google Colab environment using Python's sklearn library.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Data Description](#data-description)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Project Overview

The "College Admission Logistic Regression" project predicts student admissions utilizing logistic regression techniques based on standardized test scores from a dataset. The project demonstrates comprehensive steps from data loading and preprocessing to model training and evaluation.

## Features

- **Data Loading and Preparation**: Seamless integration with Google Colab for data handling.
- **Model Training**: Utilization of logistic regression for predictive analysis.
- **Performance Evaluation**: Metrics such as precision, recall, and F-score are used to evaluate the model's effectiveness.

## Data Description

The dataset primarily includes:
- **CET_score**: The score obtained by students.
- **Admitted**: Binary indicator (1 for admitted, 0 for not admitted).

## Installation

Set up the project environment using Google Colab for efficient execution:

```bash
from google.colab import drive
drive.mount('/content/drive')
```

Clone the repository:
```bash
git clone https://github.com/ascender1729/CollegeAdmissionLogisticRegression.git
cd CollegeAdmissionLogisticRegression
```

## Usage

Before running the notebook, install the required Python libraries. Execute the following commands to ensure all dependencies are installed:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

The libraries you will use in this project include:
- `pandas`: For data manipulation and analysis.
- `numpy`: To work with arrays and perform mathematical operations.
- `matplotlib.pyplot`: For creating static, animated, and interactive visualizations in Python.
- `seaborn`: A Python data visualization library based on matplotlib, providing a high-level interface for drawing attractive statistical graphics.
- `sklearn.model_selection`: Specifically `train_test_split`, to split the data into training and testing sets.
- `sklearn.linear_model`: Specifically `LogisticRegression`, to perform the logistic regression analysis.
- `sklearn.metrics`: Includes `classification_report`, `confusion_matrix`, and `precision_recall_fscore_support`, for model evaluation.

Execute the notebook within Google Colab to follow the detailed steps from data preprocessing to model evaluation.

## Contributing

Contributions to enhance the model or improve methodologies are highly appreciated. Please fork the repository and submit pull requests for review.

## License

This project is released under the MIT License. See the LICENSE file for more details.

## Contact

Pavan Kumar - pavankumard.pg19.ma@nitp.ac.in

LinkedIn: [@ascender1729](https://www.linkedin.com/in/im-pavankumar)

Project Link: [College Admission Logistic Regression](https://github.com/ascender1729/CollegeAdmissionLogisticRegression)
