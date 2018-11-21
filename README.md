# PostgreSQL-tutorial
PostgreSQL tutorial using notebook SQL cell magic.
# SQL Magic
PostgreSQL using cell magic

```
%%sql
(Your SQL statement)
```

## Jupyterlab PostgreSQL tutorial

This project is a tutorial on PostgreSQL using SQL cell magic in Jupyterlab notebooks

The tutorial taken through is [this tutorial](http://www.postgresqltutorial.com/) and this [book](https://www.amazon.com/PostgreSQL-2nd-Korry-Douglas/dp/0672327562) by Korry Douglas:

## Getting Started

### Prerequisites

Be running Jupyter. I use the anaconda installer: https://www.continuum.io/downloads

You'll also need to install the library listed below, if you don't have it

```
ipython-sql
```
You can also follow instructions at:https://github.com/catherinedevlin/ipython-sql

You can install it using pip like this

Windows: As admin open the anaconda prompt and run
```
pip install ipython-sql
```
Linux:\
download from https://github.com/catherinedevlin/ipython-sql and:
```
cd ipython-sql
sudo python setup.py install
```

using the load extension cell magic, load the sql extension

```
%load_ext sql
```
Connect to the database, case in point here a PostgreSQL database like this with your own information

```
postgresql://username:password@hostname/dbname
```

You can find examples like
1. http://www.jamesloach.com/misc/sql_jupyter_basics.html
2. https://github.com/catherinedevlin/ipython-sql


Use can now use %%sql cell magic in the cells to manupilate the database within the notebook.


## Author

* **Peter Otieno** - [peterakworo](https://github.com/peter-akworo) - [LinkedIn](https://www.linkedin.com/in/peter-onyango-184446132/)

## Acknowledgments

* To all my LinkedIn connections for your support.

