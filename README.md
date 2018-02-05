# TU-RP1210
A repository with sample source code for the American Trucking Association's Technology and Maintenance Council (TMC) RP1210 Windows Communication API

This is a PyQt5 project. 

The program makes use of the ctypes library in Python to connect to the RP1210 DLL driver files. 

## Installation
Install Python 3.6.

The Python package is available on pip. 

```pip install TURP1210```

The example.py program will enable you to import and run the module.

### Packaging

Read the tutorial at 
 In the `GitHub\TURP1210` directory (or wherever you saved the file), run the following
 ```python setup.py bdist_wheel```
 
 ### Compiling
 The nuitka project enables compiling into a Windows Executable. After installing, run the following from the script directory.
 
 ``` nuitka --recurse-all --standalone --plugin-enable=qt-plugins TU_RP1210.py```