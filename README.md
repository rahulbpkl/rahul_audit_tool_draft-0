## RAT.jar

This package contains a jar file which checks the given code satisfies CERT coding standard. RAT.jar is used to process a large number of source code written in java. It won't compile and generate the class file, it will only verify any coding standard violation is present or not. So input should be an error-free(completed successful compilation) java file.
For some rules RAT will do an auto fix. 

## Note
This package is under developing stage. Please report the bugs and your suggestions.

## Rules Implemented

*   [DCL00-J. Prevent class initialization cycles](https://www.securecoding.cert.org/confluence/display/java/DCL00-J.+Prevent+class+initialization+cycles)
*   [DCL01-J. Do not reuse public identifiers from the Java Standard Library](https://www.securecoding.cert.org/confluence/display/java/DCL01-J.+Do+not+reuse+public+identifiers+from+the+Java+Standard+Library)
*   [DCL02-J. Do not modify the collection's elements during an enhanced for statement](https://www.securecoding.cert.org/confluence/display/java/DCL02-J.+Do+not+modify+the+collection%27s+elements+during+an+enhanced+for+statement)
*   [MSC01-J. Do not use an empty infinite loop](https://www.securecoding.cert.org/confluence/display/java/MSC01-J.+Do+not+use+an+empty+infinite+loop)

## Auto-Fix Implemented 
*   [MSC01-J. Do not use an empty infinite loop](https://www.securecoding.cert.org/confluence/display/java/MSC01-J.+Do+not+use+an+empty+infinite+loop)

## Dependency

Compiled on 

```
openjdk version "1.8.0_45-internal"
```

## Project Structure

*   Download the .tar file of latest version from [here](https://github.com/rahulbpkl/rahul_audit_tool_draft-0/blob/master/rat.tar.gz) and unzip the file
*   The project file contains three directories.
*   config - which contains all the configuration files.
*   Sample - which contains some examples of both noncompliant and complaint code. 
*   output - contains the errorlog file
*   rat.jar - which is the actual executable file of the project.
*   Before running verify all the four are present.
 

## How To use

Open terminal and type

```
java -jar rat.jar
```
You will get a menu and you can select which option you want.

For detailed information please go to the [wiki page](https://github.com/rahulbpkl/rahul_audit_tool_draft-0/wiki)


 

