# License Grants

This file documents all official permissions granted under the CGPSAL v1.0 license.

**Purpose:** This file serves as a public record of persons or entities who have been granted additional rights beyond the base license. If this file is not present in the Official Repository, no such additional rights have been granted.

**Verification:** This file is only valid when added or modified in a commit signed with the copyright holder's GPG key (see `SIGNING.md`) or authenticated by a method designated in `verification-methods.md`.

---

## Example (Filled In)

### Active Grants

| Date | Grantee | Permission Type | Scope | Verification |
|------|---------|-----------------|-------|--------------|
| 2026-03-15 | Acme Corp. | Commercial Distribution | Unlimited redistribution of PDFTools as part of Acme Enterprise Suite | Commit `a1b2c3d` signed by CYB3RCA4T |
| 2026-05-01 | Jane Doe | Paid Hosted Service | Running PDFTools compressor as a paid SaaS at compress.janedoe.com | Commit `e4f5g6h` signed by CYB3RCA4T |

### Expired/Revoked Grants

| Date | Grantee | Permission Type | Revocation Date | Reason |
|------|---------|-----------------|-----------------|--------|
| 2026-01-10 | OldCo Ltd. | Commercial Distribution | 2026-04-20 | License agreement expired, not renewed |

---

## Template

### Active Grants

| Date | Grantee | Permission Type | Scope | Verification |
|------|---------|-----------------|-------|--------------|
| [None yet] | - | - | - | - |

### Expired/Revoked Grants

| Date | Grantee | Permission Type | Revocation Date | Reason |
|------|---------|-----------------|-----------------|--------|
| [None yet] | - | - | - | - |

### Permission Type Reference

Use one of these standard permission types in the **Permission Type** column:

| Type | Description |
|------|-------------|
| Commercial Distribution | Right to sell or monetize distribution of the Software |
| Paid Hosted Service | Right to run the Software as a paid SaaS or hosted service |
| Commercial API | Right to offer the Software as a paid API or backend service |
| White-Label License | Right to rebrand and distribute the Software under a different name |
| Custom Exception | Any other permission not covered above — describe in Scope |

### How to Add a Grant

1. Add a new row to the **Active Grants** table with the date, grantee name, permission type, scope description, and verification reference.
2. Commit the change with a GPG-signed commit (see `SIGNING.md`).
3. The grant becomes effective from the commit timestamp.

### How to Revoke a Grant

1. Move the row from **Active Grants** to **Expired/Revoked Grants**.
2. Add the revocation date and reason.
3. Commit the change with a GPG-signed commit.
4. Previously granted rights under the revoked grant terminate from the revocation timestamp.

### Notes

- Only permissions listed in this file are valid as Official Permissions under the CGPSAL v1.0 license.
- Permissions are only valid if this file was added or modified in a commit signed with the copyright holder's GPG key as specified in `SIGNING.md`, or authenticated by a method designated in `verification-methods.md`.
- The copyright holder reserves the right to modify or revoke grants at any time.
- If this file does not exist in the Official Repository, no additional rights beyond the base license have been granted to any party.
