
Docker Hub:
https://hub.docker.com/layers/gowthamee/docker-lab-5156/1.0.0/images/sha256:81781847c759b86364ae961fa3f70418869b6f7bc3a042b14b432b3c60890ecd?uuid=323acb4c-3887-4ff7-a919-1a9dd5af74de%0A

I've made some adjustments to the Dockerfile as the original instructions didn't align with my laptop's compatibility:

- I'm using a Macbook Air with M1 chip so I switched to the latest version of Ubuntu instead of version 18.04.
- I used different commands for building and pushing the Dockerfile.

COMMANDS USED:

**sudo docker build --platform linux/amd64 --no-cache -t gowthamee/docker-lab-5156:3.0.0 . - for building

sudo docker push gowthamee/docker-lab-5156:3.0.0 - for pushing**
