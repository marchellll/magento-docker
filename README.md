# Magento 2.3.4 Docker


## To build

```
cd php
docker build --platform linux/amd64 --tag marchellll/magento-php:7.3-fpm-0 .
```

# To publish

```
# `docker login` first

docker push marchellll/magento-php:7.3-fpm-0
```
