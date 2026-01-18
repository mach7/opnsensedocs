============================================
OPNsense Menu & Settings Location Reference
============================================

This single-page reference lists the documented menu locations for every OPNsense
GUI area described in this documentation set. It is intended as a map you can
hand to ChatGPT (or any operator) so each setting can be found quickly.

**How to read menu paths**

* Menu paths are shown using the UI breadcrumb notation, for example:
  :menuselection:`System --> Settings --> Administration`.
* Entries with brackets (for example :menuselection:`Interfaces --> [LAN]`) are
  interface-specific and repeat per assigned interface.
* Plugin-provided menus are grouped under **Optional / plugin menus**.

-----------------------------
Lobby & Global Navigation
-----------------------------

.. list-table::
   :widths: 40 60
   :header-rows: 1

   * - Menu location
     - Documentation
   * - :menuselection:`Lobby --> Dashboard`
     - :doc:`lobby`

-----------------------------
Reporting
-----------------------------

.. list-table::
   :widths: 40 60
   :header-rows: 1

   * - Menu location
     - Documentation
   * - :menuselection:`Reporting --> Health`
     - :doc:`manual/systemhealth`
   * - :menuselection:`Reporting --> Insight`
     - :doc:`manual/how-tos/insight`
   * - :menuselection:`Reporting --> NetFlow`
     - :doc:`manual/netflow`
   * - :menuselection:`Reporting --> Settings`
     - :doc:`manual/reporting_settings`
   * - :menuselection:`Reporting --> Traffic`
     - :doc:`manual/reporting_traffic`
   * - :menuselection:`Reporting --> Unbound DNS`
     - :doc:`manual/reporting_unbound_dns`

-----------------------------
System
-----------------------------

.. list-table::
   :widths: 40 60
   :header-rows: 1

   * - Menu location
     - Documentation
   * - :menuselection:`System --> Access --> Users`
     - :doc:`manual/users`
   * - :menuselection:`System --> Access --> Groups`
     - :doc:`manual/users`
   * - :menuselection:`System --> Access --> Servers`
     - :doc:`manual/users`
   * - :menuselection:`System --> Access --> Privileges`
     - :doc:`manual/users`
   * - :menuselection:`System --> Access --> Tester`
     - :doc:`manual/users`
   * - :menuselection:`System --> Settings --> Administration`
     - :doc:`manual/settingsmenu`
   * - :menuselection:`System --> Settings --> General`
     - :doc:`manual/settingsmenu`
   * - :menuselection:`System --> Settings --> Cron`
     - :doc:`manual/settingsmenu`
   * - :menuselection:`System --> Settings --> Logging`
     - :doc:`manual/settingsmenu`
   * - :menuselection:`System --> Settings --> Logging / Targets`
     - :doc:`manual/settingsmenu`
   * - :menuselection:`System --> Settings --> Tunables`
     - :doc:`manual/settingsmenu`
   * - :menuselection:`System --> Settings --> Miscellaneous --> Disk / Memory Settings`
     - :doc:`manual/settingsmenu`
   * - :menuselection:`System --> Settings --> Miscellaneous --> RAM Disk Settings`
     - :doc:`manual/settingsmenu`
   * - :menuselection:`System --> Configuration --> Backups`
     - :doc:`manual/backups`
   * - :menuselection:`System --> Configuration --> Backups --> Git`
     - :doc:`manual/git-backup`
   * - :menuselection:`System --> Configuration --> History`
     - :doc:`manual/snapshots`
   * - :menuselection:`System --> Firmware --> Status`
     - :doc:`manual/firmware`
   * - :menuselection:`System --> Firmware --> Updates`
     - :doc:`manual/firmware`
   * - :menuselection:`System --> Firmware --> Fetch updates`
     - :doc:`manual/firmware`
   * - :menuselection:`System --> Firmware --> Plugins`
     - :doc:`manual/firmware`
   * - :menuselection:`System --> Firmware --> Settings`
     - :doc:`manual/firmware`
   * - :menuselection:`System --> Firmware --> Log File`
     - :doc:`manual/firmware`
   * - :menuselection:`System --> Gateways --> Configuration`
     - :doc:`manual/gateways`
   * - :menuselection:`System --> Gateways --> Group`
     - :doc:`manual/gateways`
   * - :menuselection:`System --> Gateways --> Log File`
     - :doc:`manual/gateways`
   * - :menuselection:`System --> Routes --> Configuration`
     - :doc:`manual/routes`
   * - :menuselection:`System --> Routes --> Status`
     - :doc:`manual/routes`
   * - :menuselection:`System --> Routes --> Log File`
     - :doc:`manual/routes`
   * - :menuselection:`System --> High Availability --> Settings`
     - :doc:`manual/hacarp`
   * - :menuselection:`System --> High Availability --> Status`
     - :doc:`manual/hacarp`
   * - :menuselection:`System --> Trust --> Certificates`
     - :doc:`manual/certificates`
   * - :menuselection:`System --> Trust --> Authorities`
     - :doc:`manual/certificates`
   * - :menuselection:`System --> Trust --> Revocation`
     - :doc:`manual/certificates`
   * - :menuselection:`System --> Trust --> Settings`
     - :doc:`manual/certificates`
   * - :menuselection:`System --> Diagnostics --> Services`
     - :doc:`manual/diagnostics_system`
   * - :menuselection:`System --> Log Files --> General`
     - :doc:`manual/logging_system`
   * - :menuselection:`System --> Log Files --> Backend`
     - :doc:`manual/logging_system`
   * - :menuselection:`System --> Log Files --> Web GUI`
     - :doc:`manual/logging_system`
   * - :menuselection:`System --> Snapshots`
     - :doc:`manual/snapshots`

