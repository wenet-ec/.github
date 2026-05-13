div align="center">

# 🌐 WENet

### Edge computing, made boring.

*We meet you where you are. Let us bring the edge to you*

[![Website](https://img.shields.io/badge/web-wenet--ec.com-24344D?style=for-the-badge)](https://wenet-ec.com)

</div>

---

## 👋 Who we are

We're WENet — a small, focused team building the infrastructure layer for **edge computing**. EC is Edge Computing if you are wondering.

Edge is having its moment. Workloads are moving out of centralized clouds and onto machines that live closer to where data is actually produced — factory floors, retail stores, vehicles, homes, labs, kiosks. That shift is exciting, but the tooling for managing fleets of edge nodes is still rough: half-finished open-source projects, expensive proprietary platforms, or DIY scripts duct-taped together.

We think it should be calmer than that.

## 🛰️ What we build

### [`edge-core`](https://github.com/wenet-ec/edge-core)

Our flagship open-source project. A distributed control plane for fleets of edge machines — anywhere from three Raspberry Pis on a workbench to thousands of nodes across continents.

What it gives you:

- 🔐 **Secure mesh networking** — WireGuard tunnels between every node, no public IPs required
- 🖥️ **Remote SSH** — get a shell on any node, anywhere, without exposing port 22
- ⚙️ **Command execution** — run commands across nodes, get structured output back
- 📊 **Metrics out of the box** — Prometheus-compatible scraping for the whole fleet
- 🔄 **Self-update** — agents update themselves without you SSH-ing into every box
- 🧩 **Pluggable** — event broker adapters, metrics consumers, integrations of your choosing

</div>
