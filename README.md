# Pi-hole DNS Home Lab

## Project Overview
This project documents my deployment of Pi-hole on a Raspberry Pi 5 to provide DNS filtering and ad blocking for my home network.

## Goals
- Install and configure Pi-hole on a Raspberry Pi
- Understand DNS and DHCP behavior in a real home network
- Configure router DNS settings
- Troubleshoot IP address changes and connectivity issues
- Document the lab in a professional GitHub format

## Lab Environment
- Raspberry Pi 5
- Pi-hole
- Home router
- Ethernet connection
- Windows laptop
- Local network: 192.168.0.0/24

## What I Built
I installed Pi-hole on a Raspberry Pi and configured it as a DNS filtering device for my home network. During the setup, I worked through DHCP and DNS configuration issues, including the Raspberry Pi receiving a different IP address than expected.

## Key Troubleshooting Moment
The Raspberry Pi was originally expected to use `192.168.0.201`, but it later appeared on the network as `192.168.0.117`. This helped reinforce the importance of DHCP reservations, static IP planning, and verifying device addresses directly from the router.

## Skills Demonstrated
- DNS fundamentals
- DHCP troubleshooting
- Raspberry Pi setup
- Home network configuration
- IP addressing
- Network documentation
- Troubleshooting connectivity issues

## Screenshots
_Add screenshots here._

## Network Diagram
_Add draw.io diagram here._

## Lessons Learned
- DNS changes can affect access to network resources if configured incorrectly.
- DHCP can assign a new IP address unless a reservation or static configuration is used.
- Router dashboards are useful for identifying device IP changes.
- A simple home lab can create real troubleshooting experience.

## Next Steps
- Add a DHCP reservation for the Raspberry Pi
- Identify unknown devices using nmap
- Improve network diagram
- Explore Unbound for recursive DNS
