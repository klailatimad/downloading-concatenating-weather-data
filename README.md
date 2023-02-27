# Downloading Weather Data using Linux Shell Scripting and using Python in Ubuntu to merge the files

## This code was built as a mini-project for the WeCloudData Data Engineering bootcamp Lecture #2 - Linux

### Business Requirements:
- Download the data from Canadian Climate.
- Concatenate the downloaded files into one final csv file, called all_years.csv. This is the output of the lab.
- Upload your scripts and final csv file all_years.csv to the repository you created in the Github. 

### Deliverable:
Submit a shell script, a python script and all_years.csv to the github repository you created for the lab.
- Shell script: You will use the shell script to control every operation, including data downloading, log setting, python script running.
- Python script: While the Python script is used to concatenate all the data into one file.
- all_years.csv: This is the output file you concatenate all the downloads.

### Program Procedure
- Download data with shell command
- Concatenate data to one file with the python script
- Save output file in the python script
- Print out SUCCESS with shell command.
- Preate a repository in github, and upload your file to the repo with git.
- The Shell script will call the Python Script to finish the Python work.

### Specification Detail
- We only need the data of Station ID = 48549.
- The year range of the data we want is from 2020 to 2022.
- We only want the data in February.
- The data will be downloaded in hourly format.
- The output file will be named as all_years.csv.
