# Awesome LXC, LXD and Incus with stars

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of useful LXC, LXD, and Incus tools, libraries, integrations, and learning resources.

## Contents

* [Packages and Host Platforms](#packages-and-host-platforms)
* [Images and Image Building](#images-and-image-building)
* [Libraries and SDKs](#libraries-and-sdks)
* [Infrastructure as Code and Orchestration](#infrastructure-as-code-and-orchestration)
* [Tools and Development Workflows](#tools-and-development-workflows)
* [User Interfaces](#user-interfaces)
* [Operations](#operations)
* [Community and Learning](#community-and-learning)
* [Historical Reads](#historical-reads)
* [Official Resources](#official-resources)
* [Contributing](#contributing)

## Packages and Host Platforms

* [zabbly/incus](https://github.com/zabbly/incus) ⭐ 544 | 🐛 6 | 🌐 Python | 📅 2026-08-28 — Signed Incus packages for supported Debian and Ubuntu releases.
* [vpsadminos](https://github.com/vpsfreecz/vpsadminos) ⭐ 184 | 🐛 6 | 🌐 Ruby | 📅 2026-08-28 — NixOS and ZFS-based host operating system for unprivileged LXC containers.
* [incus-docker](https://github.com/cmspam/incus-docker) ⭐ 51 | 🐛 1 | 🌐 Dockerfile | 📅 2026-08-10 — Runs Incus and its web UI inside privileged Docker or Podman containers.
* [copr-lxc4](https://github.com/ganto/copr-lxc4) ⭐ 38 | 🐛 5 | 🌐 Shell | 📅 2026-05-01 — Fedora COPR packages for LXC, LXCFS, LXD, and Incus.
* [pve-container](https://git.proxmox.com/?p=pve-container.git) — Proxmox VE container manager and runtime built on LXC.

## Images and Image Building

* [lxd-openwrt](https://github.com/mikma/lxd-openwrt) ⭐ 152 | 🐛 5 | 🌐 Shell | 📅 2026-03-09 — Builds OpenWrt root filesystems as LXD system container images.
* [incus-windows](https://github.com/antifob/incus-windows) ⭐ 98 | 🐛 2 | 🌐 PowerShell | 📅 2026-07-21 — Toolset for creating Windows images for Incus virtual machines.
* [polar](https://github.com/upmaru/polar) ⭐ 52 | 🐛 0 | 🌐 Elixir | 📅 2024-07-05 — Simple Streams image server for LXD and Incus.
* [simplestreams-builder](https://github.com/MottainaiCI/simplestreams-builder) ⭐ 19 | 🐛 0 | 🌐 Go | 📅 2024-04-19 — Builds LXC, LXD, and Incus-compatible Simple Streams trees.
* [talos-incus](https://github.com/windsorcli/talos-incus) ⭐ 12 | 🐛 2 | 🌐 JavaScript | 📅 2026-08-19 — Publishes signed Talos Linux VM images through an Incus Simple Streams remote.
* [Ubuntu Cloud Images](https://cloud-images.ubuntu.com/releases/) — Official stable Ubuntu images used by the `ubuntu:` remote.

## Libraries and SDKs

* [lxc-rs](https://github.com/sanpii/lxc-rs) ⭐ 24 | 🐛 8 | 🌐 Rust | 📅 2026-06-22 — Rust bindings for the native `liblxc` API.
* [php-lxd](https://github.com/turtle0x1/php-lxd) ⭐ 13 | 🐛 5 | 🌐 PHP | 📅 2026-03-15 — PHP client library for the LXD REST API.

## Infrastructure as Code and Orchestration

* [Proxmox-GitOps](https://github.com/stevius10/Proxmox-GitOps) ⭐ 580 | 🐛 1 | 🌐 Ruby | 📅 2026-07-18 — GitOps and infrastructure-as-code framework for Proxmox LXC containers.
* [terraform-provider-lxd](https://github.com/terraform-lxd/terraform-provider-lxd) ⭐ 273 | 🐛 11 | 🌐 Go | 📅 2026-08-28 — Manages LXD resources with Terraform or OpenTofu.
* [proxmox-lxc-autoscale](https://github.com/fabriziosalmi/proxmox-lxc-autoscale) ⭐ 256 | 🐛 18 | 🌐 Python | 📅 2026-08-25 — Dynamically adjusts CPU and memory allocations for Proxmox LXC containers.
* [incus-apply](https://github.com/abiosoft/incus-apply) ⭐ 32 | 🐛 4 | 🌐 Go | 📅 2026-06-15 — Declarative configuration management for Incus resources.
* [packer-plugin-incus](https://github.com/bketelsen/packer-plugin-incus) ⭐ 15 | 🐛 0 | 🌐 Go | 📅 2026-01-11 — Builds reusable Incus images with Packer provisioners.
* [packer-plugin-lxd](https://github.com/hashicorp/packer-plugin-lxd) ⭐ 14 | 🐛 10 | 🌐 Go | 📅 2026-05-11 — Builds reusable LXD images with Packer provisioners.
* [packer-plugin-lxc](https://github.com/hashicorp/packer-plugin-lxc) ⭐ 7 | 🐛 9 | 🌐 Go | 📅 2026-05-11 — Builds native LXC container images with Packer.
* [community.general.incus](https://docs.ansible.com/ansible/latest/collections/community/general/incus_connection.html) — Runs Ansible tasks directly inside Incus instances.
* [community.general.lxd](https://docs.ansible.com/ansible/latest/collections/community/general/lxd_connection.html) — Runs Ansible tasks directly inside LXD instances.

## Tools and Development Workflows

* [colima](https://github.com/abiosoft/colima) ⭐ 30,557 | 🐛 390 | 🌐 Go | 📅 2026-08-24 — Runs Docker, containerd, Kubernetes, or Incus on macOS and Linux with minimal setup.
* [crabbox](https://github.com/openclaw/crabbox) ⭐ 1,339 | 🐛 37 | 🌐 Go | 📅 2026-08-29 — Creates Incus-backed SSH leases for remote development and test workloads.
* [code-on-incus](https://github.com/mensfeld/code-on-incus) ⭐ 674 | 🐛 26 | 🌐 Go | 📅 2026-08-28 — Runs isolated development agents with root, systemd, Docker, and network threat controls.
* [garm](https://github.com/cloudbase/garm) ⭐ 387 | 🐛 29 | 🌐 Go | 📅 2026-08-25 and [garm-provider-incus](https://github.com/cloudbase/garm-provider-incus) ⭐ 14 | 🐛 1 | 🌐 Go | 📅 2026-08-24 — Autoscale ephemeral GitHub Actions and Gitea runners on Incus.
* [mi-lxc](https://github.com/flesueur/mi-lxc) ⭐ 346 | 🐛 15 | 🌐 Shell | 📅 2026-05-26 — Builds virtual Internet-like networks with LXC for teaching and research.
* [containarium](https://github.com/FootprintAI/Containarium) ⭐ 275 | 🐛 88 | 🌐 Go | 📅 2026-08-27 — Provides SSH-native isolated environments with an LXC backend, eBPF egress controls, and GPU support.
* [bravetools](https://github.com/bravetools/bravetools) ⭐ 158 | 🐛 13 | 🌐 Go | 📅 2026-07-25 — Builds, deploys, and releases environments with system containers.
* [vibebin](https://github.com/jgbrwn/vibebin) ⭐ 105 | 🐛 0 | 🌐 Go | 📅 2026-08-10 — Creates Incus-backed coding and hosting environments on self-hosted servers.
* [incant](https://github.com/lnussbaum/incant) ⭐ 84 | 🐛 8 | 🌐 Python | 📅 2026-07-20 — Defines reproducible Incus development environments in YAML.
* [blincus](https://github.com/ublue-os/blincus) ⭐ 67 | 🐛 8 | 🌐 Shell | 📅 2026-07-07 — Creates rapid Incus-based development environments.
* [ssh2incus](https://github.com/mobydeck/ssh2incus) ⭐ 64 | 🐛 5 | 🌐 Go | 📅 2026-02-16 — SSH gateway for accessing Incus instances.
* [edi](https://github.com/lueschem/edi) ⭐ 49 | 🐛 5 | 🌐 Python | 📅 2026-04-17 — Builds reproducible embedded OS artifacts and LXD-based digital twins.
* [lxd-compose](https://github.com/MottainaiCI/lxd-compose) ⭐ 40 | 🐛 9 | 🌐 Go | 📅 2026-08-05 — Defines and runs groups of LXD or Incus instances.
* [incus-spawn](https://github.com/Sanne/incus-spawn) ⭐ 36 | 🐛 45 | 🌐 Java | 📅 2026-08-28 — CLI and TUI for disposable Incus development sandboxes.
* [lincubate](https://github.com/popey/lincubate) ⚠️ Archived — Runs development agents in sandboxed LXD containers.

## User Interfaces

* [xpipe](https://github.com/xpipe-io/xpipe) ⭐ 14,465 | 🐛 67 | 🌐 Java | 📅 2026-08-29 — Desktop interface for discovering and accessing local or remote LXD and Incus instances.
* [LxdMosaic](https://github.com/turtle0x1/LxdMosaic) ⭐ 611 | 🐛 20 | 🌐 PHP | 📅 2026-08-21 — Web interface for managing multiple LXD and Incus servers.
* [lxconsole](https://github.com/PenningLabs/lxconsole) ⭐ 469 | 🐛 27 | 🌐 HTML | 📅 2026-01-26 — Multi-server web console supporting LXD and Incus.
* [oneclickvirt](https://github.com/oneclickvirt/oneclickvirt) ⭐ 366 | 🐛 1 | 🌐 Go | 📅 2026-08-28 — Multi-hypervisor management panel with Incus and LXD support.
* [incus-ui-canonical](https://github.com/zabbly/incus-ui-canonical) ⭐ 115 | 🐛 5 | 🌐 TypeScript | 📅 2026-08-25 — Frequently rebased Incus-compatible fork of Canonical's LXD UI.
* [ararat-web](https://github.com/hyecompany/ararat-web) ⭐ 39 | 🐛 19 | 🌐 TypeScript | 📅 2026-07-25 — Incus-native web control plane currently in public beta.
* [kapsule](https://github.com/KDE/kapsule) ⭐ 22 | 🐛 0 | 🌐 Python | 📅 2026-08-28 — Incus container management with KDE Plasma integration.

## Operations

* [incusAutobackup](https://github.com/rbnhln/incusAutobackup) ⭐ 8 | 🐛 13 | 🌐 Go | 📅 2026-08-28 — Replicates Incus instances and volumes between source and target hosts.
* [incusbackup](https://github.com/ScottiBYTE/incusbackup) ⭐ 2 | 🐛 1 | 🌐 JavaScript | 📅 2026-06-14 — Web-based scheduled backup and restore across multiple Incus remotes.
* [Incus Grafana dashboard](https://grafana.com/grafana/dashboards/19727-incus/) — Dashboard for Incus server, project, and instance metrics.

## Community and Learning

* [LXC on Libera.Chat](https://web.libera.chat/#lxc) — Real-time `#lxc` community channel.
* [Zabbly on YouTube](https://www.youtube.com/@TheZabbly) — Incus demos, release announcements, and tutorials.
* [ArchWiki: LXC](https://wiki.archlinux.org/title/Linux_Containers), [Incus](https://wiki.archlinux.org/title/Incus), and [LXD](https://wiki.archlinux.org/title/LXD) — Distribution-specific installation and operations guides.
* [Creating an Incus server](https://docs.rockylinux.org/latest/books/incus_server/00-toc/) — Long-form Incus deployment guide for Rocky Linux.

## Historical Reads

These resources explain foundational concepts but may contain outdated commands or project details.

* [Comparing LXD vs. LXC](https://discuss.linuxcontainers.org/t/comparing-lxd-vs-lxc/24) — Early explanation of the different roles of the LXC runtime and LXD manager.
* [LXD 2.0 blog post series](https://stgraber.org/2016/03/11/lxd-2-0-blog-post-series-012/) — In-depth introduction to LXD's original core concepts by Stéphane Graber.

***

## Official Resources

### Projects

* [incus](https://github.com/lxc/incus) ⭐ 6,065 | 🐛 36 | 🌐 Go | 📅 2026-08-28 — Community-led system container and virtual machine manager.
* [lxc](https://github.com/lxc/lxc) ⭐ 5,248 | 🐛 151 | 🌐 C | 📅 2026-08-20 — Linux system container runtime, command-line tools, and `liblxc` library.
* [lxd](https://github.com/canonical/lxd) ⭐ 4,820 | 🐛 420 | 🌐 Go | 📅 2026-08-28 — Canonical's system container and virtual machine manager.
* [lxcfs](https://github.com/lxc/lxcfs) ⭐ 1,194 | 🐛 37 | 🌐 C | 📅 2026-05-15 — FUSE filesystem providing container-aware system information.
* [incus-os](https://github.com/lxc/incus-os) ⭐ 1,084 | 🐛 45 | 🌐 Go | 📅 2026-08-29 — Immutable operating system dedicated to running Incus.
* [microcloud](https://github.com/canonical/microcloud) ⭐ 531 | 🐛 52 | 🌐 Go | 📅 2026-08-26 — Automated private cloud built from LXD, Ceph, and OVN.
* [Linux Containers](https://linuxcontainers.org/) — Home of the LXC, LXCFS, Incus, and distrobuilder projects.

### Documentation

**LXC**

* [LXC documentation](https://linuxcontainers.org/lxc/documentation/) — Upstream configuration, API, and usage documentation.
* [Getting started with LXC](https://linuxcontainers.org/lxc/getting-started/) — Introduction to installing and creating unprivileged containers.
* [LXC man pages](https://linuxcontainers.org/lxc/manpages/) — Command and `lxc.container.conf` reference.
* [liblxc C API](https://linuxcontainers.org/lxc/apidoc/) — Generated native API reference.

**Incus**

* [Incus documentation](https://linuxcontainers.org/incus/docs/main/) — Official tutorials, how-to guides, explanations, and reference material.
* [First steps with Incus](https://linuxcontainers.org/incus/docs/main/tutorial/first_steps/) — Guided introduction to creating and managing instances.
* [Try Incus online](https://linuxcontainers.org/incus/try-it/) — Interactive tutorial in a disposable hosted environment.
* [Incus REST API](https://linuxcontainers.org/incus/docs/main/rest-api/) — API behavior, authentication, extensions, and endpoints.
* [Incus CLI reference](https://linuxcontainers.org/incus/docs/main/reference/manpages/) — Complete `incus` command reference.

**LXD**

* [LXD documentation](https://documentation.ubuntu.com/lxd/latest/) — Canonical's official tutorial, how-to, explanation, and reference hub.
* [First steps with LXD](https://documentation.ubuntu.com/lxd/latest/tutorial/first_steps/) — Guided CLI and web UI introduction.
* [LXD REST API](https://documentation.ubuntu.com/lxd/latest/restapi_landing/) — API, OpenAPI specification, extensions, and events.
* [LXD CLI reference](https://documentation.ubuntu.com/lxd/latest/reference/manpages/) — Complete `lxc` command reference.

### Images and Image Building

* [distrobuilder](https://github.com/lxc/distrobuilder) ⭐ 869 | 🐛 27 | 🌐 Go | 📅 2026-08-26 — Builds LXC and Incus images from declarative YAML definitions.
* [lxd-imagebuilder](https://github.com/canonical/lxd-imagebuilder) ⭐ 22 | 🐛 4 | 🌐 Go | 📅 2026-08-21 — Builds LXD container and VM images and Simple Streams catalogs.
* [Linux Containers image server](https://images.linuxcontainers.org/) — Continuously built and tested images for LXC and Incus.
* [Canonical LXD image server](https://images.lxd.canonical.com/) — Multi-distribution image catalog used by LXD's `images:` remote.
* [distrobuilder documentation](https://linuxcontainers.org/distrobuilder/docs/latest/) — Tutorials and reference for custom LXC and Incus images.
* [lxd-imagebuilder documentation](https://canonical-lxd-imagebuilder.readthedocs-hosted.com/) — Tutorials and reference for `lxd-imagebuilder`.

### SDKs and Integrations

* [lxd-ui](https://github.com/canonical/lxd-ui) ⭐ 493 | 🐛 44 | 🌐 TypeScript | 📅 2026-08-28 — Canonical's official browser interface, included with LXD.
* [go-lxc](https://github.com/lxc/go-lxc) ⭐ 467 | 🐛 6 | 🌐 Go | 📅 2026-03-16 — Go bindings for `liblxc`.
* [pylxd](https://github.com/canonical/pylxd) ⭐ 277 | 🐛 46 | 🌐 Python | 📅 2026-08-27 — Official Python client for the LXD REST API.
* [terraform-provider-incus](https://github.com/lxc/terraform-provider-incus) ⭐ 210 | 🐛 15 | 🌐 Go | 📅 2026-08-24 — Manages Incus instances, projects, profiles, networks, and storage.
* [incus-deploy](https://github.com/lxc/incus-deploy) ⭐ 156 | 🐛 12 | 🌐 HCL | 📅 2026-05-26 — Ansible, Terraform, and scripts for deploying Incus clusters with Ceph and OVN.
* [cluster-api-provider-incus](https://github.com/lxc/cluster-api-provider-incus) ⭐ 115 | 🐛 6 | 🌐 Go | 📅 2026-06-28 — Provisions Kubernetes clusters on Incus, LXD, and MicroCloud.
* [python3-lxc](https://github.com/lxc/python3-lxc) ⭐ 67 | 🐛 9 | 🌐 C | 📅 2026-08-20 — Python 3 bindings for `liblxc`.
* [incus-compose](https://github.com/lxc/incus-compose) ⭐ 63 | 🐛 9 | 🌐 Go | 📅 2026-08-28 — Runs Compose-spec workloads natively on Incus.
* [lxd-csi-driver](https://github.com/canonical/lxd-csi-driver) ⭐ 8 | 🐛 9 | 🌐 Go | 📅 2026-08-28 — Exposes LXD storage to Kubernetes workloads.
* [Incus Go client](https://pkg.go.dev/github.com/lxc/incus/client) — Official Go SDK shipped with Incus.
* [LXD Go client](https://pkg.go.dev/github.com/canonical/lxd/client) — Official Go SDK shipped with LXD.

### Backup and Migration

* [Migrate LXD to Incus](https://github.com/lxc/incus/blob/stable-7.0/doc/howto/server_migrate_lxd.md) ⭐ 6,065 | 🐛 36 | 🌐 Go | 📅 2026-08-28 — Version-pinned `lxd-to-incus` guide; check its compatibility table before migrating.
* [Back up an Incus server](https://linuxcontainers.org/incus/docs/main/backup/) — Official snapshot, export, recovery, and host-level backup guidance.
* [Back up an LXD server](https://documentation.ubuntu.com/lxd/latest/backup/) — Official instance, volume, and server backup guidance.
* [Incus migration overview](https://linuxcontainers.org/incus/docs/main/migration/) — Server-to-server, LXC, physical machine, and virtual machine migration guides.
* [Import machines into Incus](https://linuxcontainers.org/incus/docs/main/howto/import_machines_to_instances/) — Imports filesystems and raw, QCOW2, OVA, or VMDK images with `incus-migrate`.
* [Migrate LXC containers to Incus](https://linuxcontainers.org/incus/docs/main/howto/migrate_from_lxc/) — Converts local LXC containers with `lxc-to-incus`.
* [Migrate LXD instances](https://documentation.ubuntu.com/lxd/latest/howto/instances_migrate/) — Copies, moves, and live-migrates instances between LXD servers.
* [Import machines into LXD](https://documentation.ubuntu.com/lxd/latest/howto/import_machines_to_instances/) — Converts physical machines and foreign VM disks with `lxd-convert`.

### Monitoring and Security

* [Incus security advisories](https://github.com/lxc/incus/security) ⭐ 6,065 | 🐛 36 | 🌐 Go | 📅 2026-08-28 — Reporting policy and published advisories.
* [LXD security advisories](https://github.com/canonical/lxd/security/advisories) ⭐ 4,820 | 🐛 420 | 🌐 Go | 📅 2026-08-28 — Canonical's published vulnerability record.
* [Incus metrics](https://linuxcontainers.org/incus/docs/main/metrics/) — Exposes native Prometheus metrics for servers and instances.
* [LXD metrics](https://documentation.ubuntu.com/lxd/latest/metrics/) — Exposes native Prometheus metrics for servers and instances.
* [LXC security](https://linuxcontainers.org/lxc/security/) — Threat model, privileged versus unprivileged containers, and vulnerability reporting.
* [Incus security](https://linuxcontainers.org/incus/docs/main/explanation/security/) — Isolation, daemon access, networking, and supported-release guidance.
* [LXD security](https://documentation.ubuntu.com/lxd/latest/explanation/security/) — Security architecture and operational considerations.
* [Hardening LXD](https://documentation.ubuntu.com/lxd/latest/howto/security_harden/) — Production hardening checklist.

### Community

* [Linux Containers Forum](https://discuss.linuxcontainers.org/) — Official support forum for Incus, LXC, LXCFS, and distrobuilder.
* [Linux Containers tutorials](https://discuss.linuxcontainers.org/c/tutorials/16) — Community-reviewed tutorials across the Linux Containers projects.
* [LXD on Ubuntu Community Hub](https://discourse.ubuntu.com/c/project/lxd/126) — Official LXD support and discussion forum.
* [LXD community tutorials](https://discourse.ubuntu.com/c/project/lxd/tutorials/146) — Community-authored LXD tutorials.
* [LXD on YouTube](https://www.youtube.com/channel/UCuP6xPt0WTeZu32CkQPpbvA) — Canonical's LXD videos and tutorials.

## Contributing

Contributions are welcome. Please read [the contribution guidelines](CONTRIBUTING.md) before opening a pull request.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-29._
