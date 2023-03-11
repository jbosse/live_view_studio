FROM elixir:1.14

RUN apt-get update && apt-get -y install inotify-tools
RUN mix local.hex --force
RUN mix local.rebar --force
