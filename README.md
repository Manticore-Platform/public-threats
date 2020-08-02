# public-threats
Manticore's Public Threats Repository

# Ransomware Emulation

[ransomware.json](https://github.com/Manticore-Platform/public-threats/blob/master/ransomware/ransomware.json)

| Scenario        | Description           | Link  |
| ------------- |:-------------:| -----:|
| im-001.json      | Go Multiplatform Ransomware Emulation | [im-001.json](https://github.com/Manticore-Platform/public-scenarios/blob/master/impact/im-001.json) |
| im-002.json      | Powershell Ransomware Emulation      |   [im-002.json](https://github.com/Manticore-Platform/public-scenarios/blob/master/impact/im-002.json) |

# Lolbins Emulation For Downloading File

[lolbins.json](https://github.com/Manticore-Platform/public-threats/blob/master/lolbins/lolbins.json)

| Scenario        | Description           | Link  |
| ------------- |:-------------:| -----:|
| cc-001.json      | Use Certutil.exe to download a file from a remote server | [cc-001.json](https://github.com/Manticore-Platform/public-scenarios/blob/master/commandandcontrol/cc-001.json) |
| cc-002.json      | Use Bitsadmin.exe to download a file from a remote server      |   [cc-002.json](https://github.com/Manticore-Platform/public-scenarios/blob/master/commandandcontrol/cc-002.json) |

# APT-29 Emulation

[apt-29.json](https://github.com/Manticore-Platform/public-threats/blob/master/apt-29/apt-29.json)

| Scenario        | Description           | Link  |
| ------------- |:-------------:| -----:|
| cn-001.json      | Native API call(s) were used to collect a screenshot. | [cn-001.json](https://github.com/Manticore-Platform/public-scenarios/blob/master/collection/cn-001.json) |
| cn-002.json      | Execute PowerShell from cmd.exe to collect and compress files of specific extensions. | [cn-002.json](https://github.com/Manticore-Platform/public-scenarios/blob/master/collection/cn-002.json) |
| cn-003.json      | Load custom PowerShell module and take screenshots. | [cn-003.json](https://github.com/Manticore-Platform/public-scenarios/blob/master/collection/cn-003.json) |
| cn-004.json      | Perform e-mail collection from custom PowerShell module. | [cn-004.json](https://github.com/Manticore-Platform/public-scenarios/blob/master/collection/cn-004.json) |
| cn-005.json      | Get contents of clipboard. | [cn-005.json](https://github.com/Manticore-Platform/public-scenarios/blob/master/collection/cn-005.json) |
| ca-001.json      | Download Mimikatz Binary | [ca-001.json](https://github.com/Manticore-Platform/public-scenarios/blob/master/credential-access/ca-001.json) |
| ca-002.json      | Dumping credentials via wmidump (Mimikatz) | [cn-002.json](https://github.com/Manticore-Platform/public-scenarios/blob/master/credential-access/ca-002.json) |
| ca-003.json      | Mimikatz lsadump::sam is executed via Invoke-Mimikatz to dump hashes via process injection into LSASS. | [ca-003.json](https://github.com/Manticore-Platform/public-scenarios/blob/master/credential-access/ca-003.json) |
| de-001.json      | Invoke UAC bypass sdctl | [de-001.json](https://github.com/Manticore-Platform/public-scenarios/blob/master/defense-evasion/de-001.json) |
| de-002.json      | Timestomp kxwn.lock | [de-002.json](https://github.com/Manticore-Platform/public-scenarios/blob/master/defense-evasion/de-002.json) |
| de-003.json      | Delete registry entries post-UAC Bypass | [de-003.json](https://github.com/Manticore-Platform/public-scenarios/blob/master/defense-evasion/de-003.json) |
| dv-001.json      | Triage host for information | [dv-001.json](https://github.com/Manticore-Platform/public-scenarios/blob/master/discovery/dv-001.json) |
| dv-002.json      | The net utility is executed via cmd to enumerate hosts within the domain. | [dv-002.json](https://github.com/Manticore-Platform/public-scenarios/blob/master/discovery/dv-002.json) |
| dv-003.json      | Delete registry entries post-UAC Bypass | [dv-003.json](https://github.com/Manticore-Platform/public-scenarios/blob/master/discovery/dv-003.json) |
| dv-004.json      | Get domain controller and curret user SID for the domain | [dv-004.json](https://github.com/Manticore-Platform/public-scenarios/blob/master/discovery/dv-004.json) |
