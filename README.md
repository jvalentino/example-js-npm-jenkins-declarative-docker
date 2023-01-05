

# Building JavaScript with NPM using a Jenkins Declarative Pipeline running on a Docker-based Build Agent

This project is used to demonstrate that:

1. The build agent of https://github.com/jvalentino/jenkins-agent-npm (Docker Hub as `jvalentino2/jenkins-agent-npm`) works
2. The Jenkins project of https://github.com/jvalentino/example-jenkins-docker-jcasc-2 is able to run this pipeline on the build agent

The basis of this project is https://github.com/jvalentino/example-js-npm-lib-3, which had a Jenkinsfile added referencing the agent of `npm` that is then setup as a Docker Build agent mapping to `jvalentino2/jenkins-agent-npm`.

