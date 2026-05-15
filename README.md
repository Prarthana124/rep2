java -cp target/myapp-1.0-SNAPSHOT.jar com.example.App
clean compile test package
mvn archetype:generate -DgroupId=com.example -DartifactId=myapp -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false
