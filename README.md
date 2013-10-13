## Maven Repo

A means to an end. Somewhere to throw jars when I can't find a maven repo for them. 

### Using this maven repo

Add the following to your pom.xml

	<repositories>
    	<repository>
        	<id>Trastle-Github-mvn-repo</id>
        	<url>https://raw.github.com/trastle/maven-repo/master</url>        
        	<snapshots>
            	<enabled>true</enabled>
            	<updatePolicy>always</updatePolicy>
        	</snapshots>
    	</repository>
	</repositories>
