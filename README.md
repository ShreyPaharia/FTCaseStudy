# Solana Network Analysis

This project contains IPython Notebook files for analyzing various aspects of the Solana network, including validator counts, block times, and staking yields.

## Prerequisites

- Python 3.7 or higher
- pip (Python package installer)
- Jupyter Notebook or JupyterLab

## Installation

1. Clone this repository to your local machine:

   ```
   git clone git@github.com:ShreyPaharia/FTCaseStudy.git
   cd FTCaseStudy
   ```

2. (Optional but recommended) Create a virtual environment:

   ```
   python -m venv venv
   source venv/bin/activate
   ```

3. Install the required packages:

   ```
   pip install -r requirements.txt
   ```

## Running the Notebooks

1. Start Jupyter Notebook or JupyterLab:

   ```
   jupyter notebook
   ```

   or

   ```
   jupyter lab
   ```

2. In the Jupyter interface that opens in your web browser, navigate to the directory containing the .ipynb files.

3. Click on the notebook you want to run (e.g., `part1.ipynb` or `part2.ipynb`).

4. Once the notebook is open, you can run each cell individually by clicking the "Run" button or by using the keyboard shortcut Shift+Enter.

5. To run all cells in the notebook, click on "Cell" in the top menu, then "Run All".

## Notebooks Description

- `part1.ipynb`: This notebook analyzes validator counts, calculates average block times for recent and historical epochs, and estimates staking yields.
- `part2.ipynb`: This notebook performs analysis on the top 20 L1/L2 blockchain platforms, including market cap to DEX volume ratios and correlation studies.

## Troubleshooting

- If you encounter any import errors, make sure all required packages are installed correctly.
- If you're having issues with the Solana RPC endpoint, check your internet connection and verify that the endpoint URL is correct and accessible.

## Note

The analysis in these notebooks uses free RPC endpoints. Be mindful of rate limits and consider using a dedicated RPC provider for extensive or frequent analysis.
