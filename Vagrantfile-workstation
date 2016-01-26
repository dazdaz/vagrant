#
# vagrant up workstation
# vagrant ssh workstation
#

Vagrant.configure(2) do|config|
 config.vm.define "workstation" do |workstation|
  workstation.vm.box = "ubuntu/trusty64"
  workstation.vm.network "private_network", ip: "10.1.1.2"
  workstation.vm.hostname = "workstation.example.com"
 end
end
