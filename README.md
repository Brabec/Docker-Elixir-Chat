# Elixir-Chat


Steps to get started:

- Assuming that you have docker and docker-compose installed on your machine, run the following instructions

    $ docker-compose build # in order to build the docker image
    $ alias mix="docker-compose run --rm phoenix mix" # If you already have elixir installed locally you can skip this command
    $ mix ecto.create # initializes the database with Ecto
    $ mix ecto.migrate # runs database migrations
    $ docker-compose up # to start the application


Reference guide to dockerize this repo on:

[Use Docker to create an Elixir/Phoenix development environment](https://medium.com/swlh/use-docker-to-create-an-elixir-phoenix-development-environment-e1a81def1d2e)

Reference guide to build the chat app on:

[Phoenix Chat Example](https://github.com/dwyl/phoenix-chat-example)