I've made some adjustments to the Dockerfile as the original instructions didn't align with my laptop's compatibility:

- I switched to the latest version of Ubuntu instead of version 18.04.
- I used different commands for building and pushing the Dockerfile.

COMMANDS USED:

sudo docker build --platform linux/amd64 --no-cache -t gowthamee/docker-lab-5156:3.0.0 . - for building

sudo docker push gowthamee/docker-lab-5156:3.0.0 - for pushing
