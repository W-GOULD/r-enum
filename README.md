# R-ENUM
### RSH Enumeration
### RSH Run Commands
``` rsh <target> <command> ```

### Metasploit RSH Login Scanner
```	auxiliary/scanner/rservices/rsh_login ```

### rusers Show Logged in Users
```	rusers -al 192.168.2.1  ```

### rusers scan whole Subnet
```	rlogin -l <user> <target>
	e.g rlogin -l root TARGET-SUBNET/24
```
### Finger Enumeration
```	finger @TARGET-IP
```
### Finger a Specific Username
```	finger batman@TARGET-IP 
```
### Solaris bug that shows all logged in users:
```	finger 0@host  
```
### SunOS: RPC services allow user enum:
```	$ rusers # users logged onto LAN

	finger 'a b c d e f g h'@sunhost 

	rwho
	Use nmap to identify machines running rwhod (513 UDP)```
