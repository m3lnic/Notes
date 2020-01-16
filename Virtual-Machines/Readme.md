LA1TV has many Virtual Machines that have to be updated and maintained. This includes:
- Security patches
- Checking for software updates
- Checking you are still using the most secure HTTP headers
- That no data leaks or breaches have ocurred
    > Yes, this has happened. 2019, LA1TV-Comms VM was breached. The person who breached it informed us that it was breachable and the VM was taken down. Please make sure to read the universities documentation on virtual machines if you are doing this.
- Complying with any password updates

Please use the LA1TV Service Account (can be found in the lastpass) to do any management of these machines. There are currently 2 VM's that are not accessible via this account; LA1TV-WWW and LA1TV-Dev. All other VM's are windows based and are on the universities domain. 

There are plans to get the linux machines rebuilt down the road but that is for another year yet.

All LA1TV Virtual Machines are prefixed with LA1TV.

Please contact ISS with evidence you are the technical manager (LA1TV-Admins group in Active Directory) to gain access to the VSphere to quickly and easily manage the servers. VMWare licenses can be obtained through [Lancaster Elms](http://lancs-elms.lancs.ac.uk/).

# Current Virtual Machines
These are the current virtual machines available to LA1TV:
- [Wowza](./Wowza/Readme.md)
- [WWW](./WWW/Readme.md)
- [Dev](./Dev/Readme.md)
- [Comms](./Comms/Readme.md)