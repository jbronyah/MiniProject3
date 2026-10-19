# Disagreement Examples — jbronyah and kyandall

**Author / project owner:** Keoni Yandall (`kyandall`).  
**Validator:** Joseph Bronyah (`jbronyah`).

The initial review contained 14 disagreements across 50 project-field comparisons. The meeting outcomes resolve four ActivityPattern disagreements using the validator's labels and three WhyRecovered disagreements as differences in semantics. Seven RecentThemes disagreements remain unresolved in the supplied meeting log. The summaries below document the reported outcomes; the reconciled WhyRecovered descriptions summarize the shared interpretation rather than quoting a meeting transcript.

## Example 1 — mastoffel/rptR: WhyRecovered

**Project ID:** https://github.com/mastoffel/rptR  
**Parties:** Keoni Yandall (`kyandall`) and Joseph Bronyah (`jbronyah`).

- **Author value:** Maintenance resumed with bug fixes and feature work, although only nine commits occurred after the long gap.
- **Validator value:** Maintenance resumed to fix tibble-related overdispersion handling and update tests and documentation. The post-gap evidence does not establish new feature development.
- **Agreed value:** Limited maintenance resumed through tibble-related fixes, test updates and documentation work.
- **Resolution type:** Compromise
- **Post-discussion agreement:** Yes.

**Evidence considered:** 2024-09-20: 743e1f18c9 fixes tibble handling in rptProportion; 96ebe30fc4 fixes related rptPoisson handling; 005ee2cff7 replaces test assertions. README/license work follows, then documentation and CRAN-check fixes in April 2025. These support maintenance recovery, but not the author's additional claim of feature work.

**Resolution:** We treated the disagreement as a difference in semantics. The common wording describes the maintenance or development that resumed; it does not claim that the commit record proves a maintainer's underlying motivation.

## Example 2 — RaymanNg/3D-Wind-Field: WhyRecovered

**Project ID:** https://github.com/RaymanNg/3D-Wind-Field  
**Parties:** Keoni Yandall (`kyandall`) and Joseph Bronyah (`jbronyah`).

- **Author value:** The project briefly resumed with release and maintenance-related work, but only three commits followed the gap.
- **Validator value:** Compatibility maintenance resumed for CesiumJS 1.125 and WebGL2, with a Spector.js CDN repair and a later README update. No release event is shown in these three commits.
- **Agreed value:** Limited maintenance resumed through CesiumJS/WebGL2 compatibility updates, a CDN repair and documentation changes.
- **Resolution type:** Compromise
- **Post-discussion agreement:** Yes.

**Evidence considered:** 2025-01-21: 615f1220ba changes CesiumJS dependencies/CDN and compatibility code; 2025-01-23: ead08dd8b8 upgrades GLSL to WebGL2; 2025-06-18: ddbbca160c updates the README. "Release-related" work is not demonstrated by a release or release-preparation record.

**Resolution:** We treated the disagreement as a difference in semantics. The common wording describes the maintenance or development that resumed; it does not claim that the commit record proves a maintainer's underlying motivation.

## Example 3 — theislab/scib: WhyRecovered

**Project ID:** https://github.com/theislab/scib  
**Parties:** Keoni Yandall (`kyandall`) and Joseph Bronyah (`jbronyah`).

- **Author value:** Development resumed after the three-month pause, with seven commits following the gap in the collected data.
- **Validator value:** Dependency maintenance resumed by pinning anndata2ri. A more specific reason for returning is not stated.
- **Agreed value:** Development resumed with anndata2ri dependency maintenance after the May-July 2025 pause.
- **Resolution type:** Compromise
- **Post-discussion agreement:** Yes.

**Evidence considered:** The first exported post-gap record is 392998dc61, "pin anndata2ri", on 2025-08-29; PR #427 merges that pin on 2025-09-17. Only these two of the author's seven exported post-gap records precede 2025-10-01. The author's generic resumption statement does not identify the dependency-maintenance activity.

**Resolution:** We treated the disagreement as a difference in semantics. The common wording describes the maintenance or development that resumed; it does not claim that the commit record proves a maintainer's underlying motivation.

## Example 4 — ANTsX/ANTsR: ActivityPattern

