# Intro of Jenkins

Jenkins is an open source automation server. It helps automate the parts of software development
related to building, testing, and deploying, facilitating continuous integration and continuous
delivery. It is a server-based system that runs in servlet containers such as Apache Tomcat.

For learning how to use jenkins please see my article:

[Lets go to learn how to use Jenkins from scratch](https://mirbozorgi.com/en/how-to-use-jenkins/)

### For starting with Docker:

- Clone the repository
- Execute this command in the root directory: `docker-compose up -d`

### For starting with Docker Swarm for orchestration:

- Clone the repository and execute below commands
- sudo docker swarm init
- sudo docker stack deploy -c docker-compose-linux.yml jenkins_server