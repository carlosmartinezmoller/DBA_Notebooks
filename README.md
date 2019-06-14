# DBA_Notebooks
## Objective
Somehow Database Administrators we have been Data Scientists for a long time. Analyzing all the information available in the Database Dictionary to diagnose a job is something that may take days of data manipulation and inspection.

Some tools have been built (OEM, Toad, etc) to display the dictionary information, but we always find ourselves using our specialized scripts that we store as treasure in SQL files to end up diagnosing some uncommon issues, strange lockings, etc

As Data Scientists, we have to look what other Data Scientists are doing. And one basic tool I have noticed they use are Notebooks.

Notebooks can be very useful for DBAs too. They help to:
* Put together all of our scripts to analyze one specific issue
* Have an easy tool to quickly visualize the data we are gathering
* Give a tool so that the DBAs on a team can share and improve together the scripts

## Contents
The starting poing are notebooks that:
* Are created with Zeppelin
* Are focusing on Oracle Database

## How to use
### Download and setup Zeppelin to monitor your database
* Download Zeppelin
* Go to "Interpreter" and create a new "Interpreter" as JDBC type. Call it "oracle".
* Fill the Interpreter with the needed information to connect to your database
### Install the NoteBooks
* Download this NoteBooks from GitHub
* Import them into your Zeppelin installation
