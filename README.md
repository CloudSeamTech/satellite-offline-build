# Disconnected Satellite 6.19 on RHEL 9.8 — Offline Build Guide

A hand-held, plain-English guide to building a **Red Hat Satellite 6.19** server on **RHEL 9.8** in an air-gapped (disconnected) environment, hardened with the **DISA STIG** profile and running in **FIPS** mode.

**Live site:** https://cloudseamtech.github.io/satellite-offline-build/

## What's inside
- **Build Guide** — 11 stages from an empty vSphere VM to a working Satellite, with a checklist, "what each piece means" for every command and flag, expected output, and if/then fixes.
- **Flags 101** — when to use `-x` vs `--word`, with short and long examples for every flag used.
- **Troubleshooting** — searchable fixes for issues met during real builds (faillock lockouts, port 9091, SELinux, firewall, DNS, GPG, Kerberos, DoD certificates, and more).
- **Lab vs. production certificates** — internal CA vs. an official DoD PKI certificate.

## Notes
- All hostnames and IPs are fake lab values. Type your own into the form in Step 0; they are saved only in your browser and never leave it.
- This is a single self-contained `index.html` — no build step.
- Not an official Red Hat or DISA document. Always follow your organization's approved procedures and your ISSO's guidance.
