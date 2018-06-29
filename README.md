# Hash Generator

This was an assessed piece of work during the first semester of my second year at university. The project is a CLI driven program that allows the user to create a hash from either a filename, file item or directory of file items using an algorithm of their choice. The hashes can be compared with one another to check for changes and can also be read from and written to a text file. The project is not complete yet and I would like to add extra features before I consider it to be complete.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

To use the Hash Generator you must have Java JDK installed (found at: http://www.oracle.com/technetwork/java/javase/downloads/index.html) and a basic knowledge of either Windows Command Prompt or Linux Terminal, depending on the platform you are using.

To install Java JDK download the SDK from Oracle's downloads page. Once downloaded, run the program and go through the setup wizard. Remember where the JDK is saved if you want to recompile later.

### Installing
Assuming you have downloaded the project to C:\Users\[TomBabz]\Documents\GitHub where [TomBabz] is your own username:

Open Command Prompt and type "cd Documents\GitHub":
```
C:\Users\TomBabz> cd Documents\GitHub
```
Next type "cd hash-generator":
```
C:\Users\TomBabz\Documents\GitHub> cd hash-generator
```
Next type "cd bin":
```
C:\Users\TomBabz\Documents\GitHub\hash-generator> cd bin
```
Next type "java Main":
```
C:\Users\TomBabz\Documents\GitHub\hash-generator\bin> Java Main
```
You should now be greeted with the welcome screen for the Hash Generator:
```
Welcome to Hash Generator
This Java based application is designed to provide support tools to identify tampering with file-system contents.

Use '-man' to read the manual or '-help' for a quick tutorial if you get stuck in using the application.
User: _
```

If you want to compile the project then:

Open Command Prompt and type "cd Documents\GitHub":
```
C:\Users\TomBabz> cd Documents\GitHub
```
Next type "cd hash-generator":
```
C:\Users\TomBabz\Documents\GitHub> cd hash-generator
```
Next type "cd src":
```
C:\Users\TomBabz\Documents\GitHub\hash-generator> cd src
```
check that the java files are present with "dir". You should see .java files.
```
C:\Users\TomBabz\Documents\GitHub\hash-generator\src> dir
```
Next tell the system where your JDK programs are located with "set path=%path%;C:\Program Files\Java\[your JDK version]\bin
```
C:\Users\TomBabz\Documents\GitHub\hash-generator\src> set path=%path%;C:\Program Files\Java\jdk1.8.0_172\bin
```
Next compile the programs with javac
```
C:\Users\Tom\Documents\GitHub\hash-generator\src> javac CliReader.java DirReader.java FileByteReader.java FileControl.java HashChecker.java HashControl.java HashFunction1.java HashFunction2.java HashFunction3.java HashFunction4.java Main.java Menu.java
```
If all has gone well then you should have .java and .class files in the directory. Check with "dir":
```
C:\Users\Tom\Documents\GitHub\hash-generator\src> dir
```
Next type "java Main":
```
C:\Users\TomBabz\Documents\GitHub\hash-generator\src> Java Main
```
You should now be greeted with the welcome screen for the Football Results Manager:
```
Welcome to Hash Generator
This Java based application is designed to provide support tools to identify tampering with file-system contents.

Use '-man' to read the manual or '-help' for a quick tutorial if you get stuck in using the application.
User: _
```

## Running the tests

//TODO: Implement tests

## Deployment

Deployment was not apart of the assessment for this program, It was intended for assessment purposes only. Furthermore the program has not been thoroughly tested and so I would not recommend for real world application.

## Authors

* **Thomas Barber**

## License

This project is unlicensed

## Acknowledgements

* Leeds Beckett University
* Stack Overflow
