# CKAN PostGIS

Ckan postgis is a specific component used by [CKAN](https://github.com/italia/ckan-it). PostGIS is a spatial database extender for PostgreSQL object-relational database. It adds support for geographic objects allowing location queries to be run in SQL.

> This repo is required by the [development version of CKAN-IT v2.8](https://github.com/italia/ckan-it/pull/45).

## Tools references

The tools referenced in this repository are

* [CKAN](https://ckan.org/)
* [PostGIS](https://postgis.net/)

## Project components

* **PostGIS** version 11, packaged for CKAN and with some customizations.

## How to build this version of PostGIS and test it as part of CKAN

This specific version of PostGIS is distributed and consumed in a form of Docker container.

The container can be built using the `Dockerfile` in the root of this repository.

Docker-compose is used to build a fully-functional test environment (build the CKAN container and download pre-packaged dependencies, including PostGIS).

Instructions can be found in the [CKAN repository](https://github.com/italia/ckan-it).

## How to contribute

Contributions are welcome. Feel free to open issues and submit a pull request at any time!
