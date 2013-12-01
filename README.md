m2p2-repository
===============

Maven repo

How to use it
=============

Just add to your settings.xml
```xml
<repositories>
	<repository>
		<id>garc33-mvn-repo</id>
		<url>https://raw.github.com/garc33/m2p2-repository/mvn-repo/</url>
		<snapshots>
			<enabled>true</enabled>
			<updatePolicy>always</updatePolicy>
		</snapshots>
		<releases>
			<enabled>true</enabled>
		</releases>
	</repository>
</repositories>
```
