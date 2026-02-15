INSTRUCTIONS/DESCRIPTION ON THE PROCESS OF OBTAINING/INTERPRETING THE DATA CONTAINED IN THE FOLDER
The file Edits_as_Data.ipynb contains all of the functions used to obtain the data.
1. Download Edits_as_Data.ipynb and lexicon, move all textfiles from the lexicon into the folder containing Edits_as_Data.ipynb.
2. Find the Wikipedia articles and copy their exact titles. Capitilzation must be 1-1 with the article's actual title.
3. Paste the titles into the "TITLES" array, set the parameters as notated by the comments in the program; the most important parameter is the target time period.
4. Run all the modules.
5. Download the resulting files.
Note: The Raw Data is the entire text from the version resulting from each revision within the target time period. This is important for interpreting the data and how the code works, but also note tphat this will result in certain modules taking a long time to run, and the resulting files may be very large. 
Note: Most modules rely on others, so the modules should be run in order; after they all run at least once, individual modules can be run a second time
Note: Certain parameters were not meant to be adjusted from trial to trial, but they can be adjusted if a user was interested in to experimenting, diagnostics, etc. These include the stopword list, Min_DF, Max_DF.
