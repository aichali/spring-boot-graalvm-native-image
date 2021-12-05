1. Build a regular image with Buildpacks
	- replace the pom.xml by regular-image-pom.xml
	- build the image with the command : mvn spring-boot:build-image
	
2. Build a native image with Spring Native and GraalVM
	- the configuration is already presents in the pom.xml
	- build the image with the command : mvn spring-boot:build-image

	