# Memophant License

Memophant is licensed under **The Heirloom License, Version 1.0** —
variant `HL-1.0-MPL2.0-12mo`.

The Heirloom License is a commercial license with a built-in promise: if
the developer truly abandons the software (12 months without a maintenance
signal **and** no response to a good-faith support request within 90 days),
the source code is automatically released to the public under MPL-2.0,
permanently and irrevocably.

See [memophant.co/license](https://memophant.co/license) for a plain-English
summary, and the full legal text below.

---

## Parameters

| Parameter | This work's value |
|---|---|
| **Licensor** | Alan Wizemann |
| **Licensed Work** | Memophant version 1.0 and later versions released under this license |
| **Change License** | `MPL-2.0` |
| **Dormancy Window** | `12 months` |
| **Source Repository** | `https://github.com/awizemann/Memophant` |
| **Heartbeat Record** | `https://github.com/awizemann/memophant-public/blob/main/heartbeat.log` |

The Source Repository is currently private during the Active Period. On
Sunset, the obligation in Section 6(d) requires the Source Form to be
made publicly available at the Source Repository URL. The Heartbeat Record
is a public, timestamped JSONL log published in this repository
(`awizemann/memophant-public`), updated by a GitHub Actions workflow on
every release, a monthly schedule, and a `repository_dispatch` event fired
by the private Source Repository on each commit to its main branch. Each
heartbeat entry is committed by the `github-actions[bot]` account, which
GitHub independently verifies — the cryptographic signature on each commit
satisfies the "publicly verifiable" requirement in Section 4(a).

---

## The Heirloom License, Version 1.0

**SPDX-style identifier:** `HL-1.0-<ChangeLicense>-<DormancyWindow>`
**This variant:** `HL-1.0-MPL2.0-12mo`

## 1. Definitions

**"Licensed Work"** means the software (in Source Form, Object Form, or both)
identified in the Parameters, including all versions the Licensor distributes
under this license.

**"Source Form"** means the preferred form of the work for making
modifications to it.

**"Object Form"** means any form of the work other than Source Form, including
compiled or executable form.

**"You"** means an individual or legal entity exercising rights under this
license.

**"Sunset"** means the irrevocable event, defined in Section 5, after which the
Licensed Work is governed by the Change License.

**"Sunset Date"** means the calendar date on which Sunset occurs.

**"Dormancy"** means the state, defined in Section 4, in which the Licensor has
ceased to maintain and support the Licensed Work.

**"Competing Use"** means making the Licensed Work, or a modified version of
it, available to third parties as a commercial product or service that is
substantially similar to, and competes with, a product or service offered by
the Licensor.

## 2. Grant During the Active Period (Before Sunset)

Subject to the terms of this license, the Licensor grants You a worldwide,
royalty-free, non-exclusive, non-transferable license to use, run, and study
the Licensed Work for any purpose **other than a Competing Use**.

Unless the Licensor separately publishes the Source Form, no right to receive
or redistribute the Source Form is granted during the Active Period. The
Licensor MAY, at its sole discretion, make the Source Form visible on a
source-available basis during the Active Period; doing so does not advance the
Sunset Date and does not grant the rights described in Section 6 until Sunset
occurs.

You may not:

(a) make a Competing Use of the Licensed Work;

(b) remove or alter this license, the Parameters, or any copyright or
attribution notices; or

(c) sublicense, sell, or redistribute the Licensed Work except as the Licensor
separately permits in writing.

## 3. Reservation

All rights not expressly granted are reserved by the Licensor. This license
does not grant You any rights in the Licensor's trademarks, trade names, or
service marks.

## 4. Dormancy

The Licensed Work enters **Dormancy** when **both** of the following are true:

(a) **No maintenance signal.** The Licensor has not updated the Heartbeat
Record for a continuous period equal to the Dormancy Window. A valid update is
any timestamped, publicly verifiable signal of continued maintenance —
including a new release, a commit to the Source Repository, or a signed
heartbeat entry — recorded at the Heartbeat Record location; **and**

(b) **No support.** The Licensor has not responded to a good-faith written
support or status request, sent to the contact published with the Licensed
Work, within ninety (90) days of that request.

The most recent valid Heartbeat Record update resets the Dormancy Window. The
Licensor can prevent Dormancy at any time, indefinitely, simply by continuing
to record maintenance signals.

## 5. Sunset Trigger

**Sunset occurs automatically and irrevocably on the first date on which the
Licensed Work has been in continuous Dormancy for the full Dormancy Window.**

No declaration, notice, court order, or action by the Licensor or any third
party is required for Sunset to take effect. Sunset is self-executing.

Once Sunset has occurred for a given version of the Licensed Work, it cannot be
reversed, even if the Licensor later resumes activity. Resumed activity may
prevent Sunset for **later** versions but does not un-Sunset any version that
has already Sunset.

## 6. Grant on and After Sunset

On the Sunset Date, the Licensor irrevocably grants every recipient of the
Licensed Work all rights under the **Change License**, and the Licensed Work
(in both Source Form and Object Form) is thereafter governed by the Change
License as if it had originally been released under it.

This grant:

(a) is irrevocable and perpetual;

(b) extends to the general public, not only to prior purchasers or users;

(c) **supersedes the restrictions of Sections 2 and 3**, including the
Competing Use restriction; and

(d) obligates the Licensor (or any party then controlling the Source
Repository) to make the Source Form publicly available at the Source
Repository. The `dead-mans-switch` automation referenced in the project
documentation is the Licensor's good-faith mechanism for performing this
obligation, but the obligation is contractual and exists independently of any
automation.

## 7. Patents

The Licensor grants You a license to its patent claims that it can license,
to the extent necessary to exercise the rights granted in the applicable
period (Section 2 before Sunset, the Change License on and after Sunset). This
patent license terminates if You initiate patent litigation alleging that the
Licensed Work infringes a patent.

## 8. Disclaimer of Warranty

THE LICENSED WORK IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS
OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE, TITLE, AND NON-INFRINGEMENT. THIS DISCLAIMER
APPLIES WITH PARTICULAR FORCE ON AND AFTER SUNSET, WHEN THE LICENSED WORK MAY
BE UNMAINTAINED AND UNSUPPORTED.

## 9. Limitation of Liability

TO THE MAXIMUM EXTENT PERMITTED BY LAW, IN NO EVENT WILL THE LICENSOR BE LIABLE
TO YOU FOR ANY DAMAGES, INCLUDING ANY DIRECT, INDIRECT, SPECIAL, INCIDENTAL, OR
CONSEQUENTIAL DAMAGES ARISING OUT OF THIS LICENSE OR THE USE OF THE LICENSED
WORK, WHETHER IN CONTRACT, TORT, OR OTHERWISE.

## 10. Termination

Any rights granted under Section 2 terminate automatically if You breach this
license and do not cure the breach within thirty (30) days of becoming aware of
it. Rights that have vested under the Change License on or after Sunset are
governed solely by the Change License and are not terminated by this Section.

## 11. Miscellaneous

If any provision of this license is held unenforceable, the remaining
provisions remain in effect. This license does not create any agency,
partnership, or joint venture. Headings are for convenience only.

---

*The Heirloom License is published at <https://github.com/heirloom-license/license>.
The license text is itself dedicated to the public domain under CC0 1.0 — you
may copy, adopt, and modify it without restriction. "Heirloom License" and the
Heirloom badge are project marks; use them only to describe software actually
released under an unmodified version of this license.*
