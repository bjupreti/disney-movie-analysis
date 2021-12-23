# Disney Dataset Creation & Analysis
In this project, I have gone through series of steps to create a dataset by scraping Disney movies data from Wikipedia using Python Beautifulsoup, requests, and several other libraries.

Then I saved it in a `.json` file.

Code and Preview: [https://github.com/bjupreti/disney-movie-analysis/blob/main/movie_dataset_creation.ipynb](https://github.com/bjupreti/disney-movie-analysis/blob/main/movie_dataset_creation.ipynb) 

Then I moved towards the data cleaning where I did:
- Convert running time to number of minutes by utilizing `datetime` and `re` library.
- Convert box office and budget to number by pattern matching with regular expressions.
- Convert release date to python date. If there is only one release date in array use that one. If there are more than one release date take US release date.
- Remove references [1] [2] etc. 
- Converting ascii code to readable text while saving the file as json. (Done while loading the data)
- Get rid of all errors while scraping the data.

Code and Preview: [https://github.com/bjupreti/disney-movie-analysis/blob/main/data_cleaning.ipynb](https://github.com/bjupreti/disney-movie-analysis/blob/main/data_cleaning.ipynb)
