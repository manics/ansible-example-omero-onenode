# OMERO Vagrant Box

`cd` into this directory, then:
```
rm -rf output-vagrant/
vagrant box remove centos/7
packer build vagrant.json
```
