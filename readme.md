# Starting local development

## Running Docker
`docker-compose up`

## Symfony installation

`docker-compose exec php-fpm bash`

After that, inside php-fpm container run:

`symfony check:requirements`

`composer create-project symfony/skeleton app`

`mv /symfony/app/* /symfony`

`mv /symfony/app/.* /symfony`

`rm -Rf app`

Symfony app will be mounted from php-fpm container at host `app` directory.
