# Unsupervised Learning Lab

This project demonstrates unsupervised machine learning techniques, focusing on clustering algorithms for customer segmentation using mall customer data.

## Overview

Unsupervised learning trains models on data without labeled responses, aiming to uncover hidden patterns, structures, or relationships.

## Project Structure

- `MLClustering.ipynb`: Jupyter notebook with step-by-step clustering workflow.
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
   - Open `MLClustering.ipynb` in Jupyter Notebook or VS Code.
   - Follow the steps to download the dataset, preprocess data, and perform clustering.

## Data

The notebook downloads the [Mall_Customers.csv](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python) dataset using `kagglehub`.

## License

This project is for educational purposes.
