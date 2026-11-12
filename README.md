# Awesome-Conversion-Rate-Optimization-Cro

# Top Conversion Rate Optimization (CRO) Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on A/B Testing, Session Replay & Behavior-Driven Experimentation*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Conversion Rate Optimization (CRO)**. These tools help teams understand user behavior, test hypotheses, and optimize digital experiences—covering A/B testing, session replay, heatmaps, funnel analysis, and AI-assisted experiment generation.

**Examples** include Optimizely, VWO, Hotjar, Crazy Egg, AB Tasty, Kameleoon, Dynamic Yield, and open-source alternatives like GrowthBook, PostHog, and OpenReplay (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted A/B testing, open-source session replay, and community-driven behavior analytics—ideal for organizations seeking data sovereignty and transparent experimentation without per-event or per-session SaaS pricing.

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[Optimizely](https://www.optimizely.com/)** | Enterprise experimentation platform with feature flagging, A/B testing, and personalization. Positioned for large-scale product and marketing teams. | Quote-only (enterprise contract) | No free tier; demo via sales |
| **[VWO](https://vwo.com/)** | A/B testing and conversion optimization suite with visual editor, heatmaps, and funnel analysis. Popular for marketing-led CRO programs. | Quote-only (tiered by visitor volume) | Free trial available |
| **[Hotjar](https://www.hotjar.com/)** | Behavior analytics with heatmaps, session recordings, surveys, and feedback widgets. Widely used for qualitative CRO research. | Basic: ~$32/month (annual); Plus: ~$80/month | **Free plan**: 35 daily sessions, unlimited heatmaps, 3 surveys |
| **[Crazy Egg](https://www.crazyegg.com/)** | Heatmap and session recording tool with A/B testing capabilities. Simpler entry point for small teams. | Quote-only (tiered by traffic) | Free trial available |
| **[AB Tasty](https://www.abtasty.com/)** | Experimentation and personalization platform. Covers A/B testing, feature flags, and AI-driven optimization. | Quote-only (enterprise contract) | No free tier; demo via sales |
| **[Kameleoon](https://www.kameleoon.com/)** | AI-powered experimentation and personalization platform. Focused on enterprise-scale testing across web and mobile. | Quote-only (enterprise contract) | No free tier; demo via sales |
| **[Dynamic Yield](https://www.dynamicyield.com/)** | Personalization and experimentation platform (Mastercard company). Covers A/B testing, recommendations, and omnichannel optimization. | Quote-only (enterprise contract) | No free tier; demo via sales |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[GrowthBook](https://github.com/growthbook/growthbook)** | [![Stars](https://img.shields.io/github/stars/growthbook/growthbook?style=social&color=white)](https://github.com/growthbook/growthbook/stargazers) | **The leading open-source feature flagging and A/B testing platform** (~6,750 stars, TypeScript). Self-hostable with SDKs for JavaScript, React, Python, Go, Ruby, PHP, Swift, Kotlin, and more. Supports Bayesian and frequentist statistics, visual editor, and warehouse-native experimentation [citation:5][citation:10]. |
| **[PostHog](https://github.com/PostHog/posthog)** | [![Stars](https://img.shields.io/github/stars/PostHog/posthog?style=social&color=white)](https://github.com/PostHog/posthog/stargazers) | Open-source product analytics with **session recording, feature flags, and A/B testing**. Self-hostable or cloud. Free tier includes 1 million events and 5,000 replays per month. Combines multiple CRO tools in a single platform [citation:6]. |
| **[OpenReplay](https://github.com/openreplay/openreplay)** | [![Stars](https://img.shields.io/github/stars/openreplay/openreplay?style=social&color=white)](https://github.com/openreplay/openreplay/stargazers) | **Self-hosted session replay and product analytics** built for regulated industries. Session data never leaves your infrastructure. Includes DevTools (network, console, errors), funnels, trends, heatmaps, and cobrowsing. SOC 2 Type II for cloud; GDPR/CCPA tools built-in [citation:8][citation:14]. |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Matomo](https://github.com/matomo-org/matomo)** | [![Stars](https://img.shields.io/github/stars/matomo-org/matomo?style=social&color=white)](https://github.com/matomo-org/matomo/stargazers) | Privacy-focused open-source web analytics (formerly Piwik) with **goal conversion tracking, heatmaps, and session recordings**. Full-featured Google Analytics alternative with complete data ownership [citation:12]. |
| **[oss-clarity](https://pypi.org/project/oss-clarity/)** | — | Self-hosted **session replay, heatmaps, and rules-based behavior signals** for Django. Detects rage clicks, dead clicks, hesitations, and form abandons. Privacy-first: no IP storage, masked by default, no third-party AI processing. Early release (0.1.2) [citation:2]. |
| **[CROtomate](https://www.npmjs.com/package/crotomate)** | — | AI-powered CRO automation agent. Generates hypotheses and code changes, deploys via git push, measures conversion impact via PostHog or Plausible, and rolls back failures. Supports multiple LLM providers (Anthropic, OpenAI, Google, Mistral, xAI). ~$0.10–$0.50/day at GPT-4o pricing for one experiment per day [citation:4]. |
| **[ab-analysis-kit](https://pypi.org/project/ab-analysis-kit/)** | — | Declarative A/B experiment analysis as YAML + SQL. Computes effect, confidence interval, p-value, and MDE/power cumulatively. Includes a chart-first cockpit (`abk dashboard`) for experiment management. Database-agnostic (ClickHouse, Postgres, MySQL). Alpha stage (0.6.4) [citation:1]. |

**Frameworks for building custom systems**: Combine **GrowthBook** for feature flagging and experiment assignment, **PostHog** or **OpenReplay** for session replay and behavior analytics, and **ab-analysis-kit** for statistical rigor in experiment evaluation—all deployable via Docker without per-event SaaS fees.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- CRO tools process user behavior data and potentially PII; enforce consent management, data minimization, and compliance with GDPR, CCPA, and other applicable privacy regulations.
- Commercial platforms (Optimizely, VWO, AB Tasty, Kameleoon, Dynamic Yield) are almost universally quote-only with no public pricing or free tiers. Open-source alternatives provide genuine experimentation and analytics capabilities but require engineering effort for production hardening, statistical rigor, and cross-platform SDK maintenance. **CROtomate** and **ab-analysis-kit** are early-stage (alpha/early release) and should be validated before operational reliance [citation:1][citation:4].

---

**Made for growth teams, product managers, marketing analysts, and developers building experimentation infrastructure.**  
Let's make conversion optimization more open, data-driven, and privacy-respecting.
