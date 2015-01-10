This is an open source project

Set up Git:

'bower install' to install front end dependencies

`gulp` to make dist

`gulp serve` to run 

Postgres Commands:
Run:
postgres -D [path to db]

List table
\dt

Select:
select * from "Users"

Console:
psql [db name]

Migrations:
sequalize migration:create --name [name}

run migration (Need sequalize cli):
sequalize db:migrate
sequalize db:migrate:undo
