# Upnp-Forwarding
Port forwarding using Upnp.

This program has been used to open and close ports on game servers using Upnp, now I'm sharing it in case it works for you.

## Description
This program will **open/close Upnp ports** without the need to enter your router manually, only remember to have activated the *UPNP Enabled* option of your router.


## Requeriments
A device as you router with Upnp support and enabled it.

## OS Target
- Windows

## GUI
Screenshot

![alt text](https://raw.githubusercontent.com/HomieStart/Upnp-Forwarding/main/resources/gui_screenshot.png "GUI Screenshot")

## CMD
**You can directly use it with cmd using the arguments:**

*action=[OPEN|CLOSE] protocol=[TCP|UDP|BOTH] port=[NUMBER]*

### Examples
Open ports for minecraft or terraria server with Upnp port 7777 using TCP/UDP:

* *action=open protocol=both port=7777*

Open ports for valheim server with Upnp port 2456 using TCP/UDP:

* *action=open protocol=both port=2456*

Open ports for randomly game or application Upnp port 12345 using only TCP:

* *action=open protocol=tcp port=12345*

Open ports for randomly game or application Upnp port 12345 using only UDP:

* *action=open protocol=udp port=12345*

Close ports for randomly game or application Upnp port 12345 TCP/UDP:

* *action=close protocol=both port=12345*


## Future plans:
* Headless
* Other OS Support
