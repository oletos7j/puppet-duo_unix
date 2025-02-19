# Changelog
## Release 2.1.1
* Fixed some code quality issues

## Release 2.1.0
* Added initial support for Rocky and Alma Linux
  * They will be using the RedHat version of Puppet, not CentOS

## Release 2.0.0
* Removed older unsupported versions of various operating systems
  * This is why this is version 2x
* Switched how OS code name is derived on debian based systems
* Added some more documentation to the example

## Release 1.0.11
* Updated PPA pgp key fingerprint
* Bumped version of PDK

## Release 1.0.10
* Removed `AllowTcpForwarding no` as this conflicts in environments where the requirement for `AllowTcpForwarding` needs to be `yes`.
* Updated pdk
* Updated Changelog
* Updated Metadata.json
* Removed vscode extension

## Release 1.0.9
* scorgatelli-docutech added conditional repo management and fixed some bugs

## Release 1.0.8
* Changed ssh service name to 'sshd' on RedHat based systems

## Release 1.0.7
* Parameterize displaying diff
* Updated Yum Repo key
* Fix groups usage

## Release 1.0.6

* Updated pdk
* Updated dependency upbound limit in metadata.json

## Release 1.0.5

* Fixed my fix for the config template

## Release 1.0.4

**Bugfixes**

* Fixed issue where `group` and `http_proxy` were always set in the config even when blank

## Release 0.1.0

**Features**

**Bugfixes**

**Known Issues**
