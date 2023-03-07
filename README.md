# Data Dictionary
Python script that takes a CSV file with TIN and NAME columns and creates a Python dictionary with TIN as the key and a list of corresponding names as the value. The script then combines this dictionary with an existing one from a pickle file, updates it, and saves the updated dictionary as both a JSON and a pickle file.

### Prerequisites
Before running the script, you will need to have the following libraries installed:

pandas
numpy
re
json
pickle
csv
### Usage
Save the CSV file with TIN and NAME columns in the same directory as the script.
Run the script.
The script will create or update a dictionary and save it as both a JSON and a pickle file in the same directory as the script.
### Functions
The script contains the following functions:

read_write_pickle(): reads a dictionary from a pickle file and returns an empty dictionary if the file does not exist.
update_dict(): combines a new dictionary with an existing one, appending values to existing keys and adding new key-value pairs if they do not exist.
### Output
The script creates two output files:

dict.json: a JSON file containing the updated dictionary.
dict.pickle: a pickle file containing the updated dictionary.
### Conclusion
This script provides a simple way to combine data from a CSV file with an existing Python dictionary and export the updated dictionary to both a JSON and a pickle file. It can be used as a starting point for more complex data management tasks in Python.
