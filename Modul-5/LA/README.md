

## Tugas Modul 1 - Cisco Switch Jakarta
1. SS Topologi Switch Jakarta
![vlan](images/topo.png)

2. Screenshot show vlan brief
![vlan](images/sw_vlan.png)

3. Screenshot show interfaces trunk.
![trunk](images/sw_trunk.png)

## Tugas Modul 2 - Cisco Router Jakarta

1. Screenshot hasil perintah show ip interface brief.
![](images/rjkt_ip.png)

2.  Screenshot hasil perintah show vrrp brief.
![](images/rjkt_vrrp.png)

3.  Screenshot konfigurasi lengkap subinterface (VLAN 10, 20, 60).
![](images/rjkt_run-conf.png)

4.  Screenshot hasil ping dari Cisco Router Jakarta ke FortiGate Jakarta (10.10.100.1).
![](images/rjkt_ping.png)

## Tugas Modul 3 - MikroTik Router Jakarta

1. Screenshot hasil perintah /ip address print.
![](images/mjkt_ip.png)

2. Screenshot hasil perintah /interface vrrp print.
![](images/mjkt_vrrp.png)

3. Screenshot hasil perintah /ip dhcp-relay print.
![](images/mjkt_dhcp-r.png)

4. Screenshot hasil perintah /ip route print.
![](images/mjkt_route.png)

5. Screenshot hasil ping dari MikroTik Jakarta ke FortiGate Jakarta (10.10.101.1).
![](images/mjkt_ping.png)

## Tugas Modul 4 - Ubuntu Server Jakarta

1. Screenshot hasil perintah ip a (menampilkan IP statis VLAN 60).
![](images/ubuntu_ip.png)

2. Screenshot hasil perintah ip route (menampilkan default gateway ke IP Virtual VRRP).
![](images/ubuntu_route.png)

3. Screenshot isi file konfigurasi /etc/dhcp/dhcpd.conf.
![](images/ubuntu_conf.png)

4. Screenshot hasil ping dari Ubuntu Server ke internet (ping 8.8.8.8).
![](images/ubuntu_ping.png)

## Tugas Modul 5 - FortiGate Jakarta

1. Screenshot hasil perintah get system interface physical.
![](images/fortijkt_inter.png)

2. Screenshot hasil perintah get router info routing-table all.
![](images/fortijkt_route.png)

3. Screenshot konfigurasi firewall policy di GUI/CLI.
![](images/fortijkt_fire.png)

4. Screenshot hasil ping dari FortiGate ke internet (8.8.8.8).
![](images/fortijkt_ping8.png)

5. Screenshot hasil ping ke IP Tunnel Surabaya (172.16.0.2).
![](images/fortijkt_pingsby.png)

6. Screenshot hasil perintah get router info ospf neighbor.
![](images/fortijkt_neigh.png)

7. Screenshot hasil perintah get router info routing-table ospf.
![](images/fortijkt_routeospf.png)

## Tugas Modul 6 - MikroTik ISP

1. Screenshot hasil perintah /ip address print.
![](images/isp_ip.png)

2. Screenshot hasil perintah /ip route print.
![](images/isp_route.png)

3. Screenshot hasil perintah /ip firewall nat print.
![](images/isp_fire.png)

4. Screenshot hasil ping dari MikroTik ISP ke internet (8.8.8.8).
![](images/isp_ping8.png)

5. Screenshot hasil ping antar-WAN FortiGate (ISP ke Jakarta dan ISP ke Surabaya).

## Tugas Modul 7 - Switch & MikroTik Surabaya

1. Screenshot hasil perintah show vlan brief di Switch Surabaya.
![](images/swsby_vlan.png)

2. Screenshot hasil perintah show interfaces trunk di Switch Surabaya.
![](images/swsby_trunk.png)

3. Screenshot hasil perintah /ip address print di MikroTik Surabaya.
![](images/msby_ip.png)

4. Screenshot hasil perintah /ip dhcp-server print di MikroTik Surabaya.
![](images/msby_dhcp.png)

5. Screenshot hasil perintah /ip pool print di MikroTik Surabaya.
![](images/msby_pool.png)

6. Screenshot hasil perintah /ip route print di MikroTik Surabaya.
![](images/msby_route.png)

