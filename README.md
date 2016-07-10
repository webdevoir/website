# Personal Website

This is my personal website/blog built using Ruby on Rails. Go take a look, it's [live](http://kmon.me)! 🙂

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Installing

Install required gems:

```sh
bundle install
```

Migrate the database schema:

```sh
rake db:migrate
```

Start the server:

```sh
rails server
```

Now you're now up and running at `http://localhost:3000/`

### Creating users

Creating articles and projects requires a user login. In the rails console, create a new user:

```sh
User.create!(email: "you@example.com", password: "Rails4Life")
```

Sign in with your new user at: `http://localhost:3000/users/sign_in`

## Deployment

For simplicity and ease of use, I recommend hosting on Heroku (it's free!). Download the [Heroku Toolbelt](https://toolbelt.heroku.com/) and follow the getting started steps.

## Built With

* HTML/SCSS
* Ruby on Rails

## Versioning

This project uses [SemVer](http://semver.org/) for versioning. For all available versions, see the [tags on this repository](https://github.com/kanemontreuil/website/tags).

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
