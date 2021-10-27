## Django Password Generator

generate random strings with Django, Python and Boostrap

### Run with Docker (Recommended)

execute these commands to run with docker on any platform:

```bash
docker build --tag python-django .
docker run --publish 8000:8000 --name python-django python-django
```

### Installation

```
git clone https://github.com/luisforni/django.git
cd django-password-generator
pip install -r requeriments.txt
python manage.py runserver
```

now you can visit <a href="http://localhost:8000" target="_blank" rel="noreferrer">http://localhost:8000</a>
