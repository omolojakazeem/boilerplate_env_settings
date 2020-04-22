"# boilerplate_env_settings" 

A. i. run pip install django-debug-toolbar
  ii. run pip install django-heroku
  
B. Create static, media dir from same dir as your project


To use in development:

1. Check database settings in settings/dev.py, Default is sqlite3
2. Confirm the manage.py DJANGO_SETTINGS_MODULE'is pointing to 'psm_website.settings.dev'


To use in Production:

1. Check database settings in settings/prod.py, Default is postgresql
2. Confirm the manage.py DJANGO_SETTINGS_MODULE'is pointing to 'psm_website.settings.prod'

