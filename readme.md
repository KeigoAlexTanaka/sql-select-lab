---
title: SQL Select
type: lab
duration: "1:25"
creator:
    name: Micah Rich
    city: LA
competencies: Databases
---

# Use SQL to find Carmen Sandiego

## Introduction

> ***Note:*** _This can be a pair programming activity or done independently._

#### Where In The World Is Carmen Sandiego?

We're going to use what we've learned already about searching with SQL commands, and apply it to chase down and capture an elusive and world-renowned thief, Carmen Sandiego. Follow the clues, use the interweb - write down both the SQL commands /queries you used and your answers to the clues - and figure out where Carmen is headed, so we can catch her and bring her in.

## Exercise

#### Requirements

- Fork and clone the repository
- Use the clues.sql file as your "answer sheet"
- From the command line, let's create a new database called `carmen` and populate it with the SQL found in `world.sql`

```
# Enter psql
psql

# Create database
CREATE DATABASE carmen;

# Connect to carmen
\c carmen
# Import the database
\i world.sql
```

#### Go!

Use the `clues.sql` file to write in the SQL queries that correspond with each clue and tell us where she's heading at the bottom.

## Additional Resources

- [PostgreSQL tutorial](http://www.tutorialspoint.com/postgresql/)
- [PostgreSQL official documentation](http://www.postgresql.org/docs/)
