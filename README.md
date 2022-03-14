# api_yamdb
api_yamdb

### RestAPI based resource where you can score Titles

### Features:

- users can create account (Anonym, Regular user, Moderator, admin)
- users can create and edit reviews and evaluate Titles
- based on user's scores sustem calculate rating of the Title
- users must work with App only via RestAPI


### Authors

Evgeny Asminin, Panchanko Alexey, Akexander Shornikov

### Installation Notes:

Clone repo and change directory:

```
git clone https://github.com/plngu/api_yamdb.git
```

```
cd api_yamdb
```

Create and activate venv:

```
python3 -m venv env
```

```
source env/bin/activate
```

Upgrade pip if necessary:

```
python3 -m pip install --upgrade pip
```

Deploy venv according to requirements.txt:

```
pip install -r requirements.txt
```

Deploy migrations:

```
python3 manage.py migrate
```

Launch project server:

```
python3 manage.py runserver
```

API documentation available in [ReDoc](https://redocly.github.io/redoc/#operation/addPet) on endpoint:

```
http://127.0.0.1:8000/redoc/
```
