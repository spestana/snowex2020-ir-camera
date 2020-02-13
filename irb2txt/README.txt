Converting .irb files from the VarioCam to ascii formate brightness temperature (F)
(Note: this irb2txt.exe was provided by Arnaldo Echevarria arnaldo@arnaldo3.com
It has only been tested on Win32 and Win64 bit machines)

Command line instructions (in windows cdm or linux environment)

1) Extract .zip file somewhere 
This contains some libraries and the irb2txt.exe file, which is the converter. 

Usage: irb2txt [directory or irb file name]
Generates text file(s) of temperature data

2) Move to the folder with the .irb files

3) [full path to irb2txt.exe location]/irb2txt.exe *
or
[full path to irb2txt.exe location]/irb2txt.exe ./

4) Creates .txt files with the following format

ID  y-pixel x-pixel   Brightness temperature (F)
1     1     1     -5.00085
2     1     2     -5.31424
3     1     3     -5.45352
4     1     4     -5.00085
5     1     5     -5.07048
6     1     6     -5.07048
7     1     7     -5.07048
8     1     8     -5.17493
9     1     9     -4.93120
...
