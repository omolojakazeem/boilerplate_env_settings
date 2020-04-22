"# boilerplate_env_settings" 

A. i. run pip install django-debug-toolbar
  ii. run pip install django-heroku
  
B. Create static, ststicfiles and media dir from same dir as your project


To use in development:

1. Check database settings in settings/dev.py, Default is sqlite3
2. Confirm in settings/__init__.py change the env_name variable to dev 

  env_name = os.getenv('ENV_NAME', 'prod') -> env_name = os.getenv('ENV_NAME', 'dev')

To use in Production:

1. Check database settings in settings/prod.py, Default is postgresql
2. Confirm in settings/__init__.py change the env_name variable to prod

  env_name = os.getenv('ENV_NAME', 'dev') -> env_name = os.getenv('ENV_NAME', 'prod')

