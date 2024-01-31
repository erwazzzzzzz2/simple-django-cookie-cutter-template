# simple-django-cookie-cutter-template

## Pre-requisties:

1. Docker 
2. VSCode
3. VSCode Dev Containers extension
4. VSCode Docker extension

## How to run the application

Its assumed VSCod is the IDE

Make  a directory to conatin you project and cd into it.
Create a virtual environment and install cookiecutter
Run the command
```cookiecutter https://github.com/erwazzzzzzz2/simple-django-cookie-cutter-template.git```
Choose values for the prompts or accept the defaults

A new project folder should be created and inside this a DevContainer Django/Postgres project.
navigate intothe project
Select the VSCode command pallete and select Dev Containers: Rebuild Container 
You containerized environment should run
Run the command below to start the application and check the database is created.
``` python manage.py run_app```

See the repo https://github.com/erwazzzzzzz2/django-devcontainers  for details of the devcontainer set up, issues and so on.