# CCNA Network Portfolio

Kumpulan lab jaringan Cisco yang saya kerjakan selama training **CCNA 200-301** (ID-Networkers, 12-15 Oktober 2026) menggunakan **Cisco Packet Tracer**. Setiap lab berisi tujuan, topologi, tabel IP, konfigurasi, penjelasan, bukti verifikasi, serta masalah dan solusinya.

**Cahaya Jaya Prabasa** · Fresh graduate D4 Teknik Telekomunikasi, Politeknik Negeri Semarang<br>
Fokus: jaringan dan keamanan jaringan (Cisco CCNA, MikroTik MTCNA)

## Daftar lab

| No | Lab | Topik utama | Status |
| --- | --- | --- | --- |
| 01 | [HSRP](01-hsrp/) | Gateway redundan, NAT overload, uji failover | Selesai |
| 02 | [InterVLAN Router](02-intervlan-router/) | VLAN, trunk, router on a stick | Selesai |
| 03 | Link Aggregation | EtherChannel LACP antar MLS | Menyusul |
| 04 | STP | Rapid-PVST, root bridge | Menyusul |
| 05 | WLC | Wireless LAN Controller | Menyusul |
| 06 | Routing | Static route, OSPF, ACL antar site | Menyusul |
| 07 | InterVLAN MLS + DHCP | Routing antar VLAN di MLS, DHCP relay | Menyusul |
| 08 | Super lab | Gabungan seluruh konfigurasi | Menyusul |

## Skill yang ditunjukkan

- **Switching:** VLAN, trunk, EtherChannel, STP
- **Routing:** static route, OSPF, inter-VLAN routing, MLS
- **IP services:** DHCP dan DHCP relay, NAT/PAT
- **Redundansi:** HSRP
- **Keamanan:** ACL, port security, SSH
- **Wireless:** WLC dan AP

## Struktur tiap lab

```
NN-nama-lab/
├── README.md        # tujuan, topologi, konfigurasi, verifikasi
├── configs/         # konfigurasi per perangkat (.txt)
├── images/          # screenshot bukti
└── NAMA-LAB.pkt     # file Packet Tracer
```

## Catatan

Semua password pada konfigurasi dan screenshot sudah diganti `<password>`.
