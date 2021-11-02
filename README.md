RUNNING THE MAIN PROGRAM:
It is required that the user is logged in with username: scm and password: ensf409 in the SQL database. In order to run
the main program, you will need to cd into the directory right before the edu and lib folder(directory Group #8) and type
the following commands:

Windows
javac -cp .;lib/mysql-connector-java-8.0.23.jar;. Transaction.java
java -cp .;lib/mysql-connector-java-8.0.23.jar;. Transaction
alternatively, you can also run the run.bat file in command prompt

MACOS and linux
javac -cp .:lib/mysql-connector-java-8.0.23.jar:. Transaction.java
java -cp .:lib/mysql-connector-java-8.0.23.jar:. Transaction
alternatively, you can also run the runProgramLinux.sh file in your terminal 

Change USERNAME and PASSWORD

To get the databases downloaded locally, in your SQL command line client enter:

source <"path to SQL directories at the top level of the project">

Video Demo: https://youtu.be/5KpXf2P5t6s 
