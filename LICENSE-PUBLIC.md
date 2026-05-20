~~SPDX-License-Identifier: LicenseRef-CYB3RCA4T-GPSAL-1.0~~ **CURRENTLY NOT IN SPDX**

© 2026 CYB3RCA4T. This license text may be copied and distributed
unmodified for the purpose of adopting it in software projects.
Filling in designated placeholders is permitted. No other
modifications are allowed, unless specified in Section 8.

# CYB3RCA4T's General Purpose Source Available License
## Version 1.0

Copyright (C) [YEAR] [COPYRIGHT HOLDER] ([REPOSITORY URL])

This is a source-available, non-commercial distribution license.
You are free to use and modify the Software however you like —
the rules only apply when you distribute it publicly.

This license applies to any Software whose repository includes this
license file.

This is not an OSI-approved open source license.
Commercial distribution licensing: [REPOSITORY URL]

---

## Definitions

**"Software"** means any source code, binaries, documentation, assets,
or other materials published by [COPYRIGHT HOLDER] under this license,
including any project that explicitly adopts this license.

**"Official Repository"** means the primary public repository of the
Software maintained by [COPYRIGHT HOLDER], located at
[REPOSITORY URL] or any successor URL designated by [COPYRIGHT HOLDER].

**"Fork"** means any modified version of the Software that is publicly
distributed outside the Official Repository. Unmodified mirrors or
redistributions of the Software are not Forks but are still subject
to the Public Distribution conditions in Section 3.

**"Public Distribution"** means making the Software, or any Fork of it,
available to any person or entity outside your own organization —
including publishing to websites, package registries, app stores,
download pages, or any other public channel.

**"Official Permission"** means an express written grant from
[COPYRIGHT HOLDER] that satisfies at least one of the following:
(a) published in the Official Repository and signed with
[COPYRIGHT HOLDER]'s code signing key as specified in SIGNING.md,
or (b) documented in a file named `LICENSE-GRANTED.md` in the root
directory of the Official Repository, provided the file was added
or modified in a commit signed with [COPYRIGHT HOLDER]'s GPG key
or authenticated by a method designated in `verification-methods.md`.
`LICENSE-GRANTED.md` serves as a public record of persons or entities
who have been granted additional rights beyond this license — if this
file is not present in the Official Repository, no such additional
rights have been granted. The valid verification methods for any
project are designated in `verification-methods.md` in the root
directory of the Official Repository. If `verification-methods.md`
is not present, the methods described in this definition are the
valid verification methods for that project. If SIGNING.md is not
present, verification methods designated in `verification-methods.md`
are valid. If neither `verification-methods.md` nor SIGNING.md is
present, [COPYRIGHT HOLDER] may be contacted directly through the
Official Repository to arrange licensing on a case-by-case basis.
A claimed permission that does not satisfy either condition is not
valid under this license, regardless of how it is presented or who
presents it.

**"You"** means the individual or legal entity exercising rights under
this license.

**"Authorized Representative"** means any person authorized to represent
[COPYRIGHT HOLDER] in legal proceedings, contract negotiations, and
permission verification, including a legal guardian where
[COPYRIGHT HOLDER] lacks full legal capacity. An Authorized
Representative does not have the right to grant licenses, modify this
license, or transfer rights — those powers remain exclusively with
[COPYRIGHT HOLDER].

**"Commercial Licensing Action"** means any legally binding grant of
commercial rights, contract negotiation, settlement agreement, or
modification of license terms beyond filling in designated placeholder
fields.

**"Commercial Distribution"** means Public Distribution where access,
acquisition, or use of the Software directly or indirectly generates
revenue tied to the Software itself.

**"Commercial Use"** means any use of the Software where the Software
itself is the product being sold, or where access to functionality
powered by the Software requires payment. Internal use by a for-profit
company, advertising-funded services, and voluntary donation-funded
services are not considered Commercial Use under this license.

**"Joint Consent Model"** means that where the copyright holder lacks
full legal capacity, any Commercial Licensing Action requires the joint
consent of the copyright holder and their Authorized Representative
(Legal Guardian). A Commercial Licensing Action taken without such
joint consent is not binding. Upon the copyright holder obtaining
full legal capacity, all rights vest in the copyright holder
automatically, and the Authorized Representative is no longer required
for any purpose under this license.

