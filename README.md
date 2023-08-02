# Table of contents
- [What is Bamboo Firewall?](#What-is-Bamboo-Firewall?)
- [Community](#Community)
- [Case studies](#Case-studies)
- [Architecture](#Architecture)
- [License](#License)

# What is Bamboo Firewall?
Bamboo Firewall is an opensource software firewall that supports network segmentation, Central management and Rulers/Polices as code. It is a host base firewall, so the policy is very strict. Unlike traditional firewalls, it provides many functions for centralized policy setting as tag, label, range, annotations...

# Community
You can join the following groups or channels to discuss or ask questions about Bamboo Firewall, and to keep yourself informed of the latest Bamboo Firewall updates:
- Seek help when you use TiDB
  - Slack channels: [#everyone (Vietnamese, English)](https://join.slack.com/t/bamboo-firewall/shared_invite/zt-207jwcvcl-tIXUfYBKoe6TNPcce6iqXw)

# Case studies
- [Bamboo Firewall at GHTK](./case-studies/ghtk.md)

# Architecture
![Bamboo Firewall architecture](./imgs/architecture/architecture.png)

- etcd cluster: where store metadata of bamboo firewall. ex: server endpoint, network zone, policies
- be: API backend server. It provides API for frontend
- fe: Frontend provides user interfaces via webview
- cli: command line provides console interface for administrator  
- agent: Agent installed each server and connect to etcd cluster to apply polices

# About us
- [bienkma](https://bienkma.github.io) - Founder
- [anhcx0209](https://github.com/anhcx0209) - Backend engineer (Co-Founder)
- [uncelvel](https://github.com/uncelvel) - Designer (Co-Founder)
- [x3vuduclong](https://github.com/x3vuduclong) - Frontend engineer (Co-Founder)
- [D4r1inG](https://github.com/D4r1inG) - Frontend engineer (Co-Founder)

# License

Bamboo Firewall is under the Apache 2.0 license. See the LICENSE file for details.

