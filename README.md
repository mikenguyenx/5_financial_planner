# Financial Planner

This Jupyter notebook contains code related to an analysis that determines XXXX

## Technologies

Programming Language: Python

Interactive Development Environment: JupyterLab


Libraries: 
- Pandas - A Python library that is used for data manipulation, analysis, and visualization. 
- Pathlib - A Python module that provides an object-oriented interace to working with files & directories.
- Matplotlib - A Python library used for data visualization. 
- OS - Python standard utility module which provides functions for interacting with the computer's operating system.  
- Requests - Python library helps you access data via APIs
- JSON - Python library puts the response (that is, data) from an API into human-readable format.

Operating System(s):  Any operating system that supports Python, including Windows & macOS.

## Installation Guide

To run the application:

1. Clone the repository: 'git clone "https://github.com/mikenguyenx/bootcamp_homework/tree/main/challenge5_financial_planner"'
2. Confirm dependencies are properly installed by activating Conda dev environment and then running the following code:
```
conda list requests
conda list join
```
3. If your development environment is missing either package, you can directly install it.

To install the Requests library, check that your development environment is active, and then run the following command:
```
conda install -c anaconda requests
```
To install the JSON library, check that your development environment is active, and then run the following command:
```
conda install -c jmcmurray json
```
Launch Jupyter Lab: `jupyter lab`
4. Install the 'python-dotenv' Library
With the python-dotenv library, you can read key-value pairs from an environment file (.env) and add them as environment variables.

To install this library, run the following command in your terminal:
```
pip install python-dotenv
```
5. Install the Alpaca SDK
Alpaca is an API for stock trading. With the Alpaca SDK, you can interact with the Alpaca API.

To install this SDK, run the following command in your terminal:
```
pip install alpaca-trade-api
```
6. Verify the Installations
To verify that the library and SDK installations completed, call the pip list function together with the grep -E argument, which enables plain-text searches via the command line. The following code shows this function call:
```
pip list | grep -E "python-dotenv|alpaca-trade-api"
```
7. Get the API Keys
To use certain APIs in this module, you need API keys. You use these unique identifiers to establish an authenticated, secure connection to an API. You'll get keys for both the Nasdaq Data Link and Alpaca APIs.

8. Get the Nasdaq Data Link API Key
To get your API key, you need to sign up for a Nasdaq Data Link account. Go to the Nasdaq Data Link homepageLinks to an external site., and then click Sign Up (which appears on the main menu along the top of the page). 



 Open `XXX.ipynb` in Jupyter Lab to view and run the data analysis code.

## Usage

To use the crypto arbitrage analysis script:

1. Open `crypto_arbitrage.ipynb` in Jupyter Lab.
2. Run the code cells by clicking on the run button or by pressing the "Shift + Enter" key combination to load and preprocess the data, and generate visualizations
3. The script uses Pandas to collect CSV data into the Jupyter notebook file for analysis using summary statistics and Matplotlib for visualizations.

Below are screenshots of examples of results from the analysis:

### Analsis Title 

![]()


## Contributors

Mike Nguyen

Email: nguyen.mikeq@gmail.com

LinkedIn: https://www.linkedin.com/in/mike-nguyen-6899554/

## License

MIT
