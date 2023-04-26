### Project structure
```
aggregproject1    (project root)
├── Dockerfile
├── README.md
├── app
│   ├── app
│   │   ├── __init__.py
│   │   ├── asgi.py  [project instantiation]
│   │   ├── settings.py
│   │   ├── urls.py [urls configurations]
│   │   └── wsgi.py  [project instantiation]
│   ├── core
│   │   ├── __init__.py
│   │   ├── admin.py [support admin gui]
│   │   ├── apps.py []
│   │   ├── management
│   │   │   ├── __init__.py
│   │   │   └── commands
│   │   ├── migrations [track all db changes]
│   │   │   └── __init__.py
│   │   ├── models.py [db]
│   │   └── tests  [unit testing]
│   │       ├── __init__.py
│   │       └── test_commands.py
│   └── manage.py
├── docker-compose.yml
├── requirements.dev.txt
├── requirements.txt

```


# STEPS

1. Go and create account on hub.docker.com
2. Complete docker installation 
3. Login to Docker Hub and click on Account Setting → Security → New Access
Token
4. Copy and store the access token at some safe place.
5. Go to https://github.com/prashant5nov/project1/ and fork project into your account
6. With above step project repository will reflect into your account
7. `git clone <https-url-copied-from-git-repo>`