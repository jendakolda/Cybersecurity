![[Pasted image 20230419104329.png]]

1) Hash Values:
	Various online tools can be used to do hash lookups like [VirusTotal](https://www.virustotal.com/gui/) and [Metadefender Cloud - OPSWAT](https://metadefender.opswat.com/?lang=en).
	PS C:\\Users\\THM\\Downloads> Get-FileHash .\\OpenVPN_2.5.1_I601_amd64.msi -Algorithm MD5
2) IP Address
	From a defense standpoint, knowledge of the IP addresses an adversary uses can be valuable. A common defense tactic is to block, drop, or deny inbound requests from IP addresses on your parameter or external firewall. This tactic is often not bulletproof as it’s trivial for an experienced adversary to recover simply by using a new public IP address.
3) Domain names
	Punycode is a way of converting words that cannot be written in ASCII, into a Unicode ASCII encoding.
	Attackers usually hide the malicious domains under **URL Shorteners**
4) Host Artifacts
	Host artifacts are the traces or observables that attackers leave on the system, such as registry values, suspicious process execution, attack patterns or IOCs (Indicators of Compromise), files dropped by malicious applications, or anything exclusive to the current threat.
	
![[Pasted image 20230420082843.png]]
6) Network Artifacts
7) Tools
	[MalwareBazaar](https://bazaar.abuse.ch/) and [Malshare](https://malshare.com/) are good resources to provide you with access to the samples, malicious feeds, and YARA results - these all can be very helpful when it comes to threat hunting and incident response.
	
	