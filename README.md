[![](https://img.shields.io/pypi/pyversions/django-replace.svg?longCache=True)](https://pypi.org/pypi/django-replace/)
[![](https://img.shields.io/pypi/v/django-replace.svg?maxAge=3600)](https://pypi.org/pypi/django-replace/)
[![Travis](https://api.travis-ci.org/looking-for-a-job/django-replace.py.svg?branch=master)](https://travis-ci.org/looking-for-a-job/django-replace.py/)

#### Install
```bash
$ [sudo] pip install django-replace
```

#### Examples
`settings.py`
```python
>>> INSTALLED_APPS = [
    'django_replace'
    ...
]
```

`template.html`
```html
{% load replace %}

{{ value|replace:",search,replace" }}
```

<p align="center"><a href="https://pypi.org/project/readme-md/">readme-md</a> - README.md generator</p>