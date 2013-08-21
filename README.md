vagrant-stub
============

A simple template for vagrant running an Ubuntu 12 with 3.8.0 kernel for docker and auto VBox Guest Additions installer

## usage

1. Install vagrant and virtualbox

2. Copy the Vagrantfile and bootstrap.sh into the root of your project

3. type:

```
$ vagrant up
```

The initial run through will upgrade the kernel and update Guest Additions.

The second run through will run bootstrap.sh which you can use to provision your new machine

## licence

MIT