**"License Adoption"** means the act of adopting this license for a
Software project by including the license file in the repository.
Any individual, regardless of age or legal capacity, may adopt this
license. License Adoption is a unilateral declaration of terms and
does not require legal capacity or guardian consent.

---

## Acceptance

By using, copying, modifying, distributing, or hosting the Software,
you agree to this license. If you do not agree, do not use the Software.

---

## Grant of Rights

[COPYRIGHT HOLDER] grants you a non-exclusive, royalty-free, worldwide
license to use, copy, modify, and run the Software for any internal
purpose — personal, educational, research, or commercial — without
restriction, subject to the conditions below.

All rights not expressly granted under this license are reserved by
[COPYRIGHT HOLDER].

---

## Copyright Reservation

[COPYRIGHT HOLDER] retains sole ownership of the Software and all
associated intellectual property rights. Nothing in this license —
including the acceptance of contributions, the grant of rights to
users, or the actions of any Authorized Representative — transfers,
assigns, or diminishes [COPYRIGHT HOLDER]'s ownership of the Software
or any part of it. Rights granted under this license are licenses
only, not transfers of ownership. See the Contributions section for
how contributor ownership interacts with [COPYRIGHT HOLDER]'s
ownership of the Software as a whole.

---

## Conditions

### 1. Internal Use

You may use, modify, and run the Software internally without any
restrictions. This includes:

- Personal projects
- Internal company or organizational use
- Security research
- Education
- Any other use that does not constitute Public Distribution

No attribution, notification, or permission is required for internal use.

### 2. Hosted and SaaS Use

You may run the Software on a server or infrastructure to provide a
service to external users, provided that users are not required to
pay, directly or indirectly, to access functionality powered by the
Software. For the purposes of this license, indirect payment means
any requirement to pay specifically for access to functionality
materially enabled by the Software, where the Software is a core
component of the service. A service funded by advertising or
voluntary donations — where users access the functionality without
any payment requirement — is not considered an indirect payment and
is permitted under this section.
This includes:

- Free web applications or tools powered by the Software
- Free APIs whose responses are generated using the Software
- Free public services where users interact with the Software's output

You may not run a paid hosted service, subscription product, or
commercial API where the Software is a core component. The Software
is a core component if any of the following is true:

- Removing it would require substantial re-engineering or replacement
  of core functionality, or
- It is essential to the primary value or advertised capability of
  the service — meaning it is a feature or function that is described,
  marketed, or experienced by users as a primary reason to use the
  service, or without which the service would not deliver its
  advertised purpose, or
- Regardless of how the service is marketed, the Software processes,
  generates, or materially transforms the primary data or output
  delivered to external users of the service

All tests are independent — satisfying any one is sufficient to
classify the Software as a core component. This applies regardless
of whether you distribute the Software itself. Charging for such a
service requires a commercial license from [COPYRIGHT HOLDER].

The following are not restricted by this section:

- Internal tools or dashboards accessible only to your own employees
  or organization members, even if your organization is for-profit
- Free tiers of a service, provided the Software is not a core
  component of any paid tier. If the Software powers a free tier,
  that free tier must clearly display that the Software is used
  within it — in a location that a typical user would reasonably
  encounter, such as the tier description, feature list, about page,
  or credits section. A link or mention buried in legal documents,
  terms of service, or source code comments does not satisfy this
  requirement. You may not power any tier with the Software without
  disclosing its use in that tier's documentation.
- Shared infrastructure that serves both free and paid tiers is
  permitted, provided the functionality powered by the Software is
  materially available to users of the free tier, regardless of
  whether users directly interact with it. Tiered feature limitations
  (such as resolution limits, usage caps, or feature gating) do not
  negate material availability, provided the free tier receives
  meaningful access to the functionality powered by the Software.
  Meaningful access means the free tier can exercise the core
  functionality of the Software without payment, even if subject
  to reasonable rate or quality limits. If the Software is only
  accessible as part of a paid product or service, this exemption
  does not apply.

This license does not require publication of source code for
modifications used solely for internal or hosted use.

### 3. Public Distribution

If you engage in Public Distribution of the Software or any Fork,
you must:

