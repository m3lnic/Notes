# Options
1. Windows 10
2. Windows Server 2016
3. Windows Server 2019
4. Linux
5. FreeNAS

# Breakdowns
## Windows 10
Pros:
- Many people use this operating system
- Quick and easy to setup
- Storage spaces will work across any windows 10 machine
    - If the machine fails, can quickly build a replacement and just hot-swap in the drives
- Point and click
- Free licenses from the university
- Can be setup to work with university groups (so only LA1TV-Members can use)
- Interfaces nicely with Luna

Cons:
- Setting up tiered storage spaces requires using powershell
    - Not everyone may understand how to fix this
    - Time consuming
- Software raid can be clunky
    - Look into hardware raid? [More info here](./raid.md)
- Heavy overhead for operating system

## Windows Server 2016/19
Pros:
- Graphical interface for all stages of setting up storage spaces
    - Tiered storage easy to do
- Free licenses from the university
- Only install components that you need

Cons:
- Storage spaces don't seem to walk seemlessly across installations
    - Tested across 2 different desktops
- Can be somewhat complicated to setup (if you don't know what you are doing)
    - Going for simple and easy to fix

Cons (2016):
- Security patches may stop sooner than 19

## Linux
Pros:
- Runs very lightly

Cons:
- Requires understanding of linux CLI to use effectively
- Logins may become complex over time
- Doesn't interface nicely with AD
    - Can't use uni logins to access (not a major issue)
- Many options for creating NAS / File shares
    - Difficult to find which ones are the best

## FreeNAS
Pros:
- OS made for NAS
- Runs extremely lightly
- Can import disks from any installations
- Runs off of a USB
- Web client

Cons:
- Web client ONLY configuration
- Uni will question the ports and the security of them if the machine is connected to resnet