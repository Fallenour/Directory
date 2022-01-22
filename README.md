---
---
<div align="center">
  <a href="https://github.com/fallenour/directory#readme"></a><br>
  <img width="4000" src="https://images.freeimages.com/images/large-previews/0ad/pirate-flag-1307092.jpg" alt="Pirate logo">
</div>

# Project Directory
> A curated list of my projects. Maintained by <a rel="" href="https://github.com/fallenour">Logan Hicks</a>.

## Table of Contents

- [Django](#third-party-packages)
  - [Warehouse Management System](#Warehouse-Management-System)
  - [APIs](#apis)
  - [Async](#async)
  - [Caching](#caching)
  - [Commands](#commands)
  - [Configuration](#configuration)
  - [Content Management Systems](#content-management-systems)
  - [ECommerce](#ecommerce)
  - [Editors](#editors)
  - [Files/Images](#filesimages)
  - [Forms](#forms)
  - [Full-stack frameworks](#full-stack-frameworks)
  - [General](#general)
  - [Logging](#logging)
  - [Models](#models)
  - [Performance](#performance)
  - [Search](#search)
  - [Search engine optimisation](#search-engine-optimisation)
  - [Security](#security)
  - [Static Assets](#static-assets)
  - [Task Queues](#task-queues)
  - [Testing](#testing)
  - [URLs](#urls)
  - [Users](#users)
  - [Views](#views)
- [Javascript](#javascript)
- [Flask](#flask)
  - [Official Resources](#official-resources)
  - [Educational](#educational)
  - [Community](#community)
  - [Conferences](#conferences)
  - [Newsletters](#newsletters)
  - [Podcasts](#podcasts)
  - [Books](#books)
- [Hosted Projects](#hosting)
  - [PaaS (Platforms-as-a-Service)](#paas-platforms-as-a-service)
  - [IaaS (Infrastructure-as-a-Service)](#iaas-infrastructure-as-a-service)
- [Projects](#projects)
  - [Boilerplate](#boilerplate)
  - [Open Source Projects](#open-source-projects)
- [Django REST Framework](#django-rest-framework)
  - [DRF Resources](#drf-resources)
  - [DRF Tutorials](#drf-tutorials)
- [Wagtail](#wagtail)
  - [Wagtail Resources](#wagtail-resources)

### Warehouse-Management-System
- [Warehouse-Management-System](https://github.com/Fallenour/Warehouse-Management-System-Django) - Project Description

### Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis| |appveyor| |requires|
        | |coveralls| |codecov|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|

.. |docs| image:: https://readthedocs.org/projects/django-redisboard/badge/?style=flat
    :target: https://readthedocs.org/projects/django-redisboard
    :alt: Documentation Status


.. |travis| image:: https://travis-ci.org/ionelmc/django-redisboard.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/ionelmc/django-redisboard

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/ionelmc/django-redisboard?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/ionelmc/django-redisboard

.. |requires| image:: https://requires.io/github/ionelmc/django-redisboard/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/ionelmc/django-redisboard/requirements/?branch=master

.. |coveralls| image:: https://coveralls.io/repos/ionelmc/django-redisboard/badge.svg?branch=master&service=github
    :alt: Coverage Status
    :target: https://coveralls.io/r/ionelmc/django-redisboard

.. |codecov| image:: https://codecov.io/github/ionelmc/django-redisboard/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/ionelmc/django-redisboard

.. |version| image:: https://img.shields.io/pypi/v/django-redisboard.svg
    :alt: PyPI Package latest release
    :target: https://pypi.python.org/pypi/django-redisboard

.. |commits-since| image:: https://img.shields.io/github/commits-since/ionelmc/django-redisboard/v4.0.0.svg
    :alt: Commits since latest release
    :target: https://github.com/ionelmc/django-redisboard/compare/v4.0.0...master

.. |wheel| image:: https://img.shields.io/pypi/wheel/django-redisboard.svg
    :alt: PyPI Wheel
    :target: https://pypi.python.org/pypi/django-redisboard

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/django-redisboard.svg
    :alt: Supported versions
    :target: https://pypi.python.org/pypi/django-redisboard

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/django-redisboard.svg
    :alt: Supported implementations
    :target: https://pypi.python.org/pypi/django-redisboard


.. end-badges

Redis monitoring and inspection drop-in application using django admin.

* Free software: BSD 2-Clause License


* Sever statistics in the admin changelist
* Key summary in the inspect view
* Value introspection with pagination for lists and sorted sets



:OS: Any
:Runtime: Python 2.7, 3.4, 3.4 or PyPy
:Services: Redis 2.2 or later.
:Packages: Django>=1.8, py-redis>=2.10.0
