**Week 01 -- Portfolio Entry**

**Explanation of Activities**

During Week 1, the focus was to learn about the unit structure, install
the necessary tools and have some basic familiarity with network
simulation with GNS3.

![](media/image1.png)

**Figure 1: UTM Virtual Machine Interface -- Initial Setup Screen**

The first practice was reading about the unit profile, which helped to
get clarity on the evaluation requirements, in particular, the need to
maintain a GitHub portfolio and a weekly progress report. This gave a
precise guideline of what was expected, a technical documentation,
reflections, and frequent updates.

![](media/image2.png)

**Figure 2: Virtual Machine Hardware Configuration (Memory and CPU
Allocation)**

Secondly, I ensured that all required software was in place and all were
working. It consisted of VirtualBox, which is used in the virtualisation
process, and GNS3, which is a network simulation software which allows
testing networking concepts. These tools needed to be identified and
installed in order to allow the further smooth workflow in the following
weeks.

![](media/image2.png)

**Figure 3: Linux Virtual Machine Boot Configuration Using ISO Image**

Then, a personal repository in GitHub was formed. This will be the
repository where the portfolio entries will be kept each week. The other
tool I investigated is a Markdown formatting that is significant to
provide a coherent and professional documentation. Markdown will allow
the site to be readable, simplify its contents and even insert pictures
such as screenshots.

I did a practical activity in Section B with GNS3. I have come up with a
new project and a Linux host node. They were also annotated in the
workspace with the project name, student ID and IP address displayed.
This helped to understand how to record network settings graphically.

The most important technical task was to configure the Linux node to
have a fixed IP address by changing the /etc/network/interfaces file. I
gave it an IP address (e.g. 10.10.1.1) and specified the subnet mask.
The command sysctl net.ipv4.ip forward=0 also disabled IP forwarding,
and thus, the node is a normal host and not a router.

Once the network settings were configured, I launched the node and used
a web interface to get to the console. To verify the assigned IP
address, I ran the command ip address show, which made sure that the
assigned IP address was configured accordingly. The console output and
network topology were recorded in the form of screenshots.

**Reflection and Learning**

The area that I can practice is the one that this week has been
established in terms of technical and documentation skills. Learning the
significance of an appropriate environment setup was one of the learning
outcomes. Simulation of networking could not be done without the proper
installation of tools such as GNS3 and VirtualBox.

I also realised how important GitHub is as a professional tool, not only
as a tool to store files, but also to present the work systematically
and organised. Markdown education was also particularly useful since
Markdown improves the clarity of documentation and its professionalism.
The competence will assist in this unit and the other educational and
work projects in future.

Technically, the establishment of a fixed IP address allowed me to be
aware of the configuration of the network interfaces of Linux systems.
Configuring in the configuration files manually has provided an
understanding of how the operating systems deal with networking at a low
level. An example, such as an IP address, shows my learning in checking
configurations instead of presuming the correctness of the
configurations.

One of my frustrations was also the lack of knowledge on how the
/etc/network/interfaces file was organised and the appropriate syntax to
use. Even small formatting errors might cause misconfigurations.
However, by trial and error, I was able to work out the network
successfully.
