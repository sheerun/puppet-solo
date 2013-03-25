[![Build Status](https://secure.travis-ci.org/sheerun/puppet-solo.png?branch=master)](http://travis-ci.org/sheerun/puppet-solo)

# Puppet-solo

Auto-installable puppet executables. They:

* dont't require root access
* locally build ruby 1.9.3
* passe correct `--modulepath` option to puppet

## Available binaries

* `puppet` - main executable, you are probably interested in `puppet apply`
* `facter` - library for retrieving simple operating system facts
* `hiera` - hierarhical key/value lookup tool for configuration data

## Requirements

* `git` executable available

## Usage

* fork and clone this repository
* change `manifests/site.pp`
* run `bin/puppet apply manifests/site.pp`

## License

This project is MIT-licensed.
