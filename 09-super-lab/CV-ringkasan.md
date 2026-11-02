# Ringkasan untuk CV dan LinkedIn

**Nama proyek:** Multi-Site Enterprise Network dengan OSPF dan eBGP (Cisco Packet Tracer)
**Tautan:** https://github.com/WYdfawyt/ccna-network-portfolio/tree/main/09-super-lab

## Bahasa Indonesia

Merancang dan mengimplementasikan jaringan multi-site (Datacenter, Jakarta, Semarang) yang dihubungkan melalui satu ISP transit.

- Menerapkan **OSPF area 0** di setiap site dan **eBGP** antar site dengan tiga AS (65000, 65100, 65200)
- Menyebarkan rute BGP ke OSPF (redistribusi) sehingga seluruh MLS dan router mengetahui prefix site lain
- Membangun segmen peering ISP pada **VLAN 100** dengan satu ISP-Router sebagai speaker BGP untuk empat router border
- Memetakan topologi dengan `show cdp neighbors`, menemukan dan memperbaiki kesalahan jalur peering ISP
- Memverifikasi konektivitas end-to-end antar tiga site, termasuk kebijakan ACL, dan mendokumentasikannya di GitHub

## English

Designed and implemented a multi-site enterprise network (Datacenter, Jakarta, Semarang) connected through a single transit ISP.

- Deployed **OSPF area 0** inside each site and **eBGP** between sites across three autonomous systems (65000, 65100, 65200)
- Redistributed BGP routes into OSPF so every multilayer switch and router learns remote-site prefixes
- Built an ISP peering segment on **VLAN 100** with one ISP router acting as the BGP speaker for four border routers
- Mapped the topology with `show cdp neighbors`, then found and fixed a peering-path error on the ISP side
- Verified end-to-end connectivity across the three sites, including ACL policy, and documented the work on GitHub

## Kata kunci (ATS)

OSPF, BGP, eBGP, route redistribution, VLAN, inter-VLAN routing, DHCP relay, ACL, HSRP, NAT, GRE, Cisco IOS, Packet Tracer, network design, troubleshooting, CCNA
