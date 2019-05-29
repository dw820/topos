# 2019 Data Eng Intern Assignment

Clean and transform the data scraped from the wiki pages.
The final result is a well-format csv file with each city's historical population data

### Prerequisites

```
python=3.7.3
```

### Dependencies

```
requests
beautifulsoup4
pandas
numpy
progressbar2
jupyter notebook
```

### Steps to run the notebook

1. Create a conda enviornment for this project to work in. (Installation for conda can be found [here.](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html))
```
$ conda create -n envName python=3.7.3
```
2. Activate the conda enviornment
```
$ conda activate envName
```
3. Download relevent packages
```
$ conda install requests beautifulsoup4 pandas numpy progressbar2 jupyter notebook
```
4. Clone this repository to your local directory with this link: https://github.com/dw820/topos.git
```
$ git clone https://github.com/dw820/topos.git
```
5. Go to the topos folder
```
$ cd topos
```
6. Open the jupyter notebook
```
$ jupyter notebook
```
7. The browser should open the jupyter notebook and can start working on the topos.ipynb file

### Files in this repository

- *topos.ipynb*: The jupyter notebook is running all the web scraping and data cleaning process, also creating the result.csv file.
- *topos.html*: The HTML file shows the running results of the jupyter notebook.
- *result.csv*: The final csv output file for BigQuery.

