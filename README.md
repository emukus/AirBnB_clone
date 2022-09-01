# AirBnB Clone
![65f4a1dd9c51265f49d0](https://user-images.githubusercontent.com/101443265/187922555-5478052d-cf7f-450e-bb5e-4541c72b8e08.png)

## Description
The Airbnb clone is a complete web application, integrating database storage, a back-end API, and front-end interfacing in a clone of AirBnB.

This project currently only implements the back-end console to communicate with the application.

## Execution
Execution
Your shell should work like this in interactive mode:
```
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
But also in non-interactive mode: (like the Shell project in C)
```
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

Testing
Unittests for the Airbnb_clone project are defined in the tests folder. Execute the following command to run the entire test suite simultaneously:
```
$ python3 unittest -m discover tests
```
Alternatively, you can specify a single test file to run at a time:
```
$ python3 unittest -m tests/test_console.py
```
All tests should also pass in non-interactive mode: ```$ echo "python3 -m unittest discover tests" | bash```
