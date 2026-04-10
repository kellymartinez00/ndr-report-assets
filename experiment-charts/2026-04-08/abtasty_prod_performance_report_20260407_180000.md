# ABTasty Web — Production Performance Report

**Generated:** April 7, 2026
**Window:** March 31 – April 7, 2026 (7 days)

---

## [EXP-260313] Spanish Apply P1 All: Hispanic Testimonials

**Campaign ID:** 1605542
**Status:** Live since Mar 31
**Experiment Type:** A/B Test
**Target URL:** `https://start.nationaldebtrelief.com/apply/es`
**Device Targeting:** Responsive, Custom 400x900
**Traffic:** 100% (50/50 split)

### Forced Preview URLs

| Variation | ID | Preview URL |
|---|---|---|
| Original | `0` | `https://apply-beta.pe.nationaldebtrelief.com/apply/es?ndr_preview_abt=1&ndr_preview_test=1605542&ndr_preview_var=0` |
| ES Testimonials | `2003230` | `https://apply-beta.pe.nationaldebtrelief.com/apply/es?ndr_preview_abt=1&ndr_preview_test=1605542&ndr_preview_var=ES%20Testimonials` |
| Split Ctrl | `2005572` | `https://apply-beta.pe.nationaldebtrelief.com/apply/es?ndr_preview_abt=1&ndr_preview_test=1605542&ndr_preview_var=Split%20Ctrl` |

### Executive Summary

| Metric | ES Testimonials | Split Ctrl | Delta | Lift |
|---|---|---|---|---|
| Unique Users Exposed | 79,899 | 80,673 | — | — |
| Lead Form Submission | 2,935 | 2,974 | -39 | -1.3% |
| Lead Form CVR | 3.67% | 3.69% | -0.02pp | -0.5% |
| Credit Pulled | 574 | 569 | +5 | +0.9% |
| Credit Pulled CVR | 0.72% | 0.71% | +0.01pp | +1.4% |
| Debt Dropdown Selected | 6,113 | 6,115 | -2 | ~0% |
| Engagement Rate | 7.65% | 7.58% | +0.07pp | +0.9% |

**Verdict:** Inconclusive — no meaningful lift on primary KPI (Lead Form Submission). Both arms performing nearly identically after 7 days with strong sample size (N > 79K per arm).

