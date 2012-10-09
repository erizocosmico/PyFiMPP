PyFiM++
=======

Python compiler for the pony programming language FiM++. The compiler translates your FiM++ code to Python code and then it runs using magic.
More info: http://www.equestriadaily.com/2012/10/editorial-fim-pony-programming-language.html

Usage
=====

To run the compiler you just have to navigate to the directory where your .pony file is and run it from the command line.
```bash
cd /path/to/your/pony/file
fimpp myponyfile.pony
```
The compiler will generate a "yourfilename_c.py". That's the compiled version in Python. You can run it with python command instead of calling again fimpp.

Installation
============

```bash
sudo curl https://raw.github.com/mvader/PyFiMPP/master/fimpp -o /usr/local/bin/fimpp;
sudo chmod +x /usr/local/bin/fimpp
```
That's it. Easy, huh?

Tests folder
============

Tests folder include a portable file with the FiMppCompiler class, a test.py file if you want to try it out without using the command line tool and main.pony, a FiM++ example file.