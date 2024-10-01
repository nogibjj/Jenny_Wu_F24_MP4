[![Advanced testing with Github Actions](https://github.com/nogibjj/Jenny_Wu_F24_MP4/actions/workflows/matrix_cicd.yml/badge.svg)](https://github.com/nogibjj/Jenny_Wu_F24_MP4/actions/workflows/matrix_cicd.yml)


# Jenny_Wu_MP2_F24
F24 Mini Project 4

### Purpose of Project
This project is part of the IDS 702: Data Engineering course and demonstrates how to ensure Python code compatibility across different environments using GitHub Actions. By configuring a matrix strategy, the workflow tests Python versions 3.8, 3.9, 3.10, and 3.11, ensuring consistent performance and stability across these versions.

### Relevant Files

This repository includes the following relevant project components:

* `.devcontainer folder`

* `Makefile`

* `requirements.txt`

* `README.md` 

* `githubactions folder`
    * `matrix_cicd_yml`
        This file configures the GitHub Actions workflow. It uses the setup-python action and a matrix to test different Python versions 3.8, 3.9, 3.10 and 3.11.

* `Dockerfile`

* `main.py` 

* `test_main.py`
        When changes are pushed to the repository, tests in `test_main.py` automatically validate the functionality of `main.py` across Python 3.8, 3.9, 3.10, and 3.11.


### Requirements
- Correctly configured Gitlab Actions Matrix
- README 
- CI/CD


### Dataset Description
The dataset used for this project is the data behind FiveThirtyEight's [Congress Today Is Older Than It’s Ever Been](https://fivethirtyeight.com/features/aging-congress-boomers/), by Geoffrey Skelley (April 3, 2023).

`data_aging_congress.csv` contains information about the age of every member of the U.S. Senate and House from the 66th Congress (1919-1921) to the 118th Congress (2023-2025). Data is as of March 29, 2023, and is based on all voting members who served in either the Senate or House in each Congress. The data excludes delegates or resident commissioners from non-states. Any member who served in both chambers in the same Congress was assigned to the chamber in which they cast more votes. The dataset begins with the 66th Congress because it was the first Congress in which all senators had been directly elected, rather than elected by state legislatures, following the [ratification of the 17th Amendment in 1913](https://constitutioncenter.org/the-constitution/amendments/amendment-xvii). 

