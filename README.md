# kcli repository

[![Build Status](https://travis-ci.org/karmab/kcli.svg?branch=master)](https://travis-ci.org/karmab/kcli)
[![Pypi](http://img.shields.io/pypi/v/kcli.svg)](https://pypi.python.org/pypi/kcli/)
[![Copr](https://copr.fedorainfracloud.org/coprs/karmab/kcli/package/kcli/status_image/last_build.png)](https://copr.fedorainfracloud.org/coprs/karmab/kcli/package/kcli)
[![](https://images.microbadger.com/badges/image/karmab/kcli.svg)](https://microbadger.com/images/karmab/kcli "Get your own image badge on microbadger.com")

![Screenshot](kcli.jpg)

This tool is meant to interact with a local/remote libvirt daemon and to easily deploy from templates (optionally using cloudinit).
It will also report IPS for any vm connected to a dhcp-enabled libvirt network and generally for every vm deployed from this client.
There is also support for virtualbox and kubevirt

Refer to the [documentation](https://kcli.readthedocs.io) for more information

## [ChangeLog](https://github.com/karmab/kcli/wiki)

##  What you can do

- Interact with libvirt without XML
- Declare all your objects(vm, containers, networks, ansible,...) in a single yaml file!
- Easily grab and share those files from github
- Easily Test all Redhat Infrastructure products, and their upstream counterpart
- Easily share private keys between your vms
- Inject all configuration with cloudinit
- Use the default cloud images
- Have a web UI to do it too!
- Do all of this in virtualbox or kubevirt using same commands and files

## Demo!

[![asciicast](https://asciinema.org/a/153423.png)](https://asciinema.org/a/153423?autoplay=1)

## TODO

- Read The docs
- expose possible parameters when deploying product via web
- store hypervisor in lastvm so that action are associated to the pair (host+lastvm)
- find a better rule when deleting disks of a vm (along with it)
- Check on memory and disk space when creating vm
- validation of ips, netmasks, macs,...  within plan file
- start/delete in multiple hypervisors 
- implement rhel template sync logic

## Contributors

See [contributors on GitHub](https://github.com/karmab/kcli/graphs/contributors)

## Copyright

Copyright 2017 Karim Boumedhel

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

## Problems?

Send me a mail at [karimboumedhel@gmail.com](mailto:karimboumedhel@gmail.com) !

Mac Fly!!!

karmab
