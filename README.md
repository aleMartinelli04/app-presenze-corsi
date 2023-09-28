## Presenziapp

This is an app to manage school courses and students who joined them over the years, all in a single place.

The project is divided into 2 parts: a web server and a rest api

- The **web server** is developed with typescript and React/Remix with Mantine
- The **rest api** runs using docker, and it is composed by two containers: one for the api itself, which is developed with typescript and express js, and the other for a postgres database. I used Prisma ORM to connect to this db

The result is an extremely flexible app, which can be accessed from any device!
