# Sports-budget-allocation-using-ML
# Sports Budget Allocation Prediction
This project focuses on predicting the budget allocation for sports based on historical data. The predictive model utilizes linear regression and is deployed through a Gradio interface, allowing users to forecast the budget for a future year.

## Overview

This project focuses on predicting sports budget allocations based on historical data, utilizing three different regression models: Linear Regression, Decision Tree, and Random Forest. The predictive models are trained on a dataset containing information about budget allocations and corresponding years. Additionally, a Gradio interface has been integrated to facilitate user-friendly predictions for future budget allocations.

## Advantages

1. **Predictive Accuracy:** The project employs three different regression models to provide accurate predictions of sports budget allocations.

2. **Flexibility:** By incorporating multiple regression models, the project allows for flexibility in choosing the most suitable model for the task.

3. **User Interface:** The integration of Gradio provides an interactive and intuitive interface for users to predict sports budget allocations for a given future year.

## Process

### Data Preparation

- The dataset (`budget_allocation_for_sports.csv`) is loaded and cleaned, converting the budget allocation column to numeric values.

- The numerical year is extracted from the 'Years' column to enhance the model's understanding of the temporal aspect.

### Linear Regression Model

- A Linear Regression model is trained on the dataset to establish a baseline for predicting budget allocations.

- The model's accuracy is evaluated using mean squared error.

### Decision Tree Model

- A Decision Tree Regression model is trained to capture non-linear relationships within the data.

- The model's accuracy is assessed using mean squared error.

### Random Forest Model

- A Random Forest Regression model is employed for enhanced predictive performance through an ensemble of decision trees.

- The model's accuracy is measured using mean squared error.

### Gradio Interface Integration

- Gradio is utilized to create an interactive user interface, allowing users to input a future year and receive predictions for the corresponding sports budget allocation.

- The Linear Regression model is used within the Gradio interface for budget predictions.

### Additional Installations

- Necessary libraries such as `gradio`, `typing_extensions`, `pydantic`, `fastapi`, and `scikit-learn-intelex` are installed to support the project's functionality.

Feel free to customize this README based on any additional information or specific details relevant to your project.

## Getting Started

### Prerequisites

Ensure you have the following prerequisites installed:

- Python (>=3.6)
- Pandas
- Scikit-learn
- Gradio

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/your-repo.git
    cd your-repo
    ```

2. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

### Usage

Run the script to launch the Gradio interface:

```bash
python your_script_name.py
```

## Contribution Guidelines

If you wish to contribute to the project:

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

Feel free to customize this template further based on your specific project details.
