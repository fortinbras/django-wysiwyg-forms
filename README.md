# Django WYSIWYG Forms

*Note: this project is not production ready at this time. Stay tuned for
 updates.*

### Install:

    cd path/to/your/django/project
    git clone git://github.com/wwu-housing/django-wysiwyg-forms.git wysiwyg_forms

Add "wysiwyg_forms" to INSTALLED_APPS in settings.py.

Sync the database:

    ./manage.py syncdb

Include the urls:

    urlpatterns = patterns("",
        # ...
        (r"^wysiwyg_forms/", include("wysiwyg_forms.urls")),
        # ...
    )
