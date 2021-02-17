Vagrant.configure("2") do |config|
  # VM 2 RedHat
  config.vm.box = "generic/rhel8"
  config.vm.define "rhel-server"
  config.vm.hostname = "server2"
  # VM 2 RedHat
  config.vm.network "public_network", bridge: "Microsoft Wi-Fi Direct Virtual Adapter #2", ip: "192.168.137.112"
  config.vm.provider "virtualbox" do |vb|
    vb.gui = true
    # VM 2 RedHat
    vb.name = "rhel-server"
  #   # Customize the amount of memory on the VM:
    vb.memory = "6144"
  end
end
