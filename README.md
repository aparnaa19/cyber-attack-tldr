# Cyber Attack TL;DR

Short, plain-language breakdowns of recent cyberattacks, focused on incidents that reach ordinary users' devices and accounts. Each entry explains what happened, how the attack worked and what people should do, with diagrams of the key steps. They are written so that readers without a security background can follow them.

## Index

| Date | Incident | Summary |
|---|---|---|
| 16 Nov 2026 | [Optimizely supply-chain attack](attacks/2026-11-optimizely-supply-chain/README.md) | Malicious JavaScript served to visitors of 178+ major websites through a compromised A/B testing service. It swapped crypto addresses, skimmed cards and targeted older iPhones. |
| 29 Oct 2026 | [Binance hot wallet theft](attacks/2026-10-binance-hot-wallet-theft/README.md) | About $6.3 billion stolen, the largest crypto theft on record. It began with malware on engineers' laptops, including one infected through a fake job interview. |
| 1 Sep 2026 | [IDScan driver's license breach](attacks/2026-09-idscan-drivers-licenses/README.md) | More than 153 million scanned US and Canadian driver's licenses, taken from an ID-verification company used by bars and stores, sold on a criminal marketplace. |
| Jun 2026 | [Instagram takeovers via Meta AI](attacks/2026-06-instagram-meta-ai-takeovers/README.md) | Attackers asked Meta's AI support assistant to link their email to other people's accounts, then reset the passwords. 20,225 accounts taken over. |
| May 2026 | [Canvas breach](attacks/2026-05-canvas-instructure-breach/README.md) | ShinyHunters stole student data from the Canvas learning platform, then replaced about 330 school login pages with ransom notes during finals. |
| Apr 2026 | [Adobe Reader zero-day](attacks/2026-04-adobe-reader-zero-day/README.md) | Malicious PDFs exploited an unknown Acrobat flaw for months. Opening the file was enough to run the attacker's code. |
| Mar to May 2026 | [TeamPCP supply-chain campaign](attacks/2026-03-teampcp-supply-chain/README.md) | Poisoned developer tools (Trivy, Checkmarx, LiteLLM, Bitwarden CLI) stole secrets, and each theft was used to poison the next tool. |
| 11 Mar 2026 | [Stryker device wipe](attacks/2026-03-stryker-intune-wipe/README.md) | A hijacked Microsoft Intune admin account was used to factory reset tens of thousands of company laptops and phones. No malware involved. |
| Mar 2026 | [DarkSword iPhone exploit kit](attacks/2026-03-darksword-iphone-exploit-kit/README.md) | Visiting a hacked website in Safari was enough to take over iPhones on iOS 18 and steal passwords, messages and crypto wallets. |
| 2026, ongoing | [ClickFix fake CAPTCHAs](attacks/2026-03-clickfix-fake-captcha/README.md) | Fake "verify you are human" boxes trick Windows users into pasting a command that installs password-stealing malware. |
| Jan 2026 | [149 million stolen logins exposed](attacks/2026-01-149m-infostealer-credentials/README.md) | An open database held 149 million logins for Gmail, Facebook, Netflix and more, collected by malware on people's own devices. |

## Format

Each write-up covers:

- A short summary of the incident
- A plain-language explanation of what happened
- Diagrams of the attack flow
- A timeline
- Recommendations for users and for organizations
- A glossary of technical terms
- Indicators of compromise
- Sources, with any conflicts between reports noted

## Notes

Information reflects public reporting at the time each entry was written and may change as investigations continue. Indicators of compromise are defanged. This repository is for education and awareness.
