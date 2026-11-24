# Symfony Practice Project

A Symfony application skeleton with Docker Compose for its services, used to
work through the framework's structure.

## What is here

- Symfony 6 skeleton — kernel, bundle configuration, routing
- Doctrine ORM with migrations
- Twig templating
- Symfony Security, Forms, Validator, Mailer and Messenger wired in
- Docker Compose for PostgreSQL

## Running locally

```bash
composer install
docker compose up -d
symfony server:start
```

## Configuration

Following Symfony convention, `.env` is committed and holds non-secret
defaults only. Real credentials belong in `.env.local`, which is not committed.
