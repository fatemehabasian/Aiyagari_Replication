
# Replication of Aiyagari (1994): Uninsured Idiosyncratic Risk and Aggregate Saving

## Overview

This repository contains the Jupyter Notebook and the corresponding HTML file for the replication of S. Rao Aiyagari’s 1994 paper on "Uninsured Idiosyncratic Risk and Aggregate Saving." The replication study aims to validate Aiyagari’s findings using modern computational techniques.

## Project Structure

- **`Aiyagari_Replication.ipynb`**: The Jupyter Notebook that contains the full implementation of the replication study. It includes all the code, data processing, model simulations, and visualizations.
- **`Aiyagari_Replication.html`**: An HTML export of the Jupyter Notebook for easy viewing. This file contains the same content as the notebook but can be viewed directly in a web browser without needing to run the code.

## Key Features

- **Precautionary Savings**: Analysis of how idiosyncratic shocks to individual labor income lead to increased aggregate savings through precautionary behavior.
- **Model Simulation**: Simulation of 50,000 households over 2,000 periods using the Rouwenhorst method to approximate stochastic processes accurately.
- **Visualization**: Replication of key figures from Aiyagari’s original paper, providing visual confirmation of the model’s predictions.

## How to Use

1. **Viewing the Notebook**: 
   - If you have Jupyter Notebook installed, you can open the `.ipynb` file directly and explore or modify the code.
   - Alternatively, you can view the `.html` file in any web browser to see the output without needing to execute the code.

2. **Running the Code**: 
   - Ensure you have Python and Jupyter installed.
   - Open the `.ipynb` file in Jupyter and run the cells to reproduce the results.

## Dependencies

To run the notebook, you'll need the following Python packages:
- `numpy`
- `matplotlib`
- `scipy`
- `pandas`
- `quantecon`
- `numba`
- `time`

You can install these packages using pip:
```bash
pip install numpy matplotlib scipy pandas
```

## Conclusion

This replication study reinforces the findings of Aiyagari (1994), demonstrating the critical impact of uninsured idiosyncratic risk on aggregate savings and macroeconomic stability. The results are consistent with the original study and offer a deeper understanding of the mechanisms driving precautionary savings.
