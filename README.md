# Sports-budget-allocation-using-ML

![future-round-vector-minimal-illustration-thin-line-style-machine-learning-ai-innovation-concept-circular-symbol-future-127494158](https://github.com/MaheshwaranSelvam/Sports-budget-allocation-using-ML/assets/115611481/b21c90a9-9e2b-4dff-98e9-fe205a567372)

# Sports Budget Allocation Prediction
This project focuses on predicting the budget allocation for sports based on historical data. The predictive model utilizes linear regression and is deployed through a Gradio interface, allowing users to forecast the budget for a future year.

![77562484](https://github.com/MaheshwaranSelvam/Sports-budget-allocation-using-ML/assets/115611481/aa276c17-af4b-44f1-84a2-2255d0342d33)

## Overview

This project focuses on predicting sports budget allocations based on historical data, utilizing three different regression models: Linear Regression, Decision Tree, and Random Forest. The predictive models are trained on a dataset containing information about budget allocations and corresponding years. Additionally, a Gradio interface has been integrated to facilitate user-friendly predictions for future budget allocations.

## Advantages

1. **Predictive Accuracy:** The project employs three different regression models to provide accurate predictions of sports budget allocations.

2. **Flexibility:** By incorporating multiple regression models, the project allows for flexibility in choosing the most suitable model for the task.

3. **User Interface:** The integration of Gradio provides an interactive and intuitive interface for users to predict sports budget allocations for a given future year.

# Intel OneAPI 

![download](https://github.com/MaheshwaranSelvam/Sports-budget-allocation-using-ML/assets/115611481/53a2e65a-da15-447a-a9c6-3c7022f368bd)


## Introduction

Welcome to the Intel OneAPI toolkit, a unified programming model designed to simplify application development across diverse Intel architectures. This toolkit provides a comprehensive set of libraries, compilers, and tools, allowing developers to create high-performance applications for CPUs, GPUs, and FPGAs.

## Prerequisites

Ensure you have the following prerequisites installed before using Intel OneAPI:

- **Supported Platforms:** Intel OneAPI supports a variety of platforms, including CPUs, GPUs, and FPGAs. Check the documentation for the list of supported platforms.

- **Intel OneAPI Toolkit:** Download and install the latest version of the Intel OneAPI Toolkit from the official Intel website.

- **License:** Ensure that you have the appropriate license for Intel OneAPI. Follow the licensing instructions provided by Intel.

## Features and Components

### 1. Intel Compilers

- **DPC++ Compiler:** The Data Parallel C++ (DPC++) compiler supports heterogeneous programming across CPUs, GPUs, and FPGAs.

- **Fortran Compiler:** The Fortran compiler provides support for modern Fortran standards.

### 2. Intel Libraries

- **Intel Math Kernel Library (MKL):** Optimized mathematical functions for linear algebra, FFT, and more.

- **Intel Integrated Performance Primitives (IPP):** Library for multimedia, data processing, and cryptography.

- **Intel Threading Building Blocks (TBB):** C++ library for parallel programming.

### 3. Intel VTune Profiler

- **VTune Profiler:** Analyze application performance and identify bottlenecks with this powerful profiling tool.

### 4. Intel Advisor

- **Intel Advisor:** Guide the design and optimization of parallel programs.

### 5. Compatibility and Standards

- **SYCL:** A standard C++ language extension for heterogeneous computing.

- **OpenMP:** Standard for parallel programming in C, C++, and Fortran.

## Support and Community

![intel-logo-cpu-corporation-intel-logo-wallpaper-preview](https://github.com/MaheshwaranSelvam/Sports-budget-allocation-using-ML/assets/115611481/b84792c4-b334-4519-888e-67112aa2460d)

- **Intel DevMesh:** Engage with the community, ask questions, and share your experiences on the Intel DevMesh forum.

- **Intel Support:** For technical assistance and issue resolution, visit the Intel support website.

## License

Intel OneAPI is subject to licensing agreements. Review the license terms provided by Intel to ensure compliance.

# Intel OneAPI Optimization Guide

## Introduction
Intel OneAPI is a unified programming model that enables developers to write code that can run efficiently on various Intel architectures.

## Prerequisites

Before optimizing your code, make sure you have the following:

- **Intel OneAPI Toolkit:** Download and install the Intel OneAPI Toolkit from the official Intel website.

## Optimization Steps

Follow these steps to optimize your code:
### 1. Compiler Flags
### 2. Vectorization
### 3. Threading
### 4. Memory Alignment
### 5. Intel Math Kernel Library (MKL)
### 6. Profiling

## Process

### Data Preparation

- The dataset (`budget_allocation_for_sports.csv`) is loaded and cleaned, converting the budget allocation column to numeric values.

- The numerical year is extracted from the 'Years' column to enhance the model's understanding of the temporal aspect.

![chart-1706335920227](https://github.com/MaheshwaranSelvam/Sports-budget-allocation-using-ML/assets/115611481/983dd52f-fa7f-4538-b4de-9ec365292a9c)

### Linear Regression Model

- A Linear Regression model is trained on the dataset to establish a baseline for predicting budget allocations.

- The model's accuracy is evaluated using mean squared error.

### Decision Tree Model

- A Decision Tree Regression model is trained to capture non-linear relationships within the data.

- The model's accuracy is assessed using mean squared error.

### Random Forest Model

- A Random Forest Regression model is employed for enhanced predictive performance through an ensemble of decision trees.

- The model's accuracy is measured using mean squared error.

## Why Prefer Linear Regression Model?

### Linear Regression Advantages

Linear Regression is chosen as the baseline model for the following reasons:

1. **Interpretability:** Linear Regression provides clear interpretability, allowing stakeholders to understand the relationship between the numerical year and budget allocation in a straightforward manner.

2. **Simplicity:** Linear Regression is a simple and easy-to-understand model, making it suitable for initial predictions and as a reference point for more complex models.

3. **Linearity:** The assumption of a linear relationship between the input features and the target variable aligns with the nature of budget allocation trends, making it a reasonable choice.

4. **Training Speed:** Linear Regression typically trains faster compared to more complex models like Decision Trees or Random Forests, contributing to efficient model development.

While Linear Regression serves as the initial model, the project offers the flexibility to explore more complex models for improved predictive performance based on specific requirements.

### Linear Regression Model Accuracy

- A Linear Regression model is trained on the dataset, and its accuracy is evaluated using mean squared error.

- The model's accuracy serves as a reference point for comparing the performance of more complex models in the project.

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
---

# Predicting Sports Budget - Workflow

1. **Kaggle Setup**
   - Install Kaggle API
   - Upload Kaggle API key (kaggle.json)
   - Set up Kaggle credentials
   - List available datasets on Kaggle
   - Download dataset (`predicting-sports-budget-india.zip`)
   - Unzip downloaded dataset

2. **Data Preprocessing and Model Training**
   - *Linear Regression Model*
     - Install scikit-learn-intelex
     - Import necessary libraries and patch scikit-learn
     - Load and preprocess the dataset
     - Train the Linear Regression model

   - *Decision Tree Model*
     - Load and preprocess the dataset
     - Train the Decision Tree model

   - *Random Forest Model*
     - Load and preprocess the dataset
     - Train the Random Forest model

3. **Gradio Setup**
   - Install Gradio
   - Install required packages (typing_extensions, gradio, pydantic, fastapi)
   - Load the Linear Regression model
   - Create a Gradio interface
   - Launch the Gradio interface

4. **Running the Code**
   - Execute Kaggle setup steps
   - Run Data Preprocessing and Model Training steps for each model
   - Run Gradio Setup steps to set up the web interface
   - Execute the Gradio interface to make predictions interactively

---

## Output for this project
![Screenshot (103)](https://github.com/MaheshwaranSelvam/Sports-budget-allocation-using-ML/assets/115611481/7db5701f-e357-4b99-8a99-068b8a43c029)


https://github.com/MaheshwaranSelvam/Sports-budget-allocation-using-ML/assets/115611481/ec68ee28-56c7-49b7-a30a-942a910f3906




## Contribution Guidelines

If you wish to contribute to the project:

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Submit a pull request.

