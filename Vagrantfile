# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|
    config.vm.provider 'docker' do |d|
        d.force_host_vm = true
        d.image = 'osixia/openldap:1.1.4'
        d.ports = ['8389:389','8636:636']
        d.name = 'ldap'
        d.remains_running = true
  end
end
