[![Quarto Publish](https://github.com/vanHeemstraSystems/build-management/actions/workflows/publish.yml/badge.svg)](https://github.com/vanHeemstraSystems/build-management/actions/workflows/publish.yml)

build-management
# Permission Management

Can be read as "Build Management" at https://app.gitbook.com/s/Rs3XPuVclvoj92Exb9AA/

Can be browsed as "Build Management" at https://vanheemstrasystems.github.io/build-management/

Documentation of this repository is automatically done with Quarto using GitHub Actions as described at https://github.com/vanHeemstraSystems/quarto-to-github-pages/blob/main/300/300/README.md

Based on "How to Run PostgreSQL and pgAdmin Using Docker" at https://towardsdatascience.com/how-to-run-postgresql-and-pgadmin-using-docker-3a6a8ae918b5

Based on "Basel" at https://basel.build

Create yarn.lock file as follows:

```
$ cd containers/app/main
$ yarn install
```

Run as follows:

```
$ cd containers/app
$ docker-compose --file docker-compose.dev.yml --project-name build-management-dev up --build -d
```