- **Show the Official Repository** — any page, package, or channel
  through which the Software is distributed must display a clear,
  visible link to the Official Repository. For UI-based distributions,
  the link must be visible without requiring the user to inspect source
  code, view page source, or navigate to a separate page. For embedded
  UIs or applications where screen space is limited, the link may
  appear in an about screen, credits section, or equivalent location
  directly accessible from the main menu or primary interface. Where
  screen space is limited, the link may be placed in a popup or behind
  a dedicated button (such as a license or credits button) that opens
  directly without requiring navigation through unrelated menus. For
  non-UI distributions (libraries, APIs, CLI tools, embedded systems),
  the link must appear in the documentation, README, package metadata,
  or help output. Distributions that include both UI and non-UI
  interfaces must satisfy the requirements for at least one of those
  interface types.
- **Attribute the author** — display the original project name and
  author ([COPYRIGHT HOLDER]) in the distributed package, README, or
  equivalent documentation
- **Retain copyright notices** — do not remove or alter any existing
  copyright notices in the source code
- **Use this license** — distribute the Software or any Fork only
  under the same version of this license included with the Software,
  without alteration
- **No monetization** — you may not charge for, or generate revenue
  from, the distribution itself — see Section 4 for what this means

#### Package Registries

Publishing to genuine public package registries (such as npm, PyPI,
or Linux distribution mirrors) is permitted provided:

- The registry is a bona fide public registry open to all — not a
  commercial wrapper or storefront that presents itself as a registry
  to circumvent this license
- The package listing meets the attribution requirements above
- No fee is charged specifically for access to the Software

A registry that generates revenue from the Software itself — for
example by paywalling downloads, charging per-install, or selling
access to the package — is not a genuine public registry under this
license regardless of how it describes itself.

For package registry listings specifically, attribution may appear
anywhere reasonably visible — the package README, description field,
metadata, or any equivalent location within the listing, provided
that the complete, unmodified license text and copyright notices
remain present within the distributed package payload itself. This
constraint extends to any installation-time or runtime scripts that
fetch, replace, or execute Software assets — such assets remain
subject to this license and must preserve all attribution and license
requirements. There is no requirement for a dedicated webpage or
prominent placement beyond what is practical for the registry format.
The point is simply that anyone who finds the package can tell where
it originally came from.

#### Forks

If you publicly distribute a Fork, you must additionally:

- Display a clear, visible warning that it is not the official version
  and is not affiliated with or endorsed by [COPYRIGHT HOLDER] — for
  example: *"This is a modified version of [Software]. It is not the
  official release. The official version is available at
  [Official Repository]."*
- Document what changes were made relative to the original Software
- Not present the Fork as if it were the official release

### 4. No Monetization of Distribution

This section applies independently of Section 2. A service that
complies with Section 2 may still violate this section if it
monetizes distribution — and vice versa. Complying with one section
does not exempt you from the others. Where sections overlap, all
applicable restrictions apply.

You may not engage in Commercial Use through Public Distribution of
the Software or any Fork, where the Software itself is the product
being sold or the primary revenue driver. This includes:

- Selling the Software, or charging users for access to, or
  downloads of, the Software
- Including the Software in a paid product or service where the
  Software is a core component offered to external customers or users
- Running monetized advertising on any page whose primary purpose
  is to host or offer the Software for direct download. Pages that
  merely mention, review, link to, or discuss the Software — including
  blogs, tutorials, and documentation sites — are not subject to this
  restriction even if they carry advertising.

The Official Repository and any website, platform, or service operated
by [COPYRIGHT HOLDER] or an Authorized Representative is exempt from
the advertising restriction in this section.

The following are **not** restricted by this section:

- Internal use by a for-profit company, regardless of the company's
  revenue from unrelated activities
- Paid support or consulting services — see Section 5
- Monetized content such as tutorials, reviews, blog posts, or videos
  that discuss or demonstrate the Software, provided they do not
  themselves host or distribute it
- Server-side analytics used solely to monitor availability, security,
  and performance of the distribution channel itself, provided they
  are not monetized and are not presented as official [COPYRIGHT HOLDER]
  infrastructure
- Genuine public package registries as described in Section 3

