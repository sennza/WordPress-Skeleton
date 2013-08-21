# Sennza Skeleton

This is the new fangled base repository for Sennza work.

## Prerequisites

Before using Skeleton, this is how your system should be set up:

* Install [Vagrant](http://vagrantup.com/)
* Install vagrant-hostsupdater to access via `vagrant.local`:

		vagrant plugin install vagrant-hostsupdater

  **Note for Windows users:** You'll need to set
  `C:\Windows\system32\drivers\etc\hosts` to be writable by your user. Simply
  head to the properties and add your user with full control under security.

  Alternatively, add `vagrant.local` to your hosts file with `192.168.33.10` as
  the IP address.

## Using

```bash
# Clone this repo
git clone --recursive git@github.com:sennza/WordPress-Skeleton.git myproject
cd myproject

# Clone the content/ directory!
git clone git@github.com:sennza/myproject.git content

# Boot up a VM
vagrant up
```

Make sure you copy `local-config-sample.php` to `local-config.php`