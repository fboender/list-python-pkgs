# Python Packages

A high-level overview of which Python package you need to get the job done.

## Charting

### matplotlib

* **Support**: Python **v2**, **v3**.
* **Pure Python?**: No
* **Maintained**: Yes

### pygal

* **Support**: Python **v2**, **v3**.
* **Pure Python?**: Yes
* **Maintained**: Yes

### Plotly / plot.ly

* **Support**: Python **v2**, **v3**.
* **Pure Python?**: Yes (Webservice)
* **Maintained**: Yes

### Gnuplot.py

* **Support**: Python **v2**, **v3**.
* **Pure Python?**: No (but comes with Python by default)
* **Maintained**: Yes

### PyQtGraph

* **Support**: Python **v2**, **v3**.
* **Pure Python?**: No (but comes with Python by default)
* **Maintained**: Yes

### cairoplot

* **Support**: Python **v2**, **v3**.
* **Pure Python?**: No (but comes with Python by default)
* **Maintained**: Yes

### PyCha

* **Support**: Python **v2**, **v3**.
* **Pure Python?**: No (but comes with Python by default)
* **Maintained**: Yes

### pgplot

* **Support**: Python **v2**, **v3**.
* **Pure Python?**: No (but comes with Python by default)
* **Maintained**: Yes

### PyChart

* **Support**: Python **v2**, **v3**.
* **Pure Python?**: No (but comes with Python by default)
* **Maintained**: Yes

## Databases

Connecting to most databases in Python requires a database driver.

### Sqlite

Sqlite is a self-contained, high-reliability, embedded, full-featured, public-
domain, SQL database engine. It does not follow the server-client model like
most other databases. Instead, a single process can connect to the database
which lives on disk or in memory. Useful for persistently storing data and
configurations in your application, for testing purposes and for mocking
RDBMSes such as MySQL.

* **Support**: Python **v2**, **v3**.
* **Pure Python?**: No (but comes with Python by default)
* **Maintained**: Yes
* **URLs**:
    * [Homepage](https://dev.mysql.com/doc/connector-python/en/), 
* **Installation**: Included in all Python installations.

### MySQL

There are various connectors for MySQL. Which one to use depends on your
requirements.

#### Connector/Python

Official MySQL Python connector by the MySQL authors. Available in Pure Python
and as a C extension (binary driver).

* **Support**: Python **v2**, **v3**
* **Pure Python?**: Yes and No
* **Maintained**: Yes
* **URLs**:
    [Homepage](https://dev.mysql.com/doc/connector-python/en/), 
* **Installation**:
    * **Pure python**:
        * **pip**: FIXME
        * **Debian / Ubuntu (Python v2)**: `apt install python-mysql.connector`
        * **Debian / Ubuntu (Python v3)**: `apt install python3-mysql.connector`
    * **Binary driver**:
        * **pip**: `pip install MySQL-python`
        * **Debian / Ubuntu (Python v2)**: `apt install python-mysqldb`
        * **Debian / Ubuntu (Python v3)**: `apt install python3-mysqldb`

#### PyMYSQL

A pure-Python MySQL client library. The goal of PyMySQL is to be a drop-in
replacement for MySQLdb and work on CPython, PyPy and IronPython.

* **Support**: Python **v2**, **v3**.
* **Pure Python?**: Yes
* **Maintained**: Yes
* **URLs**:
    * [Homepage](https://github.com/PyMySQL/PyMySQL),
    * [Documentation](https://pymysql.readthedocs.io/en/latest/)
* **Installation**:
    * **pip**: `pip install pymysql`
    * **Debian / Ubuntu (Python v2)**: `apt install python-pymysql`
    * **Debian / Ubuntu (Python v3)**: `apt install python3-pymysql`

## Database Abstraction Layers / ORMs

### PyDAL

PyDAL is a Database Abstraction Layer (DAL) that maps Python objects into
database objects such as queries, tables, and records. The DAL dynamically
generates the SQL in real time using the specified dialect for the database
back end, so that you do not have to write SQL code or learn different SQL
dialects (the term SQL is used generically), and the application will be
portable among different types of databases.

* **Support**: Python **v2**, **v3**.
* **Pure Python?**: Yes
* **Maintained**: Yes
* **URLs**:
    * [Homepage](https://github.com/web2py/pydal)
    * [Documentation](http://www.web2py.com/books/default/chapter/29/06/the-database-abstraction-layer)
* **Installation**:
    * **pip**: `pip install pyDAL`

### SqlAlchemy

FIXME

## Graphical User Interface (GUI)

There are basically four options for creating graphical user interfaces.

### TkInter

Tkinter is a Python binding to the Tk GUI toolkit. It is the standard Python
interface to the Tk GUI toolkit and is Python's de facto standard GUI.
Tkinter is included with standard Linux, Microsoft Windows and Mac OS X
installs of Python.

TkInter is easy to use but doesn't always look like the rest of your desktop.
Included by default in the standard Python distribution, but needs to be
installed separately in Ubuntu. Decent support for most platforms.

* **URLs**:
    * [Python2 docs](https://docs.python.org/2/library/tk.html)
    * [Python3 docs](https://docs.python.org/3/library/tk.html)
    * [Tutorial](https://tkdocs.com/tutorial/)
    * [Reference](https://tkdocs.com/widgets/index.html)
    * [Reference](http://infohost.nmt.edu/tcc/help/pubs/tkinter/web/index.html),
* **Installation**:
    * Included in most default Python installations
    * **Debian / Ubuntu (Python v2)**: `apt install python-tk`
    * **Debian / Ubuntu (Python v3)**: `apt install python3-tk`

### GTK

FIXME

### QT

FIXME

## Templating

### Jinja2

### Mako

### Tempita
