# nginx with brotli

```shell
export ALPINE_VERSION=3.14.0
export NGINX_VERSION=1.20.1
export PKG_RELEASE=1
export NJS_VERSION=0.6.1

docker build -t nginx-brotli --build-arg ALPINE_VERSION=$ALPINE_VERSION --build-arg NGINX_VERSION=$NGINX_VERSION --build-arg PKG_RELEASE=${PKG_RELEASE} --build-arg NJS_VERSION=${NJS_VERSION} -f Dockerfile .
```