# Phishing Attack Playbook

## Description

A malicious email campaign designed to steal credentials or deliver malware.

## Indicators

* Suspicious sender address or domain
* Urgent or threatening language
* Unexpected attachments or malicious links
* Reports from users

## MITRE ATT&CK

T1566 – Phishing

## Investigation Steps

1. Analyze email headers for origin and routing
2. Sandbox and analyze attachments/links
3. Identify all recipients of the campaign
4. Check proxy logs for clicks on the malicious link

## Containment

* Remove malicious emails from user inboxes
* Block malicious domains and IP addresses at the firewall
* Disable compromised accounts immediately

## Recovery

* Reset passwords for compromised accounts
* Conduct security awareness training
* Monitor for lateral movement or subsequent attacks
