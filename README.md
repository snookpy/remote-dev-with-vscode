# remote-dev-with-vscode (with SSH)
Prevent my machine hanging, share process to other maching via SSH remote.
open MyCos session

![image](./architecture.png)

ref: https://code.visualstudio.com/docs/remote/remote-overview

## Objective
  - able to remote dev from macos which use window for complie and codebase.

## Limitation
  - Cannot remote visual studio expecelly, old version 2013, 2017, 2019
  - Cannot ssh to AzureAD local login (maybe can but not deep research yet)
  - 

## Table of Contents


## Pre Installlation
we need theses tools
### Client Side
1. [Visual Studio Code](https://code.visualstudio.com)
2. [Remote Devlopment Extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.vscode-remote-extensionpack)
3. Open SSH Client
   - Macos -> Already had from OS
   - Window -> Install the [Windows OpenSSH Client](https://learn.microsoft.com/en-us/windows-server/administration/openssh/openssh_install_firstuse?tabs=gui)

### Server Side
1. Windows - Install the [Windows OpenSSH Server](https://learn.microsoft.com/en-us/windows-server/administration/openssh/openssh_install_firstuse?tabs=gui)
2. Macos - [Enable Remote](https://support.apple.com/guide/mac-help/allow-a-remote-computer-to-access-your-mac-mchlp1066/mac)


## What is SSH?
SSH aka Secure Shell, is a cryptographic network protocol used for secure communication between a client and a server over an unsecured network.

working on Port 22
- access to remote via cli
- transfer file between them
- etc.

## Public Key Authentication
  
