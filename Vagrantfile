# -*- mode: ruby -*-
# vi: set ft=ruby :

# Vagrantfile API/syntax version. Don't touch unless you know what you're doing!
VAGRANTFILE_API_VERSION = "2"

ENV['VAGRANT_DEFAULT_PROVIDER'] ||= 'docker'

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  config.vm.network "private_network", ip: "192.168.169.170"
  config.vm.provider "docker" do |d|
    d.build_dir = "."
    d.name = "test_test"
    d.ports  = ["80:80"]
    d.cmd = ["-D", "FOREGROUND"]
  end
end