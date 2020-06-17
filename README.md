# How to use:

-   create `app` directory
-   clone your PHP (Laravel) app to `app` directory
-   copy `.dockerignore` to `app` directory (it can be deleted after build)
    -   MySQL host: `db`
    -   MySQL port: `3306`
    -   MySQL username: `root`
    -   MySQL password: ``
    -   default database: `laravel`
-   `docker-compose build` to build docker containers
-   `docker-compose up -d` to run docker containers
-   `docker exec -it laravel-app zsh` to go into shell
-   `docker-compose down` to stop all containers
