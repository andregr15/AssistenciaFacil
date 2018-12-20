# Assitência Fácil

Application designed manage an technical assistance.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

You must have docker and docker-compose installed

```
For more information, please see https://docs.docker.com/install/ 
```

### Installing

Access the project folder in your terminal enter the following

```
$ docker-compose build
```

```
$ docker-compose run --rm app bundle install
```

```
$ docker-compose run --rm app bundle exec rails db:create
```

```
$ docker-compose run --rm app bundle exec rails db:migrate
```

After that for test the installation enter the following to up the server

```
$ docker-compose up
```

Open your browser and access localhost:3000 to see the home page

## Running the tests

To run the tests run the following in your terminal

```
$ docker-compose run --rm app bundle exec rspec
```

## Built With

* [Ruby on Rails](https://rubyonrails.org/) - The web framework used
* [Devise](https://github.com/plataformatec/devise) - Authentication solution for Rails based on Warden
* [RSpec-rails](https://github.com/rspec/rspec-rails) - Testing framework for Rails 
* [FFaker](https://github.com/ffaker/ffaker) - Used to easily generate fake data
* [Materialize](https://github.com/mkhairi/materialize-sass) - The css framework used
* [PostgreSQL](https://www.postgresql.org/) - SGDB

## Authors

* **André Gonçalves Rodrigues** - *Initial work* - [andregr15](https://github.com/andregr15)
* **Breno Santos e Alves** - [losnol](https://github.com/losnol)


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc
