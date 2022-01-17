---
id: common.java
title: Java
desc: ''
updated: 1642441815036
created: 1642441815036
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# java

> Java Application Launcher.
> More information: <https://docs.oracle.com/en/java/javase/17/docs/specs/man/java.html>.

- Execute a java `.class` file that contains a main method by using just the class name:

`java {{classname}}`

- Execute a java program and use additional third-party or user-defined classes:

`java -classpath {{path/to/classes1}}:{{path/to/classes2}}:. {{classname}}`

- Execute a `.jar` program:

`java -jar {{filename.jar}}`

- Execute a `.jar` program with debug waiting to connect on port 5005:

`java -agentlib:jdwp=transport=dt_socket,server=y,suspend=y,address=*:5005 -jar {{filename.jar}}`

- Display JDK, JRE and HotSpot versions:

`java -version`

- Display usage information for the java command:

`java -help`

