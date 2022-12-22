
## Background 

By default, when we make changes to our models, Django takes care of generating the necessary migration files for us. These files are usually created to work with multiple database backends like MySQL, PostgreSQL, and SQLite. However, this generic approach might not always give us the best way to change the database structure for our Postgres backend. To reduce migration-induced downtimes, it's 