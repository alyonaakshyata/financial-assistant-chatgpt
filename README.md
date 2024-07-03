
# Financial Stock Assistant Using ChatGPT

## Overview

Welcome to the Financial Stock Assistant project. This tool leverages the power of OpenAI's GPT-3.5 model to provide various useful technical analyses of stocks. This project aims to help users make informed investment decisions by providing insightful analyses.




## Features

- Real-time Stock Analysis: Get the latest stock price information for various companies.
- Simple Moving Average (SMA): Calculate the SMA for a given stock over a specified timeframe.
- Exponential Moving Average (EMA): Calculate the EMA for a given stock over a specified timeframe.
- Relative Strength Index (RSI): Compute the RSI to understand the stock's momentum.
- Moving Average Convergence Divergence (MACD): Calculate MACD, signal line, and MACD histogram for stock trend analysis.
- Stock Price Plotting: Visualize the stock price trends over the last year with a graphical plot.
- Customizable Queries: Ask specific questions about stocks and receive tailored responses from the AI.
- User-friendly Interface: Simple and intuitive interface for easy interaction and data retrieval using Streamlit.


## Run Locally

Clone the project

```bash
  git clone https://github.com/alyonaakshyata/financial-assistant-chatgpt.git
```

Go to the project directory

```bash
  cd financial-assistant
```

Create and activate virtual environment

```bash
  python -m venv venv
  source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

Install dependencies

```bash
  pip install -r requirements.txt
```

Set up OpenAI API key

  - Obtain your OpenAI API key from OpenAI
  - Paste the API key in the 'API_KEY.txt' file

```bash
  your-api-key
```

Run the Application

```bash
  streamlit run main.py
```

## Usage

Once the application is running, you can interact with the financial assistant through the web interface. Here are some example queries you can try:

- "Get the latest stock price for AAPL."
- "Calculate the 50-day SMA for TSLA."
- "What is the EMA for AMZN over the last 20 days?"
- "Provide the RSI for GOOGL."
- "Show the MACD analysis for MSFT."
- "Plot the stock price of NFLX for the last year."

## Tech Stack

**Python**: The core programming language.

**OpenAI GPT-3.5**: For generating stock analyses and predictions.

**Streamlit**: For creating the web interface.

**Pandas**: For data manipulation and analysis.

**Matplotlib**: For plotting graphs and visualizations.

**yFinance**: For retrieving stock data.
