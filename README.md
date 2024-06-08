# Dimensionality Reduction Project

## Overview

This repository contains the implementation of various dimensionality reduction techniques, including Principal Component Analysis (PCA), Autoencoder, and Matrix Factorization. The project demonstrates the use of these techniques to compute the best rank-10 subspace approximation to a given dataset and compare their effectiveness.

## Project Structure

- **PCA_Autoencoder_Factorization_Notebook.ipynb**: Jupyter notebook with the implementation and analysis of PCA, Autoencoder, and Matrix Factorization.

## Setup and Installation

To run the notebook, you need to have Python 3.x and the following Python libraries installed:
- PyTorch
- Matplotlib
- Seaborn
- NumPy

You can install the required packages using:
```bash
pip install torch matplotlib seaborn numpy
'''

## Running the Code

Open the PCA_Autoencoder_Factorization_Notebook.ipynb file using Jupyter Notebook or Jupyter Lab to view and execute the code.

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/your-username/Dimensionality_Reduction_Project.git
    cd Dimensionality_Reduction_Project
    ```

2. **Install the Dependencies**:
    ```bash
    pip install numpy torch matplotlib seaborn
    ```

3. **Run the Notebook**:
    Open Jupyter Notebook or Jupyter Lab and navigate to PCA_Autoencoder_Factorization_Notebook.ipynb. Execute the cells to run the code.

## Detailed Description

The project implements three dimensionality reduction techniques to find the principal components and reduce the dimensionality of a dataset while preserving as much variance as possible. These techniques are widely used in data preprocessing and feature extraction.

### Implementation Steps
1. **Data Generation**: Generate a synthetic dataset with specified dimensions and noise.
2. **Zero Centering**: Center the data by subtracting the mean.
3. **PCA Computation**: Calculate the principal components and project the data onto the reduced subspace.
4. **Autoencoder Training**: Train an autoencoder to learn a reduced representation of the data.
5. **Matrix Factorization**: Perform matrix factorization to approximate the data with lower-rank matrices.
6. **Results Analysis**: Analyze and visualize the results to interpret the variance captured and the effectiveness of each technique.
        -Explained Variance: Analyze the variance captured by the principal components.
        -Scatter Plot: Visualize the first two principal components.
        -Heatmap: Display the top principal components.
        -Training Loss: Plot the training loss over iterations for both Autoencoder and Matrix Factorization.
        -Reconstruction Error: Calculate and interpret the reconstruction error.
        -Subspace Comparison: Compare the subspaces derived from PCA, Autoencoder, and Matrix Factorization.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
