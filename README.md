# docker-transparent-proxy

## Purpose

A transparent proxy for your docker containers with dynamic proxy switch depending your urls / ip.

It means that when you use this proxy:
- All you containers should use this proxy (run in a container too)
- This proxy will route the network flows depending the **proxy.pac** script you will provide
- You are able to handle multiple corporate proxies dependending host / ip you want to reach (thanks to your custom proxy.pac script)

## Credits

- Thanks to **Romain** from the initial version I reuse for this project
- Thanks to **tootallnate** to profile the [pac-proxy-agent](https://www.npmjs.com/package/pac-proxy-agent) package for node that is beeing used in this transparent proxy
- Thanks to **Loic** and **Thomas** for their specific integration model in boot2docker
