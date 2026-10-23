# Security Policy

## Supported Versions

Only the latest mod release receives security updates. Older versions are unsupported.

| Version | Supported          | Notes                          |
|---------|--------------------|--------------------------------|
| 1.0.x   | ✅ Yes             | Current stable release         |
| < 1.0   | ❌ No              | Pre-release / internal builds  |

---

## Reporting a Vulnerability

If you discover a security issue in **Scam with ur Friends 100 Players Mod**, please report it privately. **Do not open a public GitHub issue** for security-related matters.

| Contact Method | Details |
|----------------|---------|
| **Email**      | `cloudstarglide@users.noreply.github.com` (replace with your actual contact if available) |
| **GitHub**     | Use [Private vulnerability reporting](https://github.com/cloudstarglide/scam-with-ur-friends-100-players-mod/security/advisories/new) if enabled |
| **Response time** | Within 72 hours |

Please include:

- A clear description of the issue
- Steps to reproduce
- Affected version(s)
- Any proof-of-concept code or screenshots (if applicable)

You will receive an acknowledgment within 72 hours. If the issue is confirmed, a patch will be released as soon as possible, and you will be credited (unless you prefer to remain anonymous).

---

## Scope

This policy covers:

- The mod executable `ScamWithFriends100PlayersMod.exe`
- The distributed archive `ScamWithFriends100PlayersMod_v1.0.zip`
- Any scripts or configuration files shipped with the mod

**Out of scope:**

- Vulnerabilities in the base game *Scam with ur Friends* (report those to the original developer)
- Steam client or platform issues
- Social engineering attacks
- Denial-of-service attacks against GitHub Pages or GitHub itself

---

## Archive Password & Integrity

The archive is protected by the password **`8025381933`**. This password is **public** and is **not** a security control — it is used only for packaging and to prevent automatic scanning/crawling. Do not treat it as a secret.

### Verifying the Download

Always verify the integrity of the downloaded archive before running the executable.

| File | SHA-256 Checksum |
|------|------------------|
| `ScamWithFriends100PlayersMod_v1.0.zip` | `PLACEHOLDER_SHA256_HASH` |

> Replace `PLACEHOLDER_SHA256_HASH` with the actual checksum once the archive is finalized:
> ```bash
> sha256sum ScamWithFriends100PlayersMod_v1.0.zip
> ```
> Publish the hash in this file and in the `README.md`.

### Verifying the Password

The archive password is intentionally published in:

- This `SECURITY.md`
- `README.md`
- The GitHub Pages landing page (`index.html`)
- The repository description

If you obtain the archive from a third party with a different password, **do not trust it**.

---

## Antivirus & False Positives

Modded executables are frequently flagged by antivirus engines as false positives (e.g., `HEUR:Trojan.Win32.Generic`, `Wacatac.B!ml`). This is common for unsigned, modified binaries.

| Symptom | Recommended Action |
|---------|-------------------|
| Windows Defender flags the `.exe` | Add an exclusion **only** if you downloaded from the official GitHub repository or GitHub Pages |
| Browser blocks the download | Verify the source URL is `github.com/cloudstarglide/...` or `cloudstarglide.github.io/...` |
| Archive extraction warning | Confirm the SHA-256 checksum matches the value above |

**Never disable your antivirus entirely.** Use exclusions scoped to the mod folder only.

---

## Safe Usage Guidelines

| Do | Don't |
|----|-------|
| Download only from the official GitHub repository or GitHub Pages | Download from reupload sites, Discord attachments, or third-party mirrors |
| Verify the SHA-256 checksum | Run the executable without checking integrity |
| Back up game saves before first use | Run the mod on a shared/company machine |
| Keep the mod updated to the latest version | Share the archive with unknown modifications |

---

## Disclosure Policy

- Security issues are disclosed publicly **only after** a fix is released.
- Reporters are credited in the release notes unless they request anonymity.
- No bug bounty program is currently offered.

---

## Contact

For non-security questions, open a regular GitHub issue.  
For security matters, use the private reporting channels listed above.
