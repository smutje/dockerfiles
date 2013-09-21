FROM ubuntu:precise
RUN apt-get update
RUN apt-get upgrade
RUN apt-get install --yes ruby1.9.1 ruby1.9.1-dev build-essential curl
RUN gem install bundler fpm-cookery --no-rdoc --no-ri
