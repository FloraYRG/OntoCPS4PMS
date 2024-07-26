# OntoCPSC4PMS
OntoCPSC4PMS is an ontology framework for risk perception and defense control of cyber-physical coordinated threats in power monitoring systems. OntoCPSC4PMS not only references mainstream attack databases like MITRE's CAPEC, NVD, and ATT&CK, promoting the fusion analysis of multi-source heterogeneous cybersecurity data, but also deeply correlates critical information such as physical assets, network systems, vulnerabilities, security mechanisms, and attack patterns specific to power monitoring systems. This enables tracking and defense against cyber-physical coordinated attacks.

The ontology includes the following classes and subclasses:
1) Attacker (e.g. Black hat, attack host )
2) Software 
	i. Tool (e.g. burp, wireshark,snort,sniffer)
       ii. Malware   (e.g. FoggyWeb, Gazer, GrimAgent)
3) Attack Pattern (e.g. Flooding, Excavation, Code Inclusion)
4) PMS (Power Monitoring System)
	i. System   (e.g. Linux Ubuntu 10.4)
	ii. Equipment   (e.g. Circuit breakers, disconnectors, transformers, Human-Machine Interface (HMI))
5) Technique (e.g. Change Credential, Device Restart/Shutdown, System Firmware)
6) Tactic (e.g. Initial Access, Command and Control, Inhibit Response Function)
7) Consequence (e.g. Resource Consumption, Modify Data, Execute Unauthorized Commands)
8) Pitfall 
         i. Weakness   (e.g. Improper Resource Shutdown or Release, Allocation of Resources Without Limits or Throttling)
	ii. Vulnerability   (e.g. Remote Code Execution, SQL Injection, Denial of Service)
9) Solution (e.g. Phases: Implementation; Requirements Ban the use of dangerous functions. Use their safe equivalent.)
10) Mitigation (e.g. Filter Network Traffic, Network Segmentation, Communication Authenticity)
11) Indicator (e.g. IP address, protocol, cookies)
12) Detection (e.g. Operational Databases, Network Traffic, Application Log)

Here are three types of files:

1) OWL file: OWL files are usually based on XML format, supporting complex relationships and rules for describing semantic networks and ontologies. They define data categories (classes), the relationships between them (properties), and the individuals (instances) that can be used within these categories and properties.
2) RDF file: Based on the triple model (subject-predicate-object) to represent data.
3) TXT file: Records the definitions, annotations, or other related explanatory text for classes, properties, and other terms.
