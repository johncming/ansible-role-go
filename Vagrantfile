Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/trusty64"

  config.vm.provision :ansible do |ansible|
    ansible.playbook = "tests/vagrant.yml"
    ansible.galaxy_roles_path = "../"
  end
end
