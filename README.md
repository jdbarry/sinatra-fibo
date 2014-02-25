# Simple Sinatra application

This is a simple Sinatra Ruby application copied from Cloud Foundry's README.

## Local development

    sudo gem install bundler
    bundle install
    ruby fibo.rb

## Deploying to Stackato

    sudo gem install bundler
    bundle install  # creates the required Gemfile.lock file
    stackato push -n
