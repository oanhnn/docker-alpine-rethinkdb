# oanhnn/docker-alpine-rethinkdb

[![Build Status](https://travis-ci.org/oanhnn/docker-alpine-rethinkdb.svg?branch=master)](https://travis-ci.org/oanhnn/docker-alpine-rethinkdb)

Repository of `oanhnn/alpine-rethinkdb` Docker image.   
Alpine based RethinkDB image.

All installed packages (`/etc/manifest.txt`):

```text
fetch http://dl cdn.alpinelinux.org/alpine/v3.7/main/x86_64/APKINDEX.tar.gz
fetch http://dl cdn.alpinelinux.org/alpine/v3.7/community/x86_64/APKINDEX.tar.gz
musl 1.1.18
busybox 1.27.2
alpine-baselayout 3.0.5
alpine-keys 2.1
libressl2.6-libcrypto 2.6.3
libressl2.6-libssl 2.6.3
zlib 1.2.11
apk-tools 2.8.2
scanelf 1.2.2
musl-utils 1.1.18
libc-utils 0.7.1
ca-certificates 20171114
libssh2 1.8.0
libcurl 7.58.0
libexecinfo 1.1
libgcc 6.4.0
libstdc++ 6.4.0
protobuf 3.4.1
rethinkdb 2.3.6
su-exec 0.2
```

## Features

- [x] Base from `alpine:latest` image
- [x] Install rethinkdb via package manager (`apk`)

## Requirement
- Docker Engine 1.13+

## Usage

```bash
$ docker run -d oanhnn/rethinkdb
```

## Contributing

All code contributions must go through a pull request and approved by a core developer before being merged. 
This is to ensure proper review of all the code.

Fork the project, create a feature branch, and send a pull request.

If you would like to help take a look at the [list of issues](https://github.com/oanhnn/docker-alpine-rethinkdb/issues).

## License

This project is released under the MIT License.   
Copyright © 2018 [Oanh Nguyen](https://github.com/oanhnn)   
Please see [License File](https://github.com/oanhnn/docker-alpine-rethinkdb/blob/master/LICENSE) for more information.
