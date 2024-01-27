# Sports-budget-allocation-using-ML
# Sports Budget Allocation Prediction
This project focuses on predicting the budget allocation for sports based on historical data. The predictive model utilizes linear regression and is deployed through a Gradio interface, allowing users to forecast the budget for a future year.

## Overview

The core components of the project include:

- **Dataset**: The dataset (`budget_allocation_for_sports.csv`) comprises information about budget allocations and corresponding years. This dataset is crucial for training the linear regression model.

- **Linear Regression Model**: The predictive model is a simple linear regression implemented using the scikit-learn library. It analyzes the numerical years to forecast the budget allocation for sports.

- **Gradio Interface**: The Gradio library is employed to create a user-friendly interface for interacting with the predictive model. Users can input a future year, and the interface will provide the predicted budget for that year.

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

Access the provided URL in your web browser to interact with the prediction interface.

## Contribution Guidelines

If you wish to contribute to the project:

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

Feel free to customize this template further based on your specific project details.
