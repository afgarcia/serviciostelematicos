Vagrant.configure("2") do |config|
config.vm.define :cliente do |cliente|
cliente.vm.box = "bento/centos-7.7"
cliente.vm.network :private_network, ip: "192.168.50.2"
cliente.vm.hostname = "cliente"
end
config.vm.define :servidor do |servidor|
servidor.vm.box = "bento/centos-7.7"
servidor.vm.network :private_network, ip: "192.168.50.3"
servidor.vm.hostname = "servidor"
end
end
