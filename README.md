# Unsupervised Learning Lab

This project demonstrates unsupervised machine learning techniques, focusing on clustering algorithms for customer segmentation using mall customer data.

## Overview

Unsupervised learning trains models on data without labeled responses, aiming to uncover hidden patterns, structures, or relationships.

## Project Structure

- `MLClustering.ipynb`: Jupyter notebook with step-by-step clustering workflow.
- `MarketBasketAnalysis.ipynb`: Jupyter notebook for market basket analysis (association rule mining).
- `requirements.txt`: Python dependencies.
- `.gitignore`: Ignores the `.venv` directory.

## Getting Started

1. **Clone the repository**

   ```sh
   git clone <repo-url>
   cd unsupervised-learning-lab
   ```

2. **Set up a virtual environment (recommended)**

   ```sh
   python3 -m venv .venv
   source .venv/bin/activate
   ```

3. **Install dependencies**

   ```sh
   pip install -r requirements.txt
   ```

4. **Run the notebook**
   - Open `MLClustering.ipynb` for clustering analysis.
   - Open `MarketBasketAnalysis.ipynb` for market basket analysis.
   - Use Jupyter Notebook or VS Code to follow the steps in each notebook.

## Data

- `MLClustering.ipynb` downloads the [Mall_Customers.csv](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python) dataset using `kagglehub`.
- `MarketBasketAnalysis.ipynb` uses a transactional dataset for association rule mining.

## License

This project is for educational purposes.
