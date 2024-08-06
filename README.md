# Automating-Crypto-Website-API-Pull-Using-Python

This project fetches cryptocurrency data from CoinMarketCap's API, processes it into a DataFrame, and visualizes the data using Seaborn and Matplotlib. The data includes the latest listings and various percent changes over different periods.

## Project Overview

The main features of this project include:
- Fetching the latest cryptocurrency data from CoinMarketCap.
- Normalizing and processing the JSON data into a pandas DataFrame.
- Appending data periodically to track changes over time.
- Visualizing cryptocurrency trends using Seaborn and Matplotlib.

## Setup

### Prerequisites

Ensure you have the following installed:
- Python 3.x
- pip (Python package installer)
- Git (for cloning the repository)

### Installation

1. **Clone the repository:**

    ```sh
    git clone https://github.com/your-username/your-repository.git
    ```

2. **Navigate to the project directory:**

    ```sh
    cd your-repository
    ```

3. **Create and activate a virtual environment (optional but recommended):**

    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

4. **Install the required dependencies:**

    ```sh
    pip install -r requirements.txt
    ```

5. **Set up Jupyter notebook data rate limit (if necessary):**

    If you encounter issues pulling data, run the following command in Anaconda Prompt:
    ```sh
    jupyter notebook --NotebookApp.iopub_data_rate_limit=1e10
    ```

### API Key

This project requires an API key from CoinMarketCap. Replace `'YOUR_API_KEY'` in the script with your actual API key.





