# recipe-app-api
Recipe API project.

## docker commands
- `docker compose build`
- `docker compose up`
- `docker compose down`
- `docker ps`

### run tests
- `docker compose run --rm app sh -c "python manage.py test"`

### create new app within
- `docker compose run --rm app sh -c "python manage.py startapp recipe"`

### run migration scripts
- `docker compose run --rm app sh -c "python manage.py makemigrations"`