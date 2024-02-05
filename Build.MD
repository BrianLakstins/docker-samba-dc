To build and publish the docker image on the 116VB Network
1. Start a terminal in the root folder on a system with docker.
2. docker build -t docker-samba-dc ./
3. docker image tag docker-samba-dc registry.3.116vb.dns9.co/docker-samba-dc
4. docker push registry.3.116vb.dns9.co/docker-samba-dc
