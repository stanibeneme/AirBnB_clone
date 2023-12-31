# The AirBnB Clone Project
![AirBnB Logo](https://www.pngitem.com/pimgs/m/132-1322125_transparent-background-airbnb-logo-hd-png-download.png)

## Description

This is the initial phase of the Airbnb Clone: the console. This repository holds the command interpreter and classes (i.e. BaseModel class and several other classes that inherit from it: Amenity, City, State, Place, Review), and a command interpreter. The command interpreter, like a shell, can be activated, take in user input, and perform certain tasks to manipulate the object instances.

## How to Use Command Interpreter

| Command | Sample Usage | Functionality |
|-------|:------------:|--------------:|
| help | help | displays all commands available|
| create |create <class> | creates new object (ex. a new User, Place)|
|update | User.update('123', {'name' : 'Bunmi_n_Stanley'}) | updates attribute of an object|
|destroy | User.destroy('123') | destroys specified object|
|show | User.show('123') | retrieve an object from a file, a database|
|all | User.all() | display all objects in class|
|count | User.count() | returns count of objects in specified class|
|quit | quit | exits|

## installation

```git
git clone git@github.com/stanibeneme/AirBnB_clone.git
cd AirBnB_clone
```

## usage

interactive mode

```terminal
$ ./console.py
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  help  quit

(hbnb)
(hbnb)
(hbnb) quit
$
```

non-interactive

```terminal
$ echo "help" | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb)
$
$ cat test_help
help
$
$ cat test_help | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb)
$
```

## Environment

* Language: Python3
* OS: Ubuntu 14.04 LTS
* Style guidelines: PEP 8 (version 1.7) || Google Style Python Docstrings || WC3 Validator

## Authors

* Stanley Ibeneme
* Bunmi Akinola
