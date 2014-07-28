# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "precise32"
  
  config.vm.provision "shell",
    inline: "mkdir -p /root/.ssh && cp /home/vagrant/.ssh/authorized_keys /root/.ssh/"
end
