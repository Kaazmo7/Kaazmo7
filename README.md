# Matthew Dudley

Computer Science & Cyber Operations student at Cedarville University.

I build tools I actually end up using for CTFs, CCDC prep, and everyday dev work, plus the occasional web app when I can't find something that already does what I want. Most of what's in here is private and at very different stages of finish.

Flagship projects:
- [NetSentry-IDS](https://github.com/Kaazmo7/netsentry-ids) — Network intrusion detection engine: custom Snort-style signature DSL, four stateful anomaly detectors (port scan, ARP spoofing, DNS tunneling, C2 beaconing), MITRE ATT&CK-tagged alerts, 26 tests
- [ModbusGuard](https://github.com/Kaazmo7/modbusguard) — ICS/OT security toolkit: from-scratch Modbus TCP protocol implementation, an unauthenticated PLC simulator, and an inline detect/prevent security monitor mapped to MITRE ATT&CK for ICS, 30 tests
- [FieldWarden](https://github.com/Kaazmo7/fieldwarden) — Host-based EDR agent for OT/ICS environments, written in Rust: five detectors modeled on real ICS intrusions (TRITON, EKANS, INCONTROLLER) over from-scratch /proc and inotify telemetry, 31 tests

Bigger projects:
- [jarvis](https://github.com/Kaazmo7/jarvis) — (Private) Personal AI agent: agentic tool use, persistent memory, multi-provider LLM support
- [CedarCTF](https://github.com/Kaazmo7/CedarCTF) — (Private) Full-stack CTF competition platform for Cedarville: Django/DRF backend, Next.js frontend, Dockerized
- [claude-bugbounty-setup](https://github.com/Kaazmo7/claude-bugbounty-setup) — (Private) Self-contained Claude Code bug-bounty rig: recon toolchain, custom skills, vendored setup

Smaller / in progress:
- [m4tthew.org](https://github.com/Kaazmo7/m4tthew.org) — (Private) Personal site, Cloudflare Pages + Workers with a D1 database
- [nvidia-free-claude-harness](https://github.com/Kaazmo7/nvidia-free-claude-harness) — (Private) Report and harness for running Claude Code on NVIDIA's free NIM API without the model fabricating results

Toolkit suite — small client-side security tools, five of them built around National Cyber League categories:
- [cidr-calc](https://kaazmo7.github.io/cidr-calc/) — IPv4 subnet & CIDR calculator
- [hashkit](https://kaazmo7.github.io/hashkit/) — Hash digests & encode/decode
- [jwt-inspector](https://kaazmo7.github.io/jwt-inspector/) — Decode & inspect JWTs
- [cipher-toolkit](https://kaazmo7.github.io/cipher-toolkit/) — Caesar, Vigenère, Base64, Morse
- [passphrase-lab](https://kaazmo7.github.io/passphrase-lab/) — Entropy checker & passphrase generator
- [pkt-decoder](https://kaazmo7.github.io/pkt-decoder/) — Ethernet/IPv4/TCP/UDP/ICMP header decoder (NCL network traffic analysis)
- [log-triage](https://kaazmo7.github.io/log-triage/) — Access & auth log triage, brute-force detector (NCL log analysis)
- [exif-scope](https://kaazmo7.github.io/exif-scope/) — JPEG EXIF & GPS metadata viewer (NCL forensics)
- [magic-bytes](https://kaazmo7.github.io/magic-bytes/) — File signature ID & embedded-file scanner (NCL forensics)
- [header-audit](https://kaazmo7.github.io/header-audit/) — HTTP security header & cookie auditor (NCL web app exploitation)

Everything is at [m4tthew.org](https://m4tthew.org)
