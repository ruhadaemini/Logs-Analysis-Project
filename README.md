# Logs Analysis



> Ruhada Emini




## About

 
This project is a part of the Udacity's Full Stack Web Developer Nanodegree. The aim of this project is building an informative summary from logs by sql database queries. 


##Project Requirements

Reporting tool should answer the following questions:

- What are the most popular three articles of all time?
- Who are the most popular article authors of all time?
- On which days did more than 1% of requests lead to errors?




## How to run it? 



### You will need:


- Python3

- Vagrant

- VirtualBox




### Setup
 

Install Vagrant And VirtualBox
2. Clone this repository

### To Run

Launch Vagrant VM by running `vagrant up`, 
you can the log in with `vagrant ssh`

To load the data, use the command `psql -d news -f newsdata.sql` to connect a database and 
run the necessary SQL statements.

The database includes three tables:

- Authors table

- Articles table

- Log table

To execute the program, run `python3 newsdata.py` from the command line.
