Ansible scripts and jinja2 templates I wrote up for 2 different VMs for my homelab use
  - Bind9 (authoritative)
  - Adguard + Unbound (recursive)

Apply config using Ansible by running each playbook
Write your own inventory
Modify the templates to suit your subnet/VLAN needs and add your own variable values in oyur group_vars dir to fit your IPs

Used gpt as a linter to check my work and debug syntax

This repo is provided under the MIT License as a functional template/example of my homelab DNS setup. It is not production-ready; adapt and harden before use in sensitive environments.”
