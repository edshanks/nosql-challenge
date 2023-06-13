# nosql-challenge
There are two scripts (jupyter notebook files) for this project, both of which are located in the "Scripts" folder. They are named "NoSQL_setup_starter" and "NoSQL_analysis_starter". The JSON file containing the raw data to be imported is named "establishments.json" and can be found in the "Resources" folder.

Instructions for Running the Program:
1. Open the command line, select a directory, and clone this repository using the following URL:  "https://github.com/edshanks/nosql-challenge"
3. Open an Anaconda Power Shell and select the "Resources" folder located in the "nosql-challenge" repository on your computer with the command line (e.g. cd Dekstop\nosql-challenge\Resources)
4. Once you are in the correct directory, import the raw data to MongoDB by entering the following command into the Anaconda Power Shell command line:  "mongoimport --type json -d uk_food -c establishments --drop --jsonArray establishments.json"
5. Open "NoSQL_setup_starter" in Jupyter Notebook and run all cells. 
6. Open "NoSQL_analysis_starter" in Jupyter Notebook and run all cells. 
