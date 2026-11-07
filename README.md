<div align="center">

<img src="banner.svg" alt="Anish, self-taught builder of automation and Windows tooling" width="100%"/>

<img src="stack.svg" alt="Skills scrolling past in two lanes: Python, PowerShell, Windows internals, Git, Linux, SQLite, FFmpeg, pywebview, LiteLLM, Claude Code" width="100%"/>

</div>

<img src="hd-flow.svg" alt="Flow" width="100%"/>

A Windows optimizer that checks your hardware first, then only applies tweaks that make sense for your machine. Click the demo to open the repo.

<a href="https://github.com/Anish-132/Flow-Win-Opt"><img src="flow.svg" alt="Live demo of Flow: hardware fingerprint, restore point, a cursor flipping gated tweaks on" width="100%"/></a>

<details>
<summary><b>What Flow actually does</b> (click to open)</summary>

<br>

- Fingerprints CPU, RAM, disk type and GPU before touching anything
- 200+ researched tweaks, gated by OS and hardware
- Restore point first, every change logged and revertible
- Background daemon that runs safe daily cleans and blocks tweaks that keep failing
- Python, PowerShell, pywebview. MIT, no longer maintained: [Anish-132/Flow-Win-Opt](https://github.com/Anish-132/Flow-Win-Opt)

</details>

<img src="stats.svg" alt="Bars morphing from before to after: 2.85 GiB to 475 KB, 1 model to 21 combos, blind tweaks to 200+ gated" width="100%"/>

<img src="hd-how.svg" alt="How I work" width="100%"/>

<details>
<summary><b>Measure first</b></summary>

<br>

Flow fingerprints the hardware before it changes anything. I do the same with bugs: run a probe, read the real output, then fix the cause instead of the symptom.

</details>

<details>
<summary><b>Everything reversible</b></summary>

<br>

Restore point first, every change logged. If I can't undo it, I don't ship it.

</details>

<details>
<summary><b>Agent reports are claims, not evidence</b></summary>

<br>

After an unattended Claude Code session reported its own fixes, I diffed it. Files it called unchanged had changed. I audit before I trust.

</details>

<img src="hd-lab.svg" alt="The lab" width="100%"/>

Two laptops, one cable, no router. The HP is a disposable agent sandbox with key-only SSH and no sudo. Watch the pulse: when the power drops, the HP goes flat, then the ASUS wakes it back up.

<img src="homelab.svg" alt="Live replay of a power cut: HP heartbeat flatlines, ASUS sends a Wake-on-LAN packet, HP comes back" width="100%"/>

<details>
<summary><b>The power-cut sequence, step by step</b></summary>

<br>

1. Mains drops
2. HP shuts down cleanly after a 25 second grace period
3. It leaves a flag file on the ASUS
4. Mains returns
5. The ASUS sends a Wake-on-LAN packet
6. HP boots and the flag clears

</details>

<img src="hd-contact.svg" alt="Contact" width="100%"/>

[![GitHub](https://img.shields.io/badge/GitHub-Anish--132-100d1f?style=for-the-badge&logo=github&logoColor=9d7bff)](https://github.com/Anish-132)
[![Email](https://img.shields.io/badge/Email-YOUR__EMAIL-100d1f?style=for-the-badge&logo=gmail&logoColor=ff4fd8)](mailto:YOUR_EMAIL)
