_The pattern matching swiss knife for malware researchers (and everyone else)_

The proprietary language that Yara uses for rules is fairly trivial to pick up, but hard to master. This is because your rule is only as effective as your understanding of the patterns you want to search for.  
  
Using a Yara rule is simple. Every `yara` command requires two arguments to be valid, these are:  
**1)** The rule file we create  
**2)** Name of file, directory, or process ID to use the rule for.  
  
Every rule must have a name and condition.

![[Pasted image 20230519102704.png]]

#### LOKI

LOKI is a free open-source IOC (_Indicator of Compromise_) scanner 
detection is based on 4 methods:

1.  File Name IOC Check
2.  Yara Rule Check **(we are here)**
3.  Hash Check
4.  C2 Back Connect Check