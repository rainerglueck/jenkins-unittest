## How to test Jenkins pipelines
https://itnext.io/unit-testing-a-jenkins-shared-library-9bfb6b599748
`install maven, groovy`

## Setting up docker environment
1. `docker network create jenkins` [Windows cmd file](/docker/create-docker-network-jenkins.cmd)
2. Run docker:dind Docker image  [Windows cmd file](/docker/run-docker-dind.cmd)
3. `docker build -t myjenkins-blueocean:1.1 .` [Windows cmd file](/docker/build-docker-myjenkins-blueocean-1.1.cmd)
4. Run docker myjenkins-blueocean:1.1 [Windows cmd file](/docker/run-docker-myjenkins-blueocean-1.1.cmd)

## Jenkins
https://www.jenkins.io/doc/book/installing/docker/

## Docker
https://docs.docker.com/docker-for-windows/install/