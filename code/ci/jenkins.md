# x - code - continuous integration - jenkins

> The leading open source automation server, Jenkins provides hundreds of
> plugins to support building, deploying and automating any project.

## Recipe

### Connect to GitHub

The idea is to use [deploy keys](https://developer.github.com/guides/managing-deploy-keys/#deploy-keys).

1.  [Run the ssh-keygen procedure](https://help.github.com/articles/generating-an-ssh-key/)
    on the Jenkins server

2.  In the top right corner of any GitHub page, click your profile photo.

3.  On your profile page, click the **Repositories** tab, then click the name of
    your repository.

4.  In your repository's right sidebar, click **Settings**.

5.  In the sidebar, click **Deploy Keys**.

6.  Click **Add deploy key**. Paste your public key in and submit.

:warning: Make sure to have the [Git](https://wiki.jenkins-ci.org/display/JENKINS/Git+Plugin)
and the [GitHub](https://wiki.jenkins-ci.org/display/JENKINS/Github+Plugin)
plugin installed!

## Deploy with Docker

With Docker ([docker image](https://hub.docker.com/_/jenkins/)):

```sh
docker run -d --name jenkins -p 8080:8080 -p 50000:50000 -v /your/home:/var/jenkins_home jenkins
```

:warning: It's strongly recommended to mount the directory `/var/jenkins_home`
on a volume as it is the config directory where everything is saved.

## Resources

*   [Jenkins](https://jenkins.io/)
