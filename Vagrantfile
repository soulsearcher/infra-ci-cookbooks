# -*- mode: ruby -*-
# vi: set ft=ruby :

# All Vagrant configuration is done below. The "2" in Vagrant.configure
# configures the configuration version (we support older styles for
# backwards compatibility). Please don't change it unless you know what
# you're doing.
Vagrant.configure("2") do |config|
  config.vm.box = "bento/centos-7.4"

  config.vm.define :webapp do |host|
    host.vm.hostname = "webapp"
  end

  config.vm.network "private_network", ip: "192.168.56.20"
end
