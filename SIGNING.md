# Code Signing

This document contains the code signing certificate details for verifying official builds and permissions.

---

## Example (Filled In)

> **Key Type:** PGP (GPG)
> **Fingerprint:** `A1B2 C3D4 E5F6 7890 1234 5678 9ABC DEF0 1234 5678`
> **Algorithm:** RSA 4096-bit
> **Created:** 2026-01-15
> **Expires:** 2028-01-15
> **Public Key:** https://github.com/CYB3RCA4T.gpg
> **Keyserver:** `hkps://keys.openpgp.org`

---

## Template

Replace all bracketed placeholders with your actual information.

### Current Key

- **Key Type:** [e.g., PGP (GPG), X.509, Sigstore/Cosign, SSH]
- **Fingerprint:** [e.g., A1B2 C3D4 E5F6 7890 1234 5678 9ABC DEF0 1234 5678]
- **Algorithm:** [e.g., RSA 4096-bit, Ed25519, ECDSA P-256]
- **Created:** [YYYY-MM-DD]
- **Expires:** [YYYY-MM-DD or "No expiration"]
- **Public Key:** [URL to public key file, keyserver link, or inline key block]
- **Keyserver:** [e.g., hkps://keys.openpgp.org, hkps://keyserver.ubuntu.com]

### Verification Instructions

1. Download the official build and its signature file (`.sig` or `.asc`).
2. Import the public key:
   ```bash
   # For PGP/GPG:
   gpg --keyserver hkps://keys.openpgp.org --recv-keys [FINGERPRINT]
   # Or download directly:
   curl -fsSL [PUBLIC_KEY_URL] | gpg --import
   ```
3. Verify the signature:
   ```bash
   # For detached signatures:
   gpg --verify [SIGNATURE_FILE] [BUILD_FILE]
   # For Git commit signatures:
   git log --show-signature -1 [COMMIT_HASH]
   ```
4. If the output shows `Good signature from [NAME]`, the build is officially verified.

### Historical Keys

| Fingerprint | Algorithm | Created | Expires | Status |
|-------------|-----------|---------|---------|--------|
| [Fingerprint of previous key] | [Algorithm] | [YYYY-MM-DD] | [YYYY-MM-DD] | [Active / Revoked / Expired] |

### Revoked Keys

| Fingerprint | Revocation Date | Reason |
|-------------|-----------------|--------|
| [None yet] | - | - |

### Revocation Policy

Keys with a valid revocation certificate published to any keyserver or repository are not valid for verifying permissions granted after the revocation timestamp. Previously issued permissions remain valid. The revocation timestamp is determined by the keyserver publication timestamp or a trusted timestamping authority conforming to RFC 3161 or equivalent standard, not by Git metadata. Revocation certificates take effect from their publication timestamp, not from keyserver propagation time.

### Key Expiration

Keys that have reached their natural expiration date remain valid for verifying permissions granted before the expiration date. Expired keys will be flagged as "Unverified" by Git platforms but remain legally valid for historical permissions.

### Key Rotation

The copyright holder may rotate code signing keys. When a key is rotated:
- The new key details will be published in the **Current Key** section above.
- The old key will be moved to the **Historical Keys** table.
- Previously issued permissions remain valid if verifiable against any historical key published in this file.
