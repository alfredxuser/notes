[Root](../index.md) >

### UFW
###### Uncomplicated Firewall ~ For Debian/Ubuntu distributions

```bash
 $ sudo apt install ufw
```

---

## Usage

Enable/Disable firewall

```bash
 $ sudo ufw enable

 $ sudo ufw disable
```

Firewall status
```bash
 $ sudo ufw status verbose
```

Allow by port/protocol

```bash
 $ sudo ufw allow 3000/tcp
```

Firewall status rules
```bash
 $ sudo ufw status numbered
```

Firewall block connection
```bash
 $ sudo ufw deny 1                  # deny by rule

 $ sudo ufw deny 3000/tcp           # deny by app
```

Firewall delete
```bash
 $ sudo ufw delete 1                # delete by rule

 $ sudo ufw delete allow 3000/tcp   # delete by app
```

Firewall reset defaults
```bash
 $ sudo ufw reset
```
---

Firewall list apps
```bash
 $ sudo ufw app list
```

Allow by app
```bash
 $ sudo ufw allow 'http'
```

Allow by port range
```bash
 $ sudo ufw allow 3000:3030/tcp

 $ sudo ufw allow 80:88/udp
```

Allow by ip address
```bash
 $ sudo ufw allow from 192.168.100.2
```
---

[Back to top](#UFW)

[Root](../index.md) >
