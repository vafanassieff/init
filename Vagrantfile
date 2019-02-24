
Vagrant.configure("2") do |config|
  config.vm.box = "debian/stretch64"
  config.vm.synced_folder ".", "/home/vagrant/init", type: "rsync",
    rsync__exclude: ".git/"
  config.gatling.rsync_on_startup = true
end
