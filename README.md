# README

MySQL is a widely used, open-source relational database management system

⚠️ This project is no longer maintained. ⚠️

## Installation

```sh
# Define installation folder

export INSTALL_DIRECTORY=/usr/bin

# Use local installation

sudo bin/installer install

# Use remote installation

curl --location "https://gitlab.com/timonier/mysql/raw/master/bin/installer" | sudo sh -s -- install
```

__Note 1__: If you do not define `INSTALL_DIRECTORY`, `installer` will use in `/usr/local/bin`.

__Note 2__: `docker-for-mac` users have to configure [native NFS server](https://medium.com/@sean.handley/how-to-set-up-docker-for-mac-with-native-nfs-145151458adc).

## Usage

Run the command `mysql`:

```sh
# See all mysql options

mysql --help

# Run mysql

mysql -h mysql-morgan.docker -u root
```

## Links

* [image "timonier/mysql"](https://hub.docker.com/r/timonier/mysql/)
* [mysql](https://www.mysql.com/)
* [set up docker for mac with native nfs](https://medium.com/@sean.handley/how-to-set-up-docker-for-mac-with-native-nfs-145151458adc)
