gsub
====

using ruby gsub in shell scripts


install
=======

requires ruby, which comes preinstalled with almost all osx or linux operating systems

move the gsub file to a path which is loaded by your OS and make it executable

> mv gsub /usr/bin

> chmod +x gsub


usage examples
==============

open a new terminal and run the gsub command without arguments

> gsub

no arguments provided

Usage: gsub: find replace

> echo "Hello World"

Hello World

> echo "Hello World" | gsub World Universe

Hello Universe

> echo "Hello World" | gsub World Universe | gsub 'Universe' 'Universe!'

Hello Universe!


todo
====

* regular expressions
* version number
* process files 


