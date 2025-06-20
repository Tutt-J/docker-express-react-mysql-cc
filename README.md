# Launch the project in development:
`docker compose up -d`\
*You can add the flag --build if you need to rebuild the images.*

# Launch the project in production:
`docker-compose -f docker-compose.yml -f docker-compose.prod.yml up -d`\
*You can add the flag --build if you need to rebuild the images.*

# Environment
## MYSQL
Create a mysql.env at the root with:
```
MYSQL_ROOT_PASSWORD=
MYSQL_DATABASE=
```
## BACK
Create a .env on "back" folder with:
```
NODE_ENV=
ORIGIN=
PORT=
DB_host=
DB_username=
DB_password=
DB_database=
DB_dialect=
DB_port=
```

## FRONT
Create a .env file on "front" folder with:
```
VITE_API_URL=
NODE_ENV=
```
