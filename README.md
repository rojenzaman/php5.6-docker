## php5.6-docker image for pre-installed Wordpress

Running WordPress on PHP-5.6 with MySQL-5.7 on Docker container

## Motivation

- WordPress plugins/themes developers often need to make sure their plugins/themes are also compatible with php5.6
- Official WordPress docker image support start from php7.3

## Running container

pull:

```bash
docker pull rojen/php5.6-docker
```

run:

```
docker-compose up -d
```

## Access the site:

http://localhost:8080/


## Reference

- https://github.com/docker-library/wordpress/blob/394c79eafd5b345514f87cec590577e641c030ef/latest/php7.4/apache/Dockerfile
- https://github.com/khaledsaikat/wordpress-php56-docker
