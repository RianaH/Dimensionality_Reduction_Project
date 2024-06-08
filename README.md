
# Principal Component Analysis (PCA) Project

## Overview

This repository contains the implementation of Principal Component Analysis (PCA) for dimensionality reduction. The project demonstrates the use of PCA to compute the best rank-10 subspace approximation to a given dataset.

## Project Structure

- **PCA_notebook.ipynb**: Jupyter notebook with the PCA implementation and analysis.

## Setup and Installation

To run the notebook, you need to have Python 3.x and the following Python libraries installed:
- NumPy
- PyTorch
- Matplotlib

You can install the required packages using:
```bash
pip install numpy torch matplotlib
```

## Running the Code

Open the `PCA_notebook.ipynb` file using Jupyter Notebook or Jupyter Lab to view and execute the code.

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/your-username/PCA_Project.git
    cd PCA_Project
    ```

2. **Install the Dependencies**:
    ```bash
    pip install numpy torch matplotlib
    ```

3. **Run the Notebook**:
    Open Jupyter Notebook or Jupyter Lab and navigate to `PCA_notebook.ipynb`. Execute the cells to run the code.

## Detailed Description

The project implements PCA to find the principal components of a dataset and reduce its dimensionality while preserving as much variance as possible. This technique is widely used in data preprocessing and feature extraction.

### Implementation Steps
1. **Data Generation**: Generate a synthetic dataset with specified dimensions and noise.
2. **Zero Centering**: Center the data by subtracting the mean.
3. **PCA Computation**: Calculate the principal components and project the data onto the reduced subspace.
4. **Results Analysis**: Analyze and visualize the results to interpret the variance captured by the principal components.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
