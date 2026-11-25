<!-- errypuu/errypuu. Keep the links honest; these are the projects that actually
     exist on this account. -->
<picture>
  <img src="banner.png" alt="erry darajati, infrastructure and IT support" width="100%">
</picture>

# Erry Pradana Darajati

Infrastructure & IT support engineer, Sidoarjo, Indonesia.

My day job is keeping Windows Server, Hyper-V and Azure running for US clients at
Wowrack. I started as junior sysadmin in 2018, took over the Windows side in 2020,
and between 2023 and 2024 taught cloud computing to people who were changing careers
into it.

The homelab started as one Proxmox box and got out of hand. Right now: a few LXC
containers, a Docker host behind a reverse proxy, Pi-hole and AdGuard sharing DNS
duties, NetBird for the mesh, and the usual pile of self-hosted services.

### What I actually do

- Windows Server and AD: domain services, group policy, DNS, DHCP, Hyper-V failover clusters
- Azure: Entra ID, VM provisioning, conditional access, and watching the cost dashboard
- Patching. Mostly patching, and explaining afterwards why the wrong node was not the node that rebooted.
- PowerShell for anything I have had to do twice, Bash and Python when the machine is Linux
- Compose stacks, nginx, TLS, and backups that have been restored at least once

### Repos worth a look

**[AndroMouse](https://github.com/errypuu/AndroMouse)** moves a Windows mouse and
keyboard onto an Android tablet over the LAN, without root or wireless ADB. C# tray
app on the PC, Kotlin accessibility service and IME on the tablet, UDP for pointer
deltas and TCP for clicks, keys and screenshots.

**[SpectreMeltdownMitigation](https://github.com/errypuu/SpectreMeltdownMitigation)**
is PowerShell that reads Spectre and Meltdown exposure on a Windows fleet, reports it,
applies the mitigation and checks the result.

**[SimpleHostedNetworkActivator](https://github.com/errypuu/SimpleHostedNetworkActivator)**
is from 2016, when I was still in IT support and turning a laptop into a hotspot took
four dialog boxes.

Portfolio: <https://erryio.darajati.my.id>

<sub>The interesting half of the work is in private repos and on a rack at home.
This is what can be shown in public.</sub>
