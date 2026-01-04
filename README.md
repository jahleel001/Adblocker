# AdGuard DNS Sinkhole Project

This repository documents my setup and implementation of an AdGuard DNS sinkhole on a Raspberry Pi to improve network security and privacy by blocking unwanted domains and ads on my home network.

---

## Project Overview

- Installed **AdGuard Home** on a Raspberry Pi.
- Configured it as a DNS sinkhole to block malicious, tracking, and advertising domains.
- Routed network DNS queries through the Raspberry Pi for filtering.
- Monitored and analyzed DNS queries using the AdGuard dashboard.
- Enhanced network performance and privacy by blocking unnecessary traffic.

---

## Setup & Configuration

1. Flash Raspberry Pi OS onto an SD card and boot the Raspberry Pi.
2. Download and install [AdGuard Home](https://github.com/AdguardTeam/AdGuardHome).
3. Access the AdGuard Home web dashboard.
4. Configure upstream DNS servers and customize blocklists.
5. Set your router or devices to use the Raspberry Pi’s IP address as the primary DNS server.
6. Monitor queries and update blocklists as needed.

---

## Screenshots

### AdGuard Home Dashboard![539A0D8D-6873-4E6C-B748-4146485D9F08_1_105_c](https://github.com/user-attachments/assets/9829bc16-e803-49bb-9ca9-b4c7d26e5b7e)


![ADD37468-B632-46DE-8417-A8EC0785342E_1_105_c](https://github.com/user-attachments/assets/c486f587-3d37-407d-98ec-52c1a7cd4646)

### DNS Query Logs and Blocked Domains
![DNS Query Logs]()![C4F848FA-EEF5-43FD-A0DB-A95EC7446DC6_1_105_c](https://github.com/user-attachments/assets/54068193-07c0-485d-9c17-bd0dd4c51188)


---

## Benefits

- Blocks ads and trackers on all devices connected to the network.
- Prevents access to malicious and phishing domains.
- Centralized DNS filtering and monitoring.
- Easy to manage via the web interface.
