# instaparser
Instagram parser backend to get common followers of 2 users using database of
Instagram accounts.
## Usage:
1. Change username and password in [init file of the app](/flaskapp/app/__init__.py).
    1. You may want to change CORS origins to restrict it to desired origins only.
1. Add html files to [src folder in nginx folder](/nginx).
1. Start `docker-compose`.
1. Add your Instagram accounts to use for parsing through API endpoints or through your front-end.
