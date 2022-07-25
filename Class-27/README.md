# Class-27
## I’ve reviewed the following topic:

-  Using models in django

Django web applications access and manage data through Python objects referred to as models. Models define the structure of stored data, including the field types and possibly also their maximum size, default values, selection list options, help text for documentation, label text for forms, etc. The definition of the model is independent of the underlying database — you can choose one of several as part of your project settings. Once you've chosen what database you want to use, you don't need to talk to it directly at all — you just write your model structure and other code, and Django handles all the dirty work of communicating with the database for you.

- Django admin site

The Django admin gives you a full featured management site of all the models (Database objects) and other plugins you can add. It does not require any effort and is an out of the box feature with django. Pls notice that when used in production, the best practice is to create the admin site as a different site, not accessible to the whole web, to ensure that this great power does not leak or cause security flaws.
