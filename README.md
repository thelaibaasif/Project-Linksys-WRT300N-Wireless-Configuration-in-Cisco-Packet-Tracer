# Linksys WRT300N Wireless Configuration in Cisco Packet Tracer

## Description
This project demonstrates the configuration of a Linksys WRT300N wireless access point using Cisco Packet Tracer. Tasks include changing SSID, enabling WEP and WPA2 security, configuring MAC filters, and testing connectivity with various devices. The project emphasizes practical skills in setting up and securing a wireless network, including advanced configuration options.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Requirements](#requirements)
- [Usage](#usage)
  - [Task 1: Connect to Wireless Router](#task-1-connect-to-wireless-router)
  - [Task 2: Change SSID](#task-2-change-ssid)
  - [Task 3: Enable WEP Security](#task-3-enable-wep-security)
  - [Task 4: Connect Laptops using WEP](#task-4-connect-laptops-using-wep)
  - [Task 5: Enable WPA2 Security](#task-5-enable-wpa2-security)
  - [Task 6: Connect Smartphones using WPA2](#task-6-connect-smartphones-using-wpa2)
  - [Task 7: Connect Laptops using WPA2](#task-7-connect-laptops-using-wpa2)
  - [Task 8: Enable MAC Filter for Laptops](#task-8-enable-mac-filter-for-laptops)
  - [Task 9: MAC Filter for Specific Devices](#task-9-mac-filter-for-specific-devices)
  - [Task 10: Disable SSID Broadcast](#task-10-disable-ssid-broadcast)
- [Conclusion](#conclusion)
- [License](#license)

## Introduction
In this project, you will learn how to configure a Linksys WRT300N wireless access point using Cisco Packet Tracer. This includes tasks such as changing the SSID, enabling various types of wireless security, configuring MAC address filters, and testing network connectivity.

## Features
- Configure SSID on Linksys WRT300N
- Enable WEP and WPA2 security
- Configure MAC address filters
- Test connectivity with laptops and smartphones

## Requirements
- Cisco Packet Tracer software
- Basic understanding of wireless networking
- Knowledge of configuring network devices in Cisco Packet Tracer

## Usage

### Task 1: Connect to Wireless Router
1. Connect to the Linksys WRT300N router via browser using Laptop1.
    - Login: `admin`
    - Password: `admin`

### Task 2: Change SSID
1. Change the SSID name to `bvi`.

### Task 3: Enable WEP Security
1. Enable WEP wireless security with a key consisting of 10 Hex digits: `12345abcde`.

### Task 4: Connect Laptops using WEP
1. Connect Laptop1 and Laptop2 to the wireless network `bvi` using the WEP key.
2. Ping the server at `10.0.0.2` from both laptops.

### Task 5: Enable WPA2 Security
1. Change wireless security on WRT300N to WPA2 PSK AES.
2. Set the passphrase to `ciscocisco`.

### Task 6: Connect Smartphones using WPA2
1. Connect Smartphone1 and Smartphone2 to the wireless network `bvi` using the WPA2 PSK passphrase.
2. Ping the server at `10.0.0.2` from both smartphones.

### Task 7: Connect Laptops using WPA2
1. Connect Laptop1 and Laptop2 to the wireless network `bvi` using the WPA2 PSK passphrase.
2. Ping the server at `10.0.0.2` from both laptops.

### Task 8: Enable MAC Filter for Laptops
1. Enable Wireless MAC filter and allow wireless access for Laptop1 and Laptop2.
2. Ping the server at `10.0.0.2` from Laptop1, Laptop2, Smartphone1, and Smartphone2.

### Task 9: MAC Filter for Specific Devices
1. Change the MAC filter to allow all devices except Laptop1.
2. Ping the server at `10.0.0.2` from Laptop1, Laptop2, Smartphone1, and Smartphone2.

### Task 10: Disable SSID Broadcast
1. Disable SSID broadcast.
2. Check visibility of the network from Laptop1.

## Conclusion
This project covers the essential tasks for configuring a Linksys WRT300N wireless access point using Cisco Packet Tracer. By following the tasks, you will gain practical experience in setting up and securing a wireless network.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
