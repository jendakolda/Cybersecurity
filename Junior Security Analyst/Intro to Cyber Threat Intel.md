Cyber Threat Intelligence (CTI) can be defined as evidence-based knowledge about adversaries, including their indicators, tactics, motivations, and actionable advice against them. These can be utilised to protect critical assets and inform cybersecurity teams and management business decisions.

**Data:** Discrete indicators associated with an adversary such as IP addresses, URLs or hashes.

**Information:** A combination of multiple data points that answer questions such as “How many times have employees accessed tryhackme.com within the month?”

**Intelligence:** The correlation of data and information to extract patterns of actions based on contextual analysis.


-   Who’s attacking you?
-   What are their motivations?
-   What are their capabilities?
-   What artefacts and indicators of compromise (IOCs) should you look out for?

-   **Strategic Intel:** High-level intel that looks into the organisation’s threat landscape and maps out the risk areas based on trends, patterns and emerging threats that may impact business decisions.
    
-   **Technical Intel:** Looks into evidence and artefacts of attack used by an adversary. Incident Response teams can use this intel to create a baseline attack surface to analyse and develop defence mechanisms.
    
-   **Tactical Intel:** Assesses adversaries’ tactics, techniques, and procedures (TTPs). This intel can strengthen security controls and address vulnerabilities through real-time investigations.
    
-   **Operational Intel:** Looks into an adversary’s specific motives and intent to perform an attack. Security teams may use this intel to understand the critical assets available in the organisation (people, processes and technologies) that may be targeted.

![[Pasted image 20230509125214.png]]
-   [Threat Intelligence Tools](https://tryhackme.com/room/threatinteltools)
-   [YARA](https://tryhackme.com/room/yara)
-   [OpenCTI](https://tryhackme.com/room/opencti)
-   [MISP](https://tryhackme.com/room/misp)

### TAXII

[The Trusted Automated eXchange of Indicator Information (TAXII)](https://oasis-open.github.io/cti-documentation/taxii/intro) defines protocols for securely exchanging threat intel to have near real-time detection, prevention and mitigation of threats. The protocol supports two sharing models:

-   Collection: Threat intel is collected and hosted by a producer upon request by users using a request-response model.
-   Channel: Threat intel is pushed to users from a central server through a publish-subscribe model.

### STIX

[Structured Threat Information Expression (STIX)](https://oasis-open.github.io/cti-documentation/stix/intro) is a language developed for the "specification, capture, characterisation and communication of standardised cyber threat information". It provides defined relationships between sets of threat info such as observables, indicators, adversary TTPs, attack campaigns, and more.

### The Diamond Model

The diamond model looks at intrusion analysis and tracking attack groups over time. It focuses on four key areas, each representing a different point on the diamond. These are:![Image showing a possible phishing attack through the Diamond Model.](https://tryhackme-images.s3.amazonaws.com/user-uploads/5fc2847e1bbebc03aa89fbf2/room-content/e0d32b7a17c0b4326e596ae5fd9fb47e.png)

  

-   Adversary: The focus here is on the threat actor behind an attack and allows analysts to identify the motive behind the attack.
-   Victim: The opposite end of adversary looks at an individual, group or organisation affected by an attack.
-   Infrastructure: The adversaries' tools, systems, and software to conduct their attack are the main focus. Additionally, the victim's systems would be crucial to providing information about the compromise.
-   Capabilities: The focus here is on the adversary's approach to reaching its goal. This looks at the means of exploitation and the TTPs implemented across the attack timeline.