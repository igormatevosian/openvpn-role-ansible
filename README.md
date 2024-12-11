# Openvpn Role

An Ansible role for installing and configuring OpenVPN on a Linux server, generating client configuration files, and setting up a secure VPN connection.

## Requirements

- Ansible 2.9+ is required.
- Target system must be Ubuntu.

## Templates

This role includes template:

**server.conf.j2** - Main configuration file for server.

**client.conf.j2** - Main configuration file for client.

## Dependencies

This role has no dependencies on other roles.