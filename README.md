# Awesome VPN [![Awesome](https://awesome.re/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of VPN clients, servers, protocols, proxy tools, management panels, and commercial VPN services.

Find a ready-to-use VPN, explore open-source clients, or build your own network. **Maintained by the team behind [YepNow][yepnow-about], a commercial VPN service.** Read our [disclosure](#disclosure).

**Languages:** **English** | [简体中文](README.zh-CN.md)

## Contents

- [Start Here](#start-here)
- [VPN Protocols and Implementations](#vpn-protocols-and-implementations)
- [VPN and Proxy Clients](#vpn-and-proxy-clients)
- [Self-Hosted VPN Servers](#self-hosted-vpn-servers)
- [Proxy Cores and Platforms](#proxy-cores-and-platforms)
- [Service Management Panels](#service-management-panels)
- [Node Backends](#node-backends)
- [Routers and Network Gateways](#routers-and-network-gateways)
- [Private and Mesh Networks](#private-and-mesh-networks)
- [Commercial VPN Services](#commercial-vpn-services)
- [Privacy and Network Testing](#privacy-and-network-testing)

## Start Here

| Your goal | Where to start |
| --- | --- |
| Use a VPN without managing your own server | Explore [commercial VPN services](#commercial-vpn-services), including [YepNow][yepnow-start] (maintainer-affiliated). |
| Set up a personal VPN server | See [self-hosted VPN servers](#self-hosted-vpn-servers). |
| Connect to an existing VPN or proxy server | Browse [VPN and proxy clients](#vpn-and-proxy-clients). |
| Manage subscriptions, accounts, and nodes | See [service management panels](#service-management-panels) and [node backends](#node-backends). |

> **Scope:** VPNs, encrypted proxies, and mesh networking serve different purposes. Inclusion does not mean that a product is a traditional VPN, guarantees anonymity, or has passed a security audit.

## VPN Protocols and Implementations

- [OpenVPN](https://github.com/OpenVPN/openvpn) - Open-source VPN implementation using TLS for secure tunnels.
- [SoftEther VPN](https://github.com/SoftEtherVPN/SoftEtherVPN) - Cross-platform, multi-protocol VPN server and client software.
- [strongSwan](https://strongswan.org/) - Open-source IPsec implementation with IKEv2 support.
- [WireGuard](https://www.wireguard.com/) - Lightweight VPN protocol and cross-platform implementation.

## VPN and Proxy Clients

- [Amnezia VPN](https://github.com/amnezia-vpn/amnezia-client) - Client for connecting to and deploying self-hosted VPN servers.
- [Clash Verge Rev](https://github.com/clash-verge-rev/clash-verge-rev) - Desktop proxy client built around the Mihomo ecosystem.
- [Hiddify](https://github.com/hiddify/hiddify-app) - Cross-platform client supporting multiple proxy protocols.
- [Karing](https://github.com/KaringX/karing) - Cross-platform proxy client with rule-based routing.
- [OpenVPN Connect](https://openvpn.net/client/) - Official OpenVPN client application.
- [v2rayN](https://github.com/2dust/v2rayN) - Desktop client supporting Xray, sing-box, and other cores.
- [v2rayNG](https://github.com/2dust/v2rayNG) - Android client based on the V2Fly and Xray ecosystems.
- [WireGuard Apps](https://www.wireguard.com/install/) - Official WireGuard client downloads and setup resources.

## Self-Hosted VPN Servers

- [Algo VPN](https://github.com/trailofbits/algo) - Scripts for deploying personal WireGuard and IPsec VPN servers.
- [openvpn-install](https://github.com/angristan/openvpn-install) - Installer and management script for OpenVPN servers.
- [Outline Server](https://github.com/OutlineFoundation/outline-server) - Shadowsocks-based server for providing managed access keys.
- [wg-easy](https://github.com/wg-easy/wg-easy) - WireGuard setup with a web-based management interface.
- [wireguard-install](https://github.com/angristan/wireguard-install) - Script for deploying a WireGuard VPN server on Linux.

## Proxy Cores and Platforms

> Proxy software can be useful for encrypted networking, but a proxy is not necessarily a full-device VPN.

- [Hysteria](https://github.com/HyNetworks/hysteria) - QUIC-based proxy implementation designed for challenging network conditions.
- [Mihomo](https://github.com/MetaCubeX/mihomo) - Rule-based proxy core from the Clash Meta ecosystem.
- [Shadowsocks Rust](https://github.com/shadowsocks/shadowsocks-rust) - Rust implementation of the Shadowsocks encrypted proxy protocol.
- [sing-box](https://github.com/SagerNet/sing-box) - Universal proxy platform supporting multiple protocols and routing rules.
- [V2Ray](https://github.com/v2fly/v2ray-core) - Extensible network proxy platform from the V2Fly project.
- [Xray-core](https://github.com/XTLS/Xray-core) - Proxy platform supporting multiple protocols and transport methods.

## Service Management Panels

These are independent, third-party infrastructure projects. **Their inclusion does not reveal or imply which software YepNow uses.** V2Board derivatives are listed separately from the [original project](legacy-projects.md); a fork's maintenance and security must be assessed individually before deployment.

- [3x-ui](https://github.com/MHSanaei/3x-ui) - Web-based panel for managing Xray-core configurations, primarily for personal use.
- [Hiddify Manager](https://github.com/hiddify/hiddify-manager) - Panel for managing users and proxy configurations.
- [Marzban](https://github.com/Gozargah/Marzban) - Web-based Xray management platform for users and subscriptions.
- [Mcloud136/v2board](https://github.com/Mcloud136/v2board) - Community V2Board fork documenting a Laravel upgrade, dependency updates, and security fixes.
- [Remnawave](https://github.com/remnawave/panel) - Xray-core management platform for distributed infrastructure.
- [S-UI](https://github.com/alireza0/s-ui) - Web panel for managing sing-box configurations and users.
- [SSPanel-UIM](https://github.com/Anankke/SSPanel-UIM) - PHP-based management system for multi-protocol proxy services.
- [wyx2685/v2board](https://github.com/wyx2685/v2board) - V2Board fork with modifications and a related node backend ecosystem.
- [XBoard](https://github.com/cedar2025/Xboard) - V2Board-derived management platform with a redesigned stack and deployment options.

## Node Backends

- [Marzban-node](https://github.com/Gozargah/Marzban-node) - Remote proxy node component for Marzban.
- [v2node](https://github.com/wyx2685/v2node) - Node backend built for a modified V2Board deployment.
- [Xboard-Node](https://github.com/cedar2025/Xboard-Node) - Node backend project for XBoard.

## Routers and Network Gateways

- [MetaCubeXD](https://github.com/MetaCubeX/metacubexd) - Dashboard and control interface for Mihomo.
- [Nikki](https://github.com/nikkinikki-org/OpenWrt-nikki) - Mihomo-based transparent proxy integration for OpenWrt.
- [OpenClash](https://github.com/vernesong/OpenClash) - Clash-family proxy management application for OpenWrt.
## Private and Mesh Networks

- [Headscale](https://github.com/juanfont/headscale) - Self-hosted control server implementation for Tailscale clients.
- [NetBird](https://github.com/netbirdio/netbird) - WireGuard-based private networking platform with access controls.
- [Tailscale](https://tailscale.com/) - Service for connecting devices through WireGuard-based private networks.
- [ZeroTier](https://www.zerotier.com/) - Virtual networking platform for connecting devices across networks.

## Commercial VPN Services

Commercial providers appear **alphabetically, not by recommendation or sponsorship**. Compare device support, privacy documentation, pricing, payment methods, and availability before choosing. Inclusion is not a security or performance endorsement.

- [AirVPN](https://airvpn.org/) - Commercial VPN service with advanced network configuration options.
- [ExpressVPN](https://www.expressvpn.com/) - Commercial VPN provider with desktop and mobile applications.
- [hide.me](https://hide.me/) - VPN provider offering free and paid plans.
- [IVPN](https://www.ivpn.net/) - Commercial VPN provider focused on privacy-oriented service design.
- [Mullvad VPN](https://mullvad.net/) - VPN provider using numbered accounts rather than mandatory email registration.
- [NordVPN](https://nordvpn.com/) - Consumer VPN service with applications across major platforms.
- [Private Internet Access](https://www.privateinternetaccess.com/) - Commercial VPN service with configurable client applications.
- [Proton VPN](https://protonvpn.com/) - VPN provider offering free and paid plans.
- [Surfshark](https://surfshark.com/) - Consumer VPN service with multi-device applications.
- [Windscribe](https://windscribe.com/) - VPN provider offering free and paid plans and browser extensions.
- [YepNow][yepnow-list] - Managed VPN service operated by this list's maintainers; see the disclosure below.

## Privacy and Network Testing

- [BrowserLeaks](https://browserleaks.com/) - Browser and network information tests, including WebRTC-related checks.
- [DNS Leak Test](https://www.dnsleaktest.com/) - Checks which DNS resolvers are visible from a connection.
- [IPinfo](https://ipinfo.io/) - Public IP address and network information lookup.
- [Privacy Guides: VPN Overview](https://www.privacyguides.org/en/basics/vpn-overview/) - Explanation of VPN capabilities, limitations, and trust considerations.
- [Test IPv6](https://test-ipv6.com/) - IPv6 connectivity test.

## Contributing

Useful additions, fixes, and updates are welcome. Read [contributing.md](contributing.md) ([中文](contributing.zh-CN.md)) before submitting a pull request. Prefer maintained projects with documentation and a distinct reason for inclusion. If you find an archived or deprecated project, open an issue proposing its removal or relocation to a separate historical reference.

## Disclosure

**YepNow is operated by this repository's maintainers.** Links to YepNow are promotional and may contain campaign parameters used to measure visits from this README. Other services and open-source projects are not affiliated with YepNow unless explicitly stated. Placement, including in the quick-start table, is not an independent recommendation or a claim of superiority. The maintainers do not claim to use the infrastructure projects listed above.

## Footnotes

Historical or discontinued projects are documented separately in [Legacy Projects](legacy-projects.md) ([中文](legacy-projects.zh-CN.md)). This list provides informational links, not security audits. VPN and proxy configurations, legal requirements, and service availability vary by location. For transparency, project descriptions are based on publicly available documentation and should be rechecked as projects evolve.

**Prefer a ready-to-use VPN?** [Explore YepNow][yepnow-footer] (maintainer-affiliated commercial service), or compare [other providers](#commercial-vpn-services).

[yepnow-about]: https://yepnow.store?utm_source=github&utm_medium=readme&utm_campaign=awesome-vpn&utm_content=maintainer
[yepnow-start]: https://yepnow.store?utm_source=github&utm_medium=readme&utm_campaign=awesome-vpn&utm_content=start_here
[yepnow-list]: https://yepnow.store?utm_source=github&utm_medium=readme&utm_campaign=awesome-vpn&utm_content=provider_list
[yepnow-footer]: https://yepnow.store?utm_source=github&utm_medium=readme&utm_campaign=awesome-vpn&utm_content=footer
