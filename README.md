<!--
SPDX-FileCopyrightText: 2008-2021 Andreas Härtel <http://andreashaertel.anno1982.de/>
SPDX-License-Identifier: CC-BY-SA-4.0
SPDX-PackageName: parameter_handler
SPDX-PackageHomePage: https://github.com/andreashaertel/parameter_handler
-->

# parameter_handler

Handle parameters from a parameter file or from the command line in Python and C++. 

The project contains a C++ library and a Python module parameter_handler. 

In addition, the C++ library allows to define individual flags next to the standard ones. 
The whole functionality is demonstrated in a full example program, while a minimalistic 
program demonstrates the easy use of the library to just import parameters from a file 
and the command line at the same time. 
The latter has the advantage that for a standard parameter setting single parameters 
can be overwritten during each call. 


## Version

The current version is 1.0.0.  



## Install

To download and install the project, you need to clone from github and to run make init and make:
```bash
git clone https://github.com/andreashaertel/parameter_handler.git
cd parameter_handler/
make init
make
```

To make the documentation, you need to run make in the doc/ subfolder:
```bash
cd doc/
make
```
The documentation is generated by Doxygen and available in html and LaTeX. 
See doc/html/index.html for further details (html version). 
The LaTeX version must be generated by calling make in the doc/latex directory, 
which creates a refman.pdf reference manual document. 


### C++

The C++ library libHOSTNAME.parameter_handler.a is created in the bin directory. 
To include it in your system, you have to make it available, for instance, by using 
the global system variable LD_LIBRARY_PATH. 

The header file parameter_handler.hpp, stored in the include directory, 
should be available in the include path of your system. 


### Python

The python module parameter_handler.py, stored in the bin/python directory, 
should be add to your PYTHONPATH system variable such that the module can be found. 

The module can be add to a script by importing, as demonstrated in the Python example. 



## Examples

Examples on how to use the parameter_handler are given in the examples directory. 



## Maintainers

- Andreas Härtel - <http://andreashaertel.anno1982.de/>
- Moritz Bültmann - <moritz.bueltmann@gmx.de>




## Contribute

Any pull requests or suggestions are welcome at
<https://github.com/andreashaertel/parameter_handler> or via e-mail to one of the maintainers.





## License

To add licenses to files, we use SPDX-FileCopyrightText, 
as recommendet by FSFE REUSE (<https://reuse.software/>). 

This work is licensed under multiple licences. Because keeping this section
up-to-date is challenging, here is a brief summary as of August 2021:

- All original source code is licensed under either LGPL-3.0-or-later or GPL-3.0-or-later.
- All documentation is licensed under CC-BY-SA-4.0.
- Some configuration and data files are licensed under CC0-1.0.

For more accurate information, please check the individual files.






