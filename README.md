# pushover-cli

## Configuration

Copy `pushoverrc.example` to `/etc/pushoverrc` for a global configuration
```
cp pushoverrc.exampe /etc/pushoverrc
```

or into your home directory `~/.pushoverrc`
```
cp pushoverrc.example ~/.pushoverrc
```

Configure your application token and user key inside the configuration file.

**NOTE:** The user specific configuration has a higher priority than the global
configuration.

## Usage

```
pushover [MESSAGE]
```

## License
Copyright (c) 2015 Florian Goße. Licensed under the MIT license.
