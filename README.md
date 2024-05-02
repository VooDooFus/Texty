# Texty
Text File Searcher
This Python script facilitates searching for a specific word within text files in a given directory. It recursively traverses the directory structure, identifying text files based on their extensions and then searching for the specified word within them.

Key Features:
Efficient Text File Search: Utilizes file extension filtering to focus only on text files, optimizing the search process.
Automatic Encoding Detection: Detects the encoding of text files using the chardet library to ensure proper reading.
Progress Tracking: Displays a progress bar using tqdm library to indicate the search progress.
Flexible Output: Provides options to limit the number of results displayed or to show all matching files.

Usage:
Set the directory_to_search variable to the path of the directory where you want to search for text files.
Define the target_word variable to specify the word you want to search for within the text files.
Optionally, set the max_results variable to limit the number of results displayed.

Supported Text File Extensions:
.txt
.csv
.log
.md
.py
.json
Feel free to extend the list of supported extensions based on your needs; but ymmv.

Requirements:
tqdm
chardet

/VooDooFus/
