Jenkins in a box
================
Docker image of latest Jenkins

Run as:
```bash
docker run -d \
           -p 8080:8080  \
           -p 22         \
           -v ~/code:/srv/code \
           -v ~/jenkins_home:/opt/jenkins \
           anapsix/jenkins
```
