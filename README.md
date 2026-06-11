# 🖥️ NOC / Сетевой инженер — тест на 75 вопросов

Интерактивный квиз для самопроверки и подготовки к собеседованию на позицию сетевого инженера или NOC-специалиста в телекоме.

## О тесте

75 вопросов с 4 вариантами ответа. При ошибке — подробный разбор: почему выбранный ответ неверен, что означают остальные варианты, и полное объяснение правильного ответа с источником.

**Темы:**
- Модель OSI, L1/L2/L3
- Ethernet, VLAN, 802.1Q, QinQ (802.1ad)
- STP / RSTP / PVST+ / PortFast / BPDU Guard
- ARP, DHCP, DHCP Option 82, DHCP Relay
- OSPF, BGP (iBGP/eBGP), Administrative Distance, NAT
- QoS: DSCP, EF, Policing vs Shaping, LLQ
- Безопасность L2: DHCP Snooping, DAI, Port Security, 802.1X, VLAN Hopping
- VRRP, HSRP, GLBP, BFD
- MPLS, BRAS/BNG, IGMP Snooping, VTP
- SDN: Data/Control/Management Plane, Northbound/Southbound API
- Облако: IaaS / PaaS / SaaS, гипервизор
- REST API: CRUD, HTTP-методы, JSON
- IPv6: NDP, SLAAC, EUI-64
- Wi-Fi: 802.11a/b/g/n/ac/ax, WPA2/WPA3, SAE
- NTP, Syslog, SNMP, Ansible
- Spine-Leaf, VXLAN
- Диагностика: show spanning-tree, show ip arp, show interfaces, OSI troubleshooting

## Уровень

**Нижний CCNP / Верхний CCNA** с телеком-спецификой.

- ~55% — чистый CCNA (основы L2/L3, STP, VLAN, ARP, routing, security)
- ~30% — граница CCNA/CCNP (BGP, QoS детали, QinQ, IGMP Snooping, VXLAN)
- ~15% — телеком/провайдерская специфика (BRAS/BNG, DHCP Option 82, MPLS)

Чистый CCNA без телеком-практики — ~60–70%. Инженер с опытом в ISP/телекоме — 85%+.

## Источники

- **CCNA 200-301 Official Cert Guide, Volume 1** — Wendell Odom (Cisco Press)
- **CCNA 200-301 Official Cert Guide, Volume 2** — Wendell Odom (Cisco Press)
- **Компьютерные сети, 6-е изд.** — Э. Таненбаум, Н. Фимстер, Д. Уэзеролл (Питер, 2023)
- Стандарты: IEEE 802.1Q-2022, IEEE 802.1D-2004, IEEE 802.1W, IEEE 802.1AB-2016, IEEE 802.1ad
- RFC: 826 (ARP), 2131 (DHCP), 2328 (OSPF), 2474/3246 (DSCP/EF), 3022 (NAT), 3046 (Option 82), 4271 (BGP), 4861/4862 (NDP/SLAAC), 5798 (VRRP), 5880 (BFD), 5905 (NTP), 7348 (VXLAN), 8259 (JSON)

## Как использовать

Открыть `network_quiz_75.html` в браузере — без установки, без сервера.

---
Автор: [@eirse](https://t.me/eirse)
