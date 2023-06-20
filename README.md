# kube-ha-systemd
<H3>High availability for install based systemd services using K8s.</H3>

- High availability for systemd services running on VM or Bare-metal machines.<br>
- Service recovery and fail-over to another worker Node if recovery fails..<br>
- Automated take-over to another ruuning instance when primary/secondary instances are present (database services, key-value stores..).
- High availability network management VIP/EIP.<br>
- Automated fencing of lost or unhealthy server Nodes.<br>
- Quick and easy high availability configuration via single yaml file.<br>

## Table of contents
* [Installation]()
    * [High Available K8s setup]()
    * [Deploy with helm]()
    * [Deploy with kubectl]()
* [Quick Start]()
