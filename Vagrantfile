Vagrant.configure("2") do |config|

  (1..2).each do |i|
    config.vm.define "web#{i}" do |node|
      node.vm.box = "vatman/xenial64-clean"
      node.vm.box_version = "0.1"
      node.vm.hostname = "web#{i}"
    end
  end
end