**Project ID:** https://github.com/ANTsX/ANTsR  
**Parties:** Keoni Yandall (`kyandall`) and Joseph Bronyah (`jbronyah`).

- **Author value:** irregular
- **Validator value:** declining
- **Agreed value:** declining
- **Resolution type:** ValidatorKept
- **Post-discussion agreement:** Yes.

**Evidence considered:** Annual commits fall from 1,565 in 2015 to 455 in 2017, 146 in 2019, 24 in 2021 and 30 in 2023. Activity rebounds to 251 in 2024, but remains well below its earlier peak. I classify the overall trajectory as declining with a partial rebound, rather than irregular without a discernible trend.

**Resolution:** We retained the validator label after discussing the long-term trajectory, rather than treating short-term fluctuations or uninterrupted activity as sufficient evidence for the original label.

## Example 5 — shader-slang/slang: ActivityPattern

**Project ID:** https://github.com/shader-slang/slang  
**Parties:** Keoni Yandall (`kyandall`) and Joseph Bronyah (`jbronyah`).

- **Author value:** steady
- **Validator value:** rising
- **Agreed value:** rising
- **Resolution type:** ValidatorKept
- **Post-discussion agreement:** Yes.

**Evidence considered:** Annual totals rise from 1,212 in 2018 to 2,654 in 2022, 3,702 in 2023 and 6,870 in 2024. The monthly plot shows a substantially higher activity baseline in 2024-2025. Continuous activity is not the same as a steady commit rate.

**Resolution:** We retained the validator label after discussing the long-term trajectory, rather than treating short-term fluctuations or uninterrupted activity as sufficient evidence for the original label.

## Example 6 — theislab/scib: ActivityPattern

**Project ID:** https://github.com/theislab/scib  
**Parties:** Keoni Yandall (`kyandall`) and Joseph Bronyah (`jbronyah`).

- **Author value:** irregular
- **Validator value:** declining
- **Agreed value:** declining
- **Resolution type:** ValidatorKept
- **Post-discussion agreement:** Yes.

**Evidence considered:** Annual totals decline from 992 in 2020 to 297 in 2021, 314 in 2022 and 75 in 2023; the modest rise to 125 in 2024 remains far below the early peak. The 2025 May-July gap accompanies a low recent baseline. Long-term decline is more informative than irregular.

**Resolution:** We retained the validator label after discussing the long-term trajectory, rather than treating short-term fluctuations or uninterrupted activity as sufficient evidence for the original label.

## Example 7 — WorldWideTelescope/wwt-web-client: ActivityPattern

**Project ID:** https://github.com/WorldWideTelescope/wwt-web-client  
**Parties:** Keoni Yandall (`kyandall`) and Joseph Bronyah (`jbronyah`).

- **Author value:** irregular
- **Validator value:** declining
- **Agreed value:** declining
- **Resolution type:** ValidatorKept
- **Post-discussion agreement:** Yes.

**Evidence considered:** Complete-year totals rise to 322 in 2020, then fall to 30 in 2021, 29 in 2022 and 20 in 2023; 2024 has zero and 2025 only nine exported records. The post-2020 decline is clear despite earlier bursts and limited recovery.

**Resolution:** We retained the validator label after discussing the long-term trajectory, rather than treating short-term fluctuations or uninterrupted activity as sufficient evidence for the original label.

## Disagreements still open

These seven records retain their original author and validator values. Their adjudicated values are blank, their post-discussion agreement is No, and their resolution type is NA because no resolution has been recorded. They are included in the resolution CSV so that no original disagreement is omitted.

| Project | Author themes | Validator themes |
| --- | --- | --- |

| conda-forge/pyinterp-feedstock | Other:Dependency updates | Automated bot contributions:Dependency updates |

| kick-h/GPUMD | Other:Bug fixes | Feature development:Other |

| RaymanNg/3D-Wind-Field | Other:Bug fixes | Documentation updates:Dependency updates |

| shader-slang/slang | Other:Feature development | Bug fixes:Other |

| theislab/scib | Other:Dependency updates | Bug fixes:Dependency updates |

| UCL/mimix | Other:Documentation updates | Bug fixes:Other |

| WorldWideTelescope/wwt-web-client | Automated bot contributions:Other | Other:Bug fixes |

