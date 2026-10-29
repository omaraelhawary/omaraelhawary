<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/banner-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="./assets/banner-light.svg">
  <img alt="Omar ElHawary. I build and evaluate the knowledge layer behind AI." src="./assets/banner-dark.svg" width="100%">
</picture>

**Applied AI Engineer / Forward Deployed Engineer.** I own answer quality for a Claude-powered advisor for membership-site operators at [Caseproof](https://caseproof.com): the curated knowledge it draws on, the retrieval that grounds it in customer data, and the evals that catch confident wrong answers before users do. Four years of MemberPress support, two of them at Tier 3, taught me how answers go wrong.

[![Website](https://img.shields.io/badge/site-omarelhawary.com-C8F135?style=flat-square&labelColor=0B0C0A)](https://omarelhawary.com)
[![LinkedIn](https://img.shields.io/badge/linkedin-omaraelhawary-C8F135?style=flat-square&labelColor=0B0C0A)](https://www.linkedin.com/in/omaraelhawary/)
[![WordPress.org](https://img.shields.io/badge/wordpress.org-omarelhawary-C8F135?style=flat-square&labelColor=0B0C0A)](https://profiles.wordpress.org/omarelhawary/)
[![Open to work](https://img.shields.io/badge/open_to-applied_AI_work-0B0C0A?style=flat-square&labelColor=C8F135)](https://omarelhawary.com/#contact)

---

### Selected work

| | What I found | What I shipped |
|---|---|---|
| **"Cited" wasn't measuring citation** | Citation counts tracked what retrieval included, not what answers used | A retrieval-event log and nightly per-entry rollups |
| **Citation integrity** | Invented bracket tokens leaking into advisor answers | A narrower prompt, a strip layer and a grounding eval |
| **Refusing a false zero** | The advisor reported $0 revenue when the data didn't exist | Platform-level revenue-coverage logic |

Case studies: [omarelhawary.com/#work](https://omarelhawary.com/#work)

### Open source: applied AI

**[agent-memory](https://github.com/omaraelhawary/agent-memory)**: a file-based memory layer that lets AI coding agents keep context across sessions. [Write-up](https://omarelhawary.com/blog/the-memory-system-behind-my-ai-workflow)

**[ai-tell-lint](https://github.com/omaraelhawary/ai-tell-lint)**: a linter that flags stock AI phrasing in commit messages and PR bodies. Ships as a Claude Code plugin, a CLI and a [GitHub Action](https://github.com/marketplace/actions/ai-tell-lint). [Write-up](https://omarelhawary.com/blog/ai-tell-lint-a-linter-for-machine-sounding-prose)

```yaml
- uses: omaraelhawary/ai-tell-lint@v1
```

### Open source: WordPress

**[Members](https://github.com/caseproof/members)** (300,000+ active installs): [my contributions](https://github.com/caseproof/members/pulls?q=is%3Apr%20author%3Aomaraelhawary), including the [Administrator Rescue Link](https://omarelhawary.com/blog/administrator-rescue-link-members-plugin) and [Selective Role Reset](https://omarelhawary.com/blog/selective-role-reset-members-plugin).

**On WordPress.org:** [Admin Filters for MemberPress](https://wordpress.org/plugins/admin-filters-for-memberpress/) · [Gift Reporter for MemberPress](https://wordpress.org/plugins/memberpress-gift-reporter/) ([source](https://github.com/omaraelhawary/gift-reporter-for-memberpress))

<details>
<summary><b>More MemberPress tools</b></summary>
<br>

- [staging-safe-mode-memberpress](https://github.com/omaraelhawary/staging-safe-mode-memberpress): blocks customer mail, pauses reminder crons and sandboxes gateways on staging
- [memberpress-forward-only](https://github.com/omaraelhawary/memberpress-forward-only): gates content by comparing publish dates with join dates
- [pdf-invoice-generator-for-memberpress](https://github.com/omaraelhawary/pdf-invoice-generator-for-memberpress): bulk invoice generation
- [memberpress-personal-content](https://github.com/omaraelhawary/memberpress-personal-content)
- [hide-claim-fields-for-memberpress-gifting](https://github.com/omaraelhawary/hide-claim-fields-for-memberpress-gifting)
- [corporate-hide-fields-memberpress](https://github.com/omaraelhawary/corporate-hide-fields-memberpress)

</details>

### Recent writing

- [ai-tell-lint: a linter for prose that sounds machine-written](https://omarelhawary.com/blog/ai-tell-lint-a-linter-for-machine-sounding-prose) · Oct 2026
- [My AI memory kept a stale diagnosis alive](https://omarelhawary.com/blog/my-ai-memory-kept-a-stale-diagnosis-alive) · Sep 2026
- [95% at launch, 65% a month later](https://omarelhawary.com/blog/95-at-launch-65-a-month-later) · Aug 2026

[All posts →](https://omarelhawary.com/blog)

### Stack

`Claude` `Cursor` `Evals` `RAG` `MCP` `Agent loops` · `PHP` `JavaScript` `MySQL` `REST APIs` `WordPress`

---

Remote from Cairo. Open to applied AI engineering roles and consulting. **[omarelhawary.com](https://omarelhawary.com)** · Omaraelhawary@gmail.com
