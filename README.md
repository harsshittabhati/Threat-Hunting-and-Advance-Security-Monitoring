# Threat-Hunting-and-Advance-Security-Monitoring

## Objective

Cyber threats are evolving rapidly, and traditional defenses aren’t enough. I have build a system that not only detects threats but also responds automatically—reducing manual work and improving incident response time.

### Skills Learned

- Advanced understanding of threat detection and SIEM operations using Wazuh and Splunk.
- Proficiency in analyzing and interpreting network and endpoint security logs.
- Expertise in integrating and automating security workflows with LimaCharlie, Tines, and Slack.
- Strong knowledge of IDS/IPS mechanisms, network protocols, and security vulnerabilities.
- Hands-on experience in cloud security monitoring and incident response in Azure.

### Tools Used

- Wazuh – SIEM and endpoint detection for log analysis, threat monitoring, and security event correlation.
- Suricata – IDS/IPS for deep packet inspection, network traffic analysis, and real-time threat detection.
- LimaCharlie – Centralized threat detection and response, including automated device isolation.
- Splunk – Log management, security analytics, and event correlation for advanced threat detection.
- Tines – Security automation for orchestrating threat response workflows and alerting.
- Slack – Integrated for real-time security notifications and team collaboration.
- Iris – Digital forensics and incident response tool for threat intelligence and investigation.
- Azure – Cloud platform for hosting and managing security monitoring infrastructure.

## Steps
*Ref 1: Wazuh dashboard*
![Screenshot (71)](https://github.com/user-attachments/assets/72295e0e-60d2-4304-8ee3-029efacadf69)

*Ref 2: Wazuh-agents on different endpoints*
![Screenshot (71)](https://github.com/user-attachments/assets/b6234fc3-8f41-4ad4-b0bb-93ce5e6fb3b6)

*Ref 3: log rotation in suricata*
![Screenshot (71)](https://github.com/user-attachments/assets/77fab466-df74-44e6-b527-57db60c18536)

*Ref 4: Wazuh Alerts in Iris*
![Screenshot (71)](https://github.com/user-attachments/assets/e637f027-d3c0-4b56-9b8d-4faa4aae64fa)

*Ref 5: Splunk integration with Wazuh*
![Screenshot (71)](https://github.com/user-attachments/assets/5978a685-7f5d-4b84-bd46-0d316044c5cc)

*Ref 6: LimaCharlie deployed on Windows Server and Ubuntu systems*
![Screenshot (71)](https://github.com/user-attachments/assets/51f6fa42-3c35-4fb1-8f1c-210a60a46917)

*Ref 7: Tines workflow*
![Screenshot (71)](https://github.com/user-attachments/assets/f948a414-d6d4-443e-b436-63e1e6f790c8)

*Ref 8: Tines alert in slack*
![Screenshot (71)](https://github.com/user-attachments/assets/3e369bdd-5691-444b-ae85-6fc77a423bf3)

*Ref 9: Wazuh-alerts in slack which also shows the severity level*
![Screenshot (71)](https://github.com/user-attachments/assets/56017b64-4705-4d32-88be-679056597437)

*Ref 10: Anomaly  Detector in Wazuh*
![Screenshot (71)](https://github.com/user-attachments/assets/fb6e503f-a2f3-4e9a-bca8-a35f4ddeb3a0)

*Ref 11: alert and notification channel of Slack in Wazuh*
![Screenshot (71)](https://github.com/user-attachments/assets/c1004491-4cdc-4a10-b63e-52806b5aa45d)

## Resources

- __Wazuh Installation and Integration__: Official Wazuh Documentation: https://documentation.wazuh.com/  
__Guide__: Installing Wazuh on Ubuntu with Elasticsearch and Kibana.  
__Script__: wazuh-installation-script.sh from the Wazuh repository.
- __Suricata Setup__: Suricata Documentation: https://suricata.io/docs/  
Configuration Guide for Suricata with Azure traffic.  
__Rules__: Emerging Threats Open Ruleset.
- __Elasticsearch and Kibana__: Elasticsearch Installation Guide: https://www.elastic.co/guide/en/elasticsearch/reference/current/install-elasticsearch.html
- __LimaCharlie__: Developer Documentation: https://limacharlie.io/docs/  
__API Examples__: Fetching telemetry from Azure.
- __Splunk__: Splunk Installation Manual: https://docs.splunk.com/Documentation/Splunk/latest/Installation/InstallonLinux  
__Guide__: Configuring inputs for Wazuh, Suricata, and LimaCharlie logs.  
- __Slack Integration__: Slack API Documentation: https://api.slack.com/  
__Incoming Webhooks Guide__: https://api.slack.com/messaging/webhooks  
- __Tines Workflow Automation__:Tines Documentation: https://tines.com/docs/  
Templates for Incident Automation.   
- __Azure Specific Guides__: Azure Networking Fundamentals: https://learn.microsoft.com/en-us/azure/networking/
