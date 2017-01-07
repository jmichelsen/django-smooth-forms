=====
Usage
=====

To use Django Smooth Forms in a project, add it to your `INSTALLED_APPS`:

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
