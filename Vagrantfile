Vagrant.configure("2") do |config|
  config.vm.provider "virtualbox" do |vb|
    vb.name = "Projeto_00_Vagrant_Ubuntu"
    vb.memory = 1024
    vb.cpus = 1
  end

  config.vm.box = "ubuntu/focal64" 
  config.vm.network "forwarded_port", guest: 80, host: 8080
  config.vm.network "public_network", ip: "192.168.0.20"
end
