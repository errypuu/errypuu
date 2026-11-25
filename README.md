<!-- errypuu/errypuu — profile README. Keep the links real; the projects below are
     the ones that actually exist on this account. -->
<picture>
  <img src="banner.png" alt="erry darajati — infrastructure and IT support" width="100%">
</picture>

# Erry Pradana Darajati

**Infrastructure & IT Support Engineer** — Sidoarjo, Indonesia

I keep Windows Server fleets, Hyper-V hosts and Azure tenants running for US-based
clients through Wowrack. Seven years of nights where the pager goes off, the box has
to come back, and nobody cares how clever the fix was — only that it held.

Outside the day job I run a homelab that is honestly too big: Proxmox with a handful
of LXC containers, a Docker host behind a reverse proxy, Pi-hole and AdGuard for DNS,
NetBird for the mesh, and a pile of self-hosted services I actually use instead of
just collecting.

---

### What I work on

- **Windows Server / AD** — domain services, GPO, DNS, DHCP, Hyper-V failover clusters, and patching that does not reboot the wrong node
- **Azure** — Entra ID, VM provisioning, conditional access, and cost that stays inside the tenant's budget
- **Automation** — PowerShell for anything done twice; Bash and Python when the target is Linux
- **Self-hosting** — Compose stacks, nginx and NPM, TLS, backups and restore drills, because a backup nobody restored is a rumour

---

### Things I have built

**[AndroMouse](https://github.com/errypuu/AndroMouse)** — use a Windows mouse and
keyboard on an Android tablet over the LAN, no root and no wireless ADB. A C# tray app
on the PC, a Kotlin accessibility service and IME on the tablet, UDP for mouse deltas
and TCP for input and clipboard handoff.

**[SpectreMeltdownMitigation](https://github.com/errypuu/SpectreMeltdownMitigation)** —
PowerShell to audit and remediate Spectre/Meltdown exposure on a Windows fleet: read
the vulnerable state, report it, apply the mitigation, then verify it took.

**[SimpleHostedNetworkActivator](https://github.com/errypuu/SimpleHostedNetworkActivator)** —
a small tool from my first year in IT that turns a Windows machine into a hosted
network in one click. Kept as a reminder of how far the toolkit has come.

---

### Elsewhere

Portfolio and writing: <https://erryio.darajati.my.id>

<sub>Most of the work lives in private repos, in a homelab rack, and in support
tickets. This page is the part that fits on a README.</sub>
