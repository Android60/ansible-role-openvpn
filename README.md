# OpenVPN server Ansible role

This directory contains playbooks used for installing and configuring OpenVPN server.

Supported variables:
```
openvpn_port: "1194"
openvpn_proto: "udp"
openvpn_easyrsa_path: "/opt/EasyRSA"
openvpn_configuration_directory: "/etc/openvpn/"
easyrsa_version: "3.0.9"
ovpn_admin_path: "/opt/ovpn-admin"
nginx_global_auth_username: "admin"
nginx_global_auth_password: "your_password"
firewalld_default_interface_zone: "public"
ovpn_ui_install: true
```
