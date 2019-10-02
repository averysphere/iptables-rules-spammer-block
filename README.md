# iptables-rules-spammer-block
This is a shell script that will enable us to add iptables rules on *nix systems for blocking widely used IP address ranges by spammers, bad bots and crawlers, as well as brute-force attackers.

## Source of IP address blocks
Please refer to `https://www.wizcrafts.net/` for complete list and updated lists of IP ranges. This specific script only included Russian, Asian and some European IP address blocks.

These `iptables` rules should take effect immediately. However, to save the rules you need to save to a iptables config file such as `/etc/sysconfig/iptables` on a Red Hat system.

Sample:

`# iptables-save > /etc/sysconfig/iptables`

Note that these `iptables` are purely IPv4 blocks.


