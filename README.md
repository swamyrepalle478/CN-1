# CN-1
# LAN Network Configuration and Connectivity Testing

## Aim

To study network devices and test connectivity between computers in a Local Area Network (LAN) using IP configuration and the ping command.

## Objectives

* Study Hub, Switch, Router, Bridge, Repeater, Gateway, and NIC.
* Understand LAN connections using an Ethernet switch.
* Display IP configuration details.
* Test connectivity between computers using ping.

## Requirements

* Python 3
* Two or more computers connected to the same LAN
* Ethernet switch and Ethernet cables, or an existing network
* Windows or Linux operating system

## Program

The `lan_test.py` program displays network configuration information and allows users to test connectivity with another computer's IPv4 address.

## How to Run

1. Install Python 3.
2. Download or clone this repository.
3. Open a terminal in the project folder.
4. Run:

```bash
python lan_test.py
```

On some Linux systems, use `python3 lan_test.py`.

## Sample IP Configuration

| Computer | IP Address   | Subnet Mask   |
| -------- | ------------ | ------------- |
| PC1      | 192.168.1.10 | 255.255.255.0 |
| PC2      | 192.168.1.11 | 255.255.255.0 |
| PC3      | 192.168.1.12 | 255.255.255.0 |

Default gateway: 192.168.1.1, if a router with that address is present.

## Sample Test

From PC1, enter `192.168.1.11` to test connectivity to PC2.

Successful ping replies indicate that the target computer is reachable.

## Result

The program displays IP configuration details and tests LAN connectivity using the ping command.

Note: Actual connectivity results depend on the network configuration and firewall settings.
