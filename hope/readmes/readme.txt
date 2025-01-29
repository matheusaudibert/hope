Marcos Alfaro wrote the Hope interpreter of this package from 
source code written by Professor Ross Paterson. Unfortunately, 
Marcos did not provide the source code. I tried to get in touch 
twice at different times and was unsuccessful. Maybe Marcos 
Alfaro is incommunicado. If anyone has the source for this 
version and wants to contribute, it would be most welcome.

The distributed Hope interpreter is composed of two files, 
"hope.exe" as the language kernel and "Standard.hop" as the 
standard library containing important operational features of 
the language. For the environment to work both files must be 
present in the same directory. 

The original "Standard.hop" file written by Ross Paterson is 
sufficient for use in the environment, but its operation in the 
interpreter coded by Marcos Alfaro has small differences from the 
POSIX version. In this way, I created an alternative "Standard.hop" 
file that seeks to mitigate the differences between the two 
platforms in addition to implementing some common features found 
in other programming languages.

Site Marcos Alfaro: http://hopelang.blogspot.com/.
