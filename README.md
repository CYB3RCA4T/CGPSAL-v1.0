# CGPSAL v1.0 — CYB3RCA4T's General Purpose Source Available License

A source-available, non-commercial distribution license designed for individual developers who want to protect their work from commercial exploitation while keeping it freely usable for everyone else.

---

## Why This License Exists

Most licenses force a choice between two extremes:

- **Permissive (MIT, Apache)** — anyone can do anything, including selling your work as their own product
- **Copyleft (GPL, AGPL)** — forces open-sourcing of everything that touches your code

Neither fits the reality of how individual developers actually think about their work:

> *"I want people to learn from it, use it internally, build free tools on top of it. I just don't want a company quietly dropping it into a paid product and never giving anything back."*

CGPSAL v1.0 draws exactly that line.

---

## What It Achieves

| Scenario | Allowed? |
|----------|----------|
| Personal use, learning, research | ✅ Unrestricted |
| Internal company/organizational use | ✅ Unrestricted, no attribution needed |
| Free public tools, APIs, web apps | ✅ With attribution |
| Paid support, consulting, deployment | ✅ With attribution |
| Donations, sponsorships | ✅ Without feature gating |
| Selling the software itself | ❌ Requires commercial license |
| Paid SaaS where the software is a core component | ❌ Requires commercial license |
| Monetized download pages | ❌ Requires commercial license |
| Forks claiming to be official | ❌ Explicitly prohibited |

---

## Key Design Principles

### 1. Internal Use Is Completely Unrestricted
No attribution, no notification, no permission needed. A developer at a company can use this library for an internal tool without asking their legal team.

### 2. Clear SaaS Boundaries
The three-part "core component" test defines exactly when a hosted service requires a commercial license — no ambiguity about "free tier" vs. "paid product."

### 3. Forgery-Resistant Permission Verification
`LICENSE-GRANTED.md` + GPG-signed commits create a public, tamper-proof record of who has been granted commercial rights. If the file doesn't exist, no one has extra rights.

### 4. Universal Legal Capacity
The license works regardless of the author's age or legal capacity. Built to be usable by anyone, including developers who haven't reached the age of majority in their jurisdiction.

### 5. Anti-Impersonation Architecture
Strong protections against fake "official" forks, fraudulent commercial claims, forged permissions, and attribution laundering.

---

## Files

| File | Purpose |
|------|---------|
| `LICENSE-PUBLIC.md` | Parameterized template for other developers who want to adopt this license. Replace `[COPYRIGHT HOLDER]`, `[YEAR]`, `[REPOSITORY URL]`, and `[JURISDICTION]`. |
| `SIGNING.md` | Code signing certificate details and verification instructions. Template with example included. |
| `LICENSE-GRANTED.md` | Public record of commercial permissions granted. Template with example included. |
| `verification-methods.md` | Designates valid verification methods for Official Permissions. Template with example included. |

---

## How to Use

### For Other Developers
1. Copy `LICENSE-PUBLIC.md` into your repository as `LICENSE`
2. Replace all `[PLACEHOLDERS]` with your actual information
3. Optionally set up `SIGNING.md`, `LICENSE-GRANTED.md`, and `verification-methods.md` for permission verification

### For Commercial Licensing
Contact the copyright holder through the Official Repository to arrange licensing.

---

## Not Open Source

This is a **source-available** license, not an OSI-approved open source license. Source code is visible and modifiable, but commercial distribution and certain hosted uses require explicit permission.

---

## License

This license framework is authored by CYB3RCA4T. New versions may only be published by CYB3RCA4T. Adopters may fill in the designated placeholder fields when adopting it for their own projects.

**SPDX Identifier:** `LicenseRef-CYB3RCA4T-GPSAL-1.0`

**Governing Law:** Hungary (for CYB3RCA4T projects)

---

*CYB3RCA4T's General Purpose Source Available License v1.0*
*Source-available. Non-commercial distribution. Universal legal capacity.*
