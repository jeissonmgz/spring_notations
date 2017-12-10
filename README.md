# Creación del proyecto con Maven
```
mvn archetype:generate -DgroupId=com.web -DartifactId=SpringWeb -DarchetypeArtifactId=webapp-javaee7 -DinteractiveMode=false -Dversion=1.0 -Dpacakage=com -DarchetypeGroupId=org.codehaus.mojo.archetypes
```

# Compilar
* mvn clean
* mvn install

# Run
```
mvn tomcat7:run
```