![Spanish Testimonials Performance](https://raw.githubusercontent.com/kellymartinez00/ndr-report-assets/main/experiment-charts/2026-04-08/exp-260313-spanish-testimonials-branded.png)

### Conversion Funnel

| Event | ES Testimonials | Split Ctrl | ES CVR | Ctrl CVR | Delta |
|---|---|---|---|---|---|
| Exposure (assigned) | 79,899 | 80,673 | — | — | — |
| Debt Dropdown Selected | 6,113 | 6,115 | 7.65% | 7.58% | +0.07pp |
| PII Form Page View (P2) | 56 | 62 | 0.07% | 0.08% | -0.01pp |
| Lead Form Submission | 2,935 | 2,974 | 3.67% | 3.69% | -0.02pp |
| Credit Pulled | 574 | 569 | 0.72% | 0.71% | +0.01pp |
| Credit Pulled Qualified | 572 | 567 | 0.72% | 0.70% | +0.02pp |
| Ext App Quote Conversion | 574 | 569 | 0.72% | 0.71% | +0.01pp |
| lead_submitted_10k_plus | 4,859 | 4,834 | 6.08% | 5.99% | +0.09pp |

### Device Breakdown (total sessions)

| Device | ES Testimonials Sessions | Split Ctrl Sessions | ES % | Ctrl % |
|---|---|---|---|---|
| Mobile | 77,781 | 78,614 | 97.3% | 97.4% |
| Desktop | 939 | 967 | 1.2% | 1.2% |
| Tablet | 1,230 | 1,146 | 1.5% | 1.4% |

Traffic is overwhelmingly mobile (97%+). This is expected for the `/apply/es` Spanish-language entry targeting Hispanic audiences via mobile-heavy ad channels.

### Device × Lead Form Submission

| Device | ES Testimonials Leads | ES CVR | Split Ctrl Leads | Ctrl CVR |
|---|---|---|---|---|
| Mobile | 2,899 | 3.73% | 2,940 | 3.74% |
| Desktop | 15 | 1.60% | 16 | 1.65% |
| Tablet | 21 | 1.71% | 18 | 1.57% |

Mobile lead submission rates are nearly identical. Desktop sample is too small (N < 1K) for signal.

### Recommendation

**Hold** — No statistically significant difference between ES Testimonials and Split Control. With 160K+ total unique users, if there were a meaningful lift it would have surfaced by now. Consider shutting down to free traffic for new tests, or extending to 14 days for final confirmation.

---

## [EXP-260402] Apply All P1: Caveman Question Headline

**Campaign ID:** 1609832
**Status:** Live since Apr 6
**Experiment Type:** A/B Test
**Target URL:** `https://start.nationaldebtrelief.com/apply`
**Device Targeting:** Responsive, Custom 390x900
**Audience:** `7053afff-9e5b-48ae-81eb-0415ba5ca32e`
**Traffic:** 100% (25% per variation, 4 arms)

### Forced Preview URLs

| Variation | ID | Preview URL |
|---|---|---|
| Original | `0` | `https://apply-beta.pe.nationaldebtrelief.com/apply?ndr_preview_abt=1&ndr_preview_test=1609832&ndr_preview_var=0` |
| Split Control | `2008794` | `https://apply-beta.pe.nationaldebtrelief.com/apply?ndr_preview_abt=1&ndr_preview_test=1609832&ndr_preview_var=Split%20Control` |
| Need H1 | `2008798` | `https://apply-beta.pe.nationaldebtrelief.com/apply?ndr_preview_abt=1&ndr_preview_test=1609832&ndr_preview_var=Need%20H1` |
| Want H1 | `2008800` | `https://apply-beta.pe.nationaldebtrelief.com/apply?ndr_preview_abt=1&ndr_preview_test=1609832&ndr_preview_var=Want%20H1` |
| Seeking H1 | `2008801` | `https://apply-beta.pe.nationaldebtrelief.com/apply?ndr_preview_abt=1&ndr_preview_test=1609832&ndr_preview_var=Seeking%20H1` |

### Executive Summary

| Metric | Split Control | Need H1 | Want H1 | Seeking H1 |
|---|---|---|---|---|
| Unique Users Exposed | 21,741 | 22,218 | 21,693 | 21,969 |
| Lead Form Submission | 2,257 | 2,335 | 2,291 | 2,270 |
| Lead Form CVR | 10.38% | 10.51% | 10.56% | 10.34% |
| Credit Pulled | 746 | 843 | 797 | 777 |
| Credit Pulled CVR | 3.43% | 3.79% | 3.67% | 3.54% |
| Debt Dropdown Selected | 3,924 | 4,108 | 3,962 | 3,920 |
| Engagement Rate | 18.05% | 18.49% | 18.26% | 17.85% |

### CVR Lift vs Split Control

| Variation | Lead Form CVR | Lift (abs) | Lift (rel) | Credit Pulled CVR | CP Lift |
|---|---|---|---|---|---|
| Split Control | 10.38% | — | — | 3.43% | — |
| Need H1 | 10.51% | +0.13pp | +1.3% | 3.79% | +10.5% |
| Want H1 | 10.56% | +0.18pp | +1.7% | 3.67% | +7.0% |
| Seeking H1 | 10.34% | -0.04pp | -0.4% | 3.54% | +3.2% |

**Verdict:** Early signal — Want H1 shows slight lead form CVR lift (+1.7% relative) and Need H1 leads on Credit Pulled (+10.5% relative). Sample size (~22K per arm) is adequate but experiment only has ~1 day of data. Too early to call.

![Caveman Headline Performance](https://raw.githubusercontent.com/kellymartinez00/ndr-report-assets/main/experiment-charts/2026-04-08/exp-260402-caveman-headline-branded.png)

### Conversion Funnel

| Event | Split Control | Need H1 | Want H1 | Seeking H1 |
|---|---|---|---|---|
| Exposure | 21,741 | 22,218 | 21,693 | 21,969 |
| Debt Dropdown Selected | 3,924 (18.05%) | 4,108 (18.49%) | 3,962 (18.26%) | 3,920 (17.85%) |
| PII Form Page View (P2) | 3,164 (14.55%) | 3,284 (14.78%) | 3,220 (14.84%) | 3,177 (14.46%) |
| Lead Form Submission | 2,257 (10.38%) | 2,335 (10.51%) | 2,291 (10.56%) | 2,270 (10.34%) |
| Credit Pulled | 746 (3.43%) | 843 (3.79%) | 797 (3.67%) | 777 (3.54%) |
| lead_submitted_10k_plus | 3,045 (14.01%) | 3,181 (14.32%) | 3,106 (14.32%) | 2,992 (13.62%) |

### Device Breakdown (total sessions)

| Device | Split Control | Need H1 | Want H1 | Seeking H1 |
|---|---|---|---|---|
| Mobile | 17,388 (79.9%) | 17,728 (79.8%) | 17,296 (79.7%) | 17,693 (80.5%) |
| Desktop | 4,141 (19.0%) | 4,206 (18.9%) | 4,169 (19.2%) | 4,049 (18.4%) |
| Tablet | 221 (1.0%) | 292 (1.3%) | 234 (1.1%) | 236 (1.1%) |

Traffic split is ~80% mobile / 19% desktop — typical for the main `/apply` page.

### Recommendation

**Iterate** — Continue for at least 7 full days. Want H1 and Need H1 show marginally positive signals on lead form CVR. Need H1 shows a notably stronger Credit Pulled rate (+10.5% vs control). Monitor daily to watch for convergence or divergence.

---

## [EXP-260403] Apply Loan P1 GGL All: Monthly Payment CTA

**Campaign ID:** 1609834
**Status:** Live since Apr 6
**Experiment Type:** A/B Test
**Target URL:** `https://start.nationaldebtrelief.com/apply-loan`
**Device Targeting:** Responsive, Custom 400x900
**Audience:** `c6de0955-f455-41b2-8e41-f6fee42abac6`
**Traffic:** 99% (33/33/33, Original at 1%)

### Forced Preview URLs

| Variation | ID | Preview URL |
|---|---|---|
| Original | `0` | `https://apply-beta.pe.nationaldebtrelief.com/apply-loan?ndr_preview_abt=1&ndr_preview_test=1609834&ndr_preview_var=0` |
| Split Control | `2008807` | `https://apply-beta.pe.nationaldebtrelief.com/apply-loan?ndr_preview_abt=1&ndr_preview_test=1609834&ndr_preview_var=Split%20Control` |
| Double Control | `2008808` | `https://apply-beta.pe.nationaldebtrelief.com/apply-loan?ndr_preview_abt=1&ndr_preview_test=1609834&ndr_preview_var=Double%20Control` |
| Estimate My MoPay CTA | `2008809` | `https://apply-beta.pe.nationaldebtrelief.com/apply-loan?ndr_preview_abt=1&ndr_preview_test=1609834&ndr_preview_var=Estimate%20My%20MoPay%20CTA` |
| Get A MoPay CTA | `2008810` | `https://apply-beta.pe.nationaldebtrelief.com/apply-loan?ndr_preview_abt=1&ndr_preview_test=1609834&ndr_preview_var=Get%20A%20MoPay%20CTA` |

### Executive Summary

| Metric | Original (1%) | Split Control | Double Control | Estimate MoPay CTA | Get A MoPay CTA |
|---|---|---|---|---|---|
| Unique Users | 320 | 12,611 | 12,692 | 12,917 | 1,207 |
| Lead Form Submission | 54 | 2,268 | 2,176 | 2,329 | 198 |
| Lead Form CVR | 16.88% | 17.99% | 17.15% | 18.03% | 16.40% |
| Credit Pulled | 23 | 746 | 724 | 796 | 63 |
| Credit Pulled CVR | 7.19% | 5.92% | 5.70% | 6.16% | 5.22% |

### CVR Lift vs Split Control

| Variation | Lead Form CVR | Lift (abs) | Lift (rel) | Credit Pulled CVR | CP Lift |
|---|---|---|---|---|---|
| Split Control | 17.99% | — | — | 5.92% | — |
| Double Control | 17.15% | -0.84pp | -4.7% | 5.70% | -3.7% |
| Estimate My MoPay CTA | 18.03% | +0.04pp | +0.2% | 6.16% | +4.1% |
| Get A MoPay CTA | 16.40% | -1.59pp | -8.8% | 5.22% | -11.8% |

**Verdict:** Early signal — Estimate My MoPay CTA matches Split Control on lead form CVR and leads on Credit Pulled (+4.1%). Get A MoPay CTA underperforms (-8.8% lead form). Only ~1 day of data.

![Monthly Payment CTA Performance](https://raw.githubusercontent.com/kellymartinez00/ndr-report-assets/main/experiment-charts/2026-04-08/exp-260403-monthly-payment-cta-branded.png)

### Conversion Funnel

| Event | Split Control | Double Control | Estimate MoPay | Get A MoPay |
|---|---|---|---|---|
| Exposure | 12,611 | 12,692 | 12,917 | 1,207 |
| Debt Dropdown Selected | 4,073 (32.30%) | 3,985 (31.40%) | 4,210 (32.59%) | 369 (30.57%) |
| PII Form Page View (P2) | 3,028 (24.01%) | 3,008 (23.70%) | 3,297 (25.53%) | 288 (23.86%) |
| Lead Form Submission | 2,268 (17.99%) | 2,176 (17.15%) | 2,329 (18.03%) | 198 (16.40%) |
| Credit Pulled | 746 (5.92%) | 724 (5.70%) | 796 (6.16%) | 63 (5.22%) |
| lead_submitted_10k_plus | 2,936 (23.28%) | 2,813 (22.16%) | 3,054 (23.64%) | 267 (22.12%) |

### Device Breakdown (total sessions)

| Device | Split Control | Double Control | Estimate MoPay | Get A MoPay |
|---|---|---|---|---|
| Mobile | 10,854 (86.1%) | 11,026 (86.8%) | 11,170 (86.5%) | 1,052 (87.1%) |
| Desktop | 1,594 (12.6%) | 1,520 (12.0%) | 1,602 (12.4%) | 130 (10.8%) |
| Tablet | 178 (1.4%) | 156 (1.2%) | 154 (1.2%) | 27 (2.2%) |

Traffic is ~86% mobile — the `apply-loan` page via Google receives heavy mobile ad traffic.

### Recommendation

**Iterate** — Continue for 7+ days. Estimate My MoPay CTA shows consistent micro-lifts across the entire funnel (Debt Dropdown → PII → Lead Form → Credit Pulled). Get A MoPay CTA consistently underperforms — consider disabling this arm (0% traffic) to redistribute volume.

---

## [EXP-260311] Apply P1 Forbes All: Apply Loan Style

**Campaign ID:** 1606097
**Status:** Live since Mar 27
**Experiment Type:** A/B Test
**Target URL:** `https://start.nationaldebtrelief.com/apply?src=forbes.SEM`
**Device Targeting:** Responsive, Custom 550x900
**Audience:** `9184c887-3f57-4a9d-b845-934b79df8858` (Forbes SEM)
**Traffic:** 99% (33/33/33, Original at 1%)

### Forced Preview URLs

| Variation | ID | Preview URL |
|---|---|---|
| Original | `0` | `https://apply-beta.pe.nationaldebtrelief.com/apply?ndr_preview_abt=1&ndr_preview_test=1606097&ndr_preview_var=0` |
| Split Control | `2004021` | `https://apply-beta.pe.nationaldebtrelief.com/apply?ndr_preview_abt=1&ndr_preview_test=1606097&ndr_preview_var=Split%20Control` |
| ApplyLoan Style BTF | `2004024` | `https://apply-beta.pe.nationaldebtrelief.com/apply?ndr_preview_abt=1&ndr_preview_test=1606097&ndr_preview_var=ApplyLoan%20Style%20BTF` |
| Full ApplyLoan Style | `2004025` | `https://apply-beta.pe.nationaldebtrelief.com/apply?ndr_preview_abt=1&ndr_preview_test=1606097&ndr_preview_var=Full%20ApplyLoan%20Style` |

### Executive Summary

| Metric | Original (1%) | Split Control | ApplyLoan BTF | Full ApplyLoan |
|---|---|---|---|---|
| Unique Users | 113 | 3,514 | 3,500 | 3,629 |
| Lead Form Submission | 44 | 1,151 | 1,167 | 1,262 |
| Lead Form CVR | 38.94% | 32.75% | 33.34% | 34.77% |
| Credit Pulled | 17 | 464 | 401 | 468 |
| Credit Pulled CVR | 15.04% | 13.20% | 11.46% | 12.90% |

### CVR Lift vs Split Control

| Variation | Lead Form CVR | Lift (abs) | Lift (rel) | Credit Pulled CVR | CP Lift |
|---|---|---|---|---|---|
| Split Control | 32.75% | — | — | 13.20% | — |
| ApplyLoan Style BTF | 33.34% | +0.59pp | +1.8% | 11.46% | -13.2% |
| Full ApplyLoan Style | 34.77% | +2.02pp | +6.2% | 12.90% | -2.3% |

**Verdict:** Promising — Full ApplyLoan Style shows a +6.2% relative lift on Lead Form Submission with adequate sample size (~3.5K per arm over 11 days). However, Credit Pulled is slightly lower. N > 100 per arm meets minimum confidence threshold.

![Forbes ApplyLoan Performance](https://raw.githubusercontent.com/kellymartinez00/ndr-report-assets/main/experiment-charts/2026-04-08/exp-260311-forbes-applyloan-branded.png)

### Conversion Funnel

| Event | Split Control | ApplyLoan BTF | Full ApplyLoan |
|---|---|---|---|
| Exposure | 3,514 | 3,500 | 3,629 |
| Debt Dropdown Selected | 1,867 (53.13%) | 1,938 (55.37%) | 2,056 (56.64%) |
| PII Form Page View (P2) | 1,472 (41.89%) | 1,559 (44.54%) | 1,643 (45.27%) |
| Lead Form Submission | 1,151 (32.75%) | 1,167 (33.34%) | 1,262 (34.77%) |
| Credit Pulled | 464 (13.20%) | 401 (11.46%) | 468 (12.90%) |
| lead_submitted_10k_plus | 1,413 (40.21%) | 1,449 (41.40%) | 1,556 (42.87%) |

Full ApplyLoan Style outperforms at every stage of the funnel — from Debt Dropdown engagement through to lead submission and 10k+ qualified leads.

### Device Breakdown (total sessions)

| Device | Split Control | ApplyLoan BTF | Full ApplyLoan |
|---|---|---|---|
| Mobile | 2,862 (81.4%) | 2,860 (81.6%) | 2,936 (80.9%) |
| Desktop | 611 (17.4%) | 596 (17.0%) | 651 (17.9%) |
| Tablet | 43 (1.2%) | 49 (1.4%) | 45 (1.2%) |

Audience comes from `src=forbes.SEM` — 81% mobile typical for SEM landing.

### Recommendation

**Ship candidate** — Full ApplyLoan Style shows consistent lift across the entire funnel (+6.2% lead form, +2.7% lead_submitted_10k_plus). The Credit Pulled dip is marginal (-2.3%) and may normalize. With 11 days of data and 3.5K+ users per arm, this is approaching statistical significance. Recommend extending 3-5 more days for final confirmation before shipping at 100%.

---

## [EXP-260310] Apply P1 LinTV All: Min Eff Dose Land

**Campaign ID:** 1606131
**Status:** Live since Mar 28
**Experiment Type:** A/B Test
**Target URL:** `https://start.nationaldebtrelief.com/apply`
**Device Targeting:** Responsive, Custom 400x900
**Audience:** `963e5cce-0ee4-4fda-b884-6790a13ca07c` (LinTV segment)
**Traffic:** 100% (50/50 on active arms)

### Forced Preview URLs

| Variation | ID | Preview URL |
|---|---|---|
| Original | `0` | `https://apply-beta.pe.nationaldebtrelief.com/apply?ndr_preview_abt=1&ndr_preview_test=1606131&ndr_preview_var=0` |
| Split Control | `2004074` | `https://apply-beta.pe.nationaldebtrelief.com/apply?ndr_preview_abt=1&ndr_preview_test=1606131&ndr_preview_var=Split%20Control` |
| Double Control | `2004075` | `https://apply-beta.pe.nationaldebtrelief.com/apply?ndr_preview_abt=1&ndr_preview_test=1606131&ndr_preview_var=Double%20Control` |
| MinEffDose | `2004076` | `https://apply-beta.pe.nationaldebtrelief.com/apply?ndr_preview_abt=1&ndr_preview_test=1606131&ndr_preview_var=MinEffDose` |

### Executive Summary

| Metric | Double Control | MinEffDose | Delta | Lift |
|---|---|---|---|---|
| Unique Users | 116 | 154 | — | — |
| Lead Form Submission | 15 | 28 | +13 | +86.7% |
| Lead Form CVR | 12.93% | 18.18% | +5.25pp | +40.6% |
| Credit Pulled | 11 | 14 | +3 | +27.3% |
| Credit Pulled CVR | 9.48% | 9.09% | -0.39pp | -4.1% |

**Verdict:** Insufficient sample — Only 270 total unique users across both arms. The +40.6% lift on lead form CVR is eye-catching but unreliable at this sample size (N=116 and N=154). This audience segment (LinTV) has very low volume. Need 500+ per arm for minimum confidence.

![LinTV MinEffDose Performance](https://raw.githubusercontent.com/kellymartinez00/ndr-report-assets/main/experiment-charts/2026-04-08/exp-260310-lintv-mineffdose-branded.png)

### Conversion Funnel

| Event | Double Control | MinEffDose |
|---|---|---|
| Exposure | 116 | 154 |
| Debt Dropdown Selected | 36 (31.03%) | 55 (35.71%) |
| PII Form Page View (P2) | 30 (25.86%) | 50 (32.47%) |
| Lead Form Submission | 15 (12.93%) | 28 (18.18%) |
| Credit Pulled | 11 (9.48%) | 14 (9.09%) |
| lead_submitted_10k_plus | 30 (25.86%) | 48 (31.17%) |

### Device Breakdown (total sessions)

| Device | Double Control | MinEffDose |
|---|---|---|
| Mobile | 98 (84.5%) | 131 (85.1%) |
| Desktop | 16 (13.8%) | 18 (11.7%) |
| Tablet | 2 (1.7%) | 5 (3.2%) |

### Recommendation

**Hold** — Sample size insufficient for any conclusion. LinTV audience segment generates very low volume (~270 users in 10 days). Either accept a longer time horizon (30+ days) or combine with a higher-traffic segment to gather sufficient data.

---

## Cross-Experiment Summary

![ABTasty Web CVR Leaderboard](https://raw.githubusercontent.com/kellymartinez00/ndr-report-assets/main/experiment-charts/2026-04-08/abtasty-web-cvr-leaderboard-branded.png)

### Lead Form Submission CVR Leaderboard (primary KPI)

| Experiment | Best Variation | CVR | vs Control | Confidence | Verdict |
|---|---|---|---|---|---|
| [EXP-260311] Forbes Apply Loan Style | Full ApplyLoan Style | 34.77% | +6.2% | Moderate (N=3.6K) | Ship candidate |
| [EXP-260403] Monthly Payment CTA | Estimate My MoPay CTA | 18.03% | +0.2% | Low (1 day) | Iterate |
| [EXP-260310] LinTV Min Eff Dose | MinEffDose | 18.18% | +40.6% | Very Low (N=154) | Hold |
| [EXP-260402] Caveman Headline | Want H1 | 10.56% | +1.7% | Low (1 day) | Iterate |
| [EXP-260313] Spanish Testimonials | ES Testimonials | 3.67% | -0.5% | High (N=80K) | Hold/Stop |