Voluntary donations for Public Distribution of a Fork are permitted
provided they are not solicited or advertised in exchange for access
to the Fork, priority features, or any benefit not equally available
to all users without payment. Sponsor recognition benefits (such as
logo placement, name listings, or public acknowledgment) are permitted.
Sponsor tiers may not include access to features, functionality, or
support response times not equally available to all users. Donations
given freely without any quid pro quo arrangement are not restricted
by this section.

Only [COPYRIGHT HOLDER] may engage in Commercial Distribution of the
Software. Contact [COPYRIGHT HOLDER] for commercial distribution
licensing.

### 5. Paid Support

You may charge for support, consulting, deployment, integration,
or maintenance services involving the Software, provided you:

- Display a clear link to the Official Repository in any materials
  describing or offering the service
- Inform clients that free community support is available at the
  Official Repository
- Do not represent your service as officially endorsed by
  [COPYRIGHT HOLDER] unless explicitly authorized in writing by
  [COPYRIGHT HOLDER]

Charging for ongoing maintenance, hosting management, or integration
services is permitted, provided the Software itself is not the product
being sold.

### 6. No False Endorsement or Official Claim

Regardless of how you use or distribute the Software, you may not:

- Claim or imply that [COPYRIGHT HOLDER] created the Software
  specifically for you or your organization
- Claim or imply an official relationship, partnership, or endorsement
  with [COPYRIGHT HOLDER]
- Present any build or distribution as an official [COPYRIGHT HOLDER]
  release — the only official source is the Official Repository
- Use the name "[COPYRIGHT HOLDER]" or any associated project name
  to endorse or promote yourself, your organization, or any Fork,
  beyond what is required for attribution under Section 3

Attribution use as required by this license does not constitute an
endorsement claim.

### 7. No Misrepresentation

You may not:

- Claim authorship of the original Software
- Remove or obscure any existing copyright notices
- Relicense the Software or any Fork under different terms

### 8. License Integrity

The text of this license framework was authored by CYB3RCA4T and
remains their intellectual property. It may not be modified by anyone
other than CYB3RCA4T as a license framework, though [COPYRIGHT HOLDER]
may fill in the designated placeholder fields when adopting it.
New versions of this license framework may only be published by
CYB3RCA4T. [COPYRIGHT HOLDER] may adopt future versions by
updating the license file in the Official Repository. Any document that presents itself
as a version of this license but has been altered by a third party
is not a valid version of this license and grants no rights. The
replacement of clearly designated placeholder fields (such as
`[COPYRIGHT HOLDER]`, `[YEAR]`, `[REPOSITORY URL]`, and
`[JURISDICTION]`) for the purpose of adopting this license does not
constitute a modification of the license text.

Forks must include the complete original text of this license in the
root directory of the project without alteration to its legal terms
or operative provisions, except for the replacement of clearly
designated placeholder fields such as `[COPYRIGHT HOLDER]`, `[YEAR]`,
`[REPOSITORY URL]`, and `[JURISDICTION]`. Incidental differences
introduced by packaging tools — such as line ending conversions,
encoding normalization, or whitespace — do not constitute a
modification for the purposes of this clause, provided the textual
content and meaning are preserved.

[COPYRIGHT HOLDER] may publish revised versions of this license. If
the Software explicitly specifies "or any later version", you may
choose to follow either the version specified or any later version
published by [COPYRIGHT HOLDER]. Otherwise, you must follow the
version included with the Software.

#### License Contribution

The official CGPSAL repository is located at
https://github.com/CYB3RCA4T/CGPSAL-v1.0. This is the authoritative
source for the latest version of the license framework.

Forking the license framework repository for the sole purpose of
strengthening, improving, or proposing enhancements to the license
text is permitted. Such forks must be submitted as contributions
(Pull Requests) to the official repository. Modified versions of
the license framework may be published under a different name,
provided they are not represented as official versions of the CGPSAL.

Forking or modifying the license text within an existing software
project is not permitted. The license file included in a software
project may only be modified to fill in the designated placeholder
fields. Any other modification to the license text in a software
project constitutes a violation of this license.

Only CYB3RCA4T may publish versions under the name "CYB3RCA4T's
General Purpose Source Available License" or any substantially
similar name.

