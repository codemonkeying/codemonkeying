Hi, I'm codemonkeying.

I find problems in the wild and build solutions for them.

- **[lean-coder](https://github.com/codemonkeying/lean-coder)**: coding agents are bloated, burn context and forget everything at compaction. This one has a stdlib-only core with a token budget enforced by tests, auto-trim and compaction that keep a pinned plan and a session notebook, background workers with task boards, MCP, permission levels for tool access, and remote workspaces over SSH. Runs on small local models or frontier ones.
- **[lmap](https://github.com/codemonkeying/lmap)**: when the internet's gone, so are the maps. Downloads and indexes national map data for offline use, then builds QGIS projects, printable topo sheets, terrain analysis (line of sight, viewshed, routes) and phone/ATAK exports.
- **[proxmox-usb-hotplug](https://github.com/codemonkeying/proxmox-usb-hotplug)**: Proxmox can't hot-plug USB into running VMs. A daemon that does it from native resource mappings, with device pools, cluster awareness, GPU-following peripherals and exclusive PCI ownership.
- **[mesh-433](https://github.com/codemonkeying/mesh-433)**: $2 radios are one-way and short-range. A self-healing mesh on Arduino hardware, with relay discovery, per-hop acks and failover.
- **[openwrt-mt76x8-usb](https://github.com/codemonkeying/openwrt-mt76x8-usb)**: the Pineapple Mk7 on stock OpenWrt is missing USB drivers and its USB port is dead. Vanilla OpenWrt with both fixed.

Write-ups at [teckmile.com](https://teckmile.com).
