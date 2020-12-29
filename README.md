# OpenMRSCodeParsing

Steps to run CodeSensor:

1.Download the antlr-3.4-complete-no-antlrv2.jar from
```
https://www.antlr3.org/download/
```
and put it in the root folder.

2.Run the build.sh script
```
./build.sh
```
This will create a build folder with a compiled CodeSendor.jar file

3.Test with a small C code snipet
```
java -jar CodeSensor.jar test.c > output.txt
```
check the output.txt file.