Reproduction of this license text as required by its terms is expressly
permitted.

### 9. Trademarks

No trademark rights are granted under this license. The name
"[COPYRIGHT HOLDER]", any associated project names, logos, or other
trademarks of [COPYRIGHT HOLDER] may not be used to endorse or
promote products, services, or Forks derived from the Software
without prior written permission from [COPYRIGHT HOLDER]. Use of
these marks for attribution purposes as required by Section 3 is
permitted and does not constitute a trademark grant beyond such
limited use.

---

## Availability

[COPYRIGHT HOLDER] may stop publishing or distributing the Software
at any time, for any reason, without notice or obligation. No person
or entity may compel [COPYRIGHT HOLDER] to continue distributing,
maintaining, or supporting the Software. [COPYRIGHT HOLDER] may
revise this license or publish new versions of the Software under
different terms. Users who received the Software under this version
retain their rights only under the terms of this specific version —
they do not automatically gain rights under future versions or
revised licenses. Withdrawal means new official copies may no longer
be available from [COPYRIGHT HOLDER].

Rights granted under this version of the license to users who
received the Software are irrevocable, provided those rights are
not terminated under the Termination section.

---

## Patent Protection

The public commit history of the Official Repository establishes when
each feature of the Software was first publicly disclosed, and
constitutes prior art as of each commit date under applicable law.
Commit history backed up by an immutable third-party archive (such as
Software Heritage or the Internet Archive) constitutes definitive
prior art for the purposes of this section.

You may not use a patent to bring a claim against any person for their
use of the Software or any modification of it, if that patent's
earliest effective filing date is after the date the relevant
functionality first appeared in the Official Repository. If you bring
such a claim, your rights under this license terminate immediately
and permanently.

If you bring any patent claim or copyright infringement claim against
[COPYRIGHT HOLDER] or any Authorized Representative that alleges the
Software infringes intellectual property rights, your rights under
this license also terminate immediately and permanently.

[COPYRIGHT HOLDER] grants you a license under any patents
[COPYRIGHT HOLDER] holds that are necessarily infringed by the
Software in its unmodified form, solely to exercise the rights
granted here.

---

## Contributions

Contributors retain ownership of their contributions and may
separately use or license them outside the Software. Contributor
ownership of individual contributions does not confer ownership of,
or any rights in, the Software as a whole.

By opening a pull request or submitting code intentionally for
inclusion in the Software, you acknowledge that if your contribution
is accepted and merged into the Official Repository:

- You grant [COPYRIGHT HOLDER] a perpetual, worldwide, non-exclusive,
  irrevocable license to use, modify, distribute, sublicense,
  commercially license, and relicense your contribution as part of
  or derived from the Software
- If your contribution necessarily infringes patents you control,
  you grant [COPYRIGHT HOLDER] and all users a perpetual, royalty-free
  patent license for use of the contribution as part of the Software
- You grant all users of the Software the rights specified in this
  license as they apply to the final project or any Fork containing
  your contribution
- You agree not to assert copyright, patent, or license claims
  against authorized use of your merged contribution as permitted
  under this license
- This acceptance is automatic upon merging — no further confirmation
  or separate agreement is required. If a GitHub pull request
  checkbox or equivalent acknowledgment mechanism is present,
  checking it constitutes additional explicit acknowledgment of
  these terms, but is not required for acceptance.

Contributions must include a `Signed-off-by:` line in the commit
message in the format `Signed-off-by: Name <email>`, where the email
may be a masked or noreply address (e.g., `username@users.noreply.github.com`).
This line indicates the contributor's acceptance of these terms. By
submitting a contribution, you acknowledge that you have read and
understood these terms. By submitting a contribution, you represent
that you have the right to grant the licenses described above. Failure
to read this license does not exempt you from its conditions. Trivial
contributions — such as documentation fixes, typo corrections, or
single-line changes — are implicitly accepted without a Signed-off-by
line.

If your contribution is not accepted or the pull request is rejected,
no rights are granted and no obligations apply. These rights apply
only to the specific project and do not extend to code copied from
the Software into unrelated projects.

---

## Rights Holder

