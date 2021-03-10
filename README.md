# ioLibrary Driver
La ioLibrary significa “Internet Offload Library” para el chip WIZnet. Incluye controladores y protocolos de aplicación.
Los driver (ioLibrary) se puede utilizar para el diseño de aplicaciones de chips WIZnet TCP / IP como [W5500](http://wizwiki.net/wiki/doku.php?id=products:w5500:start), W5300, W5200, W5100 [W5100S](http://wizwiki.net/wiki/doku.php?id=products:w5100s:start).

## ioLibrary
Este controlador proporciona las API de tipo Berkeley Socket.
- Structura del Directorio
<!-- ioLibrary pic -->
![ioLibrary](http://wizwiki.net/wiki/lib/exe/fetch.php?media=products:w5500:iolibrary_bsd.jpg "ioLibrary")

- Ethernet : SOCKET APIs like BSD & WIZCHIP([W5500](http://wizwiki.net/wiki/doku.php?id=products:w5500:start) / W5300 /  W5200 / W5100 / [W5100S](http://wizwiki.net/wiki/doku.php?id=products:w5100s:start)) Driver
- Internet :
  - DHCP client
  - DNS client
  - FTP client
  - FTP server
  - SNMP agent/trap
  - SNTP client
  - TFTP client
  - HTTP server
  - MQTT Client
  - Others will be added.

## Cómo agregar ioLibrary en tu proyecto
  - Ejemplo: https://github.com/Leimer-G/stm32f4-eth-uart-communication
  - Se muestra una explicacion de como usar ioLibrary
    - Definir en qué chip se utiliza **wizchip_conf.h**
    - Defina en qué modo Host I / F se utiliza **wizchip_conf.h**


