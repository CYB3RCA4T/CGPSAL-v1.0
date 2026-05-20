# Verification Methods

This file designates the valid verification methods for Official Permissions under the CGPSAL v1.0 license.

**Purpose:** This file tells users how to verify that a claimed permission from the copyright holder is genuine. If this file is not present, the default verification methods described in the license's Official Permission definition apply.

---

## Example (Filled In)

### Method 1: GPG-Signed Commits (Primary)

All Official Permissions must be documented in a commit signed with the copyright holder's GPG key.

- **Key Fingerprint:** `A1B2 C3D4 E5F6 7890 1234 5678 9ABC DEF0 1234 5678`
- **Verification:** Run `git log --show-signature -1 [COMMIT_HASH]` and confirm the signature matches the key listed in `SIGNING.md`.
- **Valid Files:** `LICENSE-GRANTED.md`, any file in the `permissions/` directory.

### Method 2: Detached Signatures (Alternative)

Official Permissions may also be published as standalone `.md` files with a corresponding `.sig` detached GPG signature.

- **Signature Format:** OpenPGP detached signature (`.sig` or `.asc`)
- **Verification:** Run `gpg --verify [FILE].sig [FILE]` and confirm the signature matches the key listed in `SIGNING.md`.
- **Valid Location:** Files must be in the `permissions/` directory of the Official Repository.

### Method 3: Direct Contact (Fallback)

If neither `SIGNING.md` nor this file is present, or if a permission claim cannot be verified through the methods above, contact the copyright holder directly through the Official Repository to verify licensing on a case-by-case basis.

---

## Template

### Method 1: [Primary Method Name]

Describe your primary verification method.

- **Key Fingerprint:** [Fingerprint of the signing key]
- **Verification:** [Step-by-step instructions for verifying this method]
- **Valid Files:** [Which files or directories are covered by this method]

### Method 2: [Alternative Method Name] (Optional)

Describe an alternative verification method if applicable.

- **Signature Format:** [e.g., OpenPGP detached signature, SSH signature, Sigstore bundle]
- **Verification:** [Step-by-step instructions for verifying this method]
- **Valid Location:** [Where signed files must be located in the repository]

### Method 3: Direct Contact (Fallback)

If neither `SIGNING.md` nor this file is present, or if a permission claim cannot be verified through the methods above, [COPYRIGHT HOLDER] may be contacted directly through the Official Repository to verify licensing on a case-by-case basis.

### Adding New Methods

To add a new verification method:
1. Add a new method section below with a clear name and verification instructions.
2. Commit the change with a GPG-signed commit (see `SIGNING.md`).
3. The new method becomes effective from the commit timestamp.

### Removing Methods

To remove a verification method:
1. Delete or strike through the method section.
2. Commit the change with a GPG-signed commit.
3. Permissions verified under the removed method before its removal remain valid.

### Notes

- The valid verification methods for any project are designated in this file.
- If this file is not present, the methods described in the Official Permission definition in the license are the valid verification methods for that project.
- If `SIGNING.md` is not present, verification methods designated in this file are still valid.
- If neither this file nor `SIGNING.md` is present, the copyright holder may be contacted directly through the Official Repository to verify licensing on a case-by-case basis.
- A claimed permission that does not satisfy any designated verification method is not valid under the CGPSAL v1.0 license, regardless of how it is presented or who presents it.
