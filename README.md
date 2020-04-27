# Control-Statement-Parse
 
A tool for making predicates for control statements variables. Used for our research for java subject programs.

Takes 2 paramaters: 

- Param 1: Output directory path (file is generated by the same name as input .java).
- Param 2: Input file path.

Outputs: 

- Any .java file with it's predicates ordered from top to bottom; P\_0 ... P\_N, where N is the number of predicates in a single file.
- predicates.txt, shows the predicate name, predicate evaluation cause and line number. 

Requirements:
- Apache Maven 3.6+ - http://maven.apache.org/
- Java 8+ - https://www.java.com/en/download/
