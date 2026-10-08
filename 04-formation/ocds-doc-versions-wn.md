---
type: moc
title: OCDS Document Versions
aliases:
  - OCDS Document Version Register
tags:
  - carmel/formation
  - type/note
layer: 5
authority: personal
scope: charism
created: 2026-04-17
modified: 2026-09-10
description: OCDS Document Version Register
---

# OCDS Document Version Register

One row per document. `status: current` = this is the version in use. `status: superseded` = a newer version exists. `status: verify` = date or currency uncertain — needs confirmation.

**Key principle**: For legislation, the scanned printed book is the canonical law. For formation handbooks, `MM-YY` in the filename is the edition date. For province policies, the date in the filename is the effective date.

---

## OCD General Curia — Liturgy Decrees

Documents issued by the OCD General Curia. Versioned by **Prot. N. XX/YY** (Protocol Number / Year) — this IS the authoritative version identifier for Curia documents. Higher Prot. N. within the same year = issued later.

### Proper Calendar

| Document | Prot. N. / Edition | Year | Status | Drive File ID | Notes |
|----------|-------------------|------|--------|--------------|-------|
| OCD Propers — Divine Office text | 2007 ed. | 2007 | current | `1bad5fIk3e6qngpWRMkhSdG9y-lRwRMRg` | Base reference; amended by Prot. N. decrees below |
| OCD Proper Calendar — English Province | 2025-03 | 2025-03 | current | `1WzeWtYwT28Mug77YcvBAD4ySfku7jzKQ` | Most current English calendar |
| Calendarium Proprium OCD (Latin) | Prot. 600/23, 62/24, 36/25 | 2025 | current | — | Authoritative Latin original; local PDF in VaultOps/vault-assets/ocds-loth/ |
| 2025 Calendario Proprio OCD | 2025 | 2025 | current | `1rzVsAXB9dKfa8CTL-nmJInNiKw6IK73j` | OCD General Curia official Italian edition |

### Prot. N. Feast Decrees (amendments to 2007 Proper)

| Document | Prot. N. | Year | Status | Drive File ID | Calendar Impact |
|----------|----------|------|--------|--------------|----------------|
| Maria Felicia of Jesus in the Blessed Sacrament | 426/20 | 2020 | current | `1JCfQjVHevZcOmlS9icT8r5lllevkrown` | Adds feast to OCD calendar |
| Anne of Jesus (Ana de Jesús) | 62/24 | 2024 | current | `1frp92XKGvDgQOjMfkEF9wbBAMkZ4nEl2` | Updates/adds feast — read to determine rank impact on OCDS propers |
| Angelus Mary, Luke of St. Joseph & Companions | 113/24 | 2024 | current | `1QOG186spNl3TK2cmXEk2rRiPAXP2EnQG` | Adds feast to OCD calendar |

### Proprium Missarum

| Document | Edition | Status | Drive File ID | Notes |
|----------|---------|--------|--------------|-------|
| Proprium Missarum OCD — Missale (Latin) | Editio typica altera, 2025 | current | `1ajhwslOueEnb7x7WDOn4WZhSD6-ap_Rx` | Proper prayers for OCD feasts; confirmed from carmelitaniscalzi.com |
| Proprium Missarum OCD — Lectionarium (Latin) | Editio typica altera, 2025 | current | `1UyTyeyYjJQ7GF-EVG6KnJXpE7fi4OnmW` | Scripture readings for OCD feasts; confirmed from carmelitaniscalzi.com |
| Enchiridion Indulgentiarum OCD (Latin) | 2026 | current | `1JbIJoV1h7Pjz3RN6bQ3RNAukNP8MUTBk` | **Authoritative**; Latin is official text |
| Manuale delle Indulgenze OCD (Italian) | 2026 | current | `1iy_F-spWymckZyoxalJfGc8UlApqeyR1` | Working translation; no English edition yet |

---

## Legislation (Order & Province Level)

