Usage
===============

```bash
docker build centos-base https://raw.github.com/ttakezawa/Dockerfiles/master/centos-base/Dockerfile
docker run -i -t -d -p 10022:22 centos-base /sbin/init

ssh -p 10022 root@localhost # PASSWORD: root
```
