
Vagrant.configure("2") do |config|
  config.vm.provider "virtualbox" do |vb|
    vb.name = "Ubuntu 20.04"
    vb.memory = 1024
    vb.cpus = 1

  end 
    config.vm.box = "ubuntu/focal64"
    config.vm.network "public_network", ip: "192.168.0.121"
end
