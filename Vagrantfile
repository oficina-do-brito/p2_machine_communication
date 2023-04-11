Vagrant.configure("2") do |config|

  config.vm.box = "centos/7"
  config.vm.network "forwarded_port",guest:80,host:8080,host_ip:"127.0.0.1"
  config.vbguest.installer_options = {allow_kernel_upgrade:true}
  config.vm.provision "shell", path:"scripts/provision.sh"

end
