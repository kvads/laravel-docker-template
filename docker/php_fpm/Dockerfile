FROM php:8.3-fpm

RUN --mount=type=cache,target=/var/cache/apt \
    apt-get update && apt-get upgrade && apt-get install -y \
