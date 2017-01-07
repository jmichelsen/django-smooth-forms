=============================
Django Smooth Forms
=============================

.. image:: https://badge.fury.io/py/django_smooth_forms.png
    :target: https://badge.fury.io/py/django_smooth_forms

.. image:: https://travis-ci.org/jmichelsen/django_smooth_forms.png?branch=master
    :target: https://travis-ci.org/jmichelsen/django_smooth_forms

Smooth out the process of creating reusable a _nice_ django form templates

Documentation
-------------

The full documentation is at https://django_smooth_forms.readthedocs.io.

Quickstart
----------

Install Django Smooth Forms::

    pip install django_smooth_forms

Add it to your `INSTALLED_APPS`:

.. code-block:: python

    INSTALLED_APPS = (
        ...
        'django_smooth_forms.apps.DjangoSmoothFormsConfig',
        ...
    )

Add Django Smooth Forms's URL patterns:

.. code-block:: python

    from django_smooth_forms import urls as django_smooth_forms_urls


    urlpatterns = [
        ...
        url(r'^', include(django_smooth_forms_urls)),
        ...
    ]

Features
--------

* TODO

Running Tests
-------------

Does the code actually work?

::

    source <YOURVIRTUALENV>/bin/activate
    (myenv) $ pip install tox
    (myenv) $ tox

Credits
-------

Tools used in rendering this package:

*  Cookiecutter_
*  `cookiecutter-djangopackage`_

.. _Cookiecutter: https://github.com/audreyr/cookiecutter
.. _`cookiecutter-djangopackage`: https://github.com/pydanny/cookiecutter-djangopackage
