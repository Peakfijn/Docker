# Laravel Test

A simple image which is capable of running tests for Laravel.
This is mostly used for running [_CI_ testing](https://docs.peakfijn.nl/docker/pipelines.html).

## Features

- Runs **PHP 7.2** using `php:7.2`
- Imports **Composer 1.6** using `composer:1.6`
- Installs **Node 8 LTS** using `https://deb.nodesource.com/setup_8.x`
- Supports **SQLite 3** using `apt-get install libsqlite3-dev`
