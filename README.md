# Financial_planner_M5


This is a Jupyter Notebook that analysis the value of a set portfolio and forecast their future performance through a Monte Carlo simulation.

---

## Technologies

This project leverages python 3.7 with the following packages:

* [pandas](https://github.com/google/pandas) - Flexible and powerful data analysis / manipulation library for Python
* [requests](https://github.com/google/requests) - The Python Requests library helps you access data via APIs
* [json](https://github.com/google/json) - This library puts the response (that is, the data) from an API into a human-readable format
* [os](https://github.com/google/os) - The OS module comes under Python's standard utility models and provides functions for interacting with the computer's operating system. The OS module does not require a separate download.



---

## Installation Guide

Before running the application first install the following dependencies.

```python
  pip install pandas
  conda install -c jmcmurray json
  pip install python-dotenv
  pip install alpaca-trade-api
  
```

---

## Usage

To use the quantitative analysis application simply clone the repository and run the **financial_planning_tools.ipynb** with:

```python
financial_planning_tools.ipynb
```

Create an .env file with your API codes

## Conclusions

Based on the simulations performed, it seems very unlikely the credit union member will be able to retire in just 10 years.

## Contributors

Brought to you by Rodrigo Monge.

---

## License

N/A
