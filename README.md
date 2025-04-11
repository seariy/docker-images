# docker images
从 docker hub 上拉取常用的镜像上传到 github 的 ghcr.io。

- 把 `151.101.184.133 pkg-containers.githubusercontent.com` 加入 `hosts` 文件，可能拉取速度会变快。
- 如果想要其他镜像请提 issue，或者直接 fork 本 repo，启用 actions，然后在 hub 目录新建文件，内容为镜像的名称及 tag，请参考 [hub/nginx](https://github.com/feng2208/docker-images/blob/main/hub/nginx)。

镜像列表：
- mariadb
```nginx
docker pull mariadb:10.11.11
```

- mattermost/mattermost-team-edition
```nginx
docker pull mattermost/mattermost-team-edition:10.6.1
```

- mysql
```nginx
docker pull mysql:8.4.3
```

- nextcloud
```nginx
docker pull nextcloud:31.0.2
```

- nginx
```nginx
docker pull nginx:1.26.2
```

- postgres
```nginx
docker pull postgres:17.4
```

- python
```nginx
docker pull python:3.12.8
```

- redis
```nginx
docker pull redis:7.4.2
```

- ubuntu
```nginx
docker pull ubuntu:24.04
```

