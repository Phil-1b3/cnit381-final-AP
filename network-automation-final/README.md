# cnit381-final-AP
# Alex Carr and Philip Ibe
# Our project consists of two router and one switch, upon looking in our Github you can see all the file we created. The files you see will automate configurations for network devices. We used our network and on a ubuntu VM we created ansible playbooks inside of a VS code session with our Github repo cloned inside. 
# Our verify connections playbook will use commands to show the version 
# Our base config playbook will configure all of the base configurations that go on a device, for example the hostnames, interface descriptions and login banners.
# Our EIGRP playbook will configure eigrp with autonomous system 100 on both the routers with also advertising all networks and configure loopback interfaces.
# Our VLAN playbook will create VLANs for Data and Management and confiure trunk ports to the R1.
# Our services playbook will configure NTP and sync with Google's server time.
# Our backup playbook will check to see if playbook has connectivity and will backup the playbook configurations.
