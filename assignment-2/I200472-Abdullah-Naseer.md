Q1) Explain Docker Containers vs VMs
Answer:  Docker containers have a shared OS and kernal as the Host machine whereas VMs have their own OS and kernal.
Containers are very lightweight and use shared resources i.e. libraries and depedneices but VMs have their own resources and UI.
Docker containers are not as isolated as VMs because they still share the same kernal.

Q2) Write command to create a docker container in detached mode with name assignment-2-<ROLL_NUMBER> running on host port 9090 and container port 80 using image nginx with version 1.24.0 on a custom network named assignment-2
Ans:docker network create assignment-2
docker run -d --name assignment-2-I20-0472 -p 9090:80 --network assignment-2 nginx:1.24.0

Q3) Run the above command and add screenshot of it and share the logs
