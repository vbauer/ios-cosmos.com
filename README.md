
## Contributing

If you want to make this world a little bit better you can:

- Fork this repository
- Add some new interesting projects or fix mistakes.
  Modify file:
    - **projects/free.yml** - for free projects
    - or **projects/paid.yml** - for paid projects
- Send back a pull request

**NB:** Please, check your indentations in text to prevent possible problems with YAML parser.


## Running server locally

To install needed dependencies, run this commands in the project directory:
```sh
rvm use 2.4.3
bundle install
```

To check your changes in life, you can run server locally using the following command:

```sh
bundle exec rackup -p 8080 config.ru
```

Server should be available on [http://localhost:8080](http://localhost:8080/).
