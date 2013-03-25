# Puppet-solo

Boilerplate and installer for puppet. It:

* ensures that puppet is executed as root
* locally builds ruby 1.9.3
* installs puppet executable
* passes correct `--modulepath` option

## Requirements

* Ubuntu or OSX
* Root access for Ubuntu
* `git` executable available

## Usage

* clone this repository
* change `manifests/site.pp`
* run `bin/puppet apply manifests/site.pp`

## License

This project is MIT-licensed.