-----------------------------
Interfaces
-----------------------------

.. list-table::
   :widths: 40 60
   :header-rows: 1

   * - Menu location
     - Documentation
   * - :menuselection:`Interfaces --> Overview`
     - :doc:`manual/interfaces_overview`
   * - :menuselection:`Interfaces --> Assignments`
     - :doc:`manual/interfaces`
   * - :menuselection:`Interfaces --> Settings`
     - :doc:`manual/interfaces_settings`
   * - :menuselection:`Interfaces --> [LAN]`
     - :doc:`manual/interfaces`
   * - :menuselection:`Interfaces --> [WAN]`
     - :doc:`manual/interfaces`
   * - :menuselection:`Interfaces --> [OPTx]`
     - :doc:`manual/interfaces`
   * - :menuselection:`Interfaces --> Devices`
     - :doc:`manual/other-interfaces`
   * - :menuselection:`Interfaces --> Devices --> Bridge`
     - :doc:`manual/other-interfaces`
   * - :menuselection:`Interfaces --> Devices --> GIF`
     - :doc:`manual/other-interfaces`
   * - :menuselection:`Interfaces --> Devices --> GRE`
     - :doc:`manual/other-interfaces`
   * - :menuselection:`Interfaces --> Devices --> LAGG`
     - :doc:`manual/other-interfaces`
   * - :menuselection:`Interfaces --> Devices --> Loopback`
     - :doc:`manual/other-interfaces`
   * - :menuselection:`Interfaces --> Devices --> Point-to-Point`
     - :doc:`manual/other-interfaces`
   * - :menuselection:`Interfaces --> Devices --> VLAN`
     - :doc:`manual/other-interfaces`
   * - :menuselection:`Interfaces --> Devices --> VXLAN`
     - :doc:`manual/other-interfaces`
   * - :menuselection:`Interfaces --> Virtual IPs`
     - :doc:`manual/firewall_vip`
   * - :menuselection:`Interfaces --> Virtual IPs --> Status`
     - :doc:`manual/firewall_vip`
   * - :menuselection:`Interfaces --> Diagnostics --> ARP Table`
     - :doc:`manual/diagnostics_interfaces`
   * - :menuselection:`Interfaces --> Diagnostics --> NDP Table`
     - :doc:`manual/diagnostics_interfaces`
   * - :menuselection:`Interfaces --> Diagnostics --> Packet Capture`
     - :doc:`manual/diagnostics_interfaces`
   * - :menuselection:`Interfaces --> Diagnostics --> Ping`
     - :doc:`manual/diagnostics_interfaces`
   * - :menuselection:`Interfaces --> Diagnostics --> Trace Route`
     - :doc:`manual/diagnostics_interfaces`
   * - :menuselection:`Interfaces --> Diagnostics --> DNS lookup`
     - :doc:`manual/diagnostics_interfaces`
   * - :menuselection:`Interfaces --> Wireless`
     - :doc:`manual/wireless`
   * - :menuselection:`Interfaces --> IPv6`
     - :doc:`manual/ipv6`
   * - :menuselection:`Interfaces --> Neighbors`
     - :doc:`manual/neighbors`

