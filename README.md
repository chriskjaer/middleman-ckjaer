# Protostorm!
Middleman Protostorm is a way to quickly create prototypes for websites. It's using Sass as the CSS preprocessor which includes Compass along with SUSY. It's using Bower for JS package management.

Middleman Protostorm is using the Sassy Protostorm Boilerplate. Sassy Protostorm is not a framework, but a way to structure your Sass. It draws inspiration from various sources, like [BEM](http://bem.info/), [SMACCS](http://smacss.com/) and general OOCSS.


------

### Getting started

    $ git clone git@github.com:chriskjaer/middleman-protostorm.git projectname && cd projectname

    $ bundle install

    $ bower update

    $ middleman

..and you should be up and running on http://0.0.0.0:4567

### Pushing to Heroku

    $ heroku create projectname && git push heroku master