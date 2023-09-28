# SQL Lab

![csd](./images/csd.jpeg)

# Where In The World Is Carmen Sandiego?

## Introduction

### Use SQL to find Carmen Sandiego

We’re going to use what we’ve learned already about querying a database using SQL commands to to chase down and capture an elusive and world-renowned thief, Carmen Sandiego!

This is an excellent lab to collaborate with classmates on!

## Setup

This lab requires *.sql files used to create a database with tables that contain data about locations across the 🌎…

1. Move into your ~/code folder:
2. Clone the repo to obtain the files:
 git clone https://git.generalassemb.ly/sei-blended-learning/sql-lab.git
3. Move into the newly created sql-lab folder:
4. Open VS Code:
5. Open a terminal session (control + backtick) and run ls - you should see three files: clues.sql, world.sql & solution.md.
6. Start the psql interactive terminal:
7. Create a database named carmen and connect to it:
 CREATE DATABASE carmen;
 \c carmen
8. Run the following command to run world.sql that creates city, country & countrylanguage tables and seeds their data using the:

## Exercises

The goal is to figure out what city Carmen Sandiego is heading to so that she can be met by the proper authorities.

You’ll be writing SQL queries within clues.sql to answer each clue.

Check your progress by running the queries that you write in clues.sql using: \i clues.sql

## Hints

- Use the psql \d & \d tablename commands to list & display the schema of each of the three tables.

- Google and collaborate to reach the goal of finding out where Carmen’s destination is.

- For example, you’ll certainly need to know about the ORDER BY clause.

- Try not to peek too much at solution.sql.

## Additional Resources

- PostgreSQL official documentation

## Encore

- If you finish this exercise and want to learn more about SQL, do some of these exercises here.