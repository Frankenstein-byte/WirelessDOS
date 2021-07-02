# WirelessDOS
Python Script to automate de-authentication attacks

This script uses Wi-Fi deauthentication messages to stop all users from accessing a wifi network. In the background, we are using airmon-ng and airodump-ng to launch our attack.

## Features

* Automates to process of converting adapter to monitor mode (Airodump-ng)
* Kills all background process that may interrupt with working of adapter
* Give user options to directly select client/host to attack on
* Automates the process of De-auth (Aireplay-ng)
* Cleaning up the process
* Switches back to managed mode and turn on all network management services

## Usage

```python
sudo python3 wirelessDOS1.py
```



## Notice

This script is for educational purposes only. Do not use against any network that you don't own or have authorization to test.


## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

