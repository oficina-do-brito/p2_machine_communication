Vagrant.configure("2") do |config|

  config.vm.box = "centos/7"
  config.vm.network "forwarded_port",guest:80,host:8080
  config.vbguest.installer_options = {allow_kernel_upgrade:true}

 config.vm.provision "shell", inline: <<-SHELL
   apt-get update
   apt-get install -y apache2
 SHELL

end
