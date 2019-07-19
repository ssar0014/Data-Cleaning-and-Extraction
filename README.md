# Data-Cleaning-and-Extraction

Environment: Python 3.6.8 and Jupyter notebook

Libraries used:
**re - To use Regular Expressions in Python
**json - Used to make a json file

The following code reads a given text file with HTML code, parses the data from it, and gives out an XML and a JSON file as output.

The following code reads data from a text file named "29819253_task1.txt" which contains information about subjects offered by a Univeristy. It contains details about the Unit code, unit name, synopsis, pre-requisites, prohibitions, requirements, outcomes, and chief examiners.

This data is stored inside of HTML tags, which are used to extract chunks from the text file. These are then cleaned of the tags and the data is stored inside a dictionary, which is subsequently used to create XML and JSON files. Regular Expressions were extensively used to extract and clean the data.

I have uploaded the entire description in the jupyter notebook.
