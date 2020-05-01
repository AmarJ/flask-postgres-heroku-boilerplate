##Steps##

1. Add your HEROKU_API_KEY to your github repo keys (for deploy actions)
2. Create a heroku app and add DATABASE_URL=[YOUR_HEROKU_PSQL_DB] and FLASK_ENV=production to Config Vars 
3. Run python manage.py db init, migrate and upgrade... before running
