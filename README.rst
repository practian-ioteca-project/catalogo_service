########################################
Resource server 3: Catalogo Service
########################################

.. class:: no-web

    Catalogo Service es una app  ``Resource server`` construida sobre `Django`_ y define un modelo de *autenticación/autorización* para **aplicaciones SaaS** para los proyectos de `Django`_.




.. contents::

.. section-numbering::

.. raw:: pdf

   PageBreak oneColumn


============
Installation
============

(ve_...) D:\practian o XXX\catalogo_service>pip install -r requirements.txt

Descargar la distribución de https://github.com/practian-reapps


(ve_...) D:\practian o XXX\catalogo_service>pip install https://github.com/practian-reapps/django-backend-utils/raw/master/dist/django-backend-utils-0.1.zip

(ve_...) D:\practian o XXX\catalogo_service>pip install https://github.com/practian-reapps/django-oauth2-backend/raw/master/dist/django-oauth2-backend-0.1.zip

(ve_...) D:\practian o XXX\catalogo_service>manage.py migrate

(ve_...) D:\practian o XXX\catalogo_service>manage.py runserver 8003
Performing system checks...

System check identified no issues (0 silenced).
November 29, 2016 - 19:11:07
Django version 1.10.3, using settings 'catalogo_main.settings'
Starting development server at http://127.0.0.1:8003/
Quit the server with CTRL-BREAK.

// USER : admin
// PASSWORD : 12345

-------------------
Development version
-------------------

The **latest development version** can be installed directly from github_:

.. code-block:: bash
    
    # Universal
    $ pip install --upgrade https://github.com/practian-reapps/django-backend-utils/raw/master/dist/django-backend-utils-0.1.zip

or clone from github_:

.. code-block:: bash

    $ git clone https://github.com/practian-reapps/django-backend-utils.git

(If ``pip`` installation fails for some reason, you can try ``easy_install`` as a fallback.)


--------------
Python version
--------------

Python 3.4.4 is recommended to install Django backend_utils


=====
Usage
=====


Quick start
-----------

1. Add "backend_utils" to your INSTALLED_APPS setting like this::

    INSTALLED_APPS = [
        ...

        'backend_utils',
    ]



.. _Django OAuth Toolkit: https://django-oauth-toolkit.readthedocs.io
.. _Django: https://www.djangoproject.com
.. _github: https://github.com/practian-reapps/django-backend-utils







