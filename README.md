# Basic Wireless Manager 


 WPA Connect (command wconnect)
 2009-2015 Hpsaturn v1.3
 hpsaturn@gmail.com

## Installation:

 - mkdir CPATH and link symbolic on home root to this (see config section)
 - copy this script on ~/bin and make link simbolic on /usr/bin

## Main Commands:

#### Add new network:

   ```
   $ wconnect name ssid passw 
   ```

#### Connect to network automatically

   ```
   $ sudo wconnect 
   ```

#### Force connect to specific network

   ```
   $ sudo wconnect networkname
   ```

#### Scan networks

   ```
   $ sudo wconnect scanning
   ```

## Others commands (WPA):

**stop**      (down interface and kill wpasupplicant)
**remove**    (remove driver module)
**install**   (install driver module)
**auto**      (default)(scan and search networks on config directory then connect)

## Others wifi encryption:

   open ssid         (connect to open network)
   adhoc ssid passw  (connect to Ad-Hoc wifi)
   wep ssid passw    (connect to wep wifi) 

## Others:

**switch**    (switch to eth0)

