# Description
Maven archetype to generate a simple Java project with JUnit, Hamcrest, Podam, JavaFaker, Apache Commons-lang and optionally lombok to kick-start coding dojos or katas. Used mainly for group or individual training exercises and labs.

# Requirements
Java 1.8
Maven 3.3.9+

# How to use

 - Clone the repository
 - Then move to that cloned directory and call mvn install.
 - Finally move to a fresh directory and use the archetype:

mvn archetype:generate -B -DarchetypeCatalog=local -DarchetypeGroupId=com.rubensans.katas-java -DarchetypeArtifactId=kata-java-starter-archetype -DarchetypeVersion=0.0.1 -DgroupId=com.kata -DartifactId=kataname
