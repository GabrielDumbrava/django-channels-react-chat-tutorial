Original tutorial:
https://blog.logrocket.com/build-chat-application-react-django-channels/

As a change from the tutorial I've added `daphne` as the `asgi` server, and added `daphne` as the first app in the 
`INSTALLED_APPS` list:

```python
INSTALLED_APPS = [
    "daphne",
    "django.contrib.admin",
    "django.contrib.auth",
    "django.contrib.contenttypes",
    "django.contrib.sessions",
    "django.contrib.messages",
    "django.contrib.staticfiles",
    "app",
]
```
