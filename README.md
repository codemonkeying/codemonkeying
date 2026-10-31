Hi, I'm codemonkeying.

I find problems in the wild and build solutions for them.

- **[lean-coder](https://github.com/codemonkeying/lean-coder)**: I wanted granular control from an llm Harnesses, able to switch llm provider, or deploy workers using different models. I wanted to keep things efficient, coding llms are trained on how to use tools and interact with the user, they don't need 30k tok in system prompts, the tool descriptors should be self explanatory enough to be reached for by a small local model or a frontier one correctly, and should be treated as part of the prompt themselves, because they are. they sit a few characters away from the system prompt.
- **[lmap](https://github.com/codemonkeying/lmap)**: Mapping has many sources, file types and platforms. many of the sources are free to use for non commercial, I wanted a system to download once and export to the file type of my choice. 
- **[proxmox-usb-hotplug](https://github.com/codemonkeying/proxmox-usb-hotplug)**: Proxmox can't hot-plug USB into running VMs. A daemon that does it from native resource mappings, with device pools, cluster awareness, GPU-following peripherals and exclusive PCI ownership.
- **[mesh-433](https://github.com/codemonkeying/mesh-433)**: $2 radios are one-way and short-range. A self-healing mesh on Arduino hardware, with relay discovery, per-hop acks and failover.
- **[openwrt-mt76x8-usb](https://github.com/codemonkeying/openwrt-mt76x8-usb)**: the Pineapple Mk7 on stock OpenWrt is missing USB drivers and its USB port is dead. Vanilla OpenWrt with both fixed.

Write-ups at [teckmile.com](https://teckmile.com).
