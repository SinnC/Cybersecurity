# Cybersecurity
Labs and notes for my cybersecurity learning journey

1) Setting up my Virtual machines
   I will use the software VMware Workstation for the simulation of 2 separate working stations each with their own Network so i can test file transfering,connection between LAN networks and other network related services.

   - I have created two UBUNTU(could have been any other Linux "family members" but I find UBUNTU easier to work with)
   - I called the two machines: Virtualmachine1 and Virtualmachine2 for easy reference
    

2) Virtual Network set up via VMware Workstation

   Before creating the network I want to explain what networks will be used

   NAT: Allows VMs to access the internet through your host (good for updates).

  Host-Only: Creates a private network between your host and the VMs (ideal for isolated labs)
  
Setting up Host Only Networks for easy isolation
  Can be done in:   Edit > Virtual Network Editor
                    I have added another Host only Network called VM Net 2 which i set as host only as this will be used for my second OS
                     I decided to leave DHCP ON as I wanted it to handle automatic IP generation although i could also enter a custome one.





