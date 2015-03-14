# dokku-rails-logs

dokku-rails-logs is a plugin for [dokku][dokku] that prints the logs of your Rails app.

## Installation

```sh
$ sudo git clone https://github.com/Flink/dokku-rails-logs.git /var/lib/dokku/plugins/rails-logs
```

## Commands

```
$ dokku help
    rails:logs <app> [-t]                           Display rails logs of provided app
```

## Usage

Display rails logs of my-app
```
# dokku rails:logs my-app            # Server side
$ ssh dokku@server rails:logs my-app # Client side
```

Display rails logs of my-app continually
```
# dokku rails:logs my-app -t            # Server side
$ ssh dokku@server rails:logs my-app -t # Client side
```

## License

This plugin is released under the MIT license. See the file [LICENSE](LICENSE).

[dokku]: https://github.com/progrium/dokku
