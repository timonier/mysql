# README

MySQL is a widely used, open-source relational database management system

## Installation

Linux users can use the [installer](https://github.com/timonier/mysql/blob/master/bin/installer):

```sh
curl --location "https://github.com/timonier/mysql/raw/master/bin/installer" | sudo sh -s -- install
```

## Usage

Run the command `mysql`:

```sh
# See all mysql options

mysql --help

# Run mysql

mysql -h mysql-morgan.docker -u root
```

## Contributing

1. Fork it.
2. Create your branch: `git checkout -b my-new-feature`.
3. Commit your changes: `git commit -am 'Add some feature'`.
4. Push to the branch: `git push origin my-new-feature`.
5. Submit a pull request.

__Note__: Use the script `bin/build` to test your modifications locally.

## Links

* [image "timonier/mysql"](https://hub.docker.com/r/timonier/mysql/)
* [mysql](https://www.mysql.com/)
* [timonier/dumb-entrypoint](https://github.com/timonier/dumb-entrypoint)