Rights under this license are held by [COPYRIGHT HOLDER]
([REPOSITORY URL]). Any individual may adopt this license through
License Adoption as defined above. Where [COPYRIGHT HOLDER] lacks
full legal capacity under applicable law, any Commercial Licensing
Action requires the joint consent of [COPYRIGHT HOLDER] and their
Authorized Representative (Legal Guardian). A Commercial Licensing
Action taken without such joint consent is not binding. Upon
[COPYRIGHT HOLDER] obtaining full legal capacity, all rights vest
in [COPYRIGHT HOLDER] automatically.

---

## Termination

Your rights terminate automatically if you violate this license.
For most violations, you have 30 days from the date you become aware
of the violation, or from the date [COPYRIGHT HOLDER] provides written
notice of the violation (whichever is earlier), to come into
compliance, after which your rights are fully reinstated as if no
breach occurred. This cure period does not apply to violations of
the Patent Protection section — those terminate rights immediately
and permanently. Repeat violations after a prior cure — meaning a
second violation of any provision within 24 months of a prior cure —
terminate rights immediately and permanently.

---

## Severability

If any provision of this license is found to be unenforceable under
applicable law, that provision shall be modified to the minimum extent
necessary to make it enforceable, or if modification is not possible,
severed from this license. The remaining provisions continue in full
force and effect.

---

## No Warranty

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, TITLE, AND
NON-INFRINGEMENT. IN NO EVENT SHALL [COPYRIGHT HOLDER] OR ANY
AUTHORIZED REPRESENTATIVE BE LIABLE FOR ANY CLAIM, DAMAGES, OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT, OR OTHERWISE,
ARISING FROM, OUT OF, OR IN CONNECTION WITH THE SOFTWARE OR THE USE
OR OTHER DEALINGS IN THE SOFTWARE.

---

## Governing Law

This license is governed by the laws of [JURISDICTION]. Disputes are
subject to the exclusive jurisdiction of the courts of [JURISDICTION].
Parties agree to attempt good-faith resolution through direct
communication before initiating legal proceedings, except where
immediate injunctive relief is necessary to prevent irreparable harm.
The good-faith resolution requirement does not toll, delay, or bar
either party from seeking immediate equitable or injunctive relief.

---

## Signature and Verification

Official builds may be signed with [COPYRIGHT HOLDER]'s personal code
signing certificate. If SIGNING.md is present in the Official
Repository, see it for verification instructions and certificate
details. If SIGNING.md is not present, code signing is not enabled
for this project. Builds not carrying a valid [COPYRIGHT HOLDER]
signature are not verified — use unverified builds at your own risk.

[COPYRIGHT HOLDER] may rotate code signing keys. Previously issued
permissions remain valid if verifiable against any current or
historical key published in SIGNING.md or verification-methods.md.
Keys with a valid revocation certificate published to any keyserver
or repository are not valid for verifying permissions granted after
the revocation timestamp — previously issued permissions remain
valid. The revocation timestamp is determined by the keyserver
publication timestamp or a trusted timestamping authority conforming
to RFC 3161 or equivalent standard, not by Git metadata. Keys that
have reached their natural expiration date remain valid for verifying
permissions granted before the expiration date.

### Permission Verification

Any claimed [COPYRIGHT HOLDER] permission — including commercial
licenses, exceptions, or endorsements — is only valid as an Official
Permission, meaning it must satisfy at least one of the following
conditions:

1. It is published in the Official Repository and signed with
   [COPYRIGHT HOLDER]'s code signing key as specified in SIGNING.md
2. It is documented in a file named `LICENSE-GRANTED.md` in the root
   directory of the Official Repository, provided the file was added
   or modified in a commit signed with [COPYRIGHT HOLDER]'s GPG key

If neither `verification-methods.md` nor SIGNING.md is present,
[COPYRIGHT HOLDER] may be contacted directly through the Official
Repository to verify licensing on a case-by-case basis.

The valid verification methods for any project are designated in
`verification-methods.md` in the root directory of the Official
Repository. If `verification-methods.md` is not present, the methods
described in this section are the valid verification methods for that
project. If SIGNING.md is not present, verification methods designated
in `verification-methods.md` are valid. A permission that satisfies
neither condition is not valid. If you receive a claimed permission
that is not verifiable against either condition, treat it as invalid
and contact [COPYRIGHT HOLDER] through the Official Repository to
verify. [COPYRIGHT HOLDER] is not responsible for any reliance on
unverified permission claims.

