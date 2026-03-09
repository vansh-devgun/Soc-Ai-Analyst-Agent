# Brute Force Attack Playbook

## Description

Multiple authentication attempts indicating a brute force attack.

## Indicators

* Multiple failed logins
* Repeated login attempts from same IP
* Account lockouts

## MITRE ATT&CK

T1110 – Brute Force

## Investigation Steps

1. Check authentication logs
2. Identify attacking IP
3. Determine targeted accounts

## Containment

* Block malicious IP
* Lock affected accounts
* Enable MFA

## Recovery

* Reset passwords
* Monitor further login attempts
