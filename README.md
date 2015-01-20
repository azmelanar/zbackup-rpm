zbackup-rpm
===========

Download source code

```sh
cd /root/rpmbuild/SOURCES
VERSION='1.4.1' ; wget -c --no-check-certificate https://github.com/zbackup/zbackup/archive/${VERSION}.tar.gz -O ${VERSION}.tar.gz
```

Install dependencies

```sh
yum install -y cmake openssl-devel protobuf-devel zlib-devel xz-devel
```

Build package.
