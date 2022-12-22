
## Background 

Whenever we make changes to our models in Django, the framework automatically generates the necessary migration files for us. All we have to do is run `./manage.py makemigrations` and the files will be created for us. However, it's important to note that these files are generated in a generic manner, which means they may not always provide the most efficient strategy for updating the database structure of our Postgres backend. To reduce migration-induced downtimes, it may be necessary to review the generated files and make modifications. This document outlines a few techniques and provides resources to help us minimize migration downtimes. 

## 