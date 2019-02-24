=============================
Django helm cookiecutter
=============================

A Cookiecutter template for creating helm templates for django.

Quickstart
----------

Install cookiecutter:

.. code-block:: bash

    $ pip install "cookiecutter>=1.4.0"

Now run it against this repo:

.. code-block:: bash

    $ cookiecutter https://github.com/pydanny/django-helm-cookiecutter

Answer the prompts with your own desired options. For example:

.. code-block:: python

    chart_name [My Awesome Chart]:
    chart_slug [my_awesome_chart]:
    chart_directory_name [chart]:
    version [0.1.0]:
    image_url [gitlab.example.com/group/project]:
    project_url [https://example.com]:
    DATABASE_URL [postges:///my_awesome_chart]:

TODO
--------

* Celery
* Postgres

