
Vagrant.configure("2") do |config|
  config.vm.define "ansible" do |ansible|
  ansible.vm.box = "centos/7"
  ansible.vm.network "public_network", ip: "192.168.1.200"
  end
  config.vm.define "client" do |client|
  client.vm.box = "centos/7"
  client.vm.network "public_network", ip: "192.168.1.201"
end
end
