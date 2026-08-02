<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://capsule-render.vercel.app/api?type=waving&color=0:16324a,100:21759b&height=120&section=header&text=Omar%20El-Hawary&fontSize=36&fontColor=ffffff&fontAlignY=65">
  <img alt="Omar El-Hawary — applied AI: evals, RAG, knowledge systems" src="https://capsule-render.vercel.app/api?type=waving&color=0:e8f4f8,100:21759b&height=120&section=header&text=Omar%20El-Hawary&fontSize=36&fontColor=1a1a2e&fontAlignY=65" width="100%">
</picture>

**Applied AI — evals, RAG, knowledge systems**

I work in applied AI at Caseproof: I own the content quality of the curated knowledge base behind an AI advisor product — knowledge curation, retrieval grounding, and evals. The foundation is 10K+ support tickets, escalated to Tier 3 for the ones nobody else could solve, which taught me to tell a plausible answer from a correct one. That turns out to be most of the job. The tools I shipped along the way live here.

[![Website](https://img.shields.io/badge/omarelhawary.com-FF5722?style=flat-square&logo=google-chrome&logoColor=white)](https://omarelhawary.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/omaraelhawary/)
[![WordPress](https://img.shields.io/badge/WordPress.org-21759b?style=flat-square&logo=wordpress&logoColor=white)](https://profiles.wordpress.org/omarelhawary/)

---

<table>
<tr>
<td width="55%" valign="top">

### About

**AI Knowledge Engineer** on **Caseproof**'s AI team, working on MembersIntel — a Claude-powered advisor for MemberPress operators. I own answer quality end to end: the curated knowledge it draws on, the retrieval that grounds it in a customer's real data, and the shipped fixes when an answer comes out confident and wrong. The route in: four years at the same company on MemberPress support, the last two at Tier 3 — the highest escalation level, across subscription lifecycle failures, payment gateway conflicts, REST APIs, and platform-critical bugs.

**10K+ support tickets · 18 public five-star Trustpilot reviews · Remote across US, UAE, Egypt & Europe**

</td>
<td width="45%" valign="top">

### Currently

- Retrieval grounding, citation integrity, and evals on a production AI advisor
- Writing about the move from support engineering into applied AI — [start here](https://omarelhawary.com/blog/from-support-tickets-to-evals)
- Maintaining open-source contributions to **MemberPress** and **Members** (300,000+ active installs)
- Open to applied AI engineering roles — evals, retrieval, agent tooling, knowledge systems

</td>
</tr>
</table>

---

## Open source contributions

### [Members](https://github.com/caseproof/members) — by Caseproof · 300,000+ active installs

The leading WordPress User Roles & Capabilities plugin. I contribute directly to the codebase:

| Contribution | Status |
|---|---|
| [Admin Menus add-on (+8k lines)](https://github.com/caseproof/members/pulls?q=is%3Apr+author%3Aomaraelhawary) | Open PR |
| [Rescue Link for Administrator Role Recovery](https://github.com/caseproof/members/commit/7e3192bfeee8ea89de516c8ac6577c1c4f4b76ae) | Merged |
| [Import / Export Roles](https://github.com/caseproof/members/commit/d05e061d6ef0ee3ccd19febbc91294013d4e4b59) | Merged |
| [Reset Roles](https://github.com/caseproof/members/commit/e5054aac3d065b86866af7e4cb6c324f5d9f4b40) | Merged |
| [Allow Changing Display Name for Roles](https://github.com/caseproof/members/commit/543e875b659d2d22c8a47a781e7e5b07b524c1bf) | Merged |

---

## Published on WordPress.org

<table>
<tr>
<td width="50%" valign="top">

### [Admin Filters for MemberPress](https://wordpress.org/plugins/admin-filters-for-memberpress/)

[![WordPress.org](https://img.shields.io/badge/View-21759b?style=flat-square&logo=wordpress&logoColor=white)](https://wordpress.org/plugins/admin-filters-for-memberpress/)

Built after repeatedly hitting the limits of MemberPress's native admin filtering while resolving escalated tickets. Adds advanced filtering across Members, Transactions, and Subscriptions — turning a recurring support pain point into a maintained, public tool.

</td>
<td width="50%" valign="top">

### [Gift Reporter for MemberPress](https://wordpress.org/plugins/memberpress-gift-reporter/)

[![WordPress.org](https://img.shields.io/badge/View-21759b?style=flat-square&logo=wordpress&logoColor=white)](https://wordpress.org/plugins/memberpress-gift-reporter/)
[![GitHub](https://img.shields.io/badge/Source-black?style=flat-square&logo=github)](https://github.com/omaraelhawary/gift-reporter-for-memberpress)

Identified a reporting gap around Gift memberships while resolving escalated issues. Designed a scalable solution and published it — advanced gift reporting, scheduled reminders, weekly summary automation, and exportable data.

</td>
</tr>
</table>

---

## MemberPress ecosystem tools

Every tool here started as a real production problem from an escalated ticket.

<table>
<tr>
<td width="50%" valign="top">

**[⏩ Forward-Only Access](https://github.com/omaraelhawary/memberpress-forward-only)**
Restricts members from accessing content published before their membership start date. Configurable per rule, supports exclusions, wp-config overrides, a shortcode, and PHP helpers. **Ships with a PHPUnit test suite.**

</td>
<td width="50%" valign="top">

**[🔒 Personal Content](https://github.com/omaraelhawary/memberpress-personal-content)**
Adds a My Content tab to the MemberPress account page — per-member Wistia video links, file links, and personal notes, delivered without theme modifications.

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[🎁 Hide Claim Fields for Gifting](https://github.com/omaraelhawary/hide-claim-fields-for-memberpress-gifting)**
Per-field toggle controlling which fields gift recipients see during claim flows and on their account page. Suppresses validation on hidden fields so claim flows are never blocked.

</td>
<td width="50%" valign="top">

**[🏢 Hide Corporate Fields](https://github.com/omaraelhawary/corporate-hide-fields-memberpress)**
Per-field toggle controlling which fields corporate sub-accounts see on signup and account pages. Works with classic UI and ReadyLaunch.

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[🧾 PDF Invoice Generator](https://github.com/omaraelhawary/pdf-invoice-generator-for-memberpress)**
Generates structured, downloadable PDF invoices tied to MemberPress transactions — built for compliance-ready billing workflows.

</td>
<td width="50%" valign="top">

**[🧯 Staging Safe Mode for MemberPress](https://github.com/omaraelhawary/staging-safe-mode-memberpress)**
MemberPress staging safeguards — block MP-related mail, pause reminders, sandbox gateways at read time, optional dev-tools unload, force non-production, one-time staging notice.

</td>
</tr>
</table>

---

## Background

**AI Knowledge Engineer** · Caseproof (MembersIntel) · Jul 2026 – Present<br>
**Tier 3 Support Engineer** · Caseproof (MemberPress) · May 2024 – Jul 2026<br>
**WordPress Support Engineer** · Caseproof (MemberPress) · Sep 2022 – Apr 2024<br>
**WordPress Technical Consultant / Lead Developer** · SwiftX · Mar 2023 – Present<br>
**WordPress Developer** · Leap13 / LeapWorx · Jun 2020 – Aug 2022

**Core areas:** LLM evals · RAG grounding · Knowledge curation · Subscription lifecycle · Stripe/PayPal gateway conflicts · WordPress REST API · Access control architecture · WP-Cron async processing · Multi-environment debugging · Caching & performance

---

> [!TIP]
> Available for consulting and freelance work. [Let's connect →](https://www.linkedin.com/in/omaraelhawary/)
