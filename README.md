# Shadow Trace - TryHackMe Walkthrough

This repository contains my walkthrough for the TryHackMe room **Shadow Trace**.

The room focuses on analysing a suspicious Windows binary, extracting indicators of compromise, and correlating alerts to identify malicious activity. The investigation included reviewing PE metadata, collecting hashes, extracting embedded URLs and domains, decoding obfuscated values, and analysing alerts triggered by PowerShell and Chrome.

## Walkthrough PDF

[Download the full walkthrough PDF](./shadow-trace.pdf)

## Topics Covered

- Static malware analysis
- PE file analysis
- SHA-256 hash extraction
- IOC extraction
- URL and domain analysis
- Base64 decoding
- JavaScript character-code decoding
- Alert correlation
- SOC triage

## Tools Used

- PEStudio
- strings.exe
- CyberChef
- Shadow Trace alert dashboard

## Summary

During this investigation, I analysed `windows-update.exe` and identified suspicious indicators such as embedded URLs, domains, encoded data, and network-related imports. I then reviewed related alerts to decode malicious URLs and understand how the suspicious activity was triggered.
