# Lab Topology

The recovered CSN405 lab evidence shows an Aruba 7005 wireless controller working with Aruba access switching in a VLAN-based wireless environment.

## Logical Flow

```text
Wireless Client
      |
     WLAN
      |
Aruba 7005 Controller
      |
   VLAN / Trunk
      |
Aruba Access Switch
      |
 DHCP / Gateway
      |
 Campus / Lab Network
```

## Known Lab Detail

- Controller platform: Aruba 7005
- ArubaOS version observed: 8.3.0.9
- Controller/VLAN management IP observed in lab notes: `172.16.0.1/24`
- Access switching involved Aruba 2540/2530-class equipment

The topology document intentionally avoids inventing exact SSID names or port numbers that were not recovered with sufficient confidence.