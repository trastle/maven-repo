## Maven Repo

Somewhere to throw jars when I can't find a maven repo for them. 


### Using this maven repo

Add the following to your pom.xml

	<repositories>
    	<repository>
        	<id>YOUR-PROJECT-NAME-mvn-repo</id>
        	<url>https://raw.github.com/YOUR-USERNAME/YOUR-PROJECT-NAME/mvn-repo/</url>
        	<snapshots>
            	<enabled>true</enabled>
            	<updatePolicy>always</updatePolicy>
        	</snapshots>
    	</repository>
	</repositories>
