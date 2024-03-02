# Aircrack-ng

## Description

Aircrack-ng is a complete suite of tools to assess WiFi network security.

#### aircrack-ng
- calculates WEP key (brute force) and WPA key (dictionary attack)
#### airodump-ng
- Packet sniffer: records data traffic in pcap or IVs files and shows information about networks
#### aireplay-ng
- injects self-generated packets into networks
#### airdecap-ng
- Decrypts recorded encrypted WEP or WPA data using an already known key
#### airmon-ng
- puts WLAN cards under Linux into monitor mode
#### airtun-ng
- creates virtual tunnels
#### airolib-ng
- stores and manages ESSID and password lists (for calculating WPA keys)
#### wesside-ng
- automatically calculates the WEP keys of detected networks (unstable)
#### airdriver-ng
- builds and installs WLAN drivers under Linux
#### airbase-ng 
- simulates access points based on received SSID scans from end devices and thus makes it possible to
  intercept WEP or WPA keys in the absence of the access point by attacking the end device
#### airserv-ng 
- enables the use of a WLAN card that is not connected locally via a TCP connection (wireless card server)

## Examples

``` shell
# put your wireless card into monitor mode using airmon-ng
airmon-ng start wlan0

# to look out for networks
airodump-ng wlan0mon

```

## Additional informations

!!! info "Links"
    - Website: [https://www.aircrack-ng.org/](https://www.aircrack-ng.org/)
    - Docs: [https://www.aircrack-ng.org/documentation.html](https://www.aircrack-ng.org/documentation.html)
    - Source: [https://github.com/aircrack-ng/aircrack-ng](https://github.com/aircrack-ng/aircrack-ng)

!!! tip "Alternatives"
    - airgeddon