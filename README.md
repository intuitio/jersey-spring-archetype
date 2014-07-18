jersey-spring-archetype
=======================

A maven archetype for generating a kickstart project based on Jersey 2, Spring 4, Servlet 3.1 (annotation-based, no XMLs)

## Installing

```
% git clone https://github.com/intuitio/jersey-spring-archetype.git
% cd jersey-spring-archetype
% mvn install
```

## Creating a skeleton project

```
% mvn archetype:generate \
    -DarchetypeCatalog=local \
    -DarchetypeGroupId=intuitio.kickstart.jersey \
    -DarchetypeArtifactId=jersey-spring-kickstart-archetype \
    -DarchetypeVersion=1.0-SNAPSHOT
```
Follow the on-screen details to enter your desired groupId, package, etc. 

## Running the newly generated project

Run the app via maven using mvn tomcat7:run and see some action on http://localhost:8080/api/tasks

