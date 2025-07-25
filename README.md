# Welcome to HYTTPS script v2.0

_________

## HYTTPS

**HYTTPS** is a robust Python-based toolkit designed for penetration testing of wireless networks, specifically targeting **WPA/WPA2 handshakes**. This tool provides security professionals with a comprehensive set of features to assess the integrity of wireless networks and **identify potential vulnerabilities**.

## Supported Kernel

    Linux (Every Distro)

## How to install

**If you download it as a .zip file, it will not run. Make sure to follow these instructions in order.**

**make sure you are a root user**

    apt-get update
    git clone https://github.com/TR0JNN/HYTTPS.git
    cd HYTTPS
    cd HYTTPS

## Installation Requirements

To get started, ensure you have the necessary Python libraries and tools installed

    Python3.12
    pip3 install -r requirements.txt

## How to run

    chmod +x HYTTPS.py
    python3 HYTTPS.py

## Overview

**HYTTPS** automates several critical tasks in the penetration testing process, including ↓

    Automatically scans for available Wi-Fi interfaces, ensuring that users can easily identify their network hardware.
    Captures WPA/WPA2 handshakes through targeted deauthentication attacks, allowing for later password recovery attempts.
    brute-force attacks on captured handshakes using well-known wordlists.

## Key Features ↓

    Ensures the script is run with the necessary permissions to perform network operations (ROOT).
    Engages users with clear prompts for enhanced readability and interaction.
    Provides updates during scanning and handshake capture processes, keeping users informed at every step.
    Includes robust mechanisms to retry actions and handle common errors, enhancing overall usability.

## Technical Workflow ↓

    Checks for root privileges and detects available Wi-Fi interfaces.
    Prompts the user to select an interface and choose their operational mode.
    Initiates a network scan to identify available access points.
    Executes a targeted deauthentication attack on a specified network to capture handshakes.
    Utilizes captured handshake files to perform brute-force cracking against a specified wordlist.

## Legal Notice

**I AM NOT RESPONSIBLE HOW YOU USE THIS TOOL. BE LEGAL AND NOT STUPID.**

**HYTTPS** is intended for use on networks you own or have **explicit permission to test**. Unauthorized use is **illegal**, and **users are responsible for their actions**.
