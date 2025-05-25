Changes:  
1. pom.xml maven-compiler-plugin build version changed from 1.7 to 1.8  
2. jena versions changed from 2.13.0 to 3.16.0  
3. `com.hp.hpl.jena.` changed to `org.apache.jena.` globally  
4. in old_parser/TreeBox.java unused import commented out // import sun.misc.Regexp;  

Usage: Run `mvn install` on root with Java 11, use `csparql-ui-0.9.7-jar-with-dependencies.jar` in dependencies.  


CSPARQL-engine
==============

Reasoning over RDF stream made easy.
The project contains parent pom in the root and a number of module that inherit from parent pom.
To install the csparql-core jar, run mvn install on parent pom.
