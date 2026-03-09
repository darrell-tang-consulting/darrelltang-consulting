# Website Redesign Design — darrelltang.consulting

## Goal
Redesign the consulting website as a proof-first single-page sales page that validates credibility for prospects arriving from Upwork, LinkedIn, TikTok, or cold outreach. Primary audience: SaaS founders/CTOs evaluating Darrell for fixed-price infrastructure projects.

## Approach
**Proof-First Sales Page** — lead with anonymized case studies, not a services menu. The page reads as: problem → proof you solve it → book a call.

## Tone
Modern, startup-friendly, results-focused. Not corporate/enterprise. Should feel like "this person gets SaaS companies and moves fast."

## Tech
Single `index.html` on GitHub Pages (existing setup). No build tooling.

## Page Flow

| # | Section | Job |
|---|---------|-----|
| 1 | Hero | Position + single CTA |
| 2 | Trust bar | 3 stats to earn the scroll |
| 3 | Case studies | 3 anonymized proof cards |
| 4 | Tech stack | Scannable keyword strip |
| 5 | How I Work | 3-step engagement model |
| 6 | About | Human, brief, name-drop employers |
| 7 | CTA | Close with calendar link |

## Section Details

### 1. Hero
- **Headline:** "Production-Ready Infrastructure for SaaS Companies"
- **Subline:** "I help SaaS teams ship faster with production-ready pipelines and infrastructure."
- **CTA:** "Book a Discovery Call" → https://calendar.app.google/SgWK3rc47cbzBzHy7
- **Design:** Dark background, minimal. Name + credibility marker above headline. Single CTA.
- Copy to be refined via `copywriting` skill.

### 2. Trust Bar
Three stats, understated horizontal row:
- **3 SaaS Companies** — healthcare, govtech, legal tech
- **79-Min Rebuild** — full infrastructure from zero
- **Zero-Downtime** — migrations and deployments

### 3. Case Studies (anonymized)
Three cards. Each: who → problem → what you built → result. Raw facts below; copy to be tightened via `copywriting` skill.

**GovTech SaaS Startup**
- Needed multi-tenant platform for government contractors
- Built AKS + ArgoCD + LinkerD with mTLS tenant isolation, 4-layer Terraform
- New tenants onboarded with 3 files, zero code changes

**Healthcare Finance Platform**
- 77 repos with inconsistent pipelines and no build-time validation
- Building centralized pipeline templates, automated JSON/README validation, branch policies
- Ongoing engagement bringing consistency across the org

**Legal Tech SaaS**
- No DR, previous engineer's Terraform fragments didn't match running infrastructure
- Refactored Terraform into modular IaC, stood up multi-cloud DR, built GitHub Actions CI/CD
- Security engineer used DR capability to update SOC 2 compliance docs

### 4. Tech Stack
Compact strip of badges/text between case studies and How I Work:
Kubernetes, Terraform, ArgoCD, Docker, Helm, Azure, AWS, GCP, GitHub Actions, Azure DevOps, LinkerD, Go, Python

### 5. How I Work
Three columns signaling fixed-price engagement model:
- **Assess** — Audit current infrastructure, identify gaps and quick wins
- **Build** — Deliver production-ready infrastructure with IaC, pipelines, and operational docs
- **Support** — Optional retainer for ongoing improvements and incident support

### 6. About
- Photo or DT initials placeholder
- 1-2 sentences: who you are, SaaS focus, name-drop Paramount+ and LexisNexis
- No skills grid (case studies already prove tech chops)

### 7. CTA (closing)
- Outcome-focused headline (copywriting skill will refine)
- 1 sentence reinforcing who you help
- Single button: "Book a Discovery Call" → Google Calendar link
- Dark background, centered, clean

### Footer
Minimal: copyright 2026, privacy policy, terms of service links.

## Implementation Sequence
1. Run `product-marketing-context` skill — lock in positioning, ICP, differentiators
2. Run `copywriting` skill — write actual page copy using that context
3. Build the HTML/CSS
4. Run `page-cro` skill — review for conversion optimization
5. Deploy via GitHub Pages

## Key Decisions
- **No multi-page** — single page reduces drop-off, every click away loses conversion
- **No contact form** — direct calendar link removes friction
- **No AI mention** — clients buy outcomes (speed), not methods
- **Anonymized clients** — consistent with Upwork profile approach
- **No price ranges on site** — discussed in discovery calls instead
