# Aruba Wireless & VLAN Infrastructure

Hands-on CSN405 wireless networking lab focused on Aruba 7005 controller administration, VLAN verification, access switching, DHCP/IP connectivity, and troubleshooting through both CLI and GUI workflows.

## Verified Lab Environment

- Aruba 7005 wireless controller
- ArubaOS 8.3.0.9
- Controller name: `CSN405-group-G`
- Controller IPv4 address: `172.16.0.1`
- VLAN 1: `172.16.0.1/24`
- Aruba 2540 / 2530 switching used across related wireless/networking labs
- WLAN, VLAN, DHCP, IPv4, gateway and client-connectivity concepts

## Completed Evidence Recovered

A completed screenshot-only course submission was recovered. It contains actual verification captures for:

- `show ip interface brief`
- `show controller-ip`
- `show clock`
- `show vlan`
- Aruba Mobility Controller web dashboard

The CLI evidence shows VLAN 1 and the controller interface operational at `172.16.0.1/24`. The GUI evidence shows the Aruba 7005 controller, ArubaOS version, controller IP, deployment role, port state and event information.

## Demonstrated Skills

- Accessed and verified an Aruba wireless controller through CLI and web GUI
- Checked interface status, controller addressing, VLAN membership and operational state
- Worked with VLAN-based wired/wireless connectivity concepts
- Practiced DHCP/IP addressing and gateway troubleshooting
- Used a structured verify-isolate-test workflow for controller and client connectivity

## Documentation

- `docs/completed-evidence.md` — recovered completed-submission evidence
- `docs/lab-topology.md` — lab environment and logical traffic flow
- `docs/troubleshooting.md` — wireless/VLAN troubleshooting workflow

> Student-identifying information from the original submission is intentionally not published.

## Project Type

Completed academic wireless networking lab — Seneca Polytechnic, CSN405.