7. Screenshot Client VLAN 30 (VPCS) saat berhasil mendapatkan IP melalui ip dhcp.
![](images/vlan30_ip.png)

8. Screenshot hasil ping dari Client Surabaya ke internet (8.8.8.8).

## Tugas Modul 8 - FortiGate Surabaya

1. Screenshot hasil perintah get system interface physical.
![](images/fortisby_inter.png)

2. Screenshot hasil perintah get router info routing-table all.
![](images/fortisby_route.png)

3. Screenshot konfigurasi firewall policy di GUI/CLI.
![](images/fortisby_fire.png)

4. Screenshot hasil ping dari FortiGate ke internet (8.8.8.8).
![](images/fortisby_ping8.png)

5. Screenshot hasil ping ke IP Tunnel Jakarta (172.16.0.1).
![](images/fortisby_pingjkt.png)

6. Screenshot hasil perintah get router info ospf neighbor.
![](images/fortisby_neigh.png)

7. Screenshot hasil perintah get router info routing-table ospf.
![](images/fortisby_routeospf.png)

## Tugas Modul 9 - GRE Tunnel & OSPF over GRE


1. Screenshot hasil ping jalur WAN antar-FortiGate.
![](images/pingwanjkt-sby.png)
![](images/pingwansby-jkt.png)


2. Screenshot hasil ping antar-IP IP Tunnel (172.16.0.1 <-> 172.16.0.2).
![](images/pinggrejkt-sby.png)
![](images/pinggresby-jkt.png)
4. Screenshot hasil perintah get router info ospf neighbor (memastikan status Full).
![](images/ospfneighborjkt.png)
![](images/ospfneighborsby.png)
6. Screenshot hasil perintah get router info routing-table ospf.
![](images/ospftablejkt.png)
![](images/ospftablesby.png)
8. Screenshot hasil ping dari Client Jakarta ke Client Surabaya.
![](images/pingclientjkt-sby.png)

10. Screenshot hasil ping dari Client Surabaya ke Client Jakarta.
![](images/pingclientsby-jkt.png)

## Tugas Modul 10 - Pengujian Akhir

1. Screenshot IP DHCP Client Jakarta (VLAN 10).
![](images/ipvlan10jkt.png)
2. Screenshot IP DHCP Client Surabaya (VLAN 30).
![](images/ipvlan30sby.png)
3. Screenshot ping internet (8.8.8.8) dari sisi Jakarta.
![](images/pingclientjkt-internet.png)
4. Screenshot ping internet (8.8.8.8) dari sisi Surabaya.
![](images/pingclientsby-internet.png)
5. Screenshot ping antar-site (Contoh: Klien VLAN 10 Jakarta ke Klien VLAN 40 Surabaya).
![](images/pingantarsite.png)
6. Screenshot sukses mengakses Nginx Web Server Jakarta (192.168.60.10) dari browser/PC Client Surabaya.
![](images/akseswebserverjktdarisurabaya.png)
7. Screenshot tabel routing OSPF akhir.
![](images/tabelospfjkt.png)
![](images/tabelospfsby.png)
9. Dokumen Tambahan: Analisis singkat mengenai jalur pergerakan traffic dari Jakarta ke Surabaya.
  Apabila misalnya ada client di surabaya melakukan ping ke Jakarta maka berikut adalah alur trafficnya:
Paket akan dikirim ke mikrotik Surabaya, tapi karena network tujuan tidak ada di routing table lokal, maka paket akan diteruskan ke Fortigate Surabaya melalui port2. Setelah itu, Fortigate akan melakukan lookup routing table dan mencari ospf routing yang akan mengarahkan paket ke Fortigate Jakarta melalui GRE-Tunnel. GRE akan mengenkapsulasi paket dan meneruskannya melalui WAN ke mikrotik ISP yang akan meneruskannya ke Fortigate Jakarta. Fortigate akan melakukan de-enkapsulasi paket lalu melakukan lookup routing table untuk mencari network tujuan. Paket akan diteruskan ke Cisco Router Jakarta atau Mikrotik Jakarta berdasarkan VRRP Masternya, lalu ke switch Jakarta melalui trunk sebelum ke tujuan akhir.



