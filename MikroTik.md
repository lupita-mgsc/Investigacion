# MikroTik
## *Sobre MikroTik*
MikroTik es una compañía fundada en 1995 en Riga, capital de Latvia, creada para desarrollar routers y sistemasinalámbricos para Proveedores de Servicios de Internet (ISP – Internet Service Provider).


![enter image description here](https://i0.wp.com/elviajenotermina.com/wp-content/uploads/2017/08/riga_letonia_blog-viajes_el-viaje-no-termina.jpg)

En 1997 MikroTik creó el sistema de software RouterOS que proporciona estabilidad, control y flexibilidad para todos lostipos de interfaces de datos y ruteo.
En el 2002 MikroTik decidió fabricar su propio hardware y de esta forma nace el RouterBOARD.  MikroTik tiene distribuidoresen muchas partes del mundo, y clientes probablemente en casi todos los países del planeta.


## *¿Qué es RouterOS?*
MikroTik RouterOS es el sistema operativo del hardware MikroTik RouterBOARD, que tiene las características necesariaspara un ISP: Firewall, Router, MPLS, VPN, Wireless, HotSpot, Calidad de Servicio (QoS), etc.

RouterOS es un sistema operativo independiente basado en el kernel de Linux v3.3.5 que proporciona todas las funcionesen una instalación rápida y sencilla, con una interfaz fácil de usar.

RouterOS puede instalarse en PCs y otros dispositivos de hardware compatibles con x86, como tarjetas embebidas ysistemas miniITX. RouterOS soporta computadores multi-core y multi CPU. Soporta tambien Multiprocesamiento Simétrico(SMP: Symmetric MultiProcessing). Se puede ejecutar en los motherboards Intel más recientes y aprovechar los nuevosCPUs multicore.

## *Multiprocesamiento Simétrico*
Es una arquitectura de Software y Hardware donde dos o más procesadores idénticos son conectados a una simple memoriacompartida, teniendo acceso a todos los dispositivos I/O (entrada y salida), y que son controlados por una simple instanciadel OS (Sistema Operativo), en el cual todos los procesadores son tratados en forma igualitaria, sin que ninguno seareservado para propósitos especiales.

En el caso de los procesadores multi-core (multi-núcleo), la arquitectura SMP se aplica a los núcleos, tratándolos comoprocesadores separados.

El RouterOS formateará la partición y se convertirá en el sistema operativo por default del dispositivo. Soporta una granvariedad de interfaces de red, incluyendo tarjetas Ethernet de 10 Gigabit, tarjetas wireless 802.11a/b/g/n/ac y módems 3G y4G.

***Fechas de liberación de las versiones de RouterOS.***

• v6 - May 2013
• v5 - Mar 2010
• v4 - Oct 2009
• v3 - Ene 2008

## *Característica de RouterOS*

***Soporte de Hardware***

• Compatible con arquitectura i386
• Compatible con SMP (multi-core y multi-CPU)
• Requiere un mínimo de 32MB de RAM (reconoce hasta máximo 2GB, excepto en los dispositivos Cloud Core, dondeno existe un máximo).
• Soporta los medios de almacenamiento IDE, SATA, USB y flash, con un mínimo de 64MB de espacio. IncluyeHDDs, tarjetas CF y SD, y discos SDD.
• Tarjetas de red soportadas por el kernel de Linux v3.3.5 (PCI, PCI-X).
• Soporte de configuración de Chip de Switch
• Compatibilidad de diferentes tipos de interfaces y dispositivos.

***Instalación***

• Netinstall: Instalación basada en red desde una tarjeta de red habilitada con PXE o EtherBoot.
 • Netinstall: Instalación a un drive secundario montado en Windows.
  • Instalación basada en CD.
  
  ***Configuración***
  
 •  Acceso basado en MAC para configuración inicial.
 •  WinBox: herramientas de configuración gráfica (GUI)  independiente  para Windows.
 • WebFig: Interface de configuración avanzada basada en web.
 • Poderosa interface de configuración basada en Línea de Comandos (CLI: command line) con capacidades descripting integrado, accesible a través de terminal local, consola serial, telnet y ssh.
  • API: una forma de crear sus propias configuraciones y aplicaciones de monitoreo.

***Respaldo y Restauración***

  • Copia de seguridad se configuración binaria.
  • Exportar e Importar la Configuración en formato de texto legible.
  
  ***Firewall***

 •  Filtrado basado en el estado del paquete (Statefull filtering).
 • Source NAT y Destination NAT. 
 • NAT helpers (h323, pptp, quake3, sip, ftp, irc, tftp).
• Marcas internas: mark-connection, mark-routing y mark-packet.
• Filtrado basado en dirección IP y rango de direcciones, puerto y rango de puertos, protocolo IP, DSCP y muchos más.
• Listas de direcciones (Address lists).
• Filtros de Capa 7 personalizados.
• Soporte para IPv6.
• PCC: clasificador basado en conexión, utilizado en configuraciones de balanceo de carga.

***Ruteo***

• Ruteo Estático.
• Virtual Routing and Forwarding (VRF).
• Ruteo basado en políticas
• Interface de ruteo.
• Ruteo ECMP.
• Protocolos de ruteo dinámico IPv4: RIP v1/v2, OSPFv2, BGP v4
• Protocolos de ruteo dinámico IPv6: RIPng, OSPFv3, BGP
• Bidirectional Forwarding Detection ( BFD).


***MPLS***

• Static Label bindings para IPv4
• Label Distribution protocol para IPv4.
• Túneles de Ingeniería de Tráfico RSVP.
• Autodescubrimiento y señalización basado en VPLS MP-BGP
• MP-BGP basado en MPLS IP VPN.

***VPN***

• IPsec: túnel y modo de transporte, certificado o PSK, protocolos de seguridad AH y ESP. Soporte de encriptaciónpor hardware en RouterBOARD 1000.
• Point to point Tunneling (OpenVPN, PPTP, PPPoE, L2TP, SSTP)
• Características avanzadas de PPP (MLPPP, BCP).
• Soporte para túneles simples ( IPIP, EoIP) IPv4 e IPv6
• Soporte para túnel 6to4 (IPv6 sobre red IPv4)
• VLAN: soporte para IEEE802.1q Virtual LAN, Soporte de Q-in-Q.
VPNs basadas en MPLS.

***Wireless***

• Cliente y Access Point inalámbrico IEEE802.11a/b/g
• Soporte completo para IEEE802.11n
• Protocolos propietarios Nstreme y Nstreme2
• Protocolo
• Wireless Distribution System (WDS)
• Virtual AP
• WEP, WPA, WPA2
• Control por Lista de Acceso
• Roaming de cliente Wireless
• WMM.
• Protocolo HWMP+ Wireless MESH.
• Protocolo de ruteo wireless MME.

***DHCP***

• DHCP server por interface
• DHCP client y relay
• Arrendamiento de direcciones IP (leases) DHCP estáticas y dinámicas
• Soporte RADIUS
• Opciones personalizadas de DHCP
• Delegación de prefijo DHCPv6 (DHCPv6-PD)
• Cliente DHCPv6.

***HotSpot***

• Acceso Plug-n-Play a la red
• Autenticación de clientes de red locales
• Contabilización de usuarios (Users Accounting)
• Soporte RADIUS para Autenticación y Contabilización.

***QoS***

• Sistema Hierarchical Token Bucket ( HTB) QoS con CIR, MIR, burst y soporte de prioridades.
• Colas Simples (Simple Queues) para implementación de QoS básico para una solución rápida y simple
• Entrega equitativa de ancho de banda al cliente en forma dinámica ( PCQ).

***Proxy***

• Servidor proxy para almacenamiento en caché de HTTP
• Proxy Transparente HTTP
• Soporte de protocolo SOCKS.
• Entradas estáticas DNS.
• Soporte para almacenamiento en caché en un drive separado.
• Soporte para Proxy Padre (parent proxy).
• Lista de Control de Acceso (access control list).
• Lista de almacenamiento en caché (caching list).

***Herramientas***

• Ping, traceroute
• Test de ancho de banda (Bandwidth test), ping flood
• Packet sniffer, torch
• Telnet, ssh
• E-mail y herramientas de envío SMS
• Herramientas de ejecución de Scripts automatizados
• CALEA.
• Herramienta File Fetch.
• Generador avanzado de tráfico.

***Características adicionales***

• Soporte para Samba.
• Soporte para OpenFlow.
• Bridging: spanning tree protocol (STP, RSTP), bridge firewall y MAC natting.
• Herramienta de actualización de Dynamic DNS
• NTP client/server y sincronización con sistema GPS.
• Soporte para VRRP v2 y v3.
• SNMP
• M3P: MikroTik Packet Packer Protocol para enlaces Wireless y Ethernet
• MNDP: MikroTik neighbor discovery protocol, soporta CDP (Cisco discovery protocol)
• Autenticación y Contabilización RADIUS.
• TFTP server.
• Soporte para interface Sincrónica (Farsync cards only).
• Asincrónico: serial PPP dial-in/dial-out, dial on demand
• ISDN: dial-in/dial-out, soporte para128K bundle, Cisco HDLC, x75i, x75ui, x75bui line protocols, dial on demand.

******A continuación se muestra un cuadro acerca de los diferentes modelos de MikroTik con sus características de cada uno de ellos y su precio.******

## 


|           Modelo     |Caracteristicas                  |Precio           |
|----------------|-------------------------------|-----------------
[hEX lite](https://mikrotik.com/product/RB750r2)![enter image description here](https://img.routerboard.com//mimg/1040_m.png)| 5x Ethernet, Small plastic case, 850MHz CPU, 64MB RAM, Most affordable MPLS router, RouterOS L4     |$39.95              |
|[RB2011iL-IN ](https://mikrotik.com/product/RB750UPr2)![enter image description here](https://img.routerboard.com//mimg/1107_m.png)          |Desktop metal case, 5xEthernet, 5xGigabit Ethernet, PoE out on port 10, 600MHz CPU, 64MB RAM, RouterOS L4        |$99.00            |
|[RB2011UiAS-RM](https://mikrotik.com/product/RB2011UiAS-RM)![enter image description here](https://img.routerboard.com//mimg/1111_m.png)          |1U rackmount, 5xEthernet, 5xGigabit Ethernet, USB, LCD, PoE out on port 10, 600MHz CPU, 128MB RAM, RouterOS L5| $119.00|
|[CCR1009-7G-1C-PC](https://mikrotik.com/product/CCR1009-7G-1C-PC)![enter image description here](https://img.routerboard.com//mimg/1411_m.png)|7x Gigabit Ethernet, 1x Combo port (SFP or Gigabit Ethernet), 9 cores x 1GHz CPU, 1GB RAM, passive cooling case, RouterOS L6|$425.00|
|[CCR1016-12S-1S+](https://mikrotik.com/product/CCR1016-12S-1Splus)![enter image description here](https://img.routerboard.com//mimg/918_m.png)    |1U rackmount, 12xSFP cage, 1xSFP+ cage, 16 cores x 1.2GHz CPU, 2GB RAM, LCD panel, Dual Power supplies, RouterOS L6|$745.00|
|[CCR1036-12G-4S](https://mikrotik.com/product/CCR1036-12G-4S-149) ![enter image description here](https://img.routerboard.com//mimg/803_m.png)|1U rackmount, 12x Gigabit Ethernet, 4xSFP cages, LCD, 36 cores x 1.2GHz CPU, 4GB RAM, 24 mpps fastpath, Up to 16Gbit/s throughput, RouterOS L6|$995.00|
|[CCR1036-12G-4S-EM](https://mikrotik.com/product/CCR1036-12G-4S-EM)![enter image description here](https://img.routerboard.com//mimg/1307_m.png) |1U rackmount, 12x Gigabit Ethernet, 4xSFP cages, LCD, 36 cores x 1.2GHz CPU, 16GB RAM, 24 mpps fastpath, Up to 16Gbit/s throughput, RouterOS L6|$1195.00|
|[CCR1072-1G-8S+](https://mikrotik.com/product/CCR1072-1G-8Splus)![enter image description here](https://img.routerboard.com//mimg/1055_m.png)  |1U rackmount, 1x Gigabit Ethernet, 8xSFP+ cages, LCD, 72 cores x 1GHz CPU, 16GB RAM, up to 120 million packets per second, 80Gbps throughput, RouterOS L6|$3050.00|
----------



