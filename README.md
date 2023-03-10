## Code Details
The code is written in python and takes in input from the CLI. The following exceptions have been handled in the code:
* **FileNotFoundError**: If the required csv file is not found in the current working directory the code displays the appropriate message and exits.
* **EmptyDataError**: If the csv file is present but does not contain any data then the code displays the appropriate message and exits.
* **Negative Input**: If the user inputs negative value of points that the shopper can use then the code displays the appropriate message and exits.
* **IndexError**: If the user forgets to provide the points which they want to spend then the ode displays the appropriate message asking for a valid input and exits.
* **KeyError**: If the csv file does not contain the timestamp column, the column using which the data needs to be sorted, then the program terminates after displaying an appropriate message to use a csv file containing valid data.
 
## Run the code
To run the code, please use the command **python codingtest.py <em>points</em>** OR **python3 codingtest.py <em>points</em>**

