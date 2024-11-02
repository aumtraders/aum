# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

- Ruby version

- System dependencies

- Configuration

- Database creation

- Database initialization

- How to run the test suite

- Services (job queues, cache servers, search engines, etc.)

- Deployment instructions

- ...
  run `rails server` to start the server on localhost, shortcut for `rails server -b 0.0.0.0 -p 3000` even shorter run `rails s`
  run `rails db:migrate` to create the database
  run `rails db:seed` to create the default user
  run `rails db:reset` to create the database and seed the default user
  run `rails db:rollback` to rollback the database
  run `rails db:migrate:redo` to rollback and migrate the database
  run `rails db:migrate:up` to migrate the database
  run `rails db:migrate:down` to rollback the database
  run `rails db:migrate:status` to check the status of the database migrations
  run `rails db:schema:load` to load the schema into the database
  run `rails db:schema:dump` to dump the schema to the database
  run `rails db:schema:cache:clear` to clear the schema cache
  run `rails db:schema:cache:dump` to dump the schema cache
  run `rails db:schema:cache:load` to load the schema cache
  run `rails db:test:prepare` to prepare the test database
  run `rails db:create` to create the database
  run `rails db:drop` to drop the database
  run `rails db:environment:set` to set the environment
  run `rails db:fixtures:load` to load the fixtures
  run `rails db:migrate:reset` to reset the database

run `rails server -b 0.0.0.0` to start the server on all interfaces
run `rails server -p 3000` to start the server on port 3000
run `rails server -e development` to start the server in development mode
run `rails server -e production` to start the server in production mode
