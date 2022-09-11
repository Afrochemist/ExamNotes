This file contains notes for the OSWP

**Airmon Commands**

- converting wifi card from manager to monitor mode
sudo airmon-ng start <wifi card>

- wifi enumerating(modify)
sudo airodump-ng <wifi card>

- filtering by channel
sudo airodump-ng <wifi card>

- capturing packets on a specific AP
sudo airodump-ng -c <channel> --bssid <AP MAC> -w <file> <wifi card>

(Need to include commands for various injection test)
