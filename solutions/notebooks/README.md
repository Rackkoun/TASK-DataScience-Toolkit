# Northwind Sample Database
The Northwind database is a sample database that was originally created by Microsoft and used as the basis for their tutorials in a variety of database products for decades. The Northwind database contains the sales data for a fictitious company called “Northwind Traders,” which imports and exports specialty foods from around the world. The Northwind database is an excellent tutorial schema for a small-business ERP, with customers, orders, inventory, purchasing, suppliers, shipping, employees, and single-entry accounting. The Northwind database has since been ported to a variety of non-Microsoft databases, including PostgreSQL.

We acquired the database from our PostgreSQL server provided by Neue Fische.
One must register accessibility into the server.
Make a new .sql file for accessing the database in SQL query.
Later, the further work will be done in Jupyter notebook.

Set up the virtual environment first hand.
I'm using windows, here's git bash commands.
### Set up Environment
For Git-Bash CLI :

  pyenv local 3.11.3
  python -m venv .venv
  source .venv/Scripts/activate
  python -m pip install --upgrade pip
  pip install -r requirements.txt

  to unzip data, unzip data.zip