
## Firewall

The following commands must be run to open the relevant firewall ports for syncthing. Replace `syncthing`
with the name of the jail.

```
bastille rdr syncthing tcp 22000 22000
bastille rdr syncthing udp 22000 22000
bastille rdr syncthing udp 21027 21027
```
