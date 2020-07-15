# DataAnalyticsTeam

## Overview
The GitHub repository for the Data Analytics Team

The Random Forest Predictive Model requires the following Python libraries:
- pandas
- numpy
- sqlite3
- sklearn

## Usage
To call the script from a Java file, you can use the following line of code:

```Runtime.getRuntime().exec("python [PATH\TO\]RandomForest.py");```

*Note that an IOException may be thrown.*

## Output
The output is a 2 line CSV file. Each column represents the predicted number of individuals waiting at a particular stop in the **following** iteration. The first column is the id, the second column is the numerical estimation. The CSV file will be generated in the same directory as the python script. It will take about 5 - 10 seconds to run.

## Heads up
Some of the file paths in the script may need to be updated.
