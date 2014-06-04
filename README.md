Evaluation
====
Unix shell programming examples with a calculator functionality.

Exercise_1 -- TUI: Possibility for selecting of Time Zone and Getting of Current data & time for this TZ.

Exercise_2 -- GUI: Possibility for selecting of Time Zone and Getting of Current data & time for this TZ.

Exercise_3 -- Networked Client-Service Implementation.

Exercise_4 -- Localization to your own language

Instruction on how to run the Program
Requirements:
1. Install git by typing in the command line "apt-get install git"
2. Install dialog by typing in the command "apt-get install dialog"
3. Install xinetd (Extended Internet Services Daemon) by typing in the command "apt-get install xinetd"
4. Install netCat by typing in the command "yum -y install nc"

Exercise 1 TEXT USER INTERFACE
1. Clone the repository in your machine by typing the command "git clone https://github.com/fsangogboye/test.git
2. Navigate to the test folder in the home directory using "cd test"
3. List by typing the "ls"
4. identify the timeTUI file and enter the command "chmod 755 timeTUI" to enable access file permission to timeTUI file
5. Enter "./timeTUI" to run the program
6. Enter the "your_continent/city" and enter "OK"
7. This should give you the time in that City

Exercise 2 GRAPHICAL USER INTERFACE
1. List by typing the "ls"
2. identify the timeGUI file and enter the command "chmod 755 timeGUI" to enable access file permission to timeGUI file
3. Enter "./timeGUI" to run the program
4. Enter the "your_continent/city" and click "OK"
5. This should give you the time in that City

Exercise 3 NETWORKCLIENT-SERVICE IMPLEMENTATION
1. List by typing the "ls"
2. identify the "timeText ui" file and enter the command "chmod 755 timeText_ui" to enable access file permission to timeGUI file
3. Enter "nc localhost 1234" to create service client and TCP connection to server /usr/local/bin/timeTEXT.
4. Enter "./timeText_ui" to run the program
4. Enter the "your_continent/city" and click "OK"
5. This should give you the time in that City






