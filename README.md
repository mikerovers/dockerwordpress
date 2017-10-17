# dockerwordpress
Quick docker container for Wordpress plugin development.

## Installation
Clone the repository.
```bash
git clone git@github.com:mikerovers/dockerwordpress.git
```

## Usage
To start the containers, run:
```bash
docker-compose up -d
```

When started, Docker will make a wordpress/wp-content folder. In this folder, you can develop your plugins and themes.

You can use docker exec to get an shell in your Docker container:
```bash
docker exec -ti dockerwordpress_wordpress_1 /bin/bash
```

## Services
Wordpress is available via port `80`.

Mysql is available via port `3306`.

PHPMyadmin is available via port `8080`.
