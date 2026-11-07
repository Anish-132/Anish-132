<div align="center">

<img src="banner.svg" alt="Anish, self-taught builder of automation and Windows tooling" width="100%"/>

<img src="stack.svg" alt="Python, PowerShell, Windows internals, Git, Linux, SQLite, FFmpeg, pywebview, LiteLLM, Claude Code" width="100%"/>

</div>

## Flow

A Windows optimizer that checks your hardware first, then only applies tweaks that make sense for your machine. Restore point before anything changes, every change logged and revertible.

<img src="flow.svg" alt="Animated mock of Flow auditing hardware, creating a restore point and applying gated tweaks" width="100%"/>

`Python` `PowerShell` `pywebview` · [Anish-132/Flow-Win-Opt](https://github.com/Anish-132/Flow-Win-Opt) · MIT, no longer maintained

<img src="stats.svg" alt="2.85 GiB history down to 475 KB, 1 model to 21 combos, 200+ hardware-gated tweaks" width="100%"/>

## How I work

- **Measure first.** Flow fingerprints CPU, RAM, disk and GPU before it touches anything. I do the same with bugs: probe, then fix the cause.
- **Everything reversible.** Restore point first, every change logged. If I can't undo it, I don't ship it.
- **Agent reports are claims, not evidence.** After an unattended Claude Code session reported its own fixes, I diffed it. Some files it called unchanged had changed. I audit before I trust.

## The lab

Two laptops, one cable, no router. The HP is a disposable agent sandbox with key-only SSH and no sudo. When the power drops it shuts down cleanly, and the ASUS wakes it when power returns.

<img src="homelab.svg" alt="ASUS and HP laptops linked by one cable, replaying a power cut and Wake-on-LAN recovery" width="100%"/>

## Contact

[![GitHub](https://img.shields.io/badge/GitHub-Anish--132-100d1f?style=flat-square&logo=github&logoColor=9d7bff)](https://github.com/Anish-132)
[![Email](https://img.shields.io/badge/Email-YOUR__EMAIL-100d1f?style=flat-square&logo=gmail&logoColor=ff4fd8)](mailto:YOUR_EMAIL)
