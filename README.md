# Problem-Packet-Flow-Visualizer.
The main objective of this project is to create a visual representation of the packet flow from students&amp;#39; laptops/desktops (hosts) to external networks outside of the college campus.

The project can be divided into two key parts, as outlined below:
# Network Topology Creation:
To begin, students will need to determine the
devices present within the college network. They can achieve this by using tools like
traceroute or by consulting with the college network administrator. Based on the
gathered information, students will then create a network topology using Cisco
Packet Tracer (available at: https://www.netacad.com/courses/packet-tracer). The
topology will illustrate the various network devices, network design, and network
boundaries, as explained in the Network Essential course, showcasing the path from
the host to the external network.


# Packet Flow Investigation: 
After establishing the network topology using
Cisco Packet Tracer and configuring IPv4 addresses on all layer-3 devices, students
will proceed to collect packets at each device using a packet sniffer. They can choose
to use either the inbuilt sniffer in Cisco Packet Tracer (tutorial available at
https://www.youtube.com/watch?v=gsCSKQAVT2M ). By analyzing the packets
captured from different devices (nodes), students can extract relevant information
from the packet headers, particularly noting changes occurring in the Ethernet and IP
headers. This data will enable them to create a flow diagram illustrating the path of
the packet flow from their device (host) to the external network. Any flow chart
creator application can be used to create this diagram.

# Expected Outcome:

Upon completion of the packet inspection and header analysis at each node,
students should be able to demonstrate the following:
# A clear understanding of different blocks of network design.
# Familiarity with the different OSI model layers and the importance of layering. They
should also comprehend the relationship between the layers and the metadata
carried in each layer&#39;s packet header.
# A comprehensive understanding of the roles of various devices in a network. They
should be able to distinguish the role of a router (L3 device) from that of a switch (L2
device).
