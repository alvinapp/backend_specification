# Alvin Enterprice Technical Specifications
# Version: 1.0

# Table of Contents
1. [Introduction](#introduction)
2. [Technology](#technology)
3. [Database](#database)
4. [Installation](#installation)

# Introduction
This is a technical documentation for Alvin Enterprise. This documentation will cover the technology used, the requirements, and the database.

# Technology

## Backend
- Python 3.9
- Poetry
- Flask

### Packages used

Some of the packages used include;

|Package | Version | Description |
| :------------ |:---------------:| -----:|
|alembic               | 1.8.1  |    A database migration tool for SQLAlchemy. |
|amqp                  | 5.1.1  |    Low-level AMQP client for Python (fork of amqplib). |
|aniso8601             | 9.0.1  |    A library for parsing ISO 8601 strings. |
|appnope               | 0.1.3  |    Disable App Nap on macOS >= 10.9 |
|async-timeout         | 4.0.2  |    Timeout context manager for asyncio programs |
|attrs                 | 22.1.0 |    Classes Without Boilerplate |
|backcall              | 0.2.0  |    Specifications for callback functions passed in to an API |
|bandit                | 1.7.4  |    Security oriented static analyser for python code. |
|billiard              | 3.6.4.0 |   Python multiprocessing fork with improvements and bugfixes |
|black                 | 22.10.0 |   The uncompromising code formatter. |
|blinker               | 1.5    |   Fast, simple object-to-object and broadcast signaling |
|blis                  | 0.7.9  |   The Blis BLAS-like linear algebra library, as a self-contained C-extension. |
|cachecontrol          | 0.12.12 |   httplib2 caching for requests |
|cachelib              | 0.9.0  |   A collection of cache libraries in the same API interface. |
|cachetools            | 5.2.0  |   Extensible memoizing collections and decorators |
|catalogue             | 2.0.8  |   Super lightweight function registries for your library |
|catboost              | 1.1.1  |   Catboost Python Package |
|celery                | 5.2.7  |   Distributed Task Queue. |
|celery-redbeat        | 2.0.0  |   A Celery Beat Scheduler using Redis for persistent storage |
|certifi               | 2022.9.24 | Python package for providing Mozilla's CA Bundle. |
|charset-normalizer    | 2.1.1  |   The Real First Universal Charset Detector. Open, modern and actively maintained alternative to Chardet. |
|click                 | 8.1.3  |   Composable command line interface toolkit |
|click-didyoumean      | 0.3.0  |   Enables git-like *did-you-mean* feature in click |
|click-plugins         | 1.1.1  |   An extension module for click to enable registering CLI commands via setuptools entry-points. |
|click-repl            | 0.2.0  |   REPL plugin for Click |
|colorama              | 0.4.6  |   Cross-platform colored terminal text. |
|confection            | 0.0.3  |   The sweetest config system for Python |
|contourpy             | 1.0.6  |   Python library for calculating contours of 2D quadrilateral grids |
|cycler                | 0.11.0 |   Composable style cycles |
|cymem                 | 2.0.7  |   Manage calls to calloc/free through Cython |
|decorator             | 5.1.1  |   Decorators for Humans |
|deprecated            | 1.2.13 |   Python @deprecated decorator to deprecate old python classes, functions or methods. |
|distlib               | 0.3.6  |   Distribution utilities |
|et-xmlfile            | 1.1.0  |   An implementation of lxml.xmlfile for the standard library |
|exceptiongroup        | 1.0.1  |   Backport of PEP 654 (exception groups) |
|factory-boy           | 3.2.1  |   A versatile test fixtures replacement based on thoughtbot's factory_bot for Ruby. |
|faker                 | 8.16.0 |   Faker is a Python package that generates fake data for you. |
|filelock              | 3.8.0  |   A platform independent file lock. |
|firebase-admin        | 5.4.0  |   Firebase Admin Python SDK |
|flask                 | 2.1.3  |   A simple framework for building complex web applications. |
|flask-caching         | 2.0.1  |   Adds caching support to Flask applications. |
|flask-cors            | 3.0.10 |   A Flask extension adding a decorator to enable Cross Origin Resource Sharing (CORS) |
|flask-httpauth        | 4.7.0  |   HTTP authentication for Flask routes |
|flask-mail            | 0.9.1  |   Flask extension for sending email |
|flask-migrate         | 2.7.0  |   SQLAlchemy database migrations for Flask applications using Alembic |
|flask-restx           | 0.5.1  |   Fully featured framework for fast, easy and documented API development with Flask |
|flask-sqlalchemy      | 2.5.1  |   Adds SQLAlchemy support to your Flask application. |
|flask-testing         | 0.8.1  |   Unit testing for Flask |
|fonttools             | 4.38.0 |   Tools to manipulate font files |
|gensim                | 4.2.0  |   Python framework for fast Vector Space Modelling |
|gitdb                 | 4.0.9  |   Git Object Database |
|gitpython             | 3.1.29 |   GitPython is a python library used to interact with Git repositories |
|google-api-core       | 2.10.2 |   Google API client core library |
|google-api-python-client | 2.65.0 |   Google API Client Library for Python |
|google-auth           | 2.14.1 |   Google Authentication Library |
|google-auth-httplib2  | 0.1.0  |   Google Authentication Library: httplib2 transport |
|google-cloud-core     | 2.3.2  |   Google Cloud API client core library |
|google-cloud-firestore | 2.7.2  |   Google Cloud Firestore API client library |
|google-cloud-storage  | 2.6.0  |   Google Cloud Storage API client library |
|google-crc32c         | 1.5.0  |   A python wrapper of the C library 'Google CRC32C' |
|google-resumable-media | 2.4.0  |   Utilities for Google Media Downloads and Resumable Uploads |
|googleapis-common-protos | 1.56.4 |   Common protobufs used in Google APIs |
|graphviz              | 0.20.1 |   Simple Python interface for Graphviz |
|greenlet              | 2.0.1  |   Lightweight in-process concurrent programming |
|grpcio                | 1.50.0 |   HTTP/2-based RPC framework |
|grpcio-status         | 1.50.0 |   Status proto mapping for gRPC |
|gunicorn              | 20.1.0 |   WSGI HTTP Server for UNIX |
|httplib2              | 0.21.0 |   A comprehensive HTTP client library. |
|idna                  | 3.4    |   Internationalized Domain Names in Applications (IDNA) |
|importlib-metadata    | 5.0.0  |   Read metadata from Python packages |
|importlib-resources   | 5.10.0 |   Read resources from Python packages |
|iniconfig             | 1.1.1  |   iniconfig: brain-dead simple config-ini parsing |
|ipython               | 7.34.0 |   IPython: Productive Interactive Computing |
|isort                 | 5.10.0 |   A Python utility / library to sort imports alphabetically, and automatically separated into sections and by type. |
|itsdangerous          | 2.0.1  |   Various helpers to pass trusted data to untrusted environments and back. |
|jedi                  | 0.18.1 |   An autocompletion tool for Python that can be used for text editors. |
|jinja2                | 3.0.3  |   A very fast and expressive template engine. |
|joblib                | 1.2.0  |   Lightweight pipelining: using Python functions as pipeline jobs |
|jsonschema            | 4.17.0 |   An implementation of JSON Schema for Python |
|kiwisolver            | 1.4.4  |   A fast implementation of the Cassowary constraint solver |
|kombu                 | 5.2.4  |   Messaging library for Python. |
|langcodes             | 3.3.0  |   Tools for labeling human languages with IETF language tags |
|mako                  | 1.2.3  |   A super-fast templating language that borrows the best ideas from the existing templating languages. |
|markupsafe            | 2.1.1  |   Safely add untrusted strings to HTML/XML markup. |
|matplotlib            | 3.5.0  |   Python plotting package |
|matplotlib-inline     | 0.1.3  |   IPython magic to display matplotlib figures inline in the notebook |
|msgpack               | 1.0.4  |   MessagePack serializer |
|murmurhash            | 1.0.9  |   Cython bindings for MurmurHash |
|mypy-extensions       | 0.4.3  |   Experimental type system extensions for programs checked with the mypy typechecker. |
|numpy                 | 1.23.4 |   NumPy is the fundamental package for array computing with Python. |
|openpyxl              | 3.0.10 |   A Python library to read/write Excel 2010 xlsx/xlsm files |
|packaging             | 21.3   |   Core utilities for Python packages |
|pandas                | 1.5.1  |   Powerful data structures for data analysis, time series, and statistics |
|parso                 | 0.8.3  |   A Python Parser |
|passlib               | 1.7.4  |   comprehensive password hashing framework supporting over 30 schemes |
|pathspec              | 0.10.1 |   Utility library for gitignore style pattern matching of file paths. |
|pathy                 | 0.6.2  |   pathlib.Path subclasses for local and cloud bucket storage |
|pbr                   | 5.11.0 |   Python Build Reasonableness |
|pexpect               | 4.8.0  |   Pexpect allows easy control of interactive console applications. |
|pickleshare           | 0.7.5  |   Tiny 'shelve'-like database with concurrency support |
|pillow                | 9.3.0  |   Python Imaging Library (Fork) |
|pkgutil-resolve-name  | 1.3.10 |   Resolve a name to an object.|
|platformdirs          | 2.5.3  |   A small Python package for determining appropriate platform-specific dirs, e.g. a "user data dir". |
|plotly                | 5.11.0 |   An open-source, interactive data visualization library for Python |
|pluggy                | 1.0.0  |   plugin and hook calling mechanisms for python |
|preshed               | 3.0.8  |   Cython hash table that trusts the keys are pre-hashed |
|prompt-toolkit        | 3.0.32 |   Library for building powerful interactive command lines in Python |
|proto-plus            | 1.22.1 |   Beautiful, Pythonic protocol buffers. |
|protobuf              | 4.21.9 |   |
|psycopg2-binary       | 2.9.5  |   psycopg2 - Python-PostgreSQL Database Adapter | 
|ptyprocess            | 0.7.0  |   Run a subprocess in a pseudo terminal |
|py                    | 1.11.0 |   library with cross-python path, ini-parsing, io, code, log facilities |
|pyasn1                | 0.4.8  |   ASN.1 library for Python |
|pyasn1-modules        | 0.2.8  |   Collection of protocols modules written on top of pyasn1 |
|pydantic              | 1.8.2  |   Data validation and settings management using Python type hinting |
|pyflakes              | 2.5.0  |   passive checker of Python programs. |
|pygments              | 2.13.0 |   Pygments is a syntax highlighting package written in Python. |
|pyjwt                 | 2.6.0  |   JSON Web Token implementation in Python |
|pytest                | 7.2.0  |   pytest: simple powerful testing with Python |
|pytest-celery         | 0.0.0  |   pytest-celery a shim pytest plugin to enable celery.contrib.pytest |
|python-dateutil       | 2.8.2  |   Extensions to the standard Python datetime module |
|pytz                  | 2022.6 |   World timezone definitions, modern and historical |
|pyyaml                | 6.0    |   YAML parser and emitter for Python |
|redis                 | 4.3.4  |   Python client for Redis database and key-value store |
|requests              | 2.28.1 |   Python HTTP for Humans. |
|sentry-sdk            | 1.11.0 |   Python client for Sentry (https://sentry.io) |
|sqlalchemy            | 1.4.43 |   Database Abstraction Library |
|sqlalchemy-utils      | 0.38.3 |   Various utility functions for SQL |
|tox                   | 3.27.0 |   tox is a generic virtualenv management and test command line tool. |
|virtualenv            | 20.16.6|   Virtual Python Environment builder. |
|werkzeug              | 2.1.2  |   The comprehensive WSGI web application library. |
|wrapt                 | 1.14.1 |   Module for decorators, wrappers and monkey patching. |
|zipp                  | 3.10.0 |   Backport of pathlib-compatible object wrapper for zip files. |

### Directory structure


```
alvin_enterprise
|-.DS_Store
|-README.md
|-backend
| |-.DS_Store
| |-.dockerignore
| |-.pytest_cache
| | |-CACHEDIR.TAG
| | |-README.md
| | |-v
| | | |-cache
| | | | |-lastfailed
| | | | |-nodeids
| | | | |-stepwise
| |-.tox
| | |-.package.lock
| | |-dist
| | | |-backend-0.1.0.tar.gz
| |-Dockerfile
| |-README.md
| |-Vagrantfile
| |-api_documentation
| | |-.swagger-codegen
| | | |-VERSION
| | |-.swagger-codegen-ignore
| | |-.vscode
| | | |-settings.json
| | |-README.md
| | |-documentation.yaml
| | |-index.html
| | |-theme.json
| |-backend
| | |-__init__.py
| | |-__pycache__
| | | |-__init__.cpython-39.pyc
| | | |-app.cpython-39.pyc
| | | |-auth.cpython-39.pyc
| | | |-cache.cpython-39.pyc
| | | |-celery.cpython-39.pyc
| | | |-config.cpython-39.pyc
| | | |-extended_json_encoder.cpython-39.pyc
| | | |-extensions.cpython-39.pyc
| | | |-mail.cpython-39.pyc
| | | |-utils.cpython-39.pyc
| | | |-views.cpython-39.pyc
| | | |-wsgi.cpython-39.pyc
| | |-app.py
| | |-auth.py
| | |-cache.py
| | |-celery.py
| | |-config.py
| | |-crontab
| | | |-__init__.py
| | | |-__pycache__
| | | | |-__init__.cpython-39.pyc
| | | | |-cron.cpython-39.pyc
| | | |-cron.py
| | |-csv_endpoint
| | | |-__pycache__
| | | | |-csv_data.cpython-39.pyc
| | | |-csv_data.py
| | | |-demo_data.csv
| | | |-new_data.csv
| | |-extended_json_encoder.py
| | |-extensions.py
| | |-init_scripts
| | | |-__init__.py
| | | |-__pycache__
| | | | |-__init__.cpython-39.pyc
| | | |-categories
| | | | |-__init__.py
| | | | |-__pycache__
| | | | | |-__init__.cpython-39.pyc
| | | | | |-init_categories.cpython-39.pyc
| | | | |-init_categories.py
| | | |-dummy
| | | | |-__init__.py
| | | | |-__pycache__
| | | | | |-__init__.cpython-39.pyc
| | | | | |-user.cpython-39.pyc
| | | | |-user.py
| | | |-terms
| | | | |-__init__.py
| | | | |-__pycache__
| | | | | |-__init__.cpython-39.pyc
| | | | | |-terms.cpython-39.pyc
| | | | |-terms.html
| | | | |-terms.py
| | |-mail.py
| | |-migration_scripts
| | | |-__init__.py
| | | |-__pycache__
| | | | |-__init__.cpython-39.pyc
| | | |-anonymize.py
| | | |-goals
| | | | |-__init__.py
| | | | |-reset_active_ledger.py
| | | |-micros
| | | | |-__init__.py
| | | | |-update_micro_settings.py
| | | |-transactions
| | | | |-__init__.py
| | | | |-__pycache__
| | | | | |-__init__.cpython-39.pyc
| | | | | |-migrate_organization.cpython-39.pyc
| | | | |-migrate_assigned_at.py
| | | | |-migrate_categorize_past_transactions.py
| | | | |-migrate_micro_to_transaction_date.py
| | | | |-migrate_organization.py
| | | |-users
| | | | |-__init__.py
| | | | |-data_migrate.py
| | |-models
| | | |-__init__.py
| | | |-__pycache__
| | | | |-__init__.cpython-39.pyc
| | | | |-accounts.cpython-39.pyc
| | | | |-all.cpython-39.pyc
| | | | |-api_calls.cpython-39.pyc
| | | | |-base.cpython-39.pyc
| | | | |-categories.cpython-39.pyc
| | | | |-categorization.cpython-39.pyc
| | | | |-categorization_recommendations.cpython-39.pyc
| | | | |-contribution_settings.cpython-39.pyc
| | | | |-external_linked_accounts.cpython-39.pyc
| | | | |-external_linked_accounts_balances.cpython-39.pyc
| | | | |-fcm.cpython-39.pyc
| | | | |-goal_ledger.cpython-39.pyc
| | | | |-goals.cpython-39.pyc
| | | | |-incomes.cpython-39.pyc
| | | | |-institutions.cpython-39.pyc
| | | | |-linked_accounts.cpython-39.pyc
| | | | |-macro_goals.cpython-39.pyc
| | | | |-macro_types.cpython-39.pyc
| | | | |-merchant.cpython-39.pyc
| | | | |-merchant_alias.cpython-39.pyc
| | | | |-merchant_categories.cpython-39.pyc
| | | | |-merchant_categorization.cpython-39.pyc
| | | | |-micro_goals.cpython-39.pyc
| | | | |-mono_event.cpython-39.pyc
| | | | |-mono_event_transaction.cpython-39.pyc
| | | | |-organizations.cpython-39.pyc
| | | | |-preferences.cpython-39.pyc
| | | | |-sms.cpython-39.pyc
| | | | |-subgoals.cpython-39.pyc
| | | | |-terms_and_conditions.cpython-39.pyc
| | | | |-tokens.cpython-39.pyc
| | | | |-top_merchants.cpython-39.pyc
| | | | |-transaction_micro_goal_queries.cpython-39.pyc
| | | | |-transactions.cpython-39.pyc
| | | | |-user.cpython-39.pyc
| | | | |-users_accounts.cpython-39.pyc
| | | | |-users_organizations.cpython-39.pyc
| | | |-accounts.py
| | | |-all.py
| | | |-api_calls.py
| | | |-base.py
| | | |-categories.py
| | | |-categorization.py
| | | |-categorization_recommendations.py
| | | |-contribution_settings.py
| | | |-external_linked_accounts.py
| | | |-external_linked_accounts_balances.py
| | | |-fcm.py
| | | |-goal_contribute.py
| | | |-goal_ledger.py
| | | |-goals.py
| | | |-incomes.py
| | | |-institutions.py
| | | |-linked_accounts.py
| | | |-macro_goals.py
| | | |-macro_types.py
| | | |-merchant.py
| | | |-merchant_alias.py
| | | |-merchant_categories.py
| | | |-merchant_categorization.py
| | | |-micro_goals.py
| | | |-mono_event.py
| | | |-mono_event_transaction.py
| | | |-organizations.py
| | | |-preferences.py
| | | |-sms.py
| | | |-subgoals.py
| | | |-terms_and_conditions.py
| | | |-tokens.py
| | | |-top_merchants.py
| | | |-transaction_micro_goal_queries.py
| | | |-transactions.py
| | | |-user.py
| | | |-users_accounts.py
| | | |-users_organizations.py
| | |-resources
| | | |-__init__.py
| | | |-__pycache__
| | | | |-__init__.cpython-39.pyc
| | | | |-accounts.cpython-39.pyc
| | | | |-base.cpython-39.pyc
| | | | |-categories.cpython-39.pyc
| | | | |-contact_us.cpython-39.pyc
| | | | |-goals.cpython-39.pyc
| | | | |-graphs.cpython-39.pyc
| | | | |-health.cpython-39.pyc
| | | | |-merchants.cpython-39.pyc
| | | | |-micro_goals.cpython-39.pyc
| | | | |-mono.cpython-39.pyc
| | | | |-organizations.cpython-39.pyc
| | | | |-preferences.cpython-39.pyc
| | | | |-simulate.cpython-39.pyc
| | | | |-smses.cpython-39.pyc
| | | | |-terms_and_conditions.cpython-39.pyc
| | | | |-tokens.cpython-39.pyc
| | | | |-transactions.cpython-39.pyc
| | | | |-users.cpython-39.pyc
| | | |-accounts.py
| | | |-base.py
| | | |-categories.py
| | | |-contact_us.py
| | | |-goals.py
| | | |-graphs.py
| | | |-health.py
| | | |-merchants.py
| | | |-micro_goals.py
| | | |-mono.py
| | | |-organizations.py
| | | |-preferences.py
| | | |-simulate.py
| | | |-smses.py
| | | |-terms_and_conditions.py
| | | |-test_json
| | | | |-__init__.py
| | | | |-csvjson.json
| | | |-tokens.py
| | | |-transactions.py
| | | |-types
| | | | |-__init__.py
| | | | |-__pycache__
| | | | | |-__init__.cpython-39.pyc
| | | | | |-nullable_datetime.cpython-39.pyc
| | | | | |-nullable_string.cpython-39.pyc
| | | | |-nullable_datetime.py
| | | | |-nullable_string.py
| | | |-users.py
| | |-services
| | | |-__init__.py
| | | |-__pycache__
| | | | |-__init__.cpython-39.pyc
| | | | |-auto_categorization.cpython-39.pyc
| | | | |-categorize_past_transactions.cpython-39.pyc
| | | | |-ledger_rollovers.cpython-39.pyc
| | | | |-merchant_categorization.cpython-39.pyc
| | | | |-notifications.cpython-39.pyc
| | | | |-periodic.cpython-39.pyc
| | | | |-process_sms.cpython-39.pyc
| | | |-auto_categorization.py
| | | |-categorize_past_transactions.py
| | | |-ledger_rollovers.py
| | | |-merchant_categorization.py
| | | |-mono
| | | | |-__init__.py
| | | | |-__pycache__
| | | | | |-__init__.cpython-39.pyc
| | | | | |-retrieve_previous_transactions.cpython-39.pyc
| | | | |-enrichment_models_enterprise
| | | | | |-classifier_enterprise.pickle
| | | | | |-embedding_model_enterprise.ft
| | | | | |-embedding_model_enterprise.ft.wv.vectors_ngrams.npy
| | | | |-events
| | | | | |-__init__.py
| | | | | |-__pycache__
| | | | | | |-__init__.cpython-39.pyc
| | | | | | |-event_processor.cpython-39.pyc
| | | | | | |-transfer_event_merchant_parser.cpython-39.pyc
| | | | | |-event_processor.py
| | | | | |-transfer_event_merchant_parser.py
| | | | |-merchant_parser
| | | | | |-__pycache__
| | | | | | |-absa.cpython-39.pyc
| | | | | | |-all.cpython-39.pyc
| | | | | | |-cooperative.cpython-39.pyc
| | | | | | |-default_parser.cpython-39.pyc
| | | | | | |-equity.cpython-39.pyc
| | | | | | |-kcb.cpython-39.pyc
| | | | | | |-mpesa.cpython-39.pyc
| | | | | | |-ncba.cpython-39.pyc
| | | | | | |-stanbic.cpython-39.pyc
| | | | | |-absa.py
| | | | | |-all.py
| | | | | |-cooperative.py
| | | | | |-default_parser.py
| | | | | |-equity.py
| | | | | |-kcb.py
| | | | | |-mpesa.py
| | | | | |-ncba.py
| | | | | |-stanbic.py
| | | | |-retrieve_previous_transactions.py
| | | |-notifications.py
| | | |-periodic.py
| | | |-process_sms.py
| | |-templates
| | | |-base_email.html
| | | |-email_verification.html
| | | |-password_reset.html
| | | |-success_password_reset.html
| | |-utils.py
| | |-views.py
| | |-wsgi.py
| |-dev.db
| |-gconfig
| | |-development
| | | |-alvin-firebase-adminsdk.json
| | |-production
| | | |-alvin-firebase-adminsdk.json
| | | |-gunicorn_config.py
| |-k8s
| | |-README.md
| | |-development
| | | |-api.yml
| | | |-c-worker.yml
| | | |-config-map.yml
| | | |-debuggers.yml
| | | |-endpoints.yml
| | | |-namespace.yml
| |-migrations
| | |-README
| | |-__pycache__
| | | |-env.cpython-39.pyc
| | |-alembic.ini
| | |-env.py
| | |-script.py.mako
| | |-versions
| |-poetry.lock
| |-provisioning
| | |-playbook.yml
| | |-requirements.yml
| | |-vars
| | | |-default.yml
| |-pyproject.toml
| |-pytest.ini
| |-schema_model
| | |-README.md
| | |-schema.dbm
| |-startup.sh
| |-supervisord
| | |-celeryb.conf
| | |-celeryd.conf
| | |-supervisord.conf
| |-systemd.unit
| | |-alvin-api-gunicorn.service
| |-tests
| | |-__init__.py
| | |-__pycache__
| | | |-__init__.cpython-39.pyc
| | | |-base.cpython-39.pyc
| | | |-factories.cpython-39.pyc
| | | |-test_views.cpython-39-pytest-7.1.2.pyc
| | |-base.py
| | |-crontab
| | | |-__init__.py
| | | |-__pycache__
| | | | |-__init__.cpython-39.pyc
| | | | |-test_cron.cpython-39-pytest-7.1.2.pyc
| | | |-test_cron.py
| | |-factories.py
| | |-models
| | | |-__init__.py
| | | |-__pycache__
| | | | |-__init__.cpython-39.pyc
| | | | |-test_category.cpython-39-pytest-7.1.2.pyc
| | | | |-test_external_linked_accounts.cpython-39-pytest-7.1.2.pyc
| | | | |-test_fcm.cpython-39-pytest-7.1.2.pyc
| | | | |-test_goal_ledger.cpython-39-pytest-7.1.2.pyc
| | | | |-test_macro_goals.cpython-39-pytest-7.1.2.pyc
| | | | |-test_merchant.cpython-39-pytest-7.1.2.pyc
| | | | |-test_merchant_categorization.cpython-39-pytest-7.1.2.pyc
| | | | |-test_micro_goals.cpython-39-pytest-7.1.2.pyc
| | | | |-test_preferences.cpython-39-pytest-7.1.2.pyc
| | | | |-test_sms.cpython-39-pytest-7.1.2.pyc
| | | | |-test_top_merchants.cpython-39-pytest-7.1.2.pyc
| | | | |-test_transactions.cpython-39-pytest-7.1.2.pyc
| | | | |-test_user.cpython-39-pytest-7.1.2.pyc
| | | |-test_category.py
| | | |-test_external_linked_accounts.py
| | | |-test_fcm.py
| | | |-test_goal_ledger.py
| | | |-test_macro_goals.py
| | | |-test_merchant.py
| | | |-test_merchant_categorization.py
| | | |-test_micro_goals.py
| | | |-test_mono_event.py
| | | |-test_preferences.py
| | | |-test_sms.py
| | | |-test_top_merchants.py
| | | |-test_transactions.py
| | | |-test_user.py
| | |-resources
| | | |-__init__.py
| | | |-__pycache__
| | | | |-__init__.cpython-39.pyc
| | | | |-test_base.cpython-39-pytest-7.1.2.pyc
| | | | |-test_categories.cpython-39-pytest-7.1.2.pyc
| | | | |-test_goals.cpython-39-pytest-7.1.2.pyc
| | | | |-test_graphs.cpython-39-pytest-7.1.2.pyc
| | | | |-test_merchants.cpython-39-pytest-7.1.2.pyc
| | | | |-test_micro_goals.cpython-39-pytest-7.1.2.pyc
| | | | |-test_mono.cpython-39-pytest-7.1.2.pyc
| | | | |-test_preferences.cpython-39-pytest-7.1.2.pyc
| | | | |-test_smses.cpython-39-pytest-7.1.2.pyc
| | | | |-test_tokens.cpython-39-pytest-7.1.2.pyc
| | | | |-test_transactions.cpython-39-pytest-7.1.2.pyc
| | | | |-test_users.cpython-39-pytest-7.1.2.pyc
| | | |-test_base.py
| | | |-test_categories.py
| | | |-test_goals.py
| | | |-test_graphs.py
| | | |-test_merchants.py
| | | |-test_micro_goals.py
| | | |-test_mono.py
| | | |-test_preferences.py
| | | |-test_smses.py
| | | |-test_terms_and_conditions.py
| | | |-test_tokens.py
| | | |-test_transactions.py
| | | |-test_users.py
| | |-services
| | | |-__init__.py
| | | |-__pycache__
| | | | |-__init__.cpython-39.pyc
| | | | |-test_categorize_past_transactions.cpython-39-pytest-7.1.2.pyc
| | | | |-test_ledger_rollovers.cpython-39-pytest-7.1.2.pyc
| | | | |-test_merchant_categorization.cpython-39-pytest-7.1.2.pyc
| | | | |-test_notifications.cpython-39-pytest-7.1.2.pyc
| | | | |-test_process_sms.cpython-39-pytest-7.1.2.pyc
| | | |-mono_event
| | | | |-__init__.py
| | | | |-__pycache__
| | | | | |-__init__.cpython-39.pyc
| | | | | |-test_event_processor.cpython-39-pytest-7.1.2.pyc
| | | | | |-test_retrieve_previous_transactions.cpython-39-pytest-7.1.2.pyc
| | | | |-test_absa_fuzzy_merchant_parser.py
| | | | |-test_default_fuzzy_merchant_parser.py
| | | | |-test_event_processor.py
| | | | |-test_mpesa_fuzzy_merchant_parser.py
| | | | |-test_retrieve_previous_transactions.py
| | | |-test_categorize_past_transactions.py
| | | |-test_ledger_rollovers.py
| | | |-test_merchant_categorization.py
| | | |-test_notifications.py
| | | |-test_process_sms.py
| | |-test_views.py
| |-tox.ini
|-dev.db
|-test.py

```

## Database

The default dev database is a SQLite database. It is located in the root directory of the project. It is called `dev.db`. However, in production posgtres is used. 

### Database Schema

The database schema is located in the `migrations` directory. It is a series of files that are used to migrate the database from one version to another. The database schema is versioned. The current version is `1.0.0`.

#### Database Tables and Relationships

The image below shows all the tables and their corresponding relationships. You can download the image [here](https://res.cloudinary.com/brybzlee/image/upload/v1670311741/alvinapp/alvin_ent.png) 

![Database Tables and Relationships](https://res.cloudinary.com/brybzlee/image/upload/v1670311741/alvinapp/alvin_ent.png)


## Installation

### Quick start

#### shell script

```
poetry install
./start_up.sh
```

to start celery workers and celery beat;

```
podman run -dp 6379:6379 redis:alpine
APP=celery-workers ./startup.sh
APP=celery-beat ./startup.sh
```

#### podman/docker

```
podman build -t alvin-api .
podman run -p 5000:5000 alvin-api
```

This will start the api without its celery workers.

#### minikube

Refer to k8s directory


#### Manual start

##### configurations

```
export FLASK_ENV="development"
export FLASK_APP="backend.wsgi"
export GOOGLE_APPLICATION_CREDENTIALS=./gconfig/development/alvin-firebase-adminsdk.json
```

##### Database setup

```
poetry run flask db upgrade
poetry run flask init-categories
```

In development also run the flask task;

```commandline
poetry run flask init-sys-user
```

##### Gunicorn

```
poetry run gunicorn -c ./gconfig/prod/gunicorn_config.py
```

##### Celery

Celery worker:

```
poetry run celery -A backend.wsgi.celery worker --loglevel=debug  --logfile=/var/log/celery.worker.log --pidfile=celery-worker.pid
```

Celery beat:

```
poetry run celery -A backend.wsgi.celery beat --loglevel=debug  --logfile=/var/log/celery.beat.log --pidfile=celery-beat.pid
```

#### Supervisord service

The manual start of celery and celery-beat can be replaced by use of supervisor, as follows;

```commandline
poetry run supervisord -c supervisord/supervisord.conf
```

to [control processes](http://supervisord.org/running.html#supervisorctl-command-line-options) running under supervisor

```commandline
poetry run supervisorctl -c supervisord/supervisord.conf
```

#### Stopping services

##### Gunicorn service

```commandline
kill -QUIT `cat gunicorn.pid`
```

##### Celery worker service

Only for celery service started manually, for supervised worker refer to supervisord section

```commandline
kill -QUIT `cat celery-worker.pid`
```

##### Celery beat service

```commandline
kill -QUIT `cat celery-beat.pid`
```

to force immediate shutdown use `-TERM` or `-9` option.

## Troubleshooting

#### Permission Errors

```text
PermissionError: [Errno 13] Permission denied: '/var/log/gunicorn.error.log'
```

This can be resolved by changing the group ownership of `/var/log` to current user group;

To view the current user group;
```commandline
id
```

To change group ownership for `/var/log`

```commandline
sudo chgrp group-name /var/log
```

To change group read-write permissions for `/var/log`

```commandline
sudo chmod g+rw /var/log
```

#### Alembic migrations, only on development environment

Hard remove most recent migration
```
delete from alembic_version where version_num='470572fac7a1';
flask db stamp head
```

## API Endpoints

```json
{
  "basePath": "/",
  "paths": {
    "/accounts/{id}/goals/": {
      "parameters": [
        {
          "name": "id",
          "in": "path",
          "required": true,
          "type": "integer"
        }
      ],
      "get": {
        "responses": {
          "200": {
            "description": "goal details"
          }
        },
        "operationId": "get_account_goals",
        "tags": [
          "accounts"
        ]
      }
    },
    "/categories/": {
      "get": {
        "responses": {
          "200": {
            "description": "all category details"
          }
        },
        "operationId": "get_category_res",
        "tags": [
          "categories"
        ]
      },
      "post": {
        "responses": {
          "201": {
            "description": "category details"
          }
        },
        "operationId": "post_category_res",
        "parameters": [
          {
            "name": "payload",
            "required": true,
            "in": "body",
            "schema": {
              "$ref": "#/definitions/Category"
            }
          }
        ],
        "tags": [
          "categories"
        ]
      }
    },
    "/categories/{id}/": {
      "parameters": [
        {
          "name": "id",
          "in": "path",
          "required": true,
          "type": "integer"
        }
      ],
      "get": {
        "responses": {
          "200": {
            "description": "category details"
          }
        },
        "operationId": "get_categories",
        "tags": [
          "categories"
        ]
      }
    },
    "/contact-us/": {
      "post": {
        "responses": {
          "200": {
            "description": "request has been sent"
          }
        },
        "operationId": "post_contact_us_resource",
        "parameters": [
          {
            "name": "payload",
            "required": true,
            "in": "body",
            "schema": {
              "$ref": "#/definitions/ContactUs"
            }
          }
        ],
        "tags": [
          "contact-us"
        ]
      }
    },
    "/goals/": {
      "delete": {
        "responses": {
          "200": {
            "description": "delete all goals"
          }
        },
        "operationId": "delete_goals",
        "tags": [
          "goals"
        ]
      },
      "post": {
        "responses": {
          "201": {
            "description": "goal details"
          }
        },
        "operationId": "post_goals",
        "parameters": [
          {
            "name": "payload",
            "required": true,
            "in": "body",
            "schema": {
              "$ref": "#/definitions/Goal"
            }
          }
        ],
        "tags": [
          "goals"
        ]
      }
    },
    "/goals/macros/{id}/": {
      "parameters": [
        {
          "name": "id",
          "in": "path",
          "required": true,
          "type": "integer"
        }
      ],
      "put": {
        "responses": {
          "200": {
            "description": "goal details"
          }
        },
        "operationId": "put_macro_res",
        "parameters": [
          {
            "name": "payload",
            "required": true,
            "in": "body",
            "schema": {
              "$ref": "#/definitions/MacroGoal"
            }
          }
        ],
        "tags": [
          "goals"
        ]
      },
      "get": {
        "responses": {
          "200": {
            "description": "macro goal details"
          }
        },
        "operationId": "get_macro_res",
        "tags": [
          "goals"
        ]
      }
    },
    "/goals/macros/{id}/balance/": {
      "parameters": [
        {
          "name": "id",
          "in": "path",
          "required": true,
          "type": "integer"
        }
      ],
      "get": {
        "responses": {
          "200": {
            "description": "macro goal balance"
          }
        },
        "operationId": "get_macro_balance",
        "tags": [
          "goals"
        ]
      }
    },
    "/goals/macros/{id}/micros/": {
      "parameters": [
        {
          "name": "id",
          "in": "path",
          "required": true,
          "type": "integer"
        }
      ],
      "delete": {
        "responses": {
          "200": {
            "description": "delete status"
          }
        },
        "operationId": "delete_micros",
        "tags": [
          "goals"
        ]
      },
      "get": {
        "responses": {
          "201": {
            "description": "micro goal details"
          }
        },
        "operationId": "get_micros",
        "tags": [
          "goals"
        ]
      },
      "post": {
        "responses": {
          "201": {
            "description": "micro goal details"
          }
        },
        "operationId": "post_micros",
        "parameters": [
          {
            "name": "payload",
            "required": true,
            "in": "body",
            "schema": {
              "$ref": "#/definitions/MicroGoal"
            }
          }
        ],
        "tags": [
          "goals"
        ]
      }
    },
    "/goals/micros/{id}/": {
      "parameters": [
        {
          "name": "id",
          "in": "path",
          "required": true,
          "type": "integer"
        }
      ],
      "put": {
        "responses": {
          "200": {
            "description": "micro goal balance"
          }
        },
        "operationId": "put_micros",
        "parameters": [
          {
            "name": "payload",
            "required": true,
            "in": "body",
            "schema": {
              "$ref": "#/definitions/MicroGoal"
            }
          }
        ],
        "tags": [
          "goals"
        ]
      },
      "get": {
        "responses": {
          "200": {
            "description": "micro goal balance"
          }
        },
        "operationId": "get_micros",
        "tags": [
          "goals"
        ]
      },
      "delete": {
        "responses": {
          "200": {
            "description": "remove a micro goal"
          }
        },
        "operationId": "delete_micros",
        "tags": [
          "goals"
        ]
      }
    },
    "/goals/micros/{id}/balance/": {
      "parameters": [
        {
          "name": "id",
          "in": "path",
          "required": true,
          "type": "integer"
        }
      ],
      "get": {
        "responses": {
          "200": {
            "description": "micro goal balance"
          }
        },
        "operationId": "get_micros_balance",
        "tags": [
          "goals"
        ]
      }
    },
    "/goals/{id}/": {
      "parameters": [
        {
          "name": "id",
          "in": "path",
          "required": true,
          "type": "integer"
        }
      ],
      "put": {
        "responses": {
          "200": {
            "description": "goal details"
          }
        },
        "operationId": "put_goal_res",
        "parameters": [
          {
            "name": "payload",
            "required": true,
            "in": "body",
            "schema": {
              "$ref": "#/definitions/Goal"
            }
          }
        ],
        "tags": [
          "goals"
        ]
      },
      "get": {
        "responses": {
          "200": {
            "description": "goal details"
          }
        },
        "operationId": "get_goal_res",
        "tags": [
          "goals"
        ]
      },
      "delete": {
        "responses": {
          "200": {
            "description": "delete goal"
          }
        },
        "operationId": "delete_goal_res",
        "tags": [
          "goals"
        ]
      }
    },
    "/goals/{id}/macros/": {
      "parameters": [
        {
          "name": "id",
          "in": "path",
          "required": true,
          "type": "integer"
        }
      ],
      "post": {
        "responses": {
          "201": {
            "description": "macro goal details"
          }
        },
        "operationId": "post_macros",
        "parameters": [
          {
            "name": "payload",
            "required": true,
            "in": "body",
            "schema": {
              "$ref": "#/definitions/MacroGoal"
            }
          }
        ],
        "tags": [
          "goals"
        ]
      }
    },
    "/graphs/overview/daily/": {
      "get": {
        "responses": {
          "200": {
            "description": "Success"
          }
        },
        "operationId": "get_graphs_resource",
        "tags": [
          "graphs"
        ]
      }
    },
    "/graphs/overview/monthly/": {
      "get": {
        "responses": {
          "200": {
            "description": "Success"
          }
        },
        "operationId": "get_graphs_resource",
        "tags": [
          "graphs"
        ]
      }
    },
    "/health/": {
      "get": {
        "responses": {
          "200": {
            "description": "Success"
          }
        },
        "operationId": "get_health_resource",
        "security": [
          
        ],
        "tags": [
          "health"
        ]
      }
    },
    "/health/celery-beat": {
      "get": {
        "responses": {
          "200": {
            "description": "Success"
          }
        },
        "operationId": "get_celery_beat_health_resource",
        "security": [
          
        ],
        "tags": [
          "health"
        ]
      }
    },
    "/health/celery-worker": {
      "get": {
        "responses": {
          "200": {
            "description": "Success"
          }
        },
        "operationId": "get_celery_worker_health_resource",
        "security": [
          
        ],
        "tags": [
          "health"
        ]
      }
    },
    "/merchants/": {
      "post": {
        "responses": {
          "201": {
            "description": "add new merchants details"
          }
        },
        "operationId": "post_merchants_resource",
        "parameters": [
          {
            "name": "payload",
            "required": true,
            "in": "body",
            "schema": {
              "$ref": "#/definitions/Merchant"
            }
          }
        ],
        "tags": [
          "merchants"
        ]
      }
    },
    "/merchants/{id}/": {
      "parameters": [
        {
          "name": "id",
          "in": "path",
          "required": true,
          "type": "integer"
        }
      ],
      "put": {
        "responses": {
          "201": {
            "description": "update merchants details"
          }
        },
        "operationId": "put_merchants_resource",
        "parameters": [
          {
            "name": "payload",
            "required": true,
            "in": "body",
            "schema": {
              "$ref": "#/definitions/Merchant"
            }
          }
        ],
        "tags": [
          "merchants"
        ]
      }
    },
    "/micro-goals/{id}/settings/": {
      "parameters": [
        {
          "name": "id",
          "in": "path",
          "required": true,
          "type": "integer"
        }
      ],
      "put": {
        "responses": {
          "200": {
            "description": "micro goal setting"
          }
        },
        "operationId": "put_micro_goal_resource",
        "parameters": [
          {
            "name": "payload",
            "required": true,
            "in": "body",
            "schema": {
              "$ref": "#/definitions/MicroGoalSetting"
            }
          }
        ],
        "tags": [
          "micro-goals"
        ]
      }
    },
    "/mono/": {
      "post": {
        "responses": {
          "201": {
            "description": "mono account has been created"
          }
        },
        "operationId": "post_mono_token",
        "parameters": [
          {
            "name": "payload",
            "required": true,
            "in": "body",
            "schema": {
              "$ref": "#/definitions/ExternalLinkedAccount"
            }
          }
        ],
        "tags": [
          "mono"
        ]
      }
    },
    "/mono/account/{id}/": {
      "parameters": [
        {
          "in": "path",
          "description": "account id",
          "name": "id",
          "required": true,
          "type": "integer"
        }
      ],
      "get": {
        "responses": {
          "200": {
            "description": "account details"
          }
        },
        "operationId": "get_mono_account",
        "tags": [
          "mono"
        ]
      }
    },
    "/mono/code/": {
      "post": {
        "responses": {
          "201": {
            "description": "mono account has been created"
          }
        },
        "operationId": "post_mono_token",
        "tags": [
          "mono"
        ]
      }
    },
    "/mono/events/": {
      "post": {
        "responses": {
          "201": {
            "description": "mono-events"
          }
        },
        "operationId": "post_mono_events",
        "tags": [
          "mono"
        ]
      }
    },
    "/mono/pub-key/": {
      "get": {
        "responses": {
          "200": {
            "description": "Success"
          }
        },
        "operationId": "get_mono_key",
        "tags": [
          "mono"
        ]
      }
    },
    "/mono/unlink/": {
      "post": {
        "responses": {
          "200": {
            "description": "mono account has been unlinked"
          }
        },
        "operationId": "post_mono_unlink_account",
        "parameters": [
          {
            "name": "payload",
            "required": true,
            "in": "body",
            "schema": {
              "$ref": "#/definitions/ExternalLinkedAccount"
            }
          }
        ],
        "tags": [
          "mono"
        ]
      }
    },
    "/organizations/": {
      "get": {
        "responses": {
          "200": {
            "description": "Success",
            "schema": {
              "type": "array",
              "items": {
                "$ref": "#/definitions/Organization"
              }
            }
          }
        },
        "operationId": "get_organizations_list",
        "tags": [
          "organizations"
        ]
      },
      "post": {
        "responses": {
          "200": {
            "description": "Success"
          }
        },
        "operationId": "post_organizations_list",
        "parameters": [
          {
            "name": "payload",
            "required": true,
            "in": "body",
            "schema": {
              "$ref": "#/definitions/Organization"
            }
          }
        ],
        "tags": [
          "organizations"
        ]
      }
    },
    "/organizations/{organization_id}": {
      "parameters": [
        {
          "name": "organization_id",
          "in": "path",
          "required": true,
          "type": "integer"
        }
      ],
      "put": {
        "responses": {
          "200": {
            "description": "Success"
          }
        },
        "operationId": "put_organization_res",
        "tags": [
          "organizations"
        ]
      },
      "get": {
        "responses": {
          "200": {
            "description": "Success",
            "schema": {
              "$ref": "#/definitions/Organization"
            }
          }
        },
        "operationId": "get_organization_res",
        "tags": [
          "organizations"
        ]
      }
    },
    "/preferences/alerts/": {
      "put": {
        "responses": {
          "200": {
            "description": "alert preference updated"
          }
        },
        "operationId": "put_preference_resource",
        "parameters": [
          {
            "name": "payload",
            "required": true,
            "in": "body",
            "schema": {
              "$ref": "#/definitions/Alert"
            }
          }
        ],
        "tags": [
          "preferences"
        ]
      },
      "get": {
        "responses": {
          "200": {
            "description": "Success"
          }
        },
        "operationId": "get_preference_resource",
        "tags": [
          "preferences"
        ]
      }
    },
    "/preferences/savingspreference/": {
      "put": {
        "responses": {
          "200": {
            "description": "savings preference updated"
          }
        },
        "operationId": "put_savings_preference_resource",
        "parameters": [
          {
            "name": "payload",
            "required": true,
            "in": "body",
            "schema": {
              "$ref": "#/definitions/SavingsPreference"
            }
          }
        ],
        "tags": [
          "preferences"
        ]
      }
    },
    "/simulate/ledgers/": {
      "get": {
        "responses": {
          "200": {
            "description": "Success"
          }
        },
        "operationId": "get_goal_ledger_resource",
        "tags": [
          "simulate"
        ]
      },
      "post": {
        "responses": {
          "201": {
            "description": "a new ledger has been created"
          }
        },
        "operationId": "post_goal_ledger_resource",
        "parameters": [
          {
            "name": "payload",
            "required": true,
            "in": "body",
            "schema": {
              "$ref": "#/definitions/Ledger"
            }
          }
        ],
        "tags": [
          "simulate"
        ]
      }
    },
    "/simulate/ledgers/active/": {
      "get": {
        "responses": {
          "200": {
            "description": "Success"
          }
        },
        "operationId": "get_goal_ledger_active",
        "tags": [
          "simulate"
        ]
      }
    },
    "/simulate/ledgers/{id}/activate/": {
      "parameters": [
        {
          "name": "id",
          "in": "path",
          "required": true,
          "type": "integer"
        }
      ],
      "put": {
        "responses": {
          "200": {
            "description": "Success"
          }
        },
        "operationId": "put_goal_ledger_activate",
        "tags": [
          "simulate"
        ]
      }
    },
    "/simulate/notifications/threshold/": {
      "get": {
        "responses": {
          "200": {
            "description": "Success"
          }
        },
        "operationId": "get_thresh_hold_notification",
        "tags": [
          "simulate"
        ]
      }
    },
    "/simulate_/notifications/transactions/": {
      "post": {
        "responses": {
          "200": {
            "description": "simulation complete"
          }
        },
        "operationId": "post_notification_transactions",
        "parameters": [
          {
            "name": "payload",
            "required": true,
            "in": "body",
            "schema": {
              "$ref": "#/definitions/Simulate"
            }
          }
        ],
        "tags": [
          "simulate_"
        ]
      }
    },
    "/simulate_/savings-notification/{id}/": {
      "parameters": [
        {
          "name": "id",
          "in": "path",
          "required": true,
          "type": "integer"
        }
      ],
      "get": {
        "responses": {
          "200": {
            "description": "Success"
          }
        },
        "operationId": "get_saving_notification",
        "tags": [
          "simulate_"
        ]
      }
    },
    "/simulate_/savings-progress-notification/{id}/": {
      "parameters": [
        {
          "name": "id",
          "in": "path",
          "required": true,
          "type": "integer"
        }
      ],
      "get": {
        "responses": {
          "200": {
            "description": "Success"
          }
        },
        "operationId": "get_saving_progress_notification",
        "tags": [
          "simulate_"
        ]
      }
    },
    "/simulate_/savings-resume-notification/{id}/": {
      "parameters": [
        {
          "name": "id",
          "in": "path",
          "required": true,
          "type": "integer"
        }
      ],
      "get": {
        "responses": {
          "200": {
            "description": "Success"
          }
        },
        "operationId": "get_saving_resume_notification",
        "tags": [
          "simulate_"
        ]
      }
    },
    "/simulate_/savings-resumed-notification/{id}/": {
      "parameters": [
        {
          "name": "id",
          "in": "path",
          "required": true,
          "type": "integer"
        }
      ],
      "get": {
        "responses": {
          "200": {
            "description": "Success"
          }
        },
        "operationId": "get_saving_resumed_notification",
        "tags": [
          "simulate_"
        ]
      }
    },
    "/smses/": {
      "post": {
        "responses": {
          "201": {
            "description": "sms created"
          }
        },
        "operationId": "post_smses",
        "parameters": [
          {
            "name": "payload",
            "required": true,
            "in": "body",
            "schema": {
              "$ref": "#/definitions/Sms"
            }
          }
        ],
        "tags": [
          "smses"
        ]
      }
    },
    "/smses/age/": {
      "get": {
        "responses": {
          "200": {
            "description": "age of most recent sms"
          }
        },
        "operationId": "get_sms_age",
        "tags": [
          "smses"
        ]
      }
    },
    "/smses/count/": {
      "get": {
        "responses": {
          "200": {
            "description": "sms count"
          }
        },
        "operationId": "get_sms_count",
        "tags": [
          "smses"
        ]
      }
    },
    "/smses/{id}/": {
      "parameters": [
        {
          "in": "path",
          "description": "sms id",
          "name": "id",
          "required": true,
          "type": "integer"
        }
      ],
      "get": {
        "responses": {
          "200": {
            "description": "sms details"
          }
        },
        "operationId": "get_sms_res",
        "tags": [
          "smses"
        ]
      }
    },
    "/terms_and_conditions/": {
      "get": {
        "responses": {
          "200": {
            "description": "Success"
          }
        },
        "operationId": "get_post_terms",
        "tags": [
          "terms_and_conditions"
        ]
      },
      "post": {
        "responses": {
          "201": {
            "description": "Terms have been created"
          }
        },
        "operationId": "post_post_terms",
        "tags": [
          "terms_and_conditions"
        ]
      }
    },
    "/terms_and_conditions/{terms_id}/": {
      "parameters": [
        {
          "in": "path",
          "description": "terms id",
          "name": "terms_id",
          "required": true,
          "type": "integer"
        }
      ],
      "put": {
        "responses": {
          "200": {
            "description": "update terms details"
          }
        },
        "operationId": "put_terms",
        "tags": [
          "terms_and_conditions"
        ]
      },
      "get": {
        "responses": {
          "200": {
            "description": "terms narration"
          }
        },
        "operationId": "get_terms",
        "tags": [
          "terms_and_conditions"
        ]
      },
      "delete": {
        "responses": {
          "200": {
            "description": "Success"
          }
        },
        "operationId": "delete_terms",
        "tags": [
          "terms_and_conditions"
        ]
      }
    },
    "/token/": {
      "post": {
        "responses": {
          "200": {
            "description": "token has been validated"
          }
        },
        "operationId": "post_tokens",
        "parameters": [
          {
            "name": "payload",
            "required": true,
            "in": "body",
            "schema": {
              "$ref": "#/definitions/OAuth%20Token"
            }
          }
        ],
        "security": [
          
        ],
        "tags": [
          "token"
        ]
      }
    },
    "/token/fcm/": {
      "post": {
        "responses": {
          "200": {
            "description": "token has been saved"
          }
        },
        "operationId": "post_token_fcm",
        "parameters": [
          {
            "name": "payload",
            "required": true,
            "in": "body",
            "schema": {
              "$ref": "#/definitions/FCM%20Auth%20Token"
            }
          }
        ],
        "tags": [
          "token"
        ]
      }
    },
    "/token/refresh/": {
      "put": {
        "responses": {
          "200": {
            "description": "token has been validated"
          }
        },
        "operationId": "put_token_refresh",
        "parameters": [
          {
            "name": "payload",
            "required": true,
            "in": "body",
            "schema": {
              "$ref": "#/definitions/OAuth%20Token"
            }
          }
        ],
        "security": [
          
        ],
        "tags": [
          "token"
        ]
      },
      "post": {
        "responses": {
          "200": {
            "description": "token has been validated"
          }
        },
        "operationId": "post_token_refresh",
        "parameters": [
          {
            "name": "payload",
            "required": true,
            "in": "body",
            "schema": {
              "$ref": "#/definitions/OAuth%20Token"
            }
          }
        ],
        "security": [
          
        ],
        "tags": [
          "token"
        ]
      }
    },
    "/transactions/": {
      "get": {
        "responses": {
          "200": {
            "description": "transaction details"
          }
        },
        "operationId": "get_transactions",
        "parameters": [
          {
            "description": "transaction ids to retrieve",
            "name": "ids",
            "type": "string",
            "in": "query"
          },
          {
            "description": "mono account transaction ids to retrieve",
            "name": "mono_account_id",
            "type": "string",
            "in": "query"
          }
        ],
        "tags": [
          "transactions"
        ]
      },
      "post": {
        "responses": {
          "201": {
            "description": "add new transactions details"
          }
        },
        "operationId": "post_transactions",
        "parameters": [
          {
            "name": "payload",
            "required": true,
            "in": "body",
            "schema": {
              "$ref": "#/definitions/Transaction"
            }
          }
        ],
        "tags": [
          "transactions"
        ]
      }
    },
    "/transactions/all_accounts": {
      "get": {
        "responses": {
          "200": {
            "description": "transaction details"
          }
        },
        "operationId": "get_transaction_mono",
        "tags": [
          "transactions"
        ]
      }
    },
    "/transactions/categorized/": {
      "get": {
        "responses": {
          "200": {
            "description": "transaction details"
          }
        },
        "operationId": "get_transaction_list_categorized",
        "tags": [
          "transactions"
        ]
      }
    },
    "/transactions/categorized_transactions/": {
      "get": {
        "responses": {
          "200": {
            "description": "Success"
          }
        },
        "summary": "Get all transactions",
        "description": "Returns:\n    list: list of transactions",
        "operationId": "get_transaction_categorized",
        "parameters": [
          {
            "description": "organization id",
            "name": "organization_id",
            "type": "string",
            "in": "query"
          },
          {
            "description": "organization api_key",
            "name": "api_key",
            "type": "string",
            "in": "query"
          },
          {
            "description": "page number",
            "name": "page",
            "type": "string",
            "in": "query"
          },
          {
            "description": "number of transactions per page",
            "name": "per_page",
            "type": "string",
            "in": "query"
          }
        ],
        "tags": [
          "transactions"
        ]
      }
    },
    "/transactions/csv/": {
      "post": {
        "responses": {
          "200": {
            "description": "transaction details"
          }
        },
        "operationId": "post_transaction_list_csv",
        "tags": [
          "transactions"
        ]
      }
    },
    "/transactions/enrich_data/": {
      "post": {
        "responses": {
          "200": {
            "description": "Success"
          }
        },
        "operationId": "post_transations_enrich",
        "tags": [
          "transactions"
        ]
      }
    },
    "/transactions/raw_transactions/": {
      "get": {
        "responses": {
          "200": {
            "description": "Success"
          }
        },
        "operationId": "get_transations_raw",
        "tags": [
          "transactions"
        ]
      },
      "post": {
        "responses": {
          "200": {
            "description": "Success"
          }
        },
        "operationId": "post_transations_raw",
        "tags": [
          "transactions"
        ]
      }
    },
    "/transactions/top-uncategorized/": {
      "get": {
        "responses": {
          "200": {
            "description": "transaction details"
          }
        },
        "operationId": "get_transaction_list",
        "parameters": [
          {
            "description": "transaction id to retrieve",
            "type": "int",
            "name": "count",
            "in": "query"
          }
        ],
        "tags": [
          "transactions"
        ]
      }
    },
    "/transactions/uncategorized/": {
      "get": {
        "responses": {
          "200": {
            "description": "transaction details"
          }
        },
        "operationId": "get_transaction_list_un_categorized",
        "tags": [
          "transactions"
        ]
      }
    },
    "/transactions/{id}/": {
      "parameters": [
        {
          "in": "path",
          "description": "transaction id",
          "name": "id",
          "required": true,
          "type": "integer"
        }
      ],
      "get": {
        "responses": {
          "200": {
            "description": "transaction details"
          }
        },
        "operationId": "get_transaction_res",
        "tags": [
          "transactions"
        ]
      }
    },
    "/transactions/{id}/categorize/": {
      "parameters": [
        {
          "name": "payload",
          "required": true,
          "in": "body",
          "schema": {
            "$ref": "#/definitions/Categorize"
          }
        },
        {
          "in": "path",
          "description": "transaction id",
          "name": "id",
          "required": true,
          "type": "integer"
        }
      ],
      "post": {
        "responses": {
          "201": {
            "description": "transaction details"
          }
        },
        "operationId": "post_categorization",
        "tags": [
          "transactions"
        ]
      }
    },
    "/users/": {
      "put": {
        "responses": {
          "200": {
            "description": "user details",
            "schema": {
              "$ref": "#/definitions/User"
            }
          }
        },
        "operationId": "put_users",
        "parameters": [
          {
            "name": "payload",
            "required": true,
            "in": "body",
            "schema": {
              "$ref": "#/definitions/User"
            }
          }
        ],
        "tags": [
          "users"
        ]
      },
      "get": {
        "responses": {
          "200": {
            "description": "user details"
          }
        },
        "operationId": "get_users",
        "tags": [
          "users"
        ]
      },
      "post": {
        "responses": {
          "200": {
            "description": "user details"
          }
        },
        "operationId": "post_users",
        "parameters": [
          {
            "name": "payload",
            "required": true,
            "in": "body",
            "schema": {
              "$ref": "#/definitions/User"
            }
          }
        ],
        "tags": [
          "users"
        ]
      }
    },
    "/users/add_from_csv/{organization_id}": {
      "parameters": [
        {
          "name": "organization_id",
          "in": "path",
          "required": true,
          "type": "string"
        }
      ],
      "post": {
        "responses": {
          "200": {
            "description": "user details"
          }
        },
        "operationId": "post_users_from_csv",
        "tags": [
          "users"
        ]
      }
    },
    "/users/add_user/{organization_id}": {
      "parameters": [
        {
          "name": "organization_id",
          "in": "path",
          "required": true,
          "type": "string"
        }
      ],
      "post": {
        "responses": {
          "200": {
            "description": "user details"
          }
        },
        "operationId": "post_users_from_csv",
        "tags": [
          "users"
        ]
      }
    },
    "/users/auth/": {
      "post": {
        "responses": {
          "200": {
            "description": "user details"
          }
        },
        "operationId": "post_user_organization",
        "tags": [
          "users"
        ]
      }
    },
    "/users/confirm/{token}": {
      "parameters": [
        {
          "name": "token",
          "in": "path",
          "required": true,
          "type": "string"
        }
      ],
      "post": {
        "responses": {
          "200": {
            "description": "user details"
          }
        },
        "operationId": "post_confirm",
        "tags": [
          "users"
        ]
      }
    },
    "/users/create/": {
      "post": {
        "responses": {
          "200": {
            "description": "user details"
          }
        },
        "operationId": "post_user_organization",
        "tags": [
          "users"
        ]
      }
    },
    "/users/delete": {
      "post": {
        "responses": {
          "200": {
            "description": "Success"
          }
        },
        "operationId": "post_delete_user",
        "tags": [
          "users"
        ]
      }
    },
    "/users/edit_user/{user_id}": {
      "parameters": [
        {
          "name": "user_id",
          "in": "path",
          "required": true,
          "type": "string"
        }
      ],
      "post": {
        "responses": {
          "200": {
            "description": "Success"
          }
        },
        "operationId": "post_users_from_csv",
        "tags": [
          "users"
        ]
      }
    },
    "/users/household/": {
      "put": {
        "responses": {
          "200": {
            "description": "user_details",
            "schema": {
              "$ref": "#/definitions/User"
            }
          }
        },
        "operationId": "put_household",
        "parameters": [
          {
            "name": "payload",
            "required": true,
            "in": "body",
            "schema": {
              "$ref": "#/definitions/Household"
            }
          }
        ],
        "tags": [
          "users"
        ]
      }
    },
    "/users/income/": {
      "put": {
        "responses": {
          "200": {
            "description": "user_details",
            "schema": {
              "$ref": "#/definitions/User"
            }
          }
        },
        "operationId": "put_incomes",
        "parameters": [
          {
            "name": "payload",
            "required": true,
            "in": "body",
            "schema": {
              "$ref": "#/definitions/Income"
            }
          }
        ],
        "tags": [
          "users"
        ]
      }
    },
    "/users/login": {
      "post": {
        "responses": {
          "200": {
            "description": "user details"
          }
        },
        "operationId": "post_log_in",
        "tags": [
          "users"
        ]
      }
    },
    "/users/onboarded/": {
      "put": {
        "responses": {
          "200": {
            "description": "user_details",
            "schema": {
              "$ref": "#/definitions/User"
            }
          }
        },
        "operationId": "put_onboarding",
        "parameters": [
          {
            "name": "payload",
            "required": true,
            "in": "body",
            "schema": {
              "$ref": "#/definitions/Onboarded"
            }
          }
        ],
        "tags": [
          "users"
        ]
      }
    },
    "/users/organization/": {
      "post": {
        "responses": {
          "200": {
            "description": "user details"
          }
        },
        "operationId": "post_user_organization",
        "tags": [
          "users"
        ]
      }
    },
    "/users/organization/{organization_id}": {
      "parameters": [
        {
          "name": "organization_id",
          "in": "path",
          "required": true,
          "type": "string"
        }
      ],
      "get": {
        "responses": {
          "200": {
            "description": "user details"
          }
        },
        "operationId": "get_user_organization",
        "tags": [
          "users"
        ]
      },
      "post": {
        "responses": {
          "200": {
            "description": "user details"
          }
        },
        "operationId": "post_user_organization",
        "tags": [
          "users"
        ]
      }
    },
    "/users/resend_confirmation/": {
      "post": {
        "responses": {
          "200": {
            "description": "user details"
          }
        },
        "operationId": "post_confirm_res",
        "tags": [
          "users"
        ]
      }
    },
    "/users/reset_password/": {
      "post": {
        "responses": {
          "200": {
            "description": "user details"
          }
        },
        "operationId": "post_password_reset",
        "tags": [
          "users"
        ]
      }
    },
    "/users/reset_password/{token}": {
      "parameters": [
        {
          "name": "token",
          "in": "path",
          "required": true,
          "type": "string"
        }
      ],
      "post": {
        "responses": {
          "200": {
            "description": "user details"
          }
        },
        "operationId": "post_password_reset_confirm",
        "tags": [
          "users"
        ]
      }
    },
    "/users/terms-and-conditions/": {
      "post": {
        "responses": {
          "200": {
            "description": "user terms"
          }
        },
        "operationId": "post_user_terms",
        "tags": [
          "users"
        ]
      }
    },
    "/users/update_password": {
      "post": {
        "responses": {
          "200": {
            "description": "user details"
          }
        },
        "operationId": "post_update_password",
        "tags": [
          "users"
        ]
      }
    },
    "/users/verify/{token}": {
      "parameters": [
        {
          "name": "token",
          "in": "path",
          "required": true,
          "type": "string"
        }
      ],
      "get": {
        "responses": {
          "200": {
            "description": "user details"
          }
        },
        "operationId": "get_verify",
        "tags": [
          "users"
        ]
      }
    }
  },
  "info": {
    "title": "Alvin API",
    "version": "1.0",
    "description": "Spending Behaviour App"
  },
  "produces": [
    "application/json"
  ],
  "consumes": [
    "application/json"
  ],
  "securityDefinitions": {
    "Bearer Auth": {
      "type": "apiKey",
      "in": "header",
      "name": "Authorization"
    }
  },
  "security": [
    {
      "Bearer Auth": [
        
      ]
    }
  ],
  "tags": [
    {
      "name": "token",
      "description": "token operations"
    },
    {
      "name": "users",
      "description": "users operations"
    },
    {
      "name": "smses",
      "description": "sms operations"
    },
    {
      "name": "transactions",
      "description": "transaction operations"
    },
    {
      "name": "goals",
      "description": "goal operations"
    },
    {
      "name": "categories",
      "description": "categories operations"
    },
    {
      "name": "accounts",
      "description": "accounts operations"
    },
    {
      "name": "preferences",
      "description": "preferences operations"
    },
    {
      "name": "graphs",
      "description": "graphing data"
    },
    {
      "name": "contact-us",
      "description": "send bug reports and requests to alvin"
    },
    {
      "name": "merchants",
      "description": "merchants operations"
    },
    {
      "name": "health",
      "description": "ping endpoint"
    },
    {
      "name": "micro-goals",
      "description": "micro goal operations"
    },
    {
      "name": "mono",
      "description": "mono operations"
    },
    {
      "name": "organizations",
      "description": "organizations operations"
    },
    {
      "name": "terms_and_conditions",
      "description": "terms_and_conditions operations"
    },
    {
      "name": "simulate",
      "description": "simulate network operations"
    },
    {
      "name": "simulate_",
      "description": "simulate savings operations"
    }
  ],
  "definitions": {
    "OAuth Token": {
      "required": [
        "token"
      ],
      "properties": {
        "provider_id": {
          "type": "string",
          "description": "oauth token provider",
          "default": "google.com"
        },
        "token": {
          "type": "string",
          "description": "oauth authentication token"
        }
      },
      "type": "object"
    },
    "FCM Auth Token": {
      "required": [
        "token"
      ],
      "properties": {
        "token": {
          "type": "string",
          "description": "firebase cloud messaging authentication token"
        }
      },
      "type": "object"
    },
    "User": {
      "required": [
        "email",
        "first_name",
        "password"
      ],
      "properties": {
        "first_name": {
          "type": "string",
          "description": "user first name"
        },
        "last_name": {
          "type": [
            "string",
            "null"
          ],
          "description": "user last name",
          "example": "nullable string"
        },
        "email": {
          "type": "string",
          "description": "user work email"
        },
        "password": {
          "type": "string",
          "description": "user password"
        },
        "company": {
          "type": [
            "string",
            "null"
          ],
          "description": "user company",
          "example": "nullable string"
        },
        "country": {
          "type": [
            "string",
            "null"
          ],
          "description": "user country",
          "example": "nullable string"
        },
        "type": {
          "type": "string",
          "description": "company type"
        },
        "role": {
          "type": "string",
          "description": "user role"
        }
      },
      "type": "object"
    },
    "Onboarded": {
      "required": [
        "at"
      ],
      "properties": {
        "at": {
          "type": "string",
          "description": "ISO 8601 date time"
        }
      },
      "type": "object"
    },
    "Household": {
      "required": [
        "no"
      ],
      "properties": {
        "no": {
          "type": "integer",
          "description": "user size of family"
        }
      },
      "type": "object"
    },
    "Income": {
      "required": [
        "amount"
      ],
      "properties": {
        "amount": {
          "type": "integer",
          "description": "user size of family"
        }
      },
      "type": "object"
    },
    "Sms": {
      "required": [
        "phone",
        "time_received"
      ],
      "properties": {
        "phone": {
          "type": "string",
          "description": "phone that sent the sms",
          "default": "MPESA"
        },
        "message": {
          "type": "string",
          "description": "content of the sms",
          "default": ""
        },
        "extern_id": {
          "type": "string",
          "description": "an identifier that has meaning to the client",
          "default": 0
        },
        "time_received": {
          "type": "string",
          "description": "ISO 8601 timestamp of when the sms was received on the phone",
          "default": 0
        },
        "fcm_token": {
          "type": "string",
          "description": "Firebase cloud messaging token",
          "default": ""
        }
      },
      "type": "object"
    },
    "Transaction": {
      "required": [
        "amount",
        "merchant_id",
        "transacted_at"
      ],
      "properties": {
        "amount": {
          "type": "number",
          "description": "the value of the transaction"
        },
        "transacted_at": {
          "type": "string",
          "description": "ISO 8601 date time, the time of the transaction"
        },
        "extern_id": {
          "type": "string",
          "description": "User identifiable information such as receipt no e.tc"
        },
        "merchant_id": {
          "type": "integer",
          "description": "the merchant of the transaction"
        }
      },
      "type": "object"
    },
    "Categorize": {
      "properties": {
        "micro_id": {
          "type": "integer",
          "description": "the micro the transaction belongs to"
        },
        "category_id": {
          "type": "integer",
          "description": "the category the transaction belongs to"
        },
        "create_micro_goal": {
          "type": "boolean",
          "description": "if true a micro goal is created",
          "default": false
        }
      },
      "type": "object"
    },
    "Goal": {
      "required": [
        "amount",
        "extern_id"
      ],
      "properties": {
        "extern_id": {
          "type": "string",
          "description": "goal extern identifier, useful to the client"
        },
        "name": {
          "type": "string",
          "description": "name of the goal"
        },
        "title": {
          "type": "string",
          "description": "title that would displayable on the goal"
        },
        "amount": {
          "type": "number",
          "description": "the amount of the goal"
        },
        "contribute_from": {
          "type": "string",
          "description": "ISO 8601 date goal contributions can start"
        },
        "is_customized": {
          "type": "boolean",
          "description": "indicates if amount is not app predefined",
          "default": false
        }
      },
      "type": "object"
    },
    "MacroGoal": {
      "required": [
        "amount",
        "percentage",
        "share",
        "type_name"
      ],
      "properties": {
        "name": {
          "type": "string",
          "description": "name of the macro goal"
        },
        "type_name": {
          "type": "string",
          "description": "type name of the macro goal"
        },
        "amount": {
          "type": "number",
          "description": "amount of the macro"
        },
        "percentage": {
          "type": "number",
          "description": "the percentage of the goal monthly income"
        },
        "share": {
          "type": "number",
          "description": "macro share"
        },
        "reset_micros": {
          "type": "boolean",
          "description": "true allows the removal of all micros",
          "default": false
        }
      },
      "type": "object"
    },
    "MicroGoal": {
      "required": [
        "amount",
        "category_id",
        "name",
        "percentage"
      ],
      "properties": {
        "amount": {
          "type": "number",
          "description": "micro goal value"
        },
        "contribution_amount": {
          "type": "number",
          "description": "micro goal contribution value, only relevant to savings"
        },
        "percentage": {
          "type": "number",
          "description": "the percentage of the goal monthly income"
        },
        "category_id": {
          "type": "integer",
          "description": "category the micro belongs to"
        },
        "name": {
          "type": "string",
          "description": "name given to the micro"
        },
        "pseudo_name": {
          "type": "string",
          "description": "pseudo name given to the micro"
        },
        "extern_id": {
          "type": "integer",
          "description": "an external id that has meaning to the client"
        },
        "order": {
          "type": "integer",
          "description": "order number of the micro goal",
          "default": 0
        },
        "contribution_at": {
          "type": [
            "string",
            "null"
          ],
          "format": "date-time",
          "description": "when to contribute",
          "example": "nullable datetime"
        },
        "is_contribute_customized": {
          "type": "boolean",
          "description": "indicates whether the amount contributed is from recommended values or a user specified value",
          "default": false
        }
      },
      "type": "object"
    },
    "Category": {
      "required": [
        "extern_id",
        "macro_name",
        "name"
      ],
      "properties": {
        "extern_id": {
          "type": "string",
          "description": "category extern identifier, useful to the client"
        },
        "macro_name": {
          "type": "string",
          "description": "category macro type name"
        },
        "name": {
          "type": "string",
          "description": "name of the category"
        },
        "icon": {
          "type": "string",
          "description": "name of the icon for the category"
        }
      },
      "type": "object"
    },
    "Alert": {
      "properties": {
        "on_threshhold": {
          "type": "boolean",
          "description": "alert on thresh hold being hit",
          "default": false
        },
        "on_all_transactions": {
          "type": "boolean",
          "description": "alert on all transactions",
          "default": true
        },
        "on_transactions_at": {
          "type": "string",
          "description": "ISO 8601 datetime, time when the alert should be sent"
        },
        "emails": {
          "type": "boolean",
          "description": "alert on emails",
          "default": false
        }
      },
      "type": "object"
    },
    "SavingsPreference": {
      "properties": {
        "track_wants_expense": {
          "type": "boolean",
          "description": "indicates if total wants expenses should be tracked",
          "default": false
        },
        "track_essential_expense": {
          "type": "boolean",
          "description": "indicates if total wants expenses should be tracked",
          "default": false
        }
      },
      "type": "object"
    },
    "ContactUs": {
      "required": [
        "body",
        "subject"
      ],
      "properties": {
        "subject": {
          "type": "string",
          "description": "title of the message",
          "default": "Hi Alvin"
        },
        "body": {
          "type": "string",
          "description": "body of the message",
          "default": ""
        }
      },
      "type": "object"
    },
    "Merchant": {
      "required": [
        "name"
      ],
      "properties": {
        "name": {
          "type": "string",
          "description": "the name of the merchant"
        }
      },
      "type": "object"
    },
    "MicroGoalSetting": {
      "required": [
        "amount"
      ],
      "properties": {
        "amount": {
          "type": "number",
          "description": "the amount to contribute"
        },
        "contribution_at": {
          "type": [
            "string",
            "null"
          ],
          "format": "date-time",
          "description": "when to contribute",
          "example": "nullable datetime"
        },
        "resume_at": {
          "type": [
            "string",
            "null"
          ],
          "format": "date-time",
          "description": "when to next resume contribution",
          "example": "nullable datetime"
        },
        "is_contribution_customized": {
          "type": "boolean",
          "description": "is the goal contribution amount customized",
          "default": false
        }
      },
      "type": "object"
    },
    "ExternalLinkedAccount": {
      "properties": {
        "account_id": {
          "type": "string",
          "description": "account id"
        }
      },
      "type": "object"
    },
    "Organization": {
      "required": [
        "name"
      ],
      "properties": {
        "name": {
          "type": "string",
          "description": "organization name"
        },
        "type": {
          "type": "string",
          "description": "organization type"
        },
        "api_key": {
          "type": [
            "string",
            "null"
          ],
          "description": "organization api key",
          "example": "nullable string"
        },
        "sdk_key": {
          "type": [
            "string",
            "null"
          ],
          "description": "organization sdk key",
          "example": "nullable string"
        }
      },
      "type": "object"
    },
    "Ledger": {
      "properties": {
        "month": {
          "type": "integer",
          "description": "number of transactions to simulate",
          "default": 1
        },
        "activate": {
          "type": "boolean",
          "description": "activate the created ledger as the active ledger",
          "default": false
        }
      },
      "type": "object"
    },
    "Simulate": {
      "properties": {
        "amount": {
          "type": "number",
          "description": "transaction value",
          "default": 0
        },
        "count": {
          "type": "integer",
          "description": "number of transactions to simulate",
          "default": 1
        },
        "micro_goal_id": {
          "type": "integer",
          "description": "micro goal to assign to, its ignored for multiple transactions",
          "default": 0
        },
        "merchant_id": {
          "type": "integer",
          "description": "merchant id assign a transactions",
          "default": 0
        }
      },
      "type": "object"
    }
  },
  "responses": {
    "ParseError": {
      "description": "When a mask can't be parsed"
    },
    "MaskError": {
      "description": "When any error occurs on mask"
    }
  }
}
```

## Summary

This is a summary of the API. It is generated from the API definition.

### Authentication

The API is authenticated using a token. The token is passed in the `Authorization` header.

### Errors

The API uses the following error codes:

  * `400` - Bad Request
  * `401` - Unauthorized
  * `403` - Forbidden
  * `404` - Not Found
  * `422` - Unprocessable Entity
  * `500` - Internal Server Error

### Pagination

The API uses pagination. The `page` and `per_page` query parameters are used to control pagination. The `page` parameter is the page number, and the `per_page` parameter is the number of items per page. The `per_page` parameter can be between 1 and 100. The `page` parameter can be between 1 and 1000.

### Content Type

The API uses the `application/json` content type.

### API Versioning

The API uses versioning. The version is specified in the URL. The current version is `v1`.
