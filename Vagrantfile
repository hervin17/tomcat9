# _*_ mode: ruby _*_

VAGRANTFILE_API_VERSION = "2"


Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|

  config.vm.box = "geerlingguy/centos7"
  config.vm.provider :virtualbox do |v|
#     v.gui = true
#     v.memory = 256
#     v.linked_clone = true
  end
#serveur d'application tomcat9
 config.vm.define "tomcat9" do |app|
    app.vm.hostname = "tomcat9.dev"
    app.vm.network :private_network, ip:"192.168.204.210"
 end
end
