# Vagrant 3 Firefly
A Vagrant implementation that will spin up 3 Juniper Firefly perimeter (vSRX 1.0) VMs in a generic topology for testing various features. The inner device is in packet-mode and act as a router with multiple routing instances. The other 2 devices are in flow-mode and act as firewalls with their untrust interfaces connected together.

# Diagram
![](vagrant-FW-3vsrx.png)

# Setup
1. Review the Vagrantfile
2. Host specific values can be customized using the YML files in host_vars. See in file comments.
3. vagrant up

# Login Information
root/Juniper   (default vagrant credentials)
lab/Juniper123 (credentials included in the templates)

