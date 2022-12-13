Clone https://github.com/marquisvictor/Optimized-Modified-GetOldTweets3-OMGOT
Open the GetOldTweets3-0.0.10 folder and unpack the zip files 

Run the following files in order.

script.py : Create a 'data' folder in a location of your choice. This is where we will be saving out files with raw tweet data.
This script mines tweets and stores them in the 'data' folder. 
The 'since' and 'stop_date' can be edited to suit your purpose.

Case_counts.ipynb: Reads the 'covid_19_india.csv' file and saves 2 charts to the current working directory.

Emotion_Computation: Reads the raw tweet data from 'data' folder and computes the emotion coefficients and stores the files in 'Sentiment_Output_Files' folder.

Emotion_Visualization.ipynb: Reads the '.csv' files created in 'Sentiment_Output_Files' folder and plots a line graphs.

Correlation_analysis.ipynb: Performs correlation analysis on data from 'Sentiment_Output_Files' folder and the 'wpi_monthly_data.xlsx' file.
 
Credits: cli.py script sourced from https://github.com/marquisvictor/Optimized-Modified-GetOldTweets3-OMGOT