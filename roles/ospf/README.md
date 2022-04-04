Role Name
=========

There is 1 main steps in ospf role. Generate the OSPF xml configuration file based on the variables and configure the device with this xml file.


Role Variables
--------------

OSPF process id is 1 for every device in the network. L3 interfaces between Leafs and Spines are configured as OSPF links. So, variables are located under `group_vars` and `host_vars` directories.
