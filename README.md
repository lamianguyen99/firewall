# FIREWALL

### Catalog:

**Iptables:**
  
  - iptables flows
  
  - iptables tables & chains
    + 5 tables
    + built-in and user defined chains


    **MATCH EXTENSIONS:**  connbytes, connlimit, conntrack, hashlimit, length, limit, multiport, set, recent, string, tcp, udp, ttl.

    
  - iptables extensions

    + TARGET extensions:

    + CT (raw), DNAT, LOG, MASQUERADE (nat-POSTROUTING), NOTRACK. REJECT
  
  - ipset
  
  - iptables TRACE

**Windows Firewall:**

  - 3 core rules
  
  - profiles (domain, public, private)

**References:**

  Deep Dive in Iptables: https://www.digitalocean.com/community/tutorials/a-deep-dive-into-iptables-and-netfilter-architecture

  Iptables extensions: https://ipset.netfilter.org/iptables-extensions.man.html

  More about packet filter: https://www.netfilter.org/documentation/HOWTO/packet-filtering-HOWTO-7.html

  All about Windows Firewall: https://learn.microsoft.com/en-us/windows/security/operating-system-security/network-security/windows-firewall/best-practices-configuring

  Practical Windows Firewall: https://www.youtube.com/watch?v=n5_THlMSBSA

  Nâng cao:

  modules u32: http://www.stearns.org/doc/iptables-u32.current.html

  TCPDUMP command man page with examples https://www.cyberciti.biz/howto/question/man/tcpdump-man-page-with-examples.php

  *pcapfilter https://man.archlinux.org/man/pcap-filter.7.en

  All about iptables: https://www.frozentux.net/iptables-tutorial/iptables-tutorial.html

  Vietnix: https://github.com/vietnix-org/level2Training/blob/master/firewall/1.%20Knowledge%20base.md

Ứng dụng:

  Mô hình NAT game

  Allow, Block IP trên server

  Giới hạn số lượng kết nối
