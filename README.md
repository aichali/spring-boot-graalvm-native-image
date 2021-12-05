1. Build a regular image with Buildpacks
	- replace the pom.xml by regular-image-pom.xml
	- build the image with the command : mvn spring-boot:build-image

	![regular-image](https://user-images.githubusercontent.com/68104000/144757531-307d92e3-9445-4e8f-b241-7867271a26e1.png)

	
2. Build a native image with Spring Native and GraalVM
	- the configuration is already presents in the pom.xml
	- build the image with the command : mvn spring-boot:build-image
	
     ![native-image](https://user-images.githubusercontent.com/68104000/144757552-47adbf50-93f6-4818-8256-6802854433d3.png)
