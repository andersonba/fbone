fbone
=====

A simple Flask skeleton

## Usage

Start server: 
`$ fab run` or `$ fab grun` for gunicorn server

Interactive shell: `$ fab shell`

Unit testing: `$ fab tests`

## Structure

```
.
├── app
│   ├── __init__.py
│   ├── assets.py
│   ├── config.py
│   ├── constants.py
│   ├── module
│   │   ├── business.py
│   │   ├── constants.py
│   │   ├── decorators.py
│   │   ├── forms.py
│   │   ├── models.py
│   │   └── views.py
│   ├── static
│   │   ├── css
│   │   │   └── main.less
│   │   ├── favicon.ico
│   │   ├── gen
│   │   ├── img
│   │   ├── js
│   │   │   ├── main.js
│   │   │   └── vendor
│   │   └── robots.txt
│   ├── templates
│   │   ├── errors
│   │   │   ├── 403.html
│   │   │   ├── 404.html
│   │   │   └── 500.html
│   │   └── module
│   │       └── index.html
│   └── tests
├── fabfile.py
├── requirements.txt
├── run.py
├── shell.py
└── tests.py
```
