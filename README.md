# python-web-bazel-flask-mvc-postgres-simple

## Description
Creates a datatable of `dog` for a flask project.

If path is not found, will default to 404 error.

## Tech stack
- bazel
- python
  - flask
  - sqlalchemy
- bootstrap
- jquery
- dataTable

## Docker stack
- l.gcr.io/google/bazel:latest
- postgresql

## To run
`sudo ./install.sh -u`
- [web-bazel app](http://localhost)

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- https://stackabuse.com/using-sqlalchemy-with-flask-and-postgresql/
