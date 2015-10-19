#Rails Caching Presentation
=======

A presentation on how rails caching works.

##Installation
###An installation guide on working with the caching project.

###Clone the GIT repository
```
    git clone git@github.com:thisisbd/Rails-Caching-Presentation.git
    cd Rails-Caching-Presentation
```

###Install the dependencies
For development, setup the database.
```
    brew update
    brew install mysql
    bundle install
    bundle exec rake db:create db:migrate
```

As caching only works in production mode we also need to setup the production database.
```
    RAILS_ENV=production bundle exec rake db:create db:migrate
```

To launch the application we will start in production mode.
```
    RAILS_ENV=production bundle exec rails s
```

You should now be able to see a local version of the project at http://localhost:3000


###Viewing the presentation
There is a powerpoint presentation inside the repository called 'Rails-Caching-Presentation.pptx'.
This contains information about rails caching: explanations and examples using the project.