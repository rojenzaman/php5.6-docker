## php5.6-docker:no-mysqli image for pre-installed Wordpress which does not support mysqli

Running WordPress on PHP-5.6 with MySQL-5.7 on Docker container with mysql extension instead of mysqli.

## Motivation

- WordPress plugins/themes developers often need to make sure their plugins/themes are also compatible with php5.6
- Official WordPress docker image support start from php7.3
- Old Wordpress themes does not support mysqli extension so in this image mysql extension included.

## Running container

pull:

```bash
docker pull rojen/php5.6-docker:no-mysqli
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
