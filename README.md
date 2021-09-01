# Python_Financial_Analysis_Election_Analysis
Two python data analysis, using Python 3.8.8, using functions, kwargs and reading and writing to files.

# Python Data Analysis 

### 1. Financial Data Analysis 
### 2. Election Poll Data Analysis 


### Setup

* Inside the local git repository, created a folder for each Python Challenge. 
   **PyBank** and  **PyPoll**.

* Inside of EACH folder; added the following:

  * A new file called `main.py`. This is the main script to run for each analysis.
  * A "Resources" folder that contains the CSV files used. Make sure the script has the correct path to the CSV file.
  * An "analysis" folder that contains the text file analysis.txt that has the results from the analysis.
  * Note that this file analysis.txt can be deleted to rerun the analysis or appended to.


## PyBank

* Created a Python script [main.py](PyBank/main.py) for analyzing the financial records of a company. A set of financial data called [budget_data.csv](PyBank/Resources/budget_data.csv). The dataset is composed of two columns: `Date` and `Profit/Losses`. 

* Created a Python script that analyzes the records to calculate each of the following:

  * The total number of months included in the dataset

  * The net total amount of "Profit/Losses" over the entire period

  * Calculates the changes in "Profit/Losses" over the entire period, then finds the average of those changes

  * The greatest increase in profits (date and amount) over the entire period

  * The greatest decrease in profits (date and amount) over the entire period


* Final script prints the analysis (1) to the terminal and (2) exports a text file with the results.
   [analysis.txt](PyBank/analysis/analysis.txt).
   
*Assumptions: File is clean and sorted by date, there are no months with zero (0) for profit/loss, folder structure outlined above. Code does not check for folder structure, it must be created.
The code will create an analysis.txt file as long as the folder structure is correct. Currently the analysis.txt file is there to show the results obtained. Uses relative paths.

*Pycode : Made use of functions, kwargs with the use of default kwarg values, reading and writing to files.

* Created on a MacOS
* NOTE: used encoding if WindowsOS, Or special chars printing,ie) with io.open("output_file.txt", mode='w', encoding='utf-8') as f:

## PyPoll

* Modernizing a vote counting process to get an analysis of the resulsts.

* Poll data called [election_data.csv](PyPoll/Resources/election_data.csv). The dataset is composed of three columns: `Voter ID`, `County`, and `Candidate`. 
* Created a Python script [main.py](PyPoll/main.py). that analyzes the votes and calculates each of the following:

  * The total number of votes cast

  * A complete list of candidates who received votes

  * The percentage of votes each candidate won

  * The total number of votes each candidate won

  * The winner of the election based on popular vote.


* Final script prints the analysis (1) to the terminal and (2) exports a text file with the results.
[analysis.txt](PyPoll/analysis/analysis.txt).

* Assumptions: Data File does not need to be sorted or cleaned, folder structure as outlined above.
                           All data is consistent in csv file, code finds the relative paths
                           Currently the analysis.txt file is there to show the results obtained. Uses relative paths.
                           Python 3.8.8
* Pycode : Made use of functions, kwargs-no default value, code shows passing of 2 acceptable kwarg values, reading and writing to files.
- - -
csv files from Trilogy


