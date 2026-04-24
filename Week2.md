**Week 02 -- Portfolio Entry**

**Explanation of Activities**

Week 2 tutorial was on the setup of the static IP addresses with several
approaches and testing network connectivity with the ping command in a
simulated environment.

This project consisted of four Linux host machines and an Ethernet
switch, which were installed and interconnected to form a Local Area
Network (LAN). A local, IPv4 (e.g. 10.1.1.0/24) IP network was selected,
and each host was assigned its own IP address in this IP network.

There were three methods of setting up the static IP addresses:

**_GNS3 Configuration Interface:_**

![](media/image2.png)

**Figure 1: Proxy Configuration Screen During Linux Installation**

The default GNS3 menu of Configure was used in the case of the first two
hosts to set the IP addresses. This is a simple approach that enables
users to set network settings prior to the node being booted, and is
also maintained across reboots.

**_Manual Setup with /etc/network/interfaces:_**

On the third host, the IP was manually assigned by changing the
/etc/network/interfaces file with the help of a text editor (nano).

**_Using the ip Command:_**

This IP command achieves changes without a restart of the interface and
is short-lived and will not persist after a reboot.

![](media/image1.png){width="5.888889982502187in"
height="3.3125in"}

**Figure 2: Markdown File Rendering**

Once all the hosts were configured, the IP address show command was
executed on each of the nodes to make sure that all the IP addresses
were assigned. Evidence in the form of screenshots of the console output
of each host and the network topology was taken.

![](media/image2.png){width="4.463658136482939in"
height="3.263888888888889in"}

**Figure 3: First Portfolio Entry Commit**

The second task was on the connectivity test, where we used the ping
command. Firstly, a ping test between two hosts was performed
successfully, an exercise that confirmed the network reachability as
well as round-trip time (RTT). Measurements derived (statistically)
included transmitted packets, received packets, packet loss and average
delay.

Ping test was run to a nonexistent IP address. This provided no answers,
and this confirms that all the 100% of the packets are lost, and this
reveals how ping can be used in determining the inaccessibility of the
devices.

Finally, different ping options were tested, such as the number of
packets (-c), interval (-i) and packet size (-s). Such distinctions
helped in the perception of how the network performance and behaviour
can be studied in different situations.

**Reflection and Learning**

Week 2 assisted me considerably in understanding the IP address
configuration and troubleshooting networks. Two approaches to the
allocation of IP addresses, as well as knowledge about them, provided an
understanding of the long-term and short-term settings. I have also
realised that the GNS3 interface is user-friendly, but manual
configuration would offer extra control and understanding of the work of
the Linux network.

The editing of the /etc/network/interfaces file was particularly helpful
as it demonstrated how settings can be set and applied at the system\'s
level. However, there were some challenges in making changes, as I did
not restart the interface. This enabled me to understand the importance
of good reloading of the configuration.

The ip command was fast and effective to use, though I was informed that
it cannot be applied in permanent settings. This contrast between
temporary and permanent settings is above all in the reality network.

The ping exercises proved to be eye openers. I have developed a better
understanding of the measurement of connectivity and the use of RTT and
packet loss to gauge network performance. The graphical representation
of the ping\'s successful and unsuccessful outcomes helped to
substantiate the concepts of reachability and troubleshooting.

My testing of ping options enabled me to experiment with the
customisation of network testing. The delay and transmission were
affected by the size of the packet or the time interval, for example.
