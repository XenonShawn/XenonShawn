Setting up of Wireguard:

Copy the `conf` file into `/etc/wireguard`.

```
sudo apt install wireguard

# Installs in such a way that allows me to toggle the wireguard config through the status bar.
sudo nmcli con import type wireguard file /etc/wireguard/wg0.conf
```
