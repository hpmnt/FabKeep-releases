# Security Policy

Thank you for helping keep FabKeep and its users safe. If you believe you have found a security vulnerability in FabKeep, please report it privately as described below. **Please do not open a public issue, discussion or pull request for security problems.**

## Supported versions

FabKeep is in open beta and updates itself automatically. Security fixes are made in the **latest release** only, so please check that the problem still exists in the newest version on the [Releases page](../../releases) before reporting.

| Version | Supported |
| --- | --- |
| Latest release | ✅ |
| Older releases | ❌ (update to the latest release) |

## How to report a vulnerability

Use either of these private channels:

1. **GitHub (preferred):** open the **Security** tab of this repository and click **Report a vulnerability**. Only the maintainers can see the report.
2. **Email:** write to **fabkeepai@gmail.com** with the subject line `Security: <short description>`.

Please include as much of the following as you can:

- the FabKeep version (shown in Settings › About & licenses) and your Windows version
- what kind of problem it is (for example: running code from a crafted file, reading or leaking files or stored keys, a problem with the update process)
- step-by-step instructions to reproduce it, and a sample file if one is needed (please zip it and say what it contains)
- what an attacker could achieve, and anything you know about how to fix it

Please do **not** include real passwords, API keys or other people's personal data in a report.

## What happens next

- We aim to confirm that we received your report within **3 business days**.
- We will investigate, keep you updated on our progress, and may ask you for more details.
- Once a fix is ready, it is published as a new release. FabKeep installs it automatically for users who have automatic updates switched on.
- With your permission, we will thank you by name in the release notes. If you would rather stay anonymous, just say so.

Please give us a reasonable amount of time to fix the problem before you share details publicly. We will agree on a disclosure date with you; normally that is no later than **90 days** after your report.

## Scope

**In scope:** the FabKeep desktop app and its installer and updater as published on this repository's Releases page.

**Out of scope:**

- Problems in other programs FabKeep opens files in (Bambu Studio, OrcaSlicer, LightBurn, Cricut Design Space, Fusion 360 …), or in AI services and servers you connect to (LM Studio, Ollama, Claude, ChatGPT). Please report those to their makers. If FabKeep itself uses them in an unsafe way, that **is** in scope.
- Attacks that need someone who already controls your Windows account or has administrator access to the PC.
- Social engineering, physical access, denial-of-service and spam.
- Reports from automated scanners without a demonstrated, working problem.

## Safe harbor

We will not take legal action against anyone who acts in good faith under this policy, which means:

- testing only on your own computer and your own files
- not accessing, changing or deleting other people's data
- reporting the problem privately and giving us time to fix it before going public

FabKeep is free software and does not offer a paid bug bounty.

