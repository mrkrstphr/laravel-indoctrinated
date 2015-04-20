# laravel-indoctrinated

> A Laravel 5 Provider for Doctrine ORM

**WARNING**: This repository is not production ready and not recommended for use. This was put together
as part of the example code for the book [Clean Architecture in PHP](https://leanpub.com/cleanphp). It is
underfeatured, undertested, and underdocumented.

This project simply wires up a basic Doctrine EntityManager for use in Laravel applications.

## Motivation

At the time of writing the book, all libraries for Laravel + Doctrine integration were either targeted
at Laravel 4, had broken requirements for Doctrine (specifically migrations), or only supported using
XML or Annotation mapping drivers (and not YAML).

So I wrote this tiny little implementation to satisfy the needs of the examples in the book.
