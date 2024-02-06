## SDF Workshop Day 3

1. https://maven.apache.org/guides/getting-started/maven-in-five-minutes.html
2. In bash: create the initial Maven project scaffolding (within root folder):
``````
mvn archetype:generate -DgroupId=sg.edu.nus.iss -DartifactId=sdfworkshop3 -DarchetypeArtifactId=maven-archetype-quickstart -DarchetypeVersion=1.4 -DinteractiveMode=false
``````
3. In GitHub: initial git repo, remote link, etc.
4. In bash: navigate into the project directory (i.e. sdfworkshop3):
``````
mvn clean compile
``````
``````
4. mvn package
``````
``````
5. java -cp target/sdfworkshop3-1.0-SNAPSHOT.jar
``````