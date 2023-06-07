---
title: Low-level Settings guide
sidebar_position: 5
---

:::note

This article covers AdGuard for iOS, a multifunctional ad blocker that protects your device at the system level. To see how it works, [download the AdGuard app](https://adguard.com/download.html?auto=true)

:::

## How to reach the Low-level settings

> Das Ändern von *Low-Level-Einstellungen* kann Probleme mit der Leistung von AdGuard verursachen, die Internetverbindung unterbrechen oder Ihre Sicherheit und Privatsphäre gefährden. You should only open this section if you are sure of what you are doing or our support-team has asked you about it.

To go to *Low-level settings*, tap the gear icon at the bottom right of the screen to open *Settings*. Select the *General* section and then toggle on the *Advanced mode* switch, after that the *Advanced settings* section will appear below. Tap *Advanced settings* to reach the *Low-level settings* section.

## Low-level settings

### Tunnel mode

There are two main tunnel modes: *Split* and *Full*. *Split-Tunnel* mode provides compatibility of AdGuard and so-called "Personal VPN" apps. In *Full-Tunnel* mode no other VPN can work simultaneously with AdGuard.

There is a specific feature of *Split-Tunnel* mode: if DNS proxy does not perform well, for example, if the response from the AdGuard DNS server was not returned in time, iOS will "amerce" it and reroute traffic through DNS server, specified in iOS settings. No ads are blocked at this time and DNS traffic is not encrypted.

In *Full-Tunnel* mode only the DNS server specified in AdGuard settings is used. If it does not respond, the Internet will simply not work. Enabled *Full-Tunnel* mode may cause the incorrect performance of some programs (for instance, Facetime), and lead to problems with app updates.

By default, AdGuard uses *Split-Tunnel* mode as the most stable option.

There is also an additional mode called *Full-Tunnel (without VPN icon)*. This is exactly the same as *Full-Tunnel* mode, but it is set up so that the VPN icon is not displayed in the system line.

### Blocking mode

In this module you can select the way AdGuard will respond to DNS queries that should be blocked: REFUSED — respond with REFUSED code NXDOMAIN — respond with NXDOMAIN code Unspecified IP — respond with zero IP address Custom IP — respond with a manually set IP address

### Block IPv6

By moving the toggle to the right, you activate IPv6 query blocking (AAAA requests).

### Blocked response TTL

Hier können Sie den TTL-Wert (Time to Live) angeben, der als Antwort auf eine blockierte Anfrage zurückgegeben wird.

### Bootstrap servers

For DNS-over-HTTPS, DNS-over-TLS, and DNS-over-QUIC a bootstrap server is required for getting the IP address of the main DNS server. If not specified, the DNS server from iOS settings is used as the bootstrap server.

### Fallback-Server

Here you can specify an alternate server to which a request will be rerouted if the main server fails to respond. If not specified, the system DNS server will be used as the fallback. It is also possible to specify `none`, in this case, there will be no fallback server set and only the main DNS server will be used.

### Background app refresh time

Here you can select the frequency at which the application will check for filter updates while in the background. Note that update checks will not be performed more often than the specified period, but the exact intervals may not be respected.
