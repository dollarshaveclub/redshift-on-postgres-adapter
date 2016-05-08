# redshift-on-postgres-adapter

In Rails 5 the PostgreSQL database adapter is built in. This gem tries to use that as a base and modify just enough things to talk to Amazon Redshift.

### Tested
* Table loading
* Adding, removing records
* Drop tables
* Migrations

### TODO
* Column encoding support.
* DISTKEY and SORTKEY
* Schema dumping with .rb with correct encoding and key signature.