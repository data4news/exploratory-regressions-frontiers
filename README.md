# Exploratory Data Analysis with Linear Regression

This notebook demonstrates how linear regression may be used for exploratory data analysis.

## Learning Objective
_Why am I looking at this repo?_

- [ ] Use linear regression as a tool for exploratory data analysis
- [ ] Become familiar with some common US/NY politics & elections data


## Data

We will use election results form the 2025 NYC Mayoral Elections at the ED/AD (Election District/Assembly District) level:
- Primary Election Results ([NYTimes](https://www.nytimes.com/interactive/2025/06/24/us/elections/nyc-mayor-primary-results-precinct-map.html)) ([CUNY](https://www.electionatlas.nyc/maps.html#!NYCResults2025primaryinteractive))
- General Election Results ([NYTimes](https://www.nytimes.com/interactive/2025/11/04/us/elections/nyc-mayor-results-precinct-map.html)) ([CUNY](https://www.electionatlas.nyc/maps.html#!NYCResults2025generalinteractive))

We'll comapare these results to demographics data to answer the following question:

> ❓**Question** 
>
>   Where did Zohran Mamdani gain the most support between the primary and general election?  

## Prerequisites

### Required Software

1. **Python** (3.8 or higher)
2. **R** (4.0 or higher)

### Installation

#### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/nyc-dem-primary.git
cd nyc-dem-primary
```

#### 2. Set Up Python Environment

Create and activate a virtual environment (recommended):

```bash
python -m venv venv
source venv/bin/activate
```

Install Python dependencies:

```bash
pip install -r requirements.txt
```

#### 3. Install R and R Packages

If you don't have R installed, install it:

* **macOS:** `brew install r`
* **Other platforms:** Download from [CRAN](https://cran.r-project.org/).

Then, install required R packages:

```bash
Rscript setup.R
```
