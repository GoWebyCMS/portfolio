=====
Portfolio Plugin
=====

Portfolio is a simple Django app/plugin to handle Works and details for a proper portfolio
Demonstration.

Detailed documentation is in the "docs" directory.

Quick start
-----------
## Use it as a Django third party application
1. Add "gallery" to your INSTALLED_APPS setting like this::

    INSTALLED_APPS = [
        ...
        'portfolio',
    ]

2. Include the gallery URLconf in your project urls.py like this::

    url(r'^works/', include('portfolio.urls')),

3. Run `python manage.py migrate gallery` to create the polls models.

4. Start the development server and visit http://127.0.0.1:8000/admin/
   to create a portfolio list (you'll need the Admin app enabled).

5. Visit http://127.0.0.1:8000/works/ to vie the list of galleries you just created.

## Use it as a Django CMS plugin
TODO: Complete instructions

pip install --upgrade git+http://git@github.com/GoWebyCMS/portfolio.git