# Awesome-Digital-Adoption-Platform-Dap

# Top Digital Adoption Platform (DAP) Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on In-App Guidance, User Onboarding & Feature Adoption*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Digital Adoption Platforms (DAP)**. These tools enable organizations to guide users through software workflows, onboard new employees, drive feature adoption, and reduce support tickets — directly inside applications without code changes.

**Examples** include Salesforce In-App Guidance, WalkMe, Whatfix, Pendo, Appcues, Userlane, Spekit, Stonly, Userpilot, and Chameleon (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom in-app guidance engines, and open onboarding libraries — ideal for product teams, developers, and organizations seeking transparent, vendor-independent digital adoption.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Salesforce In-App Guidance](https://help.salesforce.com/s/articleView?id=platform.customhelp_lex.htm&type=5)**  
  Native Salesforce DAP for prompts, walkthroughs, and learning paths. Features Guidance Center, docked/floating prompts, engagement tracking, and managed package deployment. Supports up to 1,000 learning items with due dates and user-level visibility.

- **[WalkMe](https://www.walkme.com/)**  
  Enterprise DAP and AI adoption platform, now part of SAP. Features DeepUI technology for screen context, omnichannel Action Bar, workflow automation, and behavioral segmentation. G2 category leader with 100/100 satisfaction rating and 494% three-year ROI.

- **[Whatfix](https://whatfix.com/)**  
  AI-native enterprise DAP with guided flows, interactive task lists, contextual tooltips, and embedded self-help. Features ScreenSense™ AI, simulation training, product analytics, and AI agents for guidance generation. Trusted by 600+ enterprises including 80+ Fortune 500 companies.

- **[Pendo](https://www.pendo.io/)**  
  Intelligent DAP combining product analytics, in-app guides, session replay, NPS surveys, and SaaS portfolio insights. Features process analytics across apps, sentiment capture, and license optimization. SOC2, GDPR, and HIPAA compliant with 14,400+ customers.

- **[Appcues](https://www.appcues.com/)**  
  No-code DAP for in-product experiences. Features Builder Chrome extension, Flows, Checklists, Launchpads, Pins, Banners, NPS surveys, and Workflows for multi-channel orchestration. Targets users by properties, events, and segments with Goals for impact measurement.

- **[Userlane](https://www.userlane.com/)**  
  Application Intelligence and Contextual Assistance platform. Features App Discovery for shadow IT, HEART Score for adoption measurement, Validators for error prevention, and MCP integration with Microsoft Copilot. Two-hour IT setup via group policy.

- **[Spekit](https://spekit.com/)**  
  AI-powered enablement and DAP with AI Sidekick for just-in-time coaching. Unifies DAP, KMS, CMS, and LMS capabilities with content repository, governance, and change management. Deep Salesforce and Slack integrations.

- **[Stonly](https://stonly.com/)**  
  Interactive product adoption and onboarding platform. Features hotspots, tooltips, interactive guides, and rich day-zero user data capture. Adjusts tours based on real-time user actions for personalized paths.

- **[Userpilot](https://userpilot.com/)**  
  Product growth platform for onboarding, adoption, and monetization. Features AI Agent Lia, predictive analytics, MCP server, session replay, NPS/CSAT surveys, and resource center. SOC 2 Type II, GDPR, and HIPAA compliant with <200ms latency.

- **[Chameleon](https://www.chameleon.io/)**  
  Deep product adoption platform with advanced segmentation, element selection, and on-page triggers. Features Builder for custom Experiences, A/B testing, and analytics sync. Works with SPAs, Cordova mobile apps, and Segment/Freshpaint installation.

## Open-Source GitHub Projects

- **[Shepherd.js](https://github.com/shipshapecode/shepherd)**  
  Fully featured open-source DAP and user onboarding library (AGPL-3.0 with commercial license option). Guides users through custom tours, trainings, and announcements within apps. Framework agnostic — supports React, Ember, Angular, Vue.js, and plain JavaScript. Used by LogSeq, Drupal CMS, Budibase, and SimplePlanner.

- **[Driver.js](https://github.com/kamranahmedse/driver.js)**  
  Lightweight, dependency-free library for highlighting elements and guiding attention (MIT). Framework-agnostic with strong spotlight UX for feature discovery. Requires element mount management for SPAs and async UI.

- **[Intro.js](https://github.com/usablica/intro.js)**  
  Classic step tour library with straightforward API and extensive examples (AGPL-3.0 with commercial license). Easy onboarding UI with next/back flows. Commercial license required for closed-source SaaS.

- **[Reactour](https://github.com/elrumordelaluz/reactour)**  
  React-based tour library (MIT). Permission license, SPA-friendly, and designed for React applications with customizable components.

- **[Modern Tour](https://github.com/modern-tour/modern-tour)**  
  Lightweight, animated product tour library for React (MIT). Powered by Framer Motion with spring physics, smart positioning, keyboard support, dark mode, and headless mode via `useTour` hook.

- **[OpenTutorial](https://github.com/JeanPaulDot/OpenTutorial)**  
  Spec-driven in-app guidance engine (license varies). Zero runtime dependencies. Adapters for React, Vue 3, Svelte, Angular, Solid, Web Component, and vanilla JS. Features tour orchestration with priority queues, triggers (manual, auto, event, route, idle, scroll), cross-page tours, branching logic, and analytics adapters (PostHog, Mixpanel, Amplitude, GA4).

- **[Bitmapist](https://github.com/Doist/bitmapist)**  
  Open-source cohort analytics library (MIT) using Redis bitmaps. Enables real-time feature adoption tracking, retention analysis, and A/B test impact measurement. Saved Doist millions in analytics fees with 443x memory reduction.

### Additional Strong Open-Source Options

- **[Pendo Open Source](https://github.com/pendo-io)** — Various open-source utilities and libraries from Pendo.
- **[Whatfix Open Source](https://github.com/whatfix)** — Open-source components and tools from Whatfix.
- **[Appcues Open Source](https://github.com/appcues)** — Public repos including SDKs and utilities.
- **[Shepherd Rails](https://github.com/shipshapecode/shepherd-rails)** — Rails engine for generating and tracking Shepherd tours.
- **[Budibase Shepherd Plugin](https://github.com/Budibase/plugins)** — Interactive walkthrough plugin for low-code apps.
- Community **React Joyride** and **Vue Tour** projects for framework-specific tours.

**Frameworks for building custom systems**: Combine **Shepherd.js** or **Driver.js** as the tour engine with **OpenTutorial** for spec-driven orchestration, **Bitmapist** for adoption analytics, and **PostHog** or **Mixpanel** for event tracking — creating a fully self-hosted, enterprise-grade digital adoption platform.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- DAP platforms collecting user behavior data must comply with data protection regulations (GDPR, CCPA, HIPAA, etc.).
- Self-hosted open-source solutions require proper security hardening, analytics infrastructure, and ongoing maintenance for production reliability.

---

**Made for product teams, enablement leaders, customer success managers, and developers building transparent digital adoption solutions.**  
Let's make Digital Adoption Platforms more open, data-driven, and effective.
