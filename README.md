# Basic Wireless Manager 

WPA, WEP, Open and Ad-Hoc wifi networks manager. 

(2009-2016 @Hpsaturn)

## Installation:

1. mkdir CPATH and link symbolic on home root to this (see config section)
2. copy this script on ~/bin and make link simbolic on /usr/bin

## Main Commands:

##### Add new network:

   ```
   $ wconnect name ssid passw 
   ```

##### Connect to network automatically

   ```
   $ sudo wconnect 
   ```

##### Force connect to specific network

   ```
   $ sudo wconnect networkname
   ```

##### Scan networks

   ```
   $ sudo wconnect scanning
   ```

## Others commands:

##### General:

- **stop**      (down interface and kill wpasupplicant)
- **remove**    (remove driver module)
- **install**   (install driver module)
- **auto**      (default)(scan and search networks on config directory then connect)

##### Alternative encryption:

- **open** ssid          (connect to open network)
- **adhoc** ssid passw   (connect to Ad-Hoc wifi)
- **wep** ssid passw     (connect to wep wifi) 

##### Tools commands:

- **switch**    (switch to eth0)

