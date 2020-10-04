# README

# Quickstart: Compose and Rails: https://docs.docker.com/compose/rails/

# Define the project

# Steps

$ mkdir projectdocker

$ cd projectdocker

Create Dockerfile

$ touch Gemfile

Create Gemfile.lock

$ touch Gemfile.lock

Next, provide an entrypoint script to fix a Rails-specific issue that prevents the server from restarting when a certain server.pid file pre-exists. This script will be executed every time the container gets started.

$ touch entrypoint.sh

Finally, docker-compose.yml is where the magic happens..

$ docker-compose.yml

..
