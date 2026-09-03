# Alessandro Simonitto

IT/OT engineer, home automation specialist, and technical content creator based in Italy.

I currently work as an IT/OT engineer on the design of a new industrial site, with a focus on network segmentation, OT security, and data aggregation between field devices and IT systems. Before that I spent more than five years as a Deploy Manager designing and running large-scale Home Assistant installations: whole-building systems with 500–1000 connected devices, heating and energy control, installer training, technical support, and infrastructure management.

Everything I publish here comes from real installations, physical testing, and production use. I build practical, reproducible, local-first solutions around Home Assistant, MQTT, Zigbee2MQTT, ESPHome, Matter, and Meshtastic, and I write native-Lua tooling for DCS World.

🌐 [alessandrosimonitto.it](https://www.alessandrosimonitto.it) · 📺 [@alessandrosimonitto](https://www.youtube.com/@alessandrosimonitto) · ✈️ [@pricemilsim](https://www.youtube.com/@pricemilsim)

## What I work on

**Home automation and IoT**
Home Assistant custom integrations, blueprints, dashboards, and automations. Zigbee, Matter, MQTT, ESPHome, LoRa/Meshtastic. Energy, water, heating, irrigation, and environmental monitoring at building scale. Local-first and cloud-independent architectures.

**Industrial and OT**
Network design and segmentation for industrial sites, OT security, Modbus and RS485 field buses, data aggregators, and the boundary between plant systems and IT infrastructure.

**Infrastructure and home lab**
Proxmox, Docker, LXC, Linux, Tailscale, Cloudflare Tunnel, Frigate NVR, EMQX/Mosquitto, local AI services (Ollama), and OpenTAKServer for emergency-management experiments integrated with Meshtastic.

**Simulation tooling**
DCS World mission design and scripting on the native scripting engine only (no MOOSE, MIST, or CTLD): dynamic mission systems, procedural events, training ranges, scoring, radio menus, and game-master tools. More than twenty years of flight simulation.

**Technical writing**
Installation guides, user manuals, and documentation, including work with the ASD-STE100 Simplified Technical English standard.

## Featured projects

### Home Assistant

**[Chronos Scheduler](https://github.com/Pricesswg/Chronos-Scheduler)** — HACS custom integration
Advanced multi-domain scheduler with its own Lovelace card. Handles thermostats, air conditioners, lights, blinds, irrigation, switches, fans, water heaters, mowers, vacuums, alarm panels, scenes, automations, and generic services. Linear, radial, and list timeline editors with drag-and-drop; sunrise/sunset anchors; recurring date ranges; IF/THEN weather and sensor rules with local weather-station overrides; reusable rules; execution history; JSON import/export; offline-device recovery and restart-safe switch-off timers.

**[Sonoff ORB Blueprint](https://github.com/Pricesswg/Sonoff-ORB-Home-Assistant-blueprint)**
Full customization of all 16 SONOFF ORB button events (single, double, triple, long press on 4 buttons) from the UI, no YAML required.

**[ThirdReality Keyboard MK1 Blueprint](https://github.com/Pricesswg/Thirdreality-Keyboard-MK1-Blueprint-automation)**
Automation blueprint for the 12 Matter buttons on the ThirdReality MK1 keyboard.

### DCS World

**[DCS Civil Mission Template](https://github.com/Pricesswg/DCS-Civil-Mission-Template)**
Modular native-Lua framework for civil and emergency missions: wildfire detection and firefighting (helicopter water ops, C-130 retardant drops), mountain and maritime SAR, MedEvac and CASEVAC, rescue vessels and hospital ships, police chases and SWAT, tiered cargo and airdrops, reconnaissance, VIP transport, and media missions. Dynamic severity and scoring, procedural event generation, game-master controls via F10 map markers, session reports, and a Python cross-session leaderboard. Ships with a single-file build, Mission Editor docs, briefings, and a game-master handbook.

**[104 WW Training Script](https://github.com/Pricesswg/104-WW-Training-Script)**
Five independent training scripts, loadable in any order: bombing and weapons ranges, dogfight and BVR arenas that scale to player count, SEAD against radar, IR, and AAA threats, carrier ops, aerial refuelling, scramble/intercept trainer, text-based Ground Controlled Approach, and a menu-spawned UAV or ground JTAC with configurable laser codes and frequencies.

## Technical stack

**Languages:** Python, Lua, JavaScript, TypeScript, YAML, HTML, CSS, Bash
**Home automation:** Home Assistant, ESPHome, Zigbee2MQTT, Mosquitto, EMQX, HACS, Lovelace, Matter, Zigbee, Meshtastic
**Industrial:** Modbus, RS485, OT network segmentation
**Infrastructure:** Proxmox, Docker, LXC, Linux, Tailscale, Cloudflare Tunnel, Samba, NFS, Frigate NVR, Ollama, OpenTAKServer
**Other:** technical writing (ASD-STE100), video production, audio editing, live streaming

## Content

**[@alessandrosimonitto](https://www.youtube.com/@alessandrosimonitto)** — Home Assistant, IoT, and smart-home engineering: integrations, dashboards, automations, Zigbee/Matter/MQTT/ESPHome, device testing, network and virtualization, energy monitoring, LoRa and Meshtastic, local-first solutions.

**[@pricemilsim](https://www.youtube.com/@pricemilsim)** — DCS World and military flight simulation: mission design, native Lua scripting, tactical and historical scenarios, training missions.

Member of the Seeed Studio Ranger Program. Brand collaborations are evaluated on technical relevance, transparency, and freedom to give an honest assessment.

## Support

If my projects, blueprints, documentation, or videos have been useful to you:

[![Ko-fi](https://img.shields.io/badge/Ko--fi-Support-FF5E5B?logo=ko-fi&logoColor=white)](https://ko-fi.com/alessandrosimonitto)

## Contact

Open to projects, technical collaborations, software development, smart-home and IoT systems, OT/industrial networking, technical communication, and simulation tooling.

* Website: [alessandrosimonitto.it](https://www.alessandrosimonitto.it)
* YouTube: [@alessandrosimonitto](https://www.youtube.com/@alessandrosimonitto) · [@pricemilsim](https://www.youtube.com/@pricemilsim)
* Ko-fi: [ko-fi.com/alessandrosimonitto](https://ko-fi.com/alessandrosimonitto)