-----------------------------
Firewall
-----------------------------

.. list-table::
   :widths: 40 60
   :header-rows: 1

   * - Menu location
     - Documentation
   * - :menuselection:`Firewall --> Aliases`
     - :doc:`manual/aliases`
   * - :menuselection:`Firewall --> Categories`
     - :doc:`manual/firewall_categories`
   * - :menuselection:`Firewall --> Groups`
     - :doc:`manual/firewall_groups`
   * - :menuselection:`Firewall --> Rules`
     - :doc:`manual/firewall`
   * - :menuselection:`Firewall --> Rules --> Floating`
     - :doc:`manual/firewall`
   * - :menuselection:`Firewall --> Rules --> [interface]`
     - :doc:`manual/firewall`
   * - :menuselection:`Firewall --> NAT`
     - :doc:`manual/nat`
   * - :menuselection:`Firewall --> NAT --> Outbound`
     - :doc:`manual/nat`
   * - :menuselection:`Firewall --> NAT --> Destination NAT (Port Forward)`
     - :doc:`manual/nat`
   * - :menuselection:`Firewall --> NAT --> One-to-one`
     - :doc:`manual/nat`
   * - :menuselection:`Firewall --> NAT --> NPTv6`
     - :doc:`manual/nptv6`
   * - :menuselection:`Firewall --> Shaper --> Pipes`
     - :doc:`manual/shaping`
   * - :menuselection:`Firewall --> Shaper --> Status`
     - :doc:`manual/shaping`
   * - :menuselection:`Firewall --> Automation`
     - :doc:`manual/firewall_automation`
   * - :menuselection:`Firewall --> Settings --> Advanced`
     - :doc:`manual/firewall_settings`
   * - :menuselection:`Firewall --> Settings --> Normalization`
     - :doc:`manual/firewall_scrub`
   * - :menuselection:`Firewall --> Diagnostics --> Aliases`
     - :doc:`manual/diagnostics_firewall`
   * - :menuselection:`Firewall --> Diagnostics --> Sessions`
     - :doc:`manual/diagnostics_firewall`
   * - :menuselection:`Firewall --> Diagnostics --> States`
     - :doc:`manual/diagnostics_firewall`
   * - :menuselection:`Firewall --> Diagnostics --> States Dump`
     - :doc:`manual/diagnostics_firewall`
   * - :menuselection:`Firewall --> Diagnostics --> Statistics`
     - :doc:`manual/diagnostics_firewall`
   * - :menuselection:`Firewall --> Diagnostics --> pfTable`
     - :doc:`manual/diagnostics_firewall`
   * - :menuselection:`Firewall --> Log Files --> Live View`
     - :doc:`manual/logging_firewall`
   * - :menuselection:`Firewall --> Log Files --> Plain View`
     - :doc:`manual/logging_firewall`

-----------------------------
Services
-----------------------------

