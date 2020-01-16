# The Problem
With the file server, we need a system that has a decent CPU, A good amount of RAM for when the data is being read and a good (modular) power supply that will allow for hard drive expanse. 

# The Systems
There are 2 systems available for use. These are as follows:

## The Old File Server
- I5 360
- 16GB RAM
- 140W PSU

## The Old Edit PC
- I5 3570k
- 16GB RAM
- 600W PSU
- GTX 550

# Comparisons
Both systems will need a form of network card putting in. We are currently looking at direct link of SFP Fiber modules at 10 Gigabit / second. The Old file server only has 1 PCI expansion slot that will accomodate this network card and as such, any additional expansions would be difficult. The old edit PC could have the grapghics card taken out and have a dual port 10Gb/s network card putting in as well as multiple SATA 3 expansion ports. In both PC's there are enough PCI-E slots to accomodate some form of PCI compatible M.2 drive. This would be used as a form of cache whilst files are being edited.

If we kept the graphics card in the old edit PC, this could also be used as a form of render computer for any projects that may take a while. Though this could put uneeded strain on the file server and probably would be done on another PC.

The Old edit PC also has 2x USB 3.0 ports. This would allow us to make a quick ingest system directly on the file server. This is one of the targets of this system.

# Hard Drives
We have 5 old 2TB mechanical drives that can be used in the system. These drives may be a bit old and could be prone to failure soon but they are available now and can ac as an intermediary for the time being.

We currently have no SSD's that could be used to form a cache section of tiered storage. An option is to get roughly 2TB of SSD storage (that should meet the needs of any project). 

We may look at raiding these machines but that is to be decided. Please read [RAID](./Raid.md).

10% of each drive is required to store information about the storage space. As such, as drive sizes expand, we will see more space taken up by this requirement.

# Cases
There are many cases available for use as a file server. The current cases can both support a maximum of 6 3.5" hard drives. An option may be to get a case dedicated to holding drives. Such as a NAS server chassis. This would allow for quick hot swapping of drives that fail and could also provide enough drive space for any additional future drives. The one I was looking at is [this one](https://www.servercase.co.uk/shop/server-cases/rackmount/4u-chassis/4u-server-case-w-24x-35-hot-swappable-satasas-drive-bays-6gbs-minisas-sc-4824/?gclid=EAIaIQobChMIw_PgmaeI5wIVSbTtCh1R1gzVEAQYCyABEgKegvD_BwE). This would provide us with plenty of drive bays to use and could be expanded to eventually auto record all streams. Though a much more powerful system would be required for this.

# Additional Extras
One component that I would really like to add to the file server is a system to quickly backup / copy the files to an external drive. This is as we may need to provide the SU with footage in any legal issues and having this option available would be useful. We could do this from the edit PC's quickly as the 10Gb links would not affect the speeds (unless downloading over USB-C at 40Gb/s).

# Conclusion
We will use the old edit PC for the file server. We will purchase 3x dual SFP 10Gb/s network cards from ebay (or somewhere else that is cheap) and use this as the networking option. For the time being we will not put this onto the universities domain.

We will use the 5x 2TB drives to form the storage (giving us maximum 9TB of storage [as 200GB is taken to store information about the windows storage space]).

Down the road we will purchase some SATA expanders and some SSD's to allow for a form of cache drive. 