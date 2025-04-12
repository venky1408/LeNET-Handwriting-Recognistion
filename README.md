# LeNet-like Handwriting Recognition on MNIST
Authors : Sweta Ratnani Nithin Kolan Saisreevenkat Pedarla 
This project refines the classical LeNet architecture to enhance handwriting recognition on the MNIST dataset. The enhancements include deeper convolutional layers, use of ReLU activation functions, an expanded fully connected layer, and the adoption of the Adam optimizer. These modifications enable the model to achieve an accuracy exceeding 99% on the test dataset.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Repository Structure](#repository-structure)
- [Contributing](#contributing)
- [License](#license)

## Overview
The project demonstrates enhancements to a LeNet-like architecture by:
- Upgrading convolutional layers and increasing filter counts.
- Replacing sigmoid activations with ReLU to mitigate the vanishing gradient problem.
- Expanding the fully connected layer for improved feature mapping.
- Leveraging modern optimization strategies with the Adam optimizer.

Additionally, the repository includes a detailed report (`LeNET Document.pdf`) that covers the model architecture, experiments, results analysis, and a comparison with baseline models.

## Features
- **Model Enhancements:** Improved architecture to boost accuracy on the MNIST dataset.
- **Interactive Visualizations:** Use of Jupyter Notebook for model training, evaluation, and visualization.
- **Detailed Documentation:** A project report covering methodology, experiments, and results.
- **Reproducibility:** Instructions to set up a virtual environment and install dependencies ensure a reproducible setup.

## Prerequisites
Make sure you have the following installed:
- Python 3.x
- Git

The Python project uses the following libraries:
- [pandas](https://pandas.pydata.org/)
- [numpy](https://numpy.org/)
- [matplotlib](https://matplotlib.org/)
- [jupyter](https://jupyter.org/)
- [tensorflow](https://www.tensorflow.org/) (or your preferred deep learning framework)

## Installation
### 1. Clone the Repository
Open your terminal and clone the repository:
    bash :
    git clone https://github.com/venky1408/LeNet-Project.git
    cd LeNet-Project


### 2. Set Up a Virtual Environment (Recommended)
    Create and activate a virtual environment:
    On Windows (using venv):
        bash :
        python -m venv env
        env\Scripts\activate

    On macOS/Linux:
        bash :
        python3 -m venv env
        source env/bin/activate

### 3. Install Dependencies
    Install all required packages via the provided requirements.txt:
        bash : pip install -r requirements.txt

Usage
Running the Code
    1.Launch Jupyter Notebook:
        If you're using Jupyter Notebook, run:
        bash : jupyter notebook

    2.Open the Notebook: Open LeNET_code.ipynb to view the code, train the model, and see evaluation results.

Model Training & Evaluation:
The notebook contains code for model training and evaluation on the MNIST dataset. Follow the cell instructions, execute them, and review the outputs and visualizations. Detailed experimental results and analyses are provided in the accompanying report (LeNET Document.pdf).

Repository Structure
        LeNet-Project/
        ├── LeNET_code.ipynb     # Jupyter Notebook with code for model implementation, training, and evaluation.
        ├── LeNET Document.pdf         # Project report with detailed analysis and experimental results.
        ├── README.md                # This README file.
        ├── requirements.txt         # Python package dependencies.
        └── .gitignore               # Specifies files and folders to ignore in Git.

Contributing
        Contributions are welcome! If you'd like to improve this project:
        -Fork the repository.
        -Create a new branch for your feature or bug fix.
        -Commit your changes and push to your fork.
        -Create a pull request describing your changes.

License
This project is licensed under the MIT License. See the LICENSE file for details.