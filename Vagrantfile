VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|

  config.vm.box = "DreiWolt/devops007"
  config.vm.network :private_network, ip: "192.168.3.13"
  config.vm.hostname = "FCGIClientDemo"
  config.hostsupdater.aliases = ["demo.fast-cgi-client.de"]

  config.vm.provision "shell", path: "env/bootstrap.sh", run: "always"

end
