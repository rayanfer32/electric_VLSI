# electric_VLSI

# DOWNLOAD THESE FILES AND INSTALL:
## LTSPICE :
http://ltspice.analog.com/software/LTspiceXVII.exe
## Java runtime environment:
https://www.java.com/en/download/manual.jsp
## electric software binary:
https://www.staticfreesoft.com/productsFree.html
https://ftp.gnu.org/pub/gnu/electric/electricBinary-9.07.jar
## settings for spice:
![spice_settings](https://github.com/Rayanfer32/electric_VLSI/raw/master/vlsi%20settings.png)
locate the scad3.exe from the installed directory and copy that address for eg: 
C:\Program Files\LTC\LTspiceIV\scad3.exe or F:\Program Files (x86)\LTC\LTspiceIV\scad3.exe

and copy it to run program feild shown in the above image.
#### run program: 
F:\Program Files\LTC\LTspiceIV\scad3.exe (older)
C:\Program Files\LTC\LTspiceXVII\XVIIx64.exe (new)

#### with args:
-i ${FILENAME} -r ${FILENAME_NO_EXT}.raw -o ${FILENAME_NO_EXT}.out
