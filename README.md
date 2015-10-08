# Kali 2.0 Packer Vagrant Box

A basic Packer definition for Kali Linux 2.0 to build a Vagrant box.

## Requirements

The following software must be installed/present on your local machine before you can use Packer to build the Vagrant box file:

  - [Packer](http://www.packer.io/)
  - [Vagrant](http://vagrantup.com/)
  - [VirtualBox](https://www.virtualbox.org/)

## Usage

    $ packer build template.json

### To point to a different apt mirror

	Copy the desired sources.list file to localised_source_list:

	$ packer build -var 'sources_list=australia' template.json

## License

GPLv3.

