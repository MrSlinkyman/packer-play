# Starting out with Packer.

Trying out different variations with the ability to create arbitrary VMs with Desktop Managers installed.

## Research so far

Links:

- [Packer information on creating images from VirtualBox Exports](http://www.packer.io/docs/builders/virtualbox-ovf.html)
- [Installing Oracle JVM](http://docs.oracle.com/javase/7/docs/webnotes/install/linux/linux-jdk.html)
- [Installing Eclipse for Linux](http://wiki.eclipse.org/Eclipse/Installation)

Process

- Created the json file for packer
  - It has trouble trying to SSH into the box, times out, not sure why
- Created the OVA export from VirtuablBox
  - Based on CentOS
  - Has Guest Additions installed
  - Not much else

## Dependencies

- Packer version 0.6.0
- VirtualBox version 4.3.12-93733
- CentOS 6.5 64bit LiveDVD
- Vagrant 1.4.3

## Other Research

- [Testing the configuration](http://www.morethanseven.net/2014/01/01/testing-packer-created-images-with-serverspec/)
