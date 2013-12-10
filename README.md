Helloworld-Jekyll
=================

A base jekyll blog for deploying to Heroku.

## Deploy to Heroku

    heroku create --buildpack git://github.com/bacongobbler/heroku-buildpack-jekyll.git
    git push heroku master

## Deploy to Stackato

    git checkout stackato
    stackato push -n
