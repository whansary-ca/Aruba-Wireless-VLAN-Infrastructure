# Wireless & VLAN Troubleshooting

## Client Does Not Receive an IP Address

Check whether the client joined the expected WLAN, confirm VLAN mapping, verify switch-port membership/tagging, confirm the DHCP service is reachable, and validate the VLAN gateway.

## Client Associates but Cannot Reach the Gateway

Verify the assigned IP/subnet, default gateway, VLAN membership across controller/switch links, and whether the gateway interface is active.

## VLAN Traffic Does Not Pass Between Devices

Compare tagged/untagged membership on both ends of the link, confirm VLAN IDs match, and validate the physical port state before changing higher-layer settings.

## Controller Access Issues

Confirm management addressing, local reachability, browser/CLI access, and the correct interface/VLAN before changing controller settings.

## Validation Sequence

1. Physical link up
2. Correct VLAN membership
3. Wireless association
4. DHCP lease
5. Gateway ping
6. DNS/network access
7. Application connectivity

This layered method helps isolate whether the fault is wireless, switching, addressing, or upstream connectivity.