# Starting local development

## Running Docker
`docker-compose up`

## Symfony installation
`symfony check:requirements`

`docker-compose exec php-fpm bash`

After that, inside php-fpm container:

`composer create-project symfony/skeleton app`

`mv /symfony/app/* /symfony`

`mv /symfony/app/.* /symfony`

`rm -Rf app`