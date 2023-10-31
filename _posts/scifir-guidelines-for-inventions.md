---
title:  "Scifir guidelines for inventions"
date:   2023-09-08
edition: 1
categories: [inventions]
authors: [ismaelc,try]
status: draft
---

## Architecture

- **Always** use a minimalist Linux, unless it's needed an operating system cause the electronic device is too much simple. You can use **Linux from scratch** for that purpose.
- **Usually** add remote control, over SSH or another method, to be able to access the device, and execute any operation there, from any personal computer.

## Hardware

- Add **wireless communication**, and disable internet on the device unless it uses it to avoid security issues.
- Use **wifi for wireless communication**, because it can have internet if needed, and then it's not needed to add a wireless communication chip for connecting to a local computer and another for internet, it's instead just needed one.

## Software

- Use a native programming language, preferably **C** or **C++**, for the firmware, the servers and any desktop software.
- Use **libconf** or **libcfg** for configuration files, in order to follow Linux.
- Use **XML** or **YAML** for the data. Only use a database if it's explicitly needed for the fact that XML files become too large even when having a wide amount of them.
- Use a private and public key for the communication, always with a passphrase.
- The desktop program that connects to the device should allow to **monitor the activity** of it, to **control** how the device is behaving, **display the data** collected by the device and/or change the **configuration files**.
