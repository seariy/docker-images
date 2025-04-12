# docker images
从 docker hub 上拉取常用的镜像上传到 github 的 ghcr.io。

- 把 `151.101.184.133 pkg-containers.githubusercontent.com` 加入 `hosts` 文件，可能拉取速度会变快。
- 如果想要其他镜像请提 issue，或者直接 fork 本 repo，启用 actions，然后在 hub 目录新建文件，内容为镜像的名称及 tag，请参考 [hub/nginx](https://github.com/feng2208/docker-images/blob/main/hub/nginx)。

镜像列表：
- mariadb
```ruby
docker pull ghcr.io/feng2208/mariadb:11.4.5
docker pull registry.gitlab.com/feng2208/a/mariadb:11.4.5
```

- mattermost/mattermost-team-edition
```ruby
ghcr.io/feng2208/mattermost/mattermost-team-edition:10.6.1
```

- mysql
```ruby
ghcr.io/feng2208/mysql:8.4.3
```

- nextcloud
```ruby
ghcr.io/feng2208/nextcloud:31.0.2
```

- nginx
```ruby
ghcr.io/feng2208/nginx:1.26.2
```

- php
```ruby
ghcr.io/feng2208/php:8.4.5-fpm
```

- postgres
```ruby
ghcr.io/feng2208/postgres:17.4
```

- python
```ruby
ghcr.io/feng2208/python:3.12.8
```

- redis
```ruby
ghcr.io/feng2208/redis:7.4.2
```

- ubuntu
```ruby
ghcr.io/feng2208/ubuntu:24.04
```

