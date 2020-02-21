# Testing-Measurement

From the brainstorming list:
- Would be nice to have a standard recommended dnsperf test configuration, so across different implementers there is an apples-to-apples benchmark tool - https://www.dns-oarc.net/tools/dnsperf
- This can also be used by independent measurement researcher & orgs
- Seems like a key early task

# Query Tools
Name of Tool, Description, Support for Do53/DoT/DoH, where is Sourceode Repository, which supported OS, other remarks/caveats

* dox, GUI based query utility, Do53/DoT/DoH, https://github.com/wttw/dox, Windows/MacOSX, alpha, supports multi/servce and site-surveys through used editable json config files, caveat 
* kdig, CLI based dig-like query tool from CZ.NIC domain registries KNOT  open source DNS server/resolver project, Do53/DoT, https://github.com/CZ-NIC/knot/tree/master/src/utils/kdig, Linux/MacOS, may be a sponsoring opportunity for adding fine grained TCP query tuning/measurement and DoH support, binary  distrbution see here TBD
* sdig, CLI based (barebone) query tool from PowerDNS open source DNS server/resolver project, Do53/DoH (active work on DoT), s  https://github.com/PowerDNS/pdns/blob/master/pdns/sdig.cc, Linux Ubunuu >= 16.04, CentOS, SUSE, no CLI query time info, binary distribution here (make sure to use DNS Authoritiave repo and install tools  https://repo.powerdns.com/ 