---

## Simple Summary

*Not legally binding. The sections above govern in any conflict.
If you are distributing this Software, you must include the full
license text above — this summary alone does not satisfy the
license integrity requirements.*

**Internal use — zero restrictions:**
- Use it however you want personally, at work, for research, education
- Modify it, build on it, run it in production internally
- No attribution needed, no permission needed, no strings attached
- Doesn't matter if your company makes money from unrelated things

**Running it as a hosted service or API:**
- Free service/API powered by the Software → fine
- Paid service, subscription, or commercial API where the Software
  is a core component → needs [COPYRIGHT HOLDER] permission
- A service can be subject to this rule even if it doesn't advertise
  the Software — see the full license for the three-part core
  component test
- Internal tools for your own team/org → always fine regardless

**Distributing it publicly — these rules apply:**
- Link to the Official Repository visibly wherever you distribute it
  (for UI: visible on-screen or in a popup or behind a dedicated
  button that opens directly; for libraries/APIs/CLI: in docs,
  README, or metadata)
- Show [COPYRIGHT HOLDER] as the author in your package/README
- Keep copyright notices intact
- Distribute only under this same license, unmodified
- Don't make money from the distribution itself
- If your distribution has both UI and non-UI modes, satisfy the
  requirements for at least one of them

**Forking publicly — additionally:**
- Add a visible notice that it's not the official version
- Document what you changed
- Don't pretend it's the official release
- Donations are fine as long as they're not tied to access or special benefits

**Never allowed, ever:**
- Claiming [COPYRIGHT HOLDER] made it specifically for you or your organization
- Implying an official relationship or endorsement with [COPYRIGHT HOLDER]
- Presenting any build as official other than what's in the Official Repository
- Modifying the license text — only [COPYRIGHT HOLDER] can do that
- Distributing a Fork with a modified or replaced license file
- Using [COPYRIGHT HOLDER]'s name, logos, or trademarks to promote your own products
- Patent trolling users of this software — ends your rights immediately and permanently
- Suing [COPYRIGHT HOLDER] over this software — ends your rights immediately and permanently
- Claiming you wrote the original
- Removing copyright notices
- Relicensing it

**Someone claiming they have [COPYRIGHT HOLDER]'s permission?**
A permission is only real if it is posted in the Official Repository
with a valid code signature, OR documented in `LICENSE-GRANTED.md`
(a public record of who has been granted additional rights) with a
GPG-signed commit, OR verified through another method designated in
`verification-methods.md`. If `LICENSE-GRANTED.md` doesn't exist,
no one has additional rights. If you're not sure, check the Official
Repository directly.

**Making money from distributing it?**
Contact [COPYRIGHT HOLDER] through the Official Repository to arrange licensing.
Everything else is free.

**Package registries:**
Real public registries (npm, PyPI, etc.) are fine. A commercial
storefront calling itself a package manager to bypass the rules is not.

**Paid support?**
Fine — just link to the Official Repository and don't claim you're
officially endorsed by [COPYRIGHT HOLDER].

**Monetized YouTube videos, blog posts, tutorials?**
Fine — as long as you're not hosting or distributing the Software itself.

**Can [COPYRIGHT HOLDER] stop distributing it?**
Yes. But that doesn't affect you if you already have a copy — your
rights under this license stay intact. It just means new official
copies might not be available anymore.

**This license applies to any project that includes this license file.**
It is not automatically applied to all [COPYRIGHT HOLDER] projects.

**Open source?**
No. Source-available. Public, free to use internally, free to distribute
non-commercially — making money from distribution requires permission.

---

*Adopters: Replace all [PLACEHOLDERS] before use. Do not modify the license text.*

*CYB3RCA4T's General Purpose Source Available License v1.0*
*Governed by the laws of [JURISDICTION].*
*This is not legal advice. Consult a qualified attorney if needed.*

A copy of this license that remains in template form with unfilled
placeholder fields (such as [COPYRIGHT HOLDER], [YEAR], [REPOSITORY URL],
or [JURISDICTION]) does not grant any rights. A license with placeholders
substantially filled in is valid and binding.
