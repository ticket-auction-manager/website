+++
date = '2026-09-28T18:09:32-04:00'
draft = false
title = 'V0.1.0rc1'
description = "First major release of Ticket Auction Manager Go."
+++

First major release.

ticket-auction-manager/tam-go is now fully functional on a new Golang base, which means it cleanly compiles into cross-platform binaries now.

Though testing seems to prove that it works well, I cannot guarantee its stability and data integrity so please use at your own risk.

<!--more-->

## Release Github Page:

You can search for the build on your own system here:

[Link to Github Release page](https://github.com/ticket-auction-manager/tam-go/releases/tag/0.1.0rc1)

## Common builds:

Clients:

- [TAM Client - Windows (x64)](https://github.com/ticket-auction-manager/tam-go/releases/download/0.1.0rc1/tam-client-0.1.0rc1-windows-amd64.zip)
- [TAM Client - Windows (ARM64)](https://github.com/ticket-auction-manager/tam-go/releases/download/0.1.0rc1/tam-client-0.1.0rc1-windows-arm64.zip)
- [TAM Client - Linux (x64)](https://github.com/ticket-auction-manager/tam-go/releases/download/0.1.0rc1/tam-client-0.1.0rc1-linux-amd64.tar.gz)
- [TAM Client - Linux (ARM64)](https://github.com/ticket-auction-manager/tam-go/releases/download/0.1.0rc1/tam-client-0.1.0rc1-linux-arm64.tar.gz)
- [TAM Client - Mac/Darwin (ARM64)](https://github.com/ticket-auction-manager/tam-go/releases/download/0.1.0rc1/tam-client-0.1.0rc1-darwin-arm64.tar.gz)

Servers:

- [TAM Server - Windows (x64)](https://github.com/ticket-auction-manager/tam-go/releases/download/0.1.0rc1/tam-server-0.1.0rc1-windows-amd64.zip)
- [TAM Server - Windows (ARM64)](https://github.com/ticket-auction-manager/tam-go/releases/download/0.1.0rc1/tam-server-0.1.0rc1-windows-arm64.zip)
- [TAM Server - Linux (x64)](https://github.com/ticket-auction-manager/tam-go/releases/download/0.1.0rc1/tam-server-0.1.0rc1-linux-amd64.tar.gz)
- [TAM Server - Linux (ARM64)](https://github.com/ticket-auction-manager/tam-go/releases/download/0.1.0rc1/tam-server-0.1.0rc1-linux-arm64.tar.gz)
- [TAM Server - Mac/Darwin (ARM64)](https://github.com/ticket-auction-manager/tam-go/releases/download/0.1.0rc1/tam-server-0.1.0rc1-darwin-arm64.tar.gz)

## Debian-based Distros

(Debian, Ubuntu, Linux Mint)

You can download and install the client or server application for your computer's architecture. Most Debian based distros have a GUI wrapper for dpkg, which allows you to double click the .deb file and then click install. If not, you should be able to run `dpkg -i tam....deb` and answer y to start installing it.

If it installs successfully then you can open up your web browser and go to http://localhost:3080/ or http://127.0.0.1:3080/ to use the application.

### Client

- x64 systems (AMD and Intel CPU's)
  - [TAM Client Debian Package for x64](https://github.com/ticket-auction-manager/tam-go/releases/download/0.1.0rc1/tam-client_0.1.0rc1-1_amd64.deb)
- ARM64 systems (Snapdragon or other SoC's)
  - [TAM Client Debian Package for ARM64](https://github.com/ticket-auction-manager/tam-go/releases/download/0.1.0rc1/tam-client_0.1.0rc1-1_arm64.deb)

### Server

- x64 systems (AMD and Intel CPU's)
  - [TAM Server Debian Package for x64](https://github.com/ticket-auction-manager/tam-go/releases/download/0.1.0rc1/tam-server_0.1.0rc1-1_amd64.deb)
- ARM64 systems (Snapdragon or other SoC's)
  - [TAM Server Debian Package for ARM64](https://github.com/ticket-auction-manager/tam-go/releases/download/0.1.0rc1/tam-server_0.1.0rc1-1_arm64.deb)

## RPM Distros

(Red Hat, Fedora, OpenSUSE, Rocky, Alma, and others)

You can download and install the RPM package of either daemon from the links below. Some RPM distros have GUI wrapper for the package manager, so you may be able to double click on the RPM package in your files and then click install. If you don't have one on your distro, you will have to use your command line package manager, such as dnf, zypper, or another, depending on which RPM distro you're running.

If it installs successfully then you can open up your web browser and go to http://localhost:3080/ or http://127.0.0.1:3080/ to use the application.

### Client

- x64 systems (AMD and Intel CPU's)
  - [TAM Client RPM Package for x64](https://github.com/ticket-auction-manager/tam-go/releases/download/0.1.0rc1/tam-client-0.1.0rc1-1.x86_64.rpm)
- ARM64 systems (Snapdragon or other SoC's)
  - [TAM Client RPM Package for ARM64](https://github.com/ticket-auction-manager/tam-go/releases/download/0.1.0rc1/tam-client-0.1.0rc1-1.aarch64.rpm)

### Server

- x64 systems (AMD and Intel CPU's)
  - [TAM Server RPM Package for x64](https://github.com/ticket-auction-manager/tam-go/releases/download/0.1.0rc1/tam-server-0.1.0rc1-1.x86_64.rpm)
- ARM64 systems (Snapdragon or other SoC's)
  - [TAM Server RPM Package for ARM64](https://github.com/ticket-auction-manager/tam-go/releases/download/0.1.0rc1/tam-server-0.1.0rc1-1.aarch64.rpm)
