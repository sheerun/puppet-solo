[![Build Status](https://secure.travis-ci.org/sheerun/puppet-solo.png?branch=master)](http://travis-ci.org/sheerun/puppet-solo)

# Puppet-solo

## Usage

```
bin/puppet apply manifests/site.pp
```

## Features

* auto installs ruby locally if not present (no `sudo` required)
* passes correct `--modulepath` to puppet
* works on both Mac and Linux (tested on Ubuntu)

## Available binaries

* `bin/puppet` - main executable, you are probably interested in `puppet apply`
* `bin/facter` - library for retrieving simple operating system facts
* `bin/hiera` - hierarhical key/value lookup tool for configuration data

## License

This project is MIT-licensed. You are awesome.
