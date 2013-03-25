[![Build Status](https://secure.travis-ci.org/sheerun/puppet-solo.png?branch=master)](http://travis-ci.org/sheerun/puppet-solo)

# Puppet-solo

Zero-config puppet executable for OS X and Ubuntu. It:

* doesn't require root access
* locally builds ruby 1.9.3
* installs puppet executable
* passes correct `--modulepath` option to puppet

## Requirements

* `git` executable available

## Usage

* fork and clone this repository
* change `manifests/site.pp`
* run `bin/puppet apply manifests/site.pp`

## License

This project is MIT-licensed.