.. list-table::
   :widths: 40 60
   :header-rows: 1

   * - Menu location
     - Documentation
   * - :menuselection:`Services --> DHCP --> Server`
     - :doc:`manual/dhcp`
   * - :menuselection:`Services --> DHCPv4 --> [interface]`
     - :doc:`manual/dhcp`
   * - :menuselection:`Services --> DHCPv4 --> Log File`
     - :doc:`manual/dhcp`
   * - :menuselection:`Services --> DHCPv6 --> [interface]`
     - :doc:`manual/dhcp`
   * - :menuselection:`Services --> DHCP Relay`
     - :doc:`manual/dhcrelay`
   * - :menuselection:`Services --> Router Advertisements`
     - :doc:`manual/radvd`
   * - :menuselection:`Services --> ISC DHCPv4`
     - :doc:`manual/isc`
   * - :menuselection:`Services --> ISC DHCPv6`
     - :doc:`manual/isc`
   * - :menuselection:`Services --> KEA DHCP --> KEA DHCPv4`
     - :doc:`manual/kea`
   * - :menuselection:`Services --> KEA DHCP --> KEA DHCPv6`
     - :doc:`manual/kea`
   * - :menuselection:`Services --> KEA DHCP --> Control Agent`
     - :doc:`manual/kea`
   * - :menuselection:`Services --> Dnsmasq DNS & DHCP --> General`
     - :doc:`manual/dnsmasq`
   * - :menuselection:`Services --> Dnsmasq DNS & DHCP --> Domains`
     - :doc:`manual/dnsmasq`
   * - :menuselection:`Services --> Dnsmasq DNS & DHCP --> Hosts`
     - :doc:`manual/dnsmasq`
   * - :menuselection:`Services --> Dnsmasq DNS & DHCP --> DHCP ranges`
     - :doc:`manual/dnsmasq`
   * - :menuselection:`Services --> Dnsmasq DNS & DHCP --> DHCP options`
     - :doc:`manual/dnsmasq`
   * - :menuselection:`Services --> Dnsmasq DNS & DHCP --> DHCP boot`
     - :doc:`manual/dnsmasq`
   * - :menuselection:`Services --> Dnsmasq DNS & DHCP --> DHCP tags`
     - :doc:`manual/dnsmasq`
   * - :menuselection:`Services --> Dnsmasq DNS & DHCP --> Host Override`
     - :doc:`manual/dnsmasq`
   * - :menuselection:`Services --> Dnsmasq DNS & DHCP --> Log`
     - :doc:`manual/dnsmasq`
   * - :menuselection:`Services --> Unbound DNS --> General`
     - :doc:`manual/unbound`
   * - :menuselection:`Services --> Unbound DNS --> Advanced`
     - :doc:`manual/unbound`
   * - :menuselection:`Services --> Unbound DNS --> Access Lists`
     - :doc:`manual/unbound`
   * - :menuselection:`Services --> Unbound DNS --> Query Forwarding`
     - :doc:`manual/unbound`
   * - :menuselection:`Services --> Unbound DNS --> Overrides`
     - :doc:`manual/unbound`
   * - :menuselection:`Services --> Unbound DNS --> Blocklist`
     - :doc:`manual/unbound`
   * - :menuselection:`Services --> Unbound DNS --> Log File`
     - :doc:`manual/unbound`
   * - :menuselection:`Services --> Captive Portal --> Administration`
     - :doc:`manual/captiveportal`
   * - :menuselection:`Services --> Captive Portal --> Sessions`
     - :doc:`manual/captiveportal`
   * - :menuselection:`Services --> Captive Portal --> Vouchers`
     - :doc:`manual/captiveportal`
   * - :menuselection:`Services --> Captive Portal --> Log File`
     - :doc:`manual/captiveportal`
   * - :menuselection:`Services --> Intrusion Detection --> Administration`
     - :doc:`manual/ips`
   * - :menuselection:`Services --> Intrusion Detection --> Administration --> General Settings`
     - :doc:`manual/ips`
   * - :menuselection:`Services --> Intrusion Detection --> Administration / Download`
     - :doc:`manual/ips`
   * - :menuselection:`Services --> Intrusion Detection --> Log File`
     - :doc:`manual/ips`
   * - :menuselection:`Services --> Monit --> Settings`
     - :doc:`manual/monit`
   * - :menuselection:`Services --> Monit --> Status`
     - :doc:`manual/monit`
   * - :menuselection:`Services --> Network Time --> Log File`
     - :doc:`manual/ntpd`
   * - :menuselection:`Services --> NDP Proxy --> Settings`
     - :doc:`manual/ndp-proxy-go`
   * - :menuselection:`Services --> NDP Proxy --> Settings --> Aliases`
     - :doc:`manual/ndp-proxy-go`
   * - :menuselection:`Services --> NDP Proxy --> Log File`
     - :doc:`manual/ndp-proxy-go`
   * - :menuselection:`Services --> NDProxy`
     - :doc:`manual/ndproxy`
   * - :menuselection:`Services --> Dynamic DNS --> Settings`
     - :doc:`manual/dynamic_dns`
   * - :menuselection:`Services --> Proxy --> Administration`
     - :doc:`manual/proxy`
   * - :menuselection:`Services --> Proxy --> Configuration`
     - :doc:`manual/proxy`
   * - :menuselection:`Services --> Web Proxy --> Administration`
     - :doc:`manual/proxy`
   * - :menuselection:`Services --> Web Proxy --> Access control`
     - :doc:`manual/proxy`
   * - :menuselection:`Services --> Web Proxy --> Log File`
     - :doc:`manual/proxy`
   * - :menuselection:`Services --> Nginx --> Configuration`
     - :doc:`manual/reverse_proxy`
   * - :menuselection:`Services --> Nginx --> Configuration --> HTTP(s)`
     - :doc:`manual/reverse_proxy`
   * - :menuselection:`Services --> Nginx --> Configuration --> HTTP(s) --> HTTP Server`
     - :doc:`manual/reverse_proxy`
   * - :menuselection:`Services --> Nginx --> Configuration --> HTTP(s) --> URL Rewriting`
     - :doc:`manual/reverse_proxy`
   * - :menuselection:`Services --> Caddy Web Server --> General Settings`
     - :doc:`manual/reverse_proxy`
   * - :menuselection:`Services --> Caddy Web Server --> General Settings --> Advanced Settings`
     - :doc:`manual/reverse_proxy`
   * - :menuselection:`Services --> Caddy Web Server --> General Settings --> DNS Provider`
     - :doc:`manual/reverse_proxy`
   * - :menuselection:`Services --> Caddy Web Server --> General Settings --> Log Settings`
     - :doc:`manual/reverse_proxy`
   * - :menuselection:`Services --> Caddy Web Server --> Reverse Proxy --> Domains`
     - :doc:`manual/reverse_proxy`
   * - :menuselection:`Services --> Caddy Web Server --> Reverse Proxy --> Handler`
     - :doc:`manual/reverse_proxy`
   * - :menuselection:`Services --> Caddy Web Server --> Reverse Proxy --> Handlers`
     - :doc:`manual/reverse_proxy`
   * - :menuselection:`Services --> Caddy Web Server --> Reverse Proxy --> Headers`
     - :doc:`manual/reverse_proxy`
   * - :menuselection:`Services --> Caddy Web Server --> Reverse Proxy --> HTTP Access --> Access Lists`
     - :doc:`manual/reverse_proxy`
   * - :menuselection:`Services --> Caddy Web Server --> Reverse Proxy --> HTTP Access --> Basic Auth`
     - :doc:`manual/reverse_proxy`
   * - :menuselection:`Services --> Caddy Web Server --> Log File`
     - :doc:`manual/reverse_proxy`
   * - :menuselection:`Services --> Caddy Web Server --> Diagnostics --> Caddyfile`
     - :doc:`manual/reverse_proxy`