| Document | Edition / Version | Effective Date | Status | Drive File ID | Notes |
|----------|------------------|----------------|--------|--------------|-------|
| OCDS Legislation — Full Scanned Book | 2017 Edition | 2017 | current | `1ChDc5t4Q8eAPDdN0biiOHavQeKgxQ-Y4` | **Authoritative**; scanned print; includes Rule, Constitutions, Statutes, Ratio, Ritual |
| Rule of Saint Albert | 2017 Edition | 2017 | current | `1yU-Hy7WbmQRMoD0mUpdsSdGN9K5MMDaF` | Split from full scanned doc; convenience copy |
| Constitutions | 2003, revised 2014; compiled 2017 | 2014 | current | `1VBOm41PZb8U_07WeW8TSxxwb8UnhHzHc` | Constitutions text is 2003/2014; 2017 ed. is province compilation |
| Provincial Statutes (OK Semi-Province) | 2017 Edition | 2017 | current | `1JIMHjyvsRmgCmWzBRSmiTOLHj1BbKNUS` | verify — check if any statutes updated post-2017 |
| Ratio Institutionis | 2017 Edition | 2017 | current | `1w7S41jF1b7M0DPg1dyZ6xiYJ8EVyXy8F` | verify — Ratio may have been updated at Order level |
| Ritual | 2017 Edition | 2017 | current | `1BZn2oWCIY74oEXZ3aMfSUNIUpiIT_i8J` | — |

---

## Province Policies (Semi-Province of St. Thérèse)

All policies set by the semi-province council. Effective dates encoded in filenames as `MM-DD-YY`.

| Document | Effective Date | Status | Drive File ID | Notes |
|----------|----------------|--------|--------------|-------|
| Annual Check-in Interviews / Addressing Concerns | 2022-12-16 | current | `1Yz4S_NnlFVi07K1V1zXJg0SntTXFDcKG` | — |
| Community Apostolates | 2022-12-16 | current | `1JjLiIs4v7XrKKNMlS2XB_2sMBwwvzGds` | — |
| Community Attendance | 2022-12-16 | current | `1lYvxfpBmCX0l7_Ctdx3RbJZjtG_639MO` | — |
| Community Bank Accounts | 2023-03-15 | current | `1fvt9xXJVlQOg9qLdGFLeHOnMTldMYdnR` | Updated from 12-16-22 version |
| Community Dues | 2022-12-16 | current | `1i0SYl9OslrDXtYduHzigOtqNTRDbHC0Y` | — |
| Community Fundraising | 2022-12-16 | current | `1u401Mh_NDedXhm_sujZ5zQl0qQQd1nFZ` | — |
| Considerations in Making a Private Vow | 2022-12-16 | current | `1QwmK05MezjxrRq5FBMTXW2DkaQE6ERe7` | — |
| Council Member's Recusal from Certain Decisions | 2022-12-16 | current | `1lNeKjSTTeDBQJOlqZe-zJ60OWm_ZDhxI` | — |
| Elements of OCDS Meeting | 2025-09 | current | `1oHjGN1unlvd9XfPSsGxXLvDyfW2_CqhQ` | Updated Sept 2025 — newer than all other policies |
| Married Couples and Community Elections | 2022-12-16 | current | `131VrsvY_SHkanEzAmAZGMI8at8dkdNBQ` | No date in filename; date from province website listing |
| Member Files and Local Council Records | 2022-12-16 | current | `1jp_cAlesHKzKDEtKEoufImX_spx9a_in` | — |
| Members of Disbanded Communities and Study Groups | 2022-12-16 | current | `1MEJCXAjzH5bJ9rP_h80N_F4oCYzFxxH9` | — |
| OCDS Ceremonial Scapular | 2022-12-16 | current | `1sLKor10xBqQ2ZMoAJwHtErL0Ca4e_Gzd` | verify — date not in filename; estimated from batch |
| Petitioning for Spiritual Assistant | 2022-12-16 | current | `1ZRwnNr-I5IJUaoAlooYGmV0UjAuLqoLN` | — |
| Records Management | 2022-12-16 | current | `1nzG_UN7nv6Vllc_2o3k_GPq4fdPMWwKm` | — |
| Use of Titles of Devotion | 2022-12-16 | current | `1PIoMPPtWGi7b1VlnkfRW24E7ymcKrsyW` | verify — date not in filename |
| Using the "OCDS" Designation | 2022-12-16 | current | `1myF1POfKFfplI39FbrTTAUuqoHUxaQCj` | — |
| **NORM**: Isolate Member | 2022-12-16 | current | `1yFFHZh5LRH6KQwC9wFqOlnaaAD_Zoi9X` | — |
| **NORM**: Leave of Absence | 2022-12-16 | current | `130te829bPUkagoJmMA1yBLHFN9MJAwtP` | — |
| **NORM**: Infirm Members in First Promise | 2022-12-16 | verify | `17OHwoeaj8XwmrJXBnK0gnThvuAp_Al4Q` | In older Drive folder only; not on province website — confirm still current |
| **NORM**: Readmission | 2022-12-16 | verify | `1nWJUIOJ9MbNVdtylTIPJWJkWouYT7Nbk` | In older Drive folder only; not on province website — confirm still current |

