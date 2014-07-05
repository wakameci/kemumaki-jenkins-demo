Kemukins: Demo Jenkins Configuration
====================================

Deployment pipeline skeleton for Wakame CI

Build Tool
----------

+ [kemumaki](https://github.com/axsh/kemumaki)

Configuration
-------------

`/var/lib/jenkins` under version control

### Jenkins master

+ `config.xml` core config.xml
+ `buildstep-config-files.xml` managed scripts plugin
+ `jobs/` config.xml for each job

### Jekins cluster

Using ssh with no pass pharse key pair

+ ssh_config
  + `.ssh/config`
+ ssh key pair
  + `.ssh/kemukins-demo` private key
  + `.ssh/kemukins-demo.pub` public key
