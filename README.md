# JoeyJoebags
Custom version of the Joeybags software.


## Current Additions
- Allow dumping of 2048M Roms for dumping 369 In 1 carts
- Remove warning message on program start


# Compiling Windows Binaries
### Requirements
```
Python 3.4
PyUSB
py2exe
```

### Installing Requirements
1. Download & Install Python 3.4 64bit from https://www.python.org/downloads/windows/
2. open cmd as admin and type ```python -m pip install PyUSB``` & ```python -m pip install py2exe```

### Compiling
Run ```python -m py2exe JoeyJoebags***.py``` and windows binaries will be compiled.