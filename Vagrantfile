
Vagrant.configure("2") do |config|  
config.vm.define "ansible" do |ansible|
  ansible.vm.box = "ubuntu/trusty64"
  ansible.vm.network "private_network", ip: "192.168.1.90"
  ansible.vm.hostname = "ansible"
  end
  config.vm.define "client" do |client|
  client.vm.box = "ubuntu/trusty64"
  client.vm.network "private_network", ip: "192.168.1.91"
  client.vm.hostname = "client"
end
end
