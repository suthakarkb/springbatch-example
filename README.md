# Summary
Maven archetype providing a pre-configured and basic Spring Batch setup.

This setup provides the most common starting point I have seen which is reading from a flat file and writing to a database.

# Features
Some features that work out of the box are:

* Basic reader, processor and writer example.
* Uses hsqldb as an in memory data source.
* Ability to run via maven or a deployment package.
* Example test coverage.

# Local Source Install
$ git clone https://github.com/suthakarkb/springbatch-example.git

# Use
1. cd <directory> 
   mvn clean package

2. Execute the job via Maven:
   * Run: mvn exec:java
   * See the exec-maven-plugin section of the pom for more info on changing job parameters.

# Contribute
Contributions are more then welcome. Please fork the repository and create pull requests!
