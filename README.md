# STATIC
STATIC ROUTING
Two LAN networks (192.168.0.0/24 and 192.168.1.0/24) were connected via two routers through an intermediate network (192.168.2.0/24). Static routes were configured on both routers to enable proper communication between the LAN segments and the interconnecting network.

# STATIC - ROUTING CLI - COMMANDS

Router (config) # ip route "Destination" subnet Destination way

Router (config) # ip route 192.168.1.0  255.255.255.0  192.168.2.2

Router (config) # ip route 192.168.0.1  255.255.255.0  192.168.2.1
