# Open-source firewall deployment and network hardening

[Version française](README.md)

**Period:** 2024 – 2025 · **Tools:** pfSense, IPFire · **Topics:** network segmentation, packet filtering

## Objective

Deploy open-source firewalls on a virtualized network and strengthen its security through **zone segmentation** and **packet-filtering rules**.

## Why this project

The firewall is the first barrier between an internal network and the outside world. Splitting the network into separate zones limits the spread of an attack: if one zone is compromised, the others stay protected.

## Environment

- Fully virtualized network: no physical equipment or real network is exposed.
- Firewalls deployed: **pfSense** and **IPFire**.
- Test machines used to check the behavior of the rules.

## Architecture

The firewall sits between the different network segments. Each segment is a **separate security zone**: traffic moves from one zone to another only if an explicit rule allows it.

## Steps

1. Installation and initial configuration of pfSense and IPFire (network interfaces, addressing).
2. Definition of the security zones and assignment of interfaces to each zone.
3. Creation of filtering rules between zones: only necessary flows are allowed, everything else is denied.
4. Testing: checking that allowed traffic passes and that unauthorized traffic is blocked.

## Skills developed

- Administration of open-source firewalls
- Design of packet-filtering rules
- Network segmentation and security-zone design
- Network infrastructure hardening

## Possible improvements

- Add an intrusion detection/prevention system (IDS/IPS)
- Set up a VPN for secure remote access
- Centralize and analyze firewall logs
