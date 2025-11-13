# Base Parent POM for Combostrap projects


This repo contains the maven  parent project object model (POM) files.

The parent pom defines common default configuration for Combostrap projects.


The parent pom defines common default configuration for Vert.x projects:
* base plugins versions.
* file encoding.
* Java 8 source and target.
* install test-jar, sources and test-sources artifacts.
* Release/snapshots repositories.


## FAQ ?
### Why the name Parent and not Maven Parent?

Because the POM may be used also by Gradle, and it's a java convention.
