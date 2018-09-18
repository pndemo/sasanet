# Project

Sasanet is a simple microblogging application. Users are required to register to use the service and they can post
messages of up to 140 characters.

## Install

### Clone the repository

```shell
git clone https://github.com/pndemo/sasanet.git
cd sasanet
```

### Check your Ruby version

```shell
ruby -v
```

The ouput should start with something like `ruby 2.5.0`

If not, install the right ruby version using [rbenv](https://github.com/rbenv/rbenv) (it could take a while):

```shell
rbenv install 2.5.0
```

### Install dependencies

Using [Bundler](https://github.com/bundler/bundler):

```shell
bundle install
```

### Initialize the database

```shell
rails db:create db:migrate db:seed
```

## Serve

```shell
rails s
```
