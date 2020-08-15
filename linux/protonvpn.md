### ProtonVPN

```bash
sudo apt install -y openvpn dialog python3-pip python3-setuptools
sudo pip3 install protonvpn-cli
sudo pip3 install protonvpn-cli --upgrade
```

### Proton VPN Commands

Initialize ProtonVPN profile

```
protonvpn init 
```

Select a ProtonVPN server and connect to it

```
protonvpn c 
```

 Connect to a specified server.
 
```
protonvpn c [servername]
```

Connect to a random server

```
protonvpn c -r 
```

Connect to the fastest server
```
protonvpn c -f 
```

Connect to the fastest P2P server.
```
protonvpn c --p2p 
```

Connect to the fastest server in a specified country. 
```
protonvpn c --cc [countrycode]
```

 Connect to the fastest Secure Core server.
```
protonvpn c --sc
```

Reconnect or connect to the last server used.

```
protonvpn r
```

Disconnect the current session.
```
protonvpn d 
```

Print connection status.
```
protonvpn s 
```

Change CLI configuration.
```
protonvpn configure 
```

Refresh OpenVPN configuration and server data.
```
protonvpn refresh 
```

Print example commands.
```
protonvpn examples 
```
Display version.
```
protonvpn --version 
```

Show help message.
```
protonvpn --help 
```
