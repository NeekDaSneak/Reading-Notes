# Pfsense

- Open source firewall and router
- Can be completely virtualized or deployed to an appliance
- Computer tower
- Netgate device or other compatible device

- Why are we choosing pfsense
  - Generally its the community choice for an open source firewall/ router solution for home lab
  - Alternatives include DD-WRT or OpenWRT
  - Free
- Why are we virtualizing it instead of using hardware?
  - Hardware is great!
  - Downside is it costs money, electricity, and space
  - Can deploy to virtualbox to create a contained LAN
- DHCP Server
  - Automatically assigns ip address to hosts
  - Sometimes this is hosted on a windows or linux server instead
- Network perimeter firewall
  - Simple SoHo routers have simplistic firewalls
  - Enterprise grade routers tend to have higher firewall capabilities.
    - Unified Threat MAnagement (UTM) Appliances are popular
- Wi-Fi
  - SoHo Routers always have Wi-Fi rabbit ears because they're made for servicing smaller areas
  - Enterprise grader routers wont have Wi-fi because you'll deploy Wireless Access Points (WAPs) instead
  - Access Points (APs) create a mesh network over a corporate campus
  - Some Home Wi-Fi appliances now support meshed AP infrastructure
