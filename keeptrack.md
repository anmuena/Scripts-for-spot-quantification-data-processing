# 1. project structure

## 1.1 data import
- import of all .csv files in selected directory
- generation of dataframes containing 
    - the relevant columns 
    - with useful headers
- should allow for
    - traceback of .csv to sample it belongs to and analysis parameters
    - storage of all observations in a column into variables
        - stringent variable names
        - allow for abstraction

## 1.2 data restructuring
- suitable for plotting functions later in pipeline
- suitable for statistics functions later in pipeline
- functions for horizontal and vertical data combinations to provide quick info overviews
    - eg. all variables originating from one .csv to pass to plot function
    - eg. all variables originating from the same analysis parameter to pass to plot function
- functions to flexibly subset data 

## 1.3 calculations
- multiplication of columns
- division of columns for normalization
    - number of nuclei from imageC
    - total cell area detected in one FoV
- substraction
- addition

## 1.4 plotting
- dot plot
- histogram
- violin plot or similar
- combination of plots into panels
- overlays of plots
- plotting of p values and other statistic parameters

## 1.5 statistics
- t-test with definable alpha, returns p-value and data source to pass to plot function

## 1.6 testing
- unit tests for all functions

# 2. next to do´s
- identify good trategy how to 
    - deal with column headers
    - rename columns automatedly
    - create variables out of columns
    - organize those variables
 ----


# 3. general ideas 
- provide python scripts for most common EVAnalyzer data analysis use cases
