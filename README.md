Django Drip for Django 2 
====================

Next, you'll want to add `drip` to your `INSTALLED_APPS` in settings.py.

```python
INSTALLED_APPS = (
    'django.contrib.contenttypes',
    'django.contrib.comments',
    'django.contrib.sessions',
    'django.contrib.sites',
    'django.contrib.admin',

    # Your favorite apps

    'drip',
)
```

Don't forget to add `DRIP_FROM_EMAIL` to settings.py, or else we will fall back to `EMAIL_HOST_USER`.


```
python manage.py migrate drip
```
-------------------

![what the admin looks like](https://raw.github.com/zapier/django-drip/master/docs/images/drip-example.png)
![what the admin looks like for the timeline](https://raw.github.com/zapier/django-drip/master/docs/images/view-timeline.png)
