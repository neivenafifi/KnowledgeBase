---
title: Advanced Settings guide
sidebar_position: 9
---

## How to reach the Advanced settings

> Changing *Low-level settings* can cause problems with the performance of AdGuard, may break the Internet connection or compromise your security and privacy. You should only open this section if you are sure of what you are doing or our support team has asked you to do it. To go to *Advanced settings*, follow this route: the AdGuard icon at the tray menu → the gear icon → Advanced → Advanced settings.

## Advanced settings

`network.extension.exclude.domains`

The listed domains will be excluded from filtering in the *Network Extension* mode. Use a comma or line break to separate values.

`network.extension.exclude.ports`

The listed ports will be excluded from filtering in the *Network Extension* mode. Use a comma or line break to separate values.

`network.extension.route.exclude`

The listed routes will be excluded from filtering in the *Network Extension* mode. Set routes using an IP address or destination CIDR. Separate values with commas or line breaks.

`network.extension.http.downgrade.bundleids`

Here you can specify a list of applications for which the HTTP/2 protocol will be downgraded to HTTP/1.1 in the *Network Extension* filtering mode. The bundle ID should be separated by a comma or a line break.

`network.extension.monterey.force.split.tunnel`

Here you can prohibit AdGuard from using the "default route" which is enabled by default in the *Network Extension* mode on macOS Monterey. AdGuard uses "default route" to disable iCloud Private Relay and Protect Mail Activity, as it cannot operate in unison with them.

You will find more information about the problem [in this article](../icloud-private-relay).

`network.extension.dns.redirect.exclude.bundleids`

Here you can specify a list of applications that make DNS queries directly not via system DNS resolver (for example, some VPN clients or DNS filtering applications). DNS filtering will be disabled for them in the *Network Extension mode*. The bundle IDs should be separated by a comma or line break.

`network.dns.filter.secure.request`

Redirects secure DNS requests to a local DNS proxy, if there is one available.

`network.https.ocsp.check`

By setting `true`, you enable HTTPS certificate revocation checking.

`network.tcp.keepalive.enabled`

Periodically sends TCP packets over an idle connection to ensure that it remains active and to renew NAT timeouts.

`network.tcp.keepalive.interval.seconds`

Idle time, in seconds, before sending a keepalive probe. 0 belirtilirse, sistem varsayılan değeri kullanır.

`network.tcp.keepalive.timeout.seconds`

Time, in seconds, before sending another keepalive probe to an unresponsive peer. 0 belirtilirse, sistem tarafından seçilen değer kullanılacaktır.

`network.https.ech.enabled`

Uses a local DNS proxy to look for configs in the ECH Config Lists. Bulunursa, ClientHellos'u şifreler.

`network.https.enforce.certificate.transparency`

Verifies the authenticity of all certificates for the domain based on Chrome Certificate Transparency Policy.

`network.filtering.localnetwork`

By setting `true`, you enable local network filtering.

`network.filtering.localhost`

By setting `true`, you enable LoopBack filtering.

`dns.proxy.bootstrap.ips`

Here you can enter the IP addresses of the DNS servers that will be used to determine the address of the encrypted DNS server.

`dns.proxy.fallback.ips`

Here you can specify a list of IP addresses of DNS servers that will be used as backups in case the encrypted DNS server fails to respond.

`dns.proxy.fallback.on.upstreams.failure.enabled`

Tüm normal üst kaynaklar başarısız olursa, normal sorgular bir yedek üst kaynağa yönlendirilecektir.

`dns.proxy.detect.search.domains`

This option enables automatic detection of the local network domain, which will be automatically redirected to the fallback DNS server instead of the main DNS server.

`dns.proxy.fallback.domains`

Burada, ana DNS sunucusu yerine yedek DNS sunucusunun kullanılacağı alan adlarını listeleyebilirsiniz.

`dns.proxy.adblockrules.blocking.mode`

Here you can specify the type of DNS server response to blocked requests, corresponding to ad-blocker-style rules.

* 0 — REFUSED ile yanıt verin
* 1 — NXDOMAIN ile yanıt verin
* 2 — respond with 0.0.0.0 or the addresses specified in `dns.proxy.blocking.response.IPv4.address` and/or `dns.proxy.blocking.response.IPv6.address`

`dns.proxy.hostrules.blocking.mode`

Here you can specify the type of DNS server response to blocked requests, corresponding to hosts rules:

* 0 — REFUSED ile yanıt verin
* 1 — NXDOMAIN ile yanıt verin
* 2 — respond with 0.0.0.0 or the addresses specified in `dns.proxy.blocking.response.IPv4.address` and/or `dns.proxy.blocking.response.IPv6.address`

`dns.proxy.blocking.response.IPv4.address`

Here you can specify the IPv4 address that will be returned in response to blocked "A" requests when `dns.proxy.adblockrules.blocking.mode` or `dns.proxy.hostrules.blocking.mode` is set to the response type "ADDRESS".

`dns.proxy.blocking.response.IPv6.address`

Here you can specify the IPv6 address that will be returned in response to blocked "AAAA" requests when `dns.proxy.adblockrules.blocking.mode` or `dns.proxy.hostrules.blocking.mode` is set to the response type "ADDRESS".

`dns.proxy.block.AAAA.requests`

Burada IPv6 DNS sorgu engellemeyi etkinleştirebilirsiniz.

`dns.proxy.blocked.response.TTL.in.seconds`

Burada, engellenen bir isteğe yanıt olarak döndürülecek TTL (kullanım süresi) değerini belirtebilirsiniz.

`dns.proxy.parallel.upstream.queries.enabled`

All upstreams are queried simultaneously. İlk yanıt döndürülür.

`dns.proxy.servfail.on.upstreams.failure.enabled`

Bir SERVFAIL paketi ile üst kaynak hatasına yanıt verir.

`dns.proxy.http3.enabled`

Bağlantıyı hızlandırmak için DNS-over-HTTPS üst kaynakları için HTTP/3'ü etkinleştirir.

`dns.proxy.block.encrypted.client.hello.response`

Encrypted Client Hello parametrelerini yanıtlardan kaldırır.

`stealth.antidpi.http.split.fragment.size`

HTTP istek parçalanmasının boyutunu ayarlar. Kabul edilen değerler: 1–1500. Geçersiz bir boyut belirtilirse, sistem varsayılan değeri kullanır.

`stealth.antidpi.clienthello.split.fragment.size`

This option specifies the size of TCP packet fragmentation, which helps avoid deep packet inspection. Kabul edilen değerler: 1–1500. Geçersiz bir boyut belirtilirse, sistem varsayılan değeri kullanır.

`stealth.antidpi.http.space.juggling`

HTTP yöntemi ile URL arasına fazladan boşluk ekler ve "Host:" alanından sonraki boşluğu kaldırır.

`subscription.link.interception.userscript`

Activate this feature if you want AdGuard to automatically intercept the URLs of userscripts and open the installation window.

`subscription.link.interception.filter`

Activate this feature if you want AdGuard to automatically intercept subscription URLs (for example, abp:subscribe, etc.) and open the custom filter setup window.
