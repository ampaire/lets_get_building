# Sample

This is the sample application for
[*Ruby on Rails Tutorial:Learn Web Development with Rails*](https://www.railstutorial.org/)
by [Michael Hartl](http://www.michaelhartl.com/). It was created in Ruby on rails


## Prerequisite
Before starting you need to have prior knowledge on the following languages and tools

- [Ruby-v2.5.1](https://www.ruby-lang.org/en/documentation/)
- [Ruby on Rails-v6.0.1](https://guides.rubyonrails.org/)
- [Rspec](https://rspec.info/documentation/)
- Code editors like **Vscode** , **atom**


## Getting started

- To get started with the app, clone this repository and install the gems used by running:

```
$ bundle install --without production
```

- We then need to migrate our database, so we run:

```
$ rails db:migrate
```


## Useful commands

To start the server we run:

```
$ rails server
```
The results can be seen at the  [local Host Server](http://localhost:3000/)

We then put the different routes for the simple application:


                  root    | static_pages/home
                  --------|----------------------
                  Home    | static_pages/home
                  --------|----------------------
                  About   | static_pages/about
                  --------|----------------------
                  Contact | static_pages/contact
                  --------|----------------------
                  Help    | static_pages/help
                  --------|----------------------

To run our tests for the application we use:
```
$ rails test
```

## Resources


For more information, checkout these amazing Ruby on rails books and tutorials!
[Ruby on Rails](https://www.railstutorial.org/book).

[*Ruby on Rails Tutorial:Learn Web Development with Rails*](https://www.railstutorial.org/)

[Michael Hartl](http://www.michaelhartl.com/)



## Created by the amazing developer


[Phemia Ampaire](https://github.com/ampaire)