# Data Center CLI
Development command line using docker for local databases.

### MYSQL

Command `./bin/mysql`
  - `./bin/mysql start`: start a MySQL(version 5.7) docker image.
  - `./bin/mysql stop`: stop the running MySQL docker image.
  - `.bin/mysql logs`: tailing the MySQL logs.
  - `./bin/mysql create $name_of_database`: create a database if not exist.
  - `./bin/mysql drop $name_of_database`: drop a database if exist.
  - `./bin/mysql raw $sql`: execute a raw sql directly to database.


### REDIS

Command `./bin/redis`
  - `./bin/mysql start`: start a Redis(version 5.0.8) docker image.
  - `./bin/mysql stop`: stop the running Redis docker image.
  - `.bin/mysql logs`: tailing the Redis logs.
