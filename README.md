# zvadohacks

zvadohacks are tools build with python for web scouting sniffing and pen testing

## Tools
 
```
mac-change
```
Change your mac address just with a simple command whenever you want.
```
net-scan
```
Scan all the devices on your wifi and diplay infromataion such as ip address mac address and manufacturer (make sure to include /24 at the end of the ip or you will not see all devices.)
```
net-spoof
```
Trick the router and the victim by sending ARP packet to both with the MAC address of each other and become man in the middle listen for traffick.

### Usage
mac-change
```
cd ../change-mac
sudo python3 mac_change.py -i [intefrace goes here] -m [new mac goes here]
```
net-scan
```
cd ../net-scan
sudo python3 netscan.py -i [IP address goes here]
```
net-spoof
```
currently being worked on will update once done
```


## Prerequisites

```
- python 2.7
- python 3.0
- git
- pip
- pip3 install mac-vendor-lookup
- pip install --pre scapy[complete]
```

### Installing


```
clone repo
```
```
cd into cloned repo
```
```
to run a tool use python3 [name of tool] [options]
```

## Built With

* [Python 2.7/3](https://www.python.org/) - Language used to write the tools

* [Ubuntu Linux](https://ubuntu.com/) - OS used

## Authors

* **Viktor Draganov** - *Initial work* - [viktor111](https://github.com/viktor111)

