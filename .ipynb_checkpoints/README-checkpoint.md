# Financial Planner

This Jupyter notebook contains an application that helps credit union members evaluate their financial health. With this application, users are able to (1) assess their monthly budgets and (2) forecast a reasonably effective retirement plan based on their current holdings of cryptocurrencies, stocks, and bonds.

## Technologies

Programming Language: `Python 3.7.13`

Interactive Development Environment: `JupyterLab`


Libraries: 
- `Pandas` - A Python library that is used for data manipulation, analysis, and visualization. 
- `Pathlib` - A Python module that provides an object-oriented interace to working with files & directories.
- `Matplotlib` - A Python for creating static, animated, and interactive visualizations in Python. It provides a wide variety of customizable visualizations, including line plots, scatter plots, bar plots, histograms, heatmaps, and more.
- `OS` - Python standard utility module which provides functions for interacting with the computer's operating system.
- `Requests` - Python library helps you access data via APIs
- `JSON` - Python library puts the response (that is, data) from an API into human-readable format.


Operating System(s):  Any operating system that supports Python, including Windows & macOS.

## Installation Guide

To run this analysis, make sure you install the necessary dependencies:

1. Install `Python`: `https://www.python.org/downloads/`
2. Install and run `Jupyter Lab`: `https://jupyter.org/install`
3. Install the necessary libraries using pip, the package installer for Python:
```
pip install pandas pathlib numpy matplotlib
```
4. Install the `Requests` library, check that your development environment is active, and then run the following command:
```
conda install -c anaconda requests
```
5. Install the JSON library, check that your development environment is active, and then run the following command:
```
conda install -c jmcmurray json
```
6. Install the `python-dotenv` Library. With the python-dotenv library, you can read key-value pairs from an environment file `(.env)` and add them as environment variables. To install this library, run the following command in your terminal:
```
pip install python-dotenv
```
7. Install the Alpaca SDK. Alpaca is an API for stock trading. With the Alpaca SDK, you can interact with the Alpaca API. To install this SDK, run the following command in your terminal:
```
pip install alpaca-trade-api
```
8. Verify the installations. 

The Requests and JSON libraries get installed with Anaconda. To confirm their installation, do the following: 

In the terminal, activate the Conda development environment, and then run the following code:
```
conda list requests

conda list json
```
The result on your screen should resemble the following image:
![verify_requests_json](verify_requests_json.png)

To verify that the library and SDK installations completed, call the pip list function together with the grep -E argument, which enables plain-text searches via the command line. The following code shows this function call:
```
pip list | grep -E "python-dotenv|alpaca-trade-api"
```
The result on your screen should resemble the following image:
![verify_alpaca_dotenv](verify_alpaca_dotenv.png)

9. Get the API Keys. To use certain APIs in this module, you need API keys. You use these unique identifiers to establish an authenticated, secure connection to an API. You'll get keys for both the Nasdaq Data Link and Alpaca APIs.

10. Get the Nasdaq Data Link API Key. To get your API key, you need to sign up for a Nasdaq Data Link account. Go to the Nasdaq Data Link homepageLinks to an external site., and then click Sign Up (which appears on the main menu along the top of the page).

11. Clone the repository: `git clone "https://github.com/mikenguyenx/5_financial_planner"` using git or download the ZIP file and extract it to a local directory.


## Usage

To run the script for the Fund Portfolio Risk Return Analysis:

1. Open a terminal or command prompt and navigate to the directory with the application.
1. Launch Jupyter Lab: `jupyter lab`
2. Open `financial_planning_tools.ipynb` in Jupyter Lab.
3. Run the code cells by clicking on the run button or by pressing the `Shift + Enter` key combination to load and preprocess the data, and generate visualizations
4. XXX

Below are screenshots of examples of results from the analysis:

### <Title of Image> 

![]()


## Contributors

Mike Nguyen

Email: nguyen.mikeq@gmail.com

LinkedIn: https://www.linkedin.com/in/mike-nguyen-6899554/

## License

MIT

