# Server Info
- **IP:** 138.2.137.178
- **RustDesk Public Key:** NkhBuhnirkBxeidDNyLU5MVo955yyq51K8x3LHTipPk=
- **Region:** eu-frankfurt-1
- **OS:** Ubuntu 20.04
- **CPU-Cores:** 1
- **Memory:** 1GB
- **Network bandwidth (Gbps):** 0.48
- **TCP-Ports:** 8000, 21114-21119
- **UDP-Ports:** 21116

# How to setup RustDesk Client
## Automatic install via Script (Recommended)
Go to http://138.2.137.178:8000 in your browser.

Enter `username` and `passwort`. (Sent seperately)
### Linux
1. Download `linuxclientinstall.sh`. 
2. Open the Terminal
3. Go to the directory where `linuxclientinstall.sh` is.
4. Execute `./linuxclientinstall.sh`
5. Write down the displayed `RustDesk ID` & `Password`.
It should look similar to this:
```
...............................................
RustDesk ID: 235888796
Password: AzWNHPEyXUrZ
...............................................
```

**INSTALL & NETWORK CONFIG DONE. --> SEE Enable unattended Access**


### Windows
1. Download `WindowsAgentAIOInstall.ps1`. 
2. Open PowerShell as Administrator
3. Go to the directory where `WindowsAgentAIOInstall.ps1` is.
4. Execute `Set-ExecutionPolicy -ExecutionPolicy Unrestricted -Scope Process`. (This temporarely allows the execution of all PowerShelll Scripts, until the Session is closed)
5. Execute `./WindowsAgentAIOInstall.ps1`
6. Write down the displayed `RustDesk ID` & `Password`.
It should look similar to this:
```
...............................................
RustDesk ID: 235888796
Password: AzWNHPEyXUrZ
...............................................
```

**INSTALL & NETWORK CONFIG DONE. --> SEE Enable unattended Access**

## Manual innstall 
1. Go to the official RustDesk [github](https://github.com/rustdesk/rustdesk/releases). 
2. Select the latest stable release. (1.3.7, as of 2025-02-21)

### Windows install
1. Download `rustdesk-1.3.7-x86_64.msi` or ` rustdesk-1.3.7-x86_64.exe `
### Linux install
Depends on version:
- Debian (Ubuntu): ` rustdesk-1.3.7-x86_64.deb`
- RPM (RedHat, CentOS): `rustdesk-1.3.7-0.x86_64.rpm`

## Network Configuration
1. Select 3 Small dots nex to **ID**
2. Network
3. ID/Relay-Server:
- ID-Server: `138.2.137.178`
- Relay-Server: `138.2.137.178`
- API-Server: `https://138.2.137.178`
- Key: `NkhBuhnirkBxeidDNyLU5MVo955yyq51K8x3LHTipPk=`

## Enable unattended Access
1. Select 3 Small dots nex to **ID**
2. Password -> Confirm Session with Password
3. Set Permanent Password