This project was an assignment in the "Python Project for Data Engineering" course on Coursera. 
After submitting the project, it was evaluated by other students enrolled in the course. (Jupyter Notebook was used for this project.)

The project file is named 'banks_project,' and the goal is to implement a simple ETL (Extract, Transform, Load) process using worldwide bank data.

Extract:
I created a function using the Python requests library to collect data from the website https://web.archive.org/web/20230908091635%20/https://en.wikipedia.org/wiki/List_of_largest_banks.

Transformation:
I created a new column in the DataFrame based on the exchange rates indicated in exchage_rate.csv and saved it to the DataFrame.

Load:
The processed DataFrame is saved as both a CSV file named 'largest_banks_data.csv' and in a database.

In the following section, you can verify the processes by calling the functions. Additionally, the 'log_process' function saves log data of the ETL process in a file named 'code_log.txt.'
