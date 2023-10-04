# They're Digging in the Wrong Place
## Identifying and dealing with one-sided network traffic
* 'duplex' indicates bidirectional traffic packet capture
* 'tx' indicates transmit only capture at client switch port
* 'rx' indicates receive only capture at client switch port

## Packet Captures
* dig-curl-*-securityonion.com.pcapng - curl https://www.securityonion.com
* dig-dns*seconionsolutions.pcapng - dig securityonionsolutions.com
* dig-*-mix.pcapng - mixed network traffic short timespan
* dig-http*plink.pcapng - wget http://voxpop.freeshell.org/plink.exe
* dig-rdp*-10.1.1.36.pcapng - rdp to host 10.1.1.36
* dig-smb-*-10.1.1.36.pcapng - smb file transfer from 10.1.1.36
