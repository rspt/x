# x - code - continuous integration - docker

> Docker is the world’s leading software containerization platform.

## Container management

### Rancher

#### Adding a custom private library to catalog

1.  exec into your rancher server container (`docker exec -i -t <container-id> /bin/sh`)
2.  `ssh-keygen`
3.  provide id_rsa.pub to your git repo
4.  `cd /var/lib/cattle/DATA`
5.  `mkdir <catalog-alias>`
6.  `git clone <your repo> <catalog-alias>`
7.  add the git repo to Rancher via the webUI using the same catalog alias and git URI you used above.

There is an open issue for this feature: [https://github.com/rancher/rancher/issues/3248](https://github.com/rancher/rancher/issues/3248)

## Resources

*   [Awesome Docker](https://github.com/veggiemonk/awesome-docker)

*   Docker Management
    *   [Rancher](http://rancher.com/)
    *   [Shipyard](http://shipyard-project.com/)
