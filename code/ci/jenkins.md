# x - code - continuous integration - jenkins

> The leading open source automation server, Jenkins provides hundreds of
> plugins to support building, deploying and automating any project.

## Recipe

With Docker ([docker image](https://hub.docker.com/_/jenkins/)):

```sh
docker run -d --name jenkins -p 8080:8080 -p 50000:50000 -v /your/home:/var/jenkins_home jenkins
```

## Resources

*   [Jenkins](https://jenkins.io/)
