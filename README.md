# azure-vm-game-server-lab
Repository focused on deploying, configuring, and troubleshooting an Azure Windows Server VM for Assetto Corsa hosting.

# Objective
Deploy a Windows Server VM in Azure to host an Assetto Corsa server.

## Technologies
- Azure Virtual Machine (VM)
- Network Security Group (NSG)
- Public IP
- Windows Firewall
- Port Forwarding

## Problem
Game clients were unable to connect to the server.

## Troubleshooting
- Validated required ports using `Test-NetConnection`
- Adjusted inbound NSG rules
- Corrected local Windows Firewall rules

## Result
Successfully deployed a functional game server with client connectivity working.
