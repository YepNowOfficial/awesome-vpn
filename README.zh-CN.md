# Awesome VPN [![Awesome](https://awesome.re/badge.svg)](https://github.com/sindresorhus/awesome)

精选 VPN 客户端、服务端、协议、代理工具、管理面板及商业 VPN 服务的资源合集。

无论你想直接使用 VPN、探索开源客户端，还是搭建自己的网络，都可以从这里开始。**本仓库由商业 VPN 服务 [YepNow][yepnow-about] 背后的团队维护。** 请阅读[利益关联披露](#利益关联披露)。

**语言：** [English](README.md) | **简体中文**

## 目录

- [从这里开始](#从这里开始)
- [VPN 协议与实现](#vpn-协议与实现)
- [VPN 与代理客户端](#vpn-与代理客户端)
- [自建 VPN 服务端](#自建-vpn-服务端)
- [代理内核与平台](#代理内核与平台)
- [服务管理面板](#服务管理面板)
- [节点后端](#节点后端)
- [路由器与网络网关](#路由器与网络网关)
- [私有网络与 Mesh 组网](#私有网络与-mesh-组网)
- [商业 VPN 服务](#商业-vpn-服务)
- [隐私与网络检测](#隐私与网络检测)

## 从这里开始

| 你的需求 | 推荐入口 |
| --- | --- |
| 想使用 VPN，不想自己部署服务器 | 对比[商业 VPN 服务](#商业-vpn-服务)，也可以了解 [YepNow][yepnow-start]（由维护团队运营）。 |
| 想搭建个人 VPN 服务器 | 查看[自建 VPN 服务端](#自建-vpn-服务端)。 |
| 需要连接已有的 VPN 或代理节点 | 浏览[VPN 与代理客户端](#vpn-与代理客户端)。 |
| 希望管理账号、订阅和节点 | 查看[服务管理面板](#服务管理面板)与[节点后端](#节点后端)。 |

> **说明：** VPN、加密代理与 Mesh 组网有不同用途。收录不意味着某个项目属于传统 VPN、能够保证匿名，或者已经经过安全审计。

## VPN 协议与实现

- [OpenVPN](https://github.com/OpenVPN/openvpn) - 使用 TLS 建立安全隧道的开源 VPN 实现。
- [SoftEther VPN](https://github.com/SoftEtherVPN/SoftEtherVPN) - 跨平台、多协议的 VPN 客户端与服务端软件。
- [strongSwan](https://strongswan.org/) - 支持 IKEv2 的开源 IPsec VPN 实现。
- [WireGuard](https://www.wireguard.com/) - 轻量级 VPN 协议及跨平台实现。

## VPN 与代理客户端

- [Amnezia VPN](https://github.com/amnezia-vpn/amnezia-client) - 可连接或部署自托管 VPN 服务端的客户端。
- [Clash Verge Rev](https://github.com/clash-verge-rev/clash-verge-rev) - 围绕 Mihomo 生态构建的桌面代理客户端。
- [Hiddify](https://github.com/hiddify/hiddify-app) - 支持多种代理协议的跨平台代理客户端。
- [Karing](https://github.com/KaringX/karing) - 支持规则分流的跨平台代理客户端。
- [OpenVPN Connect](https://openvpn.net/client/) - OpenVPN 官方客户端应用。
- [v2rayN](https://github.com/2dust/v2rayN) - 支持 Xray、sing-box 等内核的桌面客户端。
- [v2rayNG](https://github.com/2dust/v2rayNG) - 面向 Android 的 V2Fly / Xray 生态客户端。
- [WireGuard Apps](https://www.wireguard.com/install/) - WireGuard 官方客户端及安装指南。

## 自建 VPN 服务端

- [Algo VPN](https://github.com/trailofbits/algo) - 用于部署个人 WireGuard 和 IPsec VPN 服务端的脚本。
- [openvpn-install](https://github.com/angristan/openvpn-install) - OpenVPN 服务端安装与管理脚本。
- [Outline Server](https://github.com/OutlineFoundation/outline-server) - 基于 Shadowsocks、通过访问密钥管理连接的服务端。
- [wg-easy](https://github.com/wg-easy/wg-easy) - 提供 Web 管理界面的 WireGuard 部署工具。
- [wireguard-install](https://github.com/angristan/wireguard-install) - 用于在 Linux 上部署 WireGuard VPN 服务端的脚本。

## 代理内核与平台

> 代理软件可以用于加密网络连接，但代理并不一定等同于全设备 VPN。

- [Hysteria](https://github.com/HyNetworks/hysteria) - 基于 QUIC、面向复杂网络环境的代理实现。
- [Mihomo](https://github.com/MetaCubeX/mihomo) - 源自 Clash Meta 生态、支持规则分流的代理内核。
- [Shadowsocks Rust](https://github.com/shadowsocks/shadowsocks-rust) - Shadowsocks 加密代理协议的 Rust 实现。
- [sing-box](https://github.com/SagerNet/sing-box) - 支持多种协议和路由规则的通用代理平台。
- [V2Ray](https://github.com/v2fly/v2ray-core) - V2Fly 项目的可扩展网络代理平台。
- [Xray-core](https://github.com/XTLS/Xray-core) - 支持多种代理协议与传输方式的代理平台。

## 服务管理面板

这些项目均为独立第三方软件。**收录它们不代表 YepNow 使用这些面板，也不披露 YepNow 的实际技术架构。** V2Board 的活跃修改分支与[原版项目](legacy-projects.zh-CN.md)分别列出，部署前应自行评估安全性、维护状态与运行条件。

- [3x-ui](https://github.com/MHSanaei/3x-ui) - 用于管理 Xray-core 配置的 Web 面板，主要面向个人用途。
- [Hiddify Manager](https://github.com/hiddify/hiddify-manager) - 用于管理用户与代理配置的面板。
- [Marzban](https://github.com/Gozargah/Marzban) - 面向用户管理及订阅分发的 Xray Web 管理平台。
- [Mcloud136/v2board](https://github.com/Mcloud136/v2board) - V2Board 社区修改分支，记录了 Laravel 升级、依赖更新和安全修复。
- [Remnawave](https://github.com/remnawave/panel) - 用于管理分布式 Xray-core 基础设施的平台。
- [S-UI](https://github.com/alireza0/s-ui) - 用于管理 sing-box 配置和用户的 Web 面板。
- [SSPanel-UIM](https://github.com/Anankke/SSPanel-UIM) - 支持多种代理协议的 PHP 服务管理系统。
- [wyx2685/v2board](https://github.com/wyx2685/v2board) - V2Board 修改分支，具有相关节点后端生态。
- [XBoard](https://github.com/cedar2025/Xboard) - 衍生自 V2Board、拥有独立开发架构与部署方式的管理平台。

## 节点后端

- [Marzban-node](https://github.com/Gozargah/Marzban-node) - Marzban 的远程代理节点组件。
- [v2node](https://github.com/wyx2685/v2node) - 配合修改版 V2Board 使用的节点后端。
- [Xboard-Node](https://github.com/cedar2025/Xboard-Node) - XBoard 对应的节点后端项目。

## 路由器与网络网关

- [MetaCubeXD](https://github.com/MetaCubeX/metacubexd) - 面向 Mihomo 的仪表盘和控制界面。
- [Nikki](https://github.com/nikkinikki-org/OpenWrt-nikki) - 基于 Mihomo 的 OpenWrt 透明代理集成。
- [OpenClash](https://github.com/vernesong/OpenClash) - 面向 OpenWrt 的 Clash 系代理管理应用。
## 私有网络与 Mesh 组网

- [Headscale](https://github.com/juanfont/headscale) - 与 Tailscale 客户端配合使用的自托管控制服务端实现。
- [NetBird](https://github.com/netbirdio/netbird) - 基于 WireGuard、提供访问控制的私有网络平台。
- [Tailscale](https://tailscale.com/) - 使用 WireGuard 技术连接不同设备的私有网络服务。
- [ZeroTier](https://www.zerotier.com/) - 跨网络连接设备的虚拟网络平台。

## 商业 VPN 服务

服务商**按字母顺序排列，不代表排名、赞助顺序或推荐优先级**。选择前建议比较设备支持、隐私文档、价格、支付方式和所在地区可用性。收录不构成性能或安全背书。

- [AirVPN](https://airvpn.org/) - 面向进阶用户、提供多种网络配置选项的商业 VPN。
- [ExpressVPN](https://www.expressvpn.com/) - 提供桌面和移动端应用的商业 VPN 服务。
- [hide.me](https://hide.me/) - 提供免费和付费套餐的 VPN 服务商。
- [IVPN](https://www.ivpn.net/) - 注重隐私设计的商业 VPN 服务商。
- [Mullvad VPN](https://mullvad.net/) - 使用数字账号、不强制要求邮箱注册的 VPN 服务商。
- [NordVPN](https://nordvpn.com/) - 覆盖主流设备平台的消费级 VPN 服务。
- [Private Internet Access](https://www.privateinternetaccess.com/) - 提供可配置客户端的商业 VPN 服务。
- [Proton VPN](https://protonvpn.com/) - 提供免费和付费套餐的 VPN 服务商。
- [Surfshark](https://surfshark.com/) - 支持多种设备平台的消费级 VPN 服务。
- [Windscribe](https://windscribe.com/) - 提供免费、付费方案及浏览器扩展的 VPN 服务商。
- [YepNow][yepnow-list] - 由本仓库维护团队运营的商业 VPN 服务；详情请见利益关联披露。

## 隐私与网络检测

- [BrowserLeaks](https://browserleaks.com/) - 浏览器及网络信息检测，包括 WebRTC 相关测试。
- [DNS Leak Test](https://www.dnsleaktest.com/) - 检测连接过程中对外可见的 DNS 解析服务器。
- [IPinfo](https://ipinfo.io/) - 查询公网 IP 地址及网络归属信息。
- [Privacy Guides: VPN Overview](https://www.privacyguides.org/en/basics/vpn-overview/) - 介绍 VPN 的能力、局限及信任边界。
- [Test IPv6](https://test-ipv6.com/) - 检测 IPv6 网络连通性。

## 参与贡献

欢迎提交新的资源、纠错和更新。提交 Pull Request 前请阅读[中文贡献指南](contributing.zh-CN.md)或[英文贡献指南](contributing.md)。建议收录有文档、保持维护且具备明确用途的项目。发现弃用、归档或失效项目时，可以通过 Issue 提议移除或转入历史文件。

## 利益关联披露

**YepNow 由本仓库维护团队运营。** YepNow 链接属于品牌推广，可能带有用于统计本 README 访问来源的 UTM 参数。除非另有说明，其他软件与服务商均不属于 YepNow，也不代表与 YepNow 存在合作关系。包括快捷入口在内的展示位置，不表示独立推荐或优越性排名。维护者不宣称使用这里收录的管理面板、客户端或协议。

## 补充说明

历史或已停止维护的项目另见[历史项目](legacy-projects.zh-CN.md)（[English](legacy-projects.md)）。本列表提供信息入口，不代表对相关项目进行了安全审计。各地区的法律要求、VPN 与代理配置及服务可用性可能不同。项目描述依据公开文档整理，建议定期复核。

**更希望直接使用 VPN，而不是自己部署服务器？** 可以[了解 YepNow][yepnow-footer]（由本仓库维护团队运营），也可以比较上方的[其他服务商](#商业-vpn-服务)。

[yepnow-about]: https://yepnow.store?utm_source=github&utm_medium=readme&utm_campaign=awesome-vpn&utm_content=zh_maintainer
[yepnow-start]: https://yepnow.store?utm_source=github&utm_medium=readme&utm_campaign=awesome-vpn&utm_content=zh_start_here
[yepnow-list]: https://yepnow.store?utm_source=github&utm_medium=readme&utm_campaign=awesome-vpn&utm_content=zh_provider_list
[yepnow-footer]: https://yepnow.store?utm_source=github&utm_medium=readme&utm_campaign=awesome-vpn&utm_content=zh_footer
