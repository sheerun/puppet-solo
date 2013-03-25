# Puppet-solo

Zero-config puppet executable for OS X and Ubuntu. It:

* doesn't require root access
* locally builds ruby 1.9.3
* installs puppet executable
* passes correct `--modulepath` option to puppet

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
