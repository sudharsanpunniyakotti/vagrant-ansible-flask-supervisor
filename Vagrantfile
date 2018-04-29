# ./Vagrantfile
Vagrant.configure("2") do |config|

  # Base image to use
  config.vm.box = "ubuntu/xenial64"
  config.vm.network "private_network", ip: "10.10.10.20"
  # Declare ansible provisioner
  config.vm.provision "ansible" do |ansible|
    ansible.playbook = "playbook.yml"
  end
end