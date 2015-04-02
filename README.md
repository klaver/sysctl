# sysctl.conf
Linux/BSD kernel tuning and network security hardening optimizations, improving the performance of server systems via optimized sysctl tweaks

This file should be saved as /etc/sysctl.conf and can be activated using the command:
sysctl -e -p /etc/sysctl.conf

For binary values, 0 is disabled, 1 is enabled.  See sysctl(8) and sysctl.conf(5) for more details.

Intended use for dedicated server systems at high-speed networks with loads of RAM and bandwidth available
Optimised and tuned for high-performance web/ftp/mail/dns servers with high connection-rates
DO NOT USE at busy networks or xDSL/Cable connections where packetloss can be expected

Credits: <br>
http://www.enigma.id.au/linux_tuning.txt <br>
http://www.securityfocus.com/infocus/1729 <br>
http://fasterdata.es.net/TCP-tuning/linux.html <br>
http://fedorahosted.org/ktune/browser/sysctl.ktune <br>
http://www.cymru.com/Documents/ip-stack-tuning.html <br>
http://www.kernel.org/doc/Documentation/networking/ip-sysctl.txt <br>
http://www.frozentux.net/ipsysctl-tutorial/chunkyhtml/index.html <br>
http://knol.google.com/k/linux-performance-tuning-and-measurement <br>
http://www.cyberciti.biz/faq/linux-kernel-tuning-virtual-memory-subsystem/ <br>
http://www.redbooks.ibm.com/abstracts/REDP4285.html <br>
http://www.speedguide.net/read_articles.php?id=121 <br>
http://lartc.org/howto/lartc.kernel.obscure.html <br>
http://en.wikipedia.org/wiki/Sysctl <br>
