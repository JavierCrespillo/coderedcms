# -*- mode: ruby -*-
# vi: set ft=ruby :


Vagrant.configure("2") do |config|
config.vm.define :cmspython do |cmspython|
    cmspython.vm.box = "debian/bullseye64"
    cmspython.vm.hostname = "cmspython"
    cmspython.vm.synced_folder ".", "/vagrant", disabled: true
 end
end

