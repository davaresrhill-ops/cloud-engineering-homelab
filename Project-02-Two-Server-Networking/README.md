# Project 2 — Two-Server Networking Lab

## 📌 Overview

Built a two-server Ubuntu environment in Proxmox and configured communication between an application server and web server.

## 🎯 Objectives

- Deploy a second Ubuntu server
- Configure network connectivity
- Establish SSH communication
- Test HTTP communication
- Understand IP addresses and ports
- Verify network services

## 🖥️ Environment

- Virtualization: Proxmox
- Web Server: Ubuntu + Nginx
- App Server: Ubuntu
- Communication: SSH and HTTP

## 🌐 Architecture

App Server → HTTP → Web Server → Nginx

App Server → SSH → Web Server

## 🔌 Network Testing

### Connectivity

Tested network connectivity using:

```bash
ping -c 4 WEB_SERVER_IP
