# hasystemd
<H3>High availability for systemd services using K8s.</H3>

- High availability for <b>systemd</b> based network services running on VM or Bare-metal machines.<br>
- Constant service monitoring, detecting service failures caused by various (ex. Disk, Memroy, CPU, Network, Software..) failures.<br>
- Automated switch-over to another ruuning service instance with primary/secondary (ex. Database, Mail, Web, VPN, Key-Value stores..).<br>
- High availability network management (Virtual IP) associated with the primary instance.<br>
- Automated fencing of lost or unhealthy server Nodes if enabled.<br>
- Setup alerts based on events.<br>
- Quick and easy installation, configuration and managment.<br>

### Table of contents
* [Installation]()
    * [High Available K8s setup]()
    * [Deploy with helm]()
    * [Deploy with kubectl]()
* [Quick Start]()
