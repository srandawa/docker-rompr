# docker-rompr
RompR Docker image.

Built on Alpine and running Apache+PHP7.
This only includes RompR.
There is no built in database other than using the built-in SQLite, but connecting to a Mysql DB can be configured at startup.
For now, all the Apache defaults are used.

## Build

Run the normal:  
`docker build .`
