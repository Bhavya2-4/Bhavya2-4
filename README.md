# Hi, I'm Bhavya Mittal

I work on detection engineering and threat hunting. Most of what's here starts the same way: a new attack gets reported, I read the primary sources, work out what the attacker actually had to do, and write detections for that behaviour. Then I try to break them, because a rule that fires on the attack is only half the job. It also has to stay quiet on everything that merely looks like it.

I mostly write for Elastic Security (KQL, EQL, ES|QL) and Microsoft Defender / Sentinel KQL. I map to MITRE ATT&CK, share in STIX 2.1, and use Python and GitHub Actions to test it all.

## Projects

**[optimjack-detection-engineering](https://github.com/Bhavya2-4/optimjack-detection-engineering)**
In November 2026 an attacker used a flaw in Optimizely to inject a card skimmer and crypto-address swapper into the JavaScript that 178+ organisations served to their visitors. None of those companies' own systems were touched, so their usual tools saw nothing. This project works out where the evidence actually was. It covers the attack itself, nine Elastic rules, synthetic test data and a STIX 2.1 export.

**[Threat-hunting-Reports](https://github.com/Bhavya2-4/Threat-hunting-Reports)**
Hunt reports on recent campaigns: OPTIMJACK, Lotus Blossom's Notepad++ update hijack, MuddyWater's Rust implant, macOS ClickFix infostealers, LockBit 5.0, and an LNK/VBS LOLBin campaign.

**[Detection-rules-SOC](https://github.com/Bhavya2-4/Detection-rules-SOC)**
Standalone Elastic rules: ActiveMQ CVE-2023-46604 exploitation leading to LockBit, the GRIDTIDE Linux backdoor, and the OPTIMJACK rule set.
