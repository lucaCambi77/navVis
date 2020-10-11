
## Task ##

Write a Java-based program (command line) that reads text from a file, splits it into words
at spaces and newline characters and constructs an (unbalanced) binary tree where each
leaf node represents a unique word.

See pdf in /pdf/NavVis_CodeChallenge_Web_1.pdf

## Install and run the application
To use the application you need java 8 installed in your machine

To create jar

	- mvn clean package

To run  

	- java -jar target/navVis.jar {path/to/file}

To edit source code, you must install lombok (https://projectlombok.org/) depending on your IDE