# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|

  config.vm.define "sandbox" do |sandbox|
    sandbox.vm.box = "ubuntu/precise64"


    sandbox.vm.provision "ansible" do |ansible|
      ansible.playbook = "test.yml"
      ansible.verbose = "vvvv"
    end

  end
end

