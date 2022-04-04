Role Name
=========

There is multiple steps in vpc role. Since vPC configuration needs to be done part by part, steps are generating xml configuration files based on the variables and configure the devices with these xml configuration  for vPC VRF, PeerKeepalive, vPC domain and PeerLinks.


Role Variables
--------------

vPC configuration are the same with peer Leaf devices but different for different vPC peers. So, variables are located under `host_vars` directory. 
