# Wazuh_Custom_Rules
A repository to catalogue my custom rules for Wazuh to provide valuable alerts for SOC analysts.

The complete rules file is found [here](/local_rules.xml)


I've also included a [Vega spec for a Sankey Diagram](Visualization-Sankey_Diagram_IP_Flows_vega_spec.json) to map IP Flows which I copied from [here](https://www.elastic.co/blog/sankey-visualization-with-vega-in-kibana).  I found this visualization useful for mapping source and destination IPs logged on my firewall by Suricata and for mapping email subjects tagged as Phishing by Office365 with their intended recipients.  The final result looks something like this and terms are clickable to enable filtering:

<img width="1562" height="850" alt="image" src="https://github.com/user-attachments/assets/510bd493-eb3b-446a-9967-6fa07fe36e73" />


