# Inflam
![Continuous Integration build in GitHub Actions](https://github.com/<your_github_username>/python-intermediate-inflammation/actions/workflows/main.yml/badge.svg?branch=main)
Inflam is a data management system written in Python that manages trial data used in clinical inflammation studies.

## Main features
Here are some key features of Inflam:

- Provide basic statistical analyses over clinical trial data
- Ability to work on trial data in Comma-Separated Value (CSV) format
- Generate plots of trial data
- Analytical functions and views can be easily extended based on its Model-View-Controller architecture

## Prerequisites
Inflam requires the following Python packages:

- [NumPy](https://www.numpy.org/) - makes use of NumPy's statistical functions
- [Matplotlib](https://matplotlib.org/stable/index.html) - uses Matplotlib to generate statistical plots

The following optional packages are required to run Inflam's unit tests:

- [pytest](https://docs.pytest.org/en/stable/) - Inflam's unit tests are written using pytest
- [pytest-cov](https://pypi.org/project/pytest-cov/) - Adds test coverage stats to unit testing

## Installation
Here is a step-by-step guide for how to install Inflam:

- clone this repository onto your local machine
- cd into the cloned directory
- setup a virtual environment: in the root directory of the project, run 'python3 -m venv venv'
- activate the virtual environment: run 'source venv/bin/activate'
- run 'pip install -r requirements.txt' to install all required dependencies
- enjoy!!!