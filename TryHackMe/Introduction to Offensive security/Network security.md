#### Intro:
network security refers to the devices, technologies, and processes to protect the confidentiality, integrity, and availability of a computer network and the data on it

#### Methodology:
Cyber Kill Chain:
1) Recon
2)  Weaponization
3) Delivery
4) Exploitation
5) Installation
6) Command & Control (C2)
7) Actions on Objectives

### Practical Example:
- `nmap <ip address>`

`root@AttackBox# nmap 10.10.199.157
`Starting Nmap 7.92 ( https://nmap.org ) at 2022-04-06 17:38 EEST
`Nmap scan report for 10.20.30.130 Host is up (0.00024s latency).
`Not shown: 997 closed tcp ports (reset)
`PORT STATE SERVICE
`21/tcp open ftp
`22/tcp open ssh
`80/tcp open http 
`Nmap done: 1 IP address (1 host up) scanned in 0.33 seconds`

1.  We will connect to the target FTP server by typing on the AttackBox’s terminal `ftp 10.10.199.157`.
2.  Next, we will try to log in using the login `anonymous` to see if this FTP server supports anonymous logins. To our luck, it worked.
3.  We try to see the files available using the command `ls`, short for _list_. We get a list of the filenames along with their details.
4.  If you are curious about any file, you can download it using `get filename`. I wonder what the file `secret.txt` contains, so let’s download it using `get secret.txt`.
5.  Once you download the files, type `exit` or `bye` to quit the FTP client.