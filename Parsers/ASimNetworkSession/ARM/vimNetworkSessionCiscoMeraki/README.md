# Cisco Meraki ASIM NetworkSession Normalization Parser

ARM template for ASIM NetworkSession schema parser for Cisco Meraki.

This ASIM parser supports normalizing Cisco Meraki logs ingested in 'meraki_CL' to the ASIM Network Session normalized schema. Cisco Meraki events are generated from network activity and security events from Meraki devices such as firewalls, switches, and access points. These logs are captured through the Cisco Meraki Sentinel connector which uses a Linux agent to collect logs in Syslog format.


The Advanced Security Information Model (ASIM) enables you to use and create source-agnostic content, simplifying your analysis of the data in your Microsoft Sentinel workspace.

For more information, see:

- [Normalization and the Advanced Security Information Model (ASIM)](https://aka.ms/AboutASIM)
- [Deploy all of ASIM](https://aka.ms/DeployASIM)
- [ASIM NetworkSession normalization schema reference](https://aka.ms/ASimNetworkSessionDoc)

<br>

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2FAzure-Sentinel%2Fmaster%2FParsers%2FASimNetworkSession%2FARM%2FvimNetworkSessionCiscoMeraki%2FvimNetworkSessionCiscoMeraki.json) [![Deploy to Azure Gov](https://aka.ms/deploytoazuregovbutton)](https://portal.azure.us/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2FAzure-Sentinel%2Fmaster%2FParsers%2FASimNetworkSession%2FARM%2FvimNetworkSessionCiscoMeraki%2FvimNetworkSessionCiscoMeraki.json)
