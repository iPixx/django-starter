# django-starter

A django project to use as a starter for other projects ready to be uploaded to a VPS.

## Features

- The Django project files are under the `project` folder
- The main app is under `main` folder and it will only print `Hello, World!` when accessed
- The project is configured to use `postgresql` as the database
- The environment variables are loaded from a `.env` file
- The User object is customized at the beginning of the project

> For more information on customizing the User object, refer to the [Django documentation](https://docs.djangoproject.com/en/5.1/topics/auth/customizing/). At the same link, it is well explained how to correctly reference the custom User model in the project.

## Docker

- The starter project is dockerized
- The project is configured to use a dockerized `postgresql` as the database
- A reverse proxy is used to serve the project using `traefik`