---

## Formation Handbooks (US Provinces)

Edition suffix in filename: `NN-YY` = issue number within year (NOT month-year). `02-24` = 2nd issue of 2024, effective March 1, 2024. `01-24` = 1st issue of 2024 (superseded).

| Document | Edition | Effective Date | Status | Drive File ID | Supersedes |
|----------|---------|----------------|--------|--------------|------------|
| OCDS Formation Handbook (USA) | 02-24 | 2024-03-01 | current | `1BMx0NKdnso9JkpKZCHrotL8qPxGrgSO-` | Supersedes 01-24; effective March 1, 2024 |
| Aspirancy Handbook | 02-24 | 2024-03-01 | current | `1o0BhRPm9achFv7282HFomD1th6tkpy5-` | Supersedes 01-24; effective March 1, 2024 |
| Formation I — Year A: Ways of Prayer | 02-24 | 2024-03-01 | current | `1TvawEad32nTeXWU4oyn50aVi0vyNwq5Y` | Supersedes 01-24; effective March 1, 2024 |
| Formation I — Year B: History & Charism | 02-24 | 2024-03-01 | current | `1yuW8FcNRP8hC_5yG2COvAELG2QNw4v8J` | Supersedes 01-24; effective March 1, 2024 |
| Formation II — Year A: [[jc-ccel-ascent|Ascent of Mt. Carmel]] | 02-24 | 2024-03-01 | current | `1gPOWO_eD6x5Xk6zwtoJS1i-omJQsbNG7` | Supersedes 01-24; effective March 1, 2024 |
| Formation II — Year B: [[tj-interior-castle-ccel|Interior Castle]] | 02-24 | 2024-03-01 | current | `1VE-zw3Vyl-0_o25mfhwdChhZjPHni696` | Supersedes 01-24; effective March 1, 2024 |
| Formation II — Year C: [[_tcj-soas-ccel|Story of a Soul]] | 02-24 | 2024-03-01 | current | `1U6sew4JcR5vfNuxLytZbepRNooyrz-7d` | Supersedes 01-24; effective March 1, 2024 |
| Ongoing Formation Vol. 1 (Definitives) | — | verify | current | `161z-MW_BL33P7rGK2y81OY8zIUu3akyJ` | No edition date in filename |
| Ongoing Formation Vol. 2 (Definitives) | — | verify | current | `1vN5KLbvFdKZEOpW3Gwa9FJsckAysw8Pv` | No edition date in filename |

---

## Local Community Policies (Austin OCDS)

| Document | Effective Date | Status | Drive File ID | Notes |
|----------|----------------|--------|--------------|-------|
| Austin OCDS Policy Manual | verify | current | `1Hr0YrAF9w71dEc_iZervPbXSeor8iRWr` | No date in filename — check inside document (approved 12/1/2021, updated 2023 and 2026 per plugin README) |
| Community Life & Attendance Policy | 2026-02-09 | current | `1PEzlhkDgECmtY2W0mRu_OZCXNs1zUnYa` | Supersedes earlier attendance policy |
| Absence Notifications Policy | 2025-10-07 | current | `16IRqNjnufbqd-yKUeakjHfGBRNIxgeGF` | — |

---

## Items Needing Verification

These need a date confirmed from inside the document or from the issuing body.

| Document | Question | Who to ask |
|----------|----------|------------|
| Provincial Statutes | Any updates since 2017 edition? | Semi-Province central office |
| Ratio Institutionis | Any updates at Order level post-2017? | OCD General Curia |
| NORM: Infirm Members in First Promise | Still current? Not on province website | Semi-Province central office |
| NORM: Readmission | Still current? Not on province website | Semi-Province central office |
| OCDS Formation Handbook (USA) | Is there a 02-24 edition? | US province formation office |
| Ongoing Formation Vol. 1 & 2 | What edition/year? | Check inside PDF |
| Austin OCDS Policy Manual | Exact effective date of current version | Council secretary |
