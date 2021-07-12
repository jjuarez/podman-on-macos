# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "fedora/34-cloud-base"
  config.vm.provider :virtualbox do |vb|
    vb.cpus   = "2"
    vb.memory = "1024"
  end

  # config.vm.provision :shell, name: "pre-ansible", path: "provision/shell/pre-ansible.sh"
  config.vm.provision :ansible_local do |ansible|
    ansible.verbose            = "true"
    ansible.config_file        = "provision/ansible/ansible.cfg"
    ansible.compatibility_mode = "2.0"
    ansible.playbook           = "provision/ansible/playbook.yml"
  end
end
