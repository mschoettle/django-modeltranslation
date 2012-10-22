================
Modeltranslation
================

The modeltranslation application can be used to translate dynamic content of
existing Django models to an arbitrary number of languages without having to
change the original model classes. It uses a registration approach (comparable
to Django's admin app) to be able to add translations to existing or new
projects and is fully integrated into the Django admin backend.

The advantage of a registration approach is the ability to add translations to
models on a per-app basis. You can use the same app in different projects,
may they use translations or not, and you never have to touch the original
model class.


Features
========

- Unlimited number of target languages
- Add translations without changing existing models
- Django admin support
- Supports inherited models


Project Home
------------
https://github.com/deschler/django-modeltranslation

Documentation
-------------
https://readthedocs.org/projects/django-modeltranslation

Mailing List
------------
http://groups.google.com/group/django-modeltranslation