-----------------------------
VPN
-----------------------------

.. list-table::
   :widths: 40 60
   :header-rows: 1

   * - Menu location
     - Documentation
   * - :menuselection:`VPN --> IPsec --> Connections`
     - :doc:`manual/vpnet`
   * - :menuselection:`VPN --> IPsec --> Tunnel Settings`
     - :doc:`manual/vpnet`
   * - :menuselection:`VPN --> IPsec --> Mobile Clients`
     - :doc:`manual/vpnet`
   * - :menuselection:`VPN --> IPsec --> Pre-Shared Keys`
     - :doc:`manual/vpnet`
   * - :menuselection:`VPN --> IPsec --> Key Pairs`
     - :doc:`manual/vpnet`
   * - :menuselection:`VPN --> IPsec --> Advanced Settings`
     - :doc:`manual/vpnet`
   * - :menuselection:`VPN --> IPsec --> Status Overview`
     - :doc:`manual/vpnet`
   * - :menuselection:`VPN --> IPsec --> Security Policy Database`
     - :doc:`manual/vpnet`
   * - :menuselection:`VPN --> IPsec --> Virtual Tunnel Interfaces`
     - :doc:`manual/vpnet`
   * - :menuselection:`VPN --> IPsec --> Log File`
     - :doc:`manual/vpnet`
   * - :menuselection:`VPN --> OpenVPN --> Instances`
     - :doc:`manual/vpnet`
   * - :menuselection:`VPN --> OpenVPN --> Servers`
     - :doc:`manual/vpnet`
   * - :menuselection:`VPN --> OpenVPN --> Clients`
     - :doc:`manual/vpnet`
   * - :menuselection:`VPN --> OpenVPN --> Client Specific Overrides`
     - :doc:`manual/vpnet`
   * - :menuselection:`VPN --> OpenVPN --> Client Export`
     - :doc:`manual/vpnet`
   * - :menuselection:`VPN --> OpenVPN --> Connection Status`
     - :doc:`manual/vpnet`
   * - :menuselection:`VPN --> OpenVPN --> Instances --> Static Keys`
     - :doc:`manual/vpnet`
   * - :menuselection:`VPN --> WireGuard --> General`
     - :doc:`manual/vpnet`
   * - :menuselection:`VPN --> WireGuard --> Instances`
     - :doc:`manual/vpnet`
   * - :menuselection:`VPN --> WireGuard --> Peers`
     - :doc:`manual/vpnet`
   * - :menuselection:`VPN --> WireGuard --> Settings`
     - :doc:`manual/vpnet`
   * - :menuselection:`VPN --> WireGuard --> Diagnostics`
     - :doc:`manual/vpnet`
   * - :menuselection:`VPN --> WireGuard --> Status`
     - :doc:`manual/vpnet`
   * - :menuselection:`VPN --> WireGuard --> Log File`
     - :doc:`manual/vpnet`
   * - :menuselection:`VPN --> WireGuard --> Peer generator`
     - :doc:`manual/vpnet`
   * - :menuselection:`VPN --> OpenConnect`
     - :doc:`manual/vpnet`
   * - :menuselection:`VPN --> Stunnel --> General`
     - :doc:`manual/vpnet`
   * - :menuselection:`VPN --> Stunnel --> Configuration`
     - :doc:`manual/vpnet`

-----------------------------
Diagnostics
-----------------------------

.. list-table::
   :widths: 40 60
   :header-rows: 1

   * - Menu location
     - Documentation
   * - :menuselection:`System --> Diagnostics --> Services`
     - :doc:`manual/diagnostics_system`
   * - :menuselection:`Interfaces --> Diagnostics --> ARP Table`
     - :doc:`manual/diagnostics_interfaces`
   * - :menuselection:`Interfaces --> Diagnostics --> NDP Table`
     - :doc:`manual/diagnostics_interfaces`
   * - :menuselection:`Interfaces --> Diagnostics --> Packet Capture`
     - :doc:`manual/diagnostics_interfaces`
   * - :menuselection:`Interfaces --> Diagnostics --> Ping`
     - :doc:`manual/diagnostics_interfaces`
   * - :menuselection:`Interfaces --> Diagnostics --> Trace Route`
     - :doc:`manual/diagnostics_interfaces`
   * - :menuselection:`Interfaces --> Diagnostics --> DNS lookup`
     - :doc:`manual/diagnostics_interfaces`
   * - :menuselection:`Firewall --> Diagnostics --> Aliases`
     - :doc:`manual/diagnostics_firewall`
   * - :menuselection:`Firewall --> Diagnostics --> Sessions`
     - :doc:`manual/diagnostics_firewall`
   * - :menuselection:`Firewall --> Diagnostics --> States`
     - :doc:`manual/diagnostics_firewall`
   * - :menuselection:`Firewall --> Diagnostics --> States Dump`
     - :doc:`manual/diagnostics_firewall`
   * - :menuselection:`Firewall --> Diagnostics --> Statistics`
     - :doc:`manual/diagnostics_firewall`
   * - :menuselection:`Firewall --> Diagnostics --> pfTable`
     - :doc:`manual/diagnostics_firewall`

------------------------------------
Optional / Plugin Menus (documented)
------------------------------------

These menus appear when the corresponding plugin is installed. They are listed
here so that all documented settings have a location reference.

.. list-table::
   :widths: 40 60
   :header-rows: 1

   * - Menu location
     - Documentation
   * - :menuselection:`Routing --> General`
     - :doc:`manual/dynamic_routing`
   * - :menuselection:`Routing --> BFD --> General`
     - :doc:`manual/dynamic_routing`
   * - :menuselection:`Routing --> BFD --> Neighbors`
     - :doc:`manual/dynamic_routing`
   * - :menuselection:`Routing --> BGP --> General`
     - :doc:`manual/dynamic_routing`
   * - :menuselection:`Routing --> BGP --> Neighbors`
     - :doc:`manual/dynamic_routing`
   * - :menuselection:`Routing --> BGP --> Prefix Lists`
     - :doc:`manual/dynamic_routing`
   * - :menuselection:`Routing --> BGP --> Route Maps`
     - :doc:`manual/dynamic_routing`
   * - :menuselection:`Routing --> OSPF --> General`
     - :doc:`manual/dynamic_routing`
   * - :menuselection:`Routing --> OSPF --> Interfaces`
     - :doc:`manual/dynamic_routing`
   * - :menuselection:`Routing --> OSPF --> Prefix Lists`
     - :doc:`manual/dynamic_routing`
   * - :menuselection:`Routing --> OSPF --> Route Maps`
     - :doc:`manual/dynamic_routing`
   * - :menuselection:`Routing --> OSPFv3`
     - :doc:`manual/dynamic_routing`
   * - :menuselection:`Routing --> RIP`
     - :doc:`manual/dynamic_routing`
   * - :menuselection:`Routing --> STATIC`
     - :doc:`manual/dynamic_routing`
   * - :menuselection:`Routing --> Diagnostics --> General`
     - :doc:`manual/dynamic_routing`
   * - :menuselection:`Routing --> Diagnostics --> BFD`
     - :doc:`manual/dynamic_routing`
   * - :menuselection:`Routing --> Diagnostics --> Log`
     - :doc:`manual/dynamic_routing`
   * - :menuselection:`Security --> Q-Feeds Connect`
     - :doc:`manual/qfeeds`
   * - :menuselection:`Services --> Wazuh Agent --> Settings`
     - :doc:`manual/wazuh-agent`
   * - :menuselection:`Services --> Wazuh Agent --> Logfile / active-responses`
     - :doc:`manual/wazuh-agent`

-----------------------------
Notes
-----------------------------

* The documentation set also contains a number of platform-specific or third-
  party UI steps (for example, operating system dialogs). Those are not OPNsense
  menus and are not listed here.
* Use the **Quick Navigation** search box in the OPNsense GUI to jump directly
  to any of these menu paths if you are unsure where a menu item lives.
