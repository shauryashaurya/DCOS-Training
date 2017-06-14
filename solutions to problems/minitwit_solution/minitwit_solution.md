# All steps mentioned in the training document 02.md remains same.Only the following modifications were made

After cloning the minitwit repo.Update the following two files in the 
* application.yml ---
	port: 8080

* Dockerfile ---
	EXPOSE 8080

* Please start the container with the following command:
	docker run -d -p 8081:8080 -name minitwit ${DOCKER_USER}/minitwit

# Win 7:
 
 Run the following in toolbox 
 
 	docker-machine env default
 	The reult should be something like
 	export DOCKER_TLS_VERIFY="1"
	export DOCKER_HOST="tcp://192.168.99.100:2376"
	export DOCKER_CERT_PATH="C:\Users\nboro\.docker\machine\machines\default"
	export DOCKER_MACHINE_NAME="default"
	# Run this command to configure your shell:
	# eval $("C:\Program Files\Docker Toolbox\docker-machine.exe" env default)
	
 Please access the application using http://192.168.99.100:8081

# Win 10

I presume since docker is running as aprt of the host machine,The url should be
	http://`<hostMachineIp>`:8081

