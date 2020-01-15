# The Problem
There are many ways to store data on hard drives and many ways to improve redundancy or decrease the losses of a drive / OS failure. In storing video footage on a hard drive, we want to ensure a form of redundancy in case of failures.

# Raid
Pros:
- If a drive fails, data can be rebuilt
- Many different variations to add failsafes to the data
- Improves performance of the hard drives
    - For editing 4k footage from a NAS we are looking at around 1GB/s of data transfer between editing machines and the NAS to edit with no performance loss

Cons:
- Adds a level of complexity to the file server
- Rebuilding data takes time
- There should be no need if we backup to LUNA
    - What happens if LUNA is down for a period of time?
- Reduces total storage size

# Software Raid vs Hardware Raid
## Software:
Pros: 
- Quick and easy to setup
- Comes with the OS typically

Cons:
- Will only work with the OS that it has been software raided on
- Difficult to get data back if a write fails
- Uses CPU to calculate data locations

## Hardware
Pros:
- Much faster speeds
- All in one that does the SATA connections and the RAIDing
    - Processes where the data is going itself without using the CPU
- Easy to resetup and replace a failed module

Cons:
- Requires setup in BIOS
- Expensive ($$$)
- Requires PCI-E slots typically