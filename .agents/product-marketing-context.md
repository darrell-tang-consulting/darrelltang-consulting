# Product Marketing Context

*Last updated: 2026-03-09*

## Product Overview
**One-liner:** DevOps and infrastructure consulting for SaaS companies
**What it does:** Darrell Tang Consulting (DT Consulting LLC, S-Corp) delivers fixed-price infrastructure projects for SaaS companies — multi-tenant platforms, CI/CD pipelines, IaC, disaster recovery, and cloud architecture. The focus is on building production-ready infrastructure that the client's team can operate after handoff.
**Product category:** DevOps consulting / infrastructure consulting
**Product type:** Professional services (consulting)
**Business model:** Fixed-price projects ($3k-$15k range depending on scope), with optional ongoing retainer. Moving away from hourly staff augmentation toward project-based engagements.

## Target Audience
**Target companies:** SaaS startups and mid-stage SaaS companies (seed to Series B). Industries: govtech, healthcare, legal tech, fintech — any SaaS company that has outgrown their initial infrastructure but doesn't have a dedicated DevOps team.
**Decision-makers:** CTOs, technical co-founders, VP Engineering at companies with 5-50 engineers
**Primary use case:** "We need production-ready infrastructure but don't have the DevOps expertise in-house to build it right"
**Jobs to be done:**
- Build a reliable deployment pipeline so the team can ship without fear
- Set up infrastructure-as-code so environments are reproducible and auditable
- Get multi-tenant architecture right before scaling to more customers
**Use cases:**
- SaaS company launching multi-tenant platform and needs AKS/K8s + tenant isolation
- Team deploying manually and needs CI/CD pipelines + IaC from scratch
- Previous engineer left half-finished Terraform and someone needs to pick it up and make it work
- Company approaching SOC 2 audit and needs infrastructure that supports compliance

## Personas
| Persona | Cares about | Challenge | Value we promise |
|---------|-------------|-----------|------------------|
| CTO / Technical Co-founder | Shipping product, not managing infra | Can't afford a full-time SRE but needs production-grade infrastructure | Production-ready infrastructure delivered as a project, not an open-ended engagement |
| VP Engineering | Team velocity, reliability, compliance | Engineers are spending time on infra instead of product features | Free up your engineering team — I handle the infrastructure so they can ship |

## Problems & Pain Points
**Core problem:** SaaS companies need production-grade infrastructure (pipelines, IaC, multi-tenant architecture, DR) but can't afford or justify a full-time DevOps hire, and the founding engineers are spending their time on infra instead of product.
**Why alternatives fall short:**
- Hiring full-time: expensive ($150-200k+), slow to hire, may not have enough work to justify
- Other freelancers: many know the tools but haven't operated at enterprise scale; deliver config files but not operational knowledge transfer
- DIY: founding engineers piece together tutorials, accumulate tech debt, create infrastructure that only they understand
**What it costs them:** Slow deployments, manual processes, fear of deploying on Fridays, inability to pass compliance audits, infrastructure that breaks when the one person who built it leaves
**Emotional tension:** "We know our infrastructure is held together with duct tape and we're one bad deploy away from a customer-facing outage"

## Competitive Landscape
**Direct:** Other DevOps freelancers on Upwork and similar platforms — often lack enterprise experience, deliver Terraform files without operational context, or work hourly without defined outcomes
**Secondary:** Managed DevOps agencies (e.g., Gruntwork, Spacelift professional services) — expensive, slow onboarding, may not understand your specific stack or constraints
**Indirect:** DIY / internal engineers wearing the DevOps hat — gets things running but accumulates tech debt, no one else can maintain it

## Differentiation
**Key differentiators:**
- Enterprise background (Paramount+, LexisNexis) applied to SaaS-scale problems — knows what production-grade looks like
- Fixed-price project model with clear deliverables, not open-ended hourly billing
- Delivers operational documentation alongside infrastructure — the client can maintain it after handoff
- Multi-cloud experience (Azure, AWS, GCP) — not locked into one ecosystem
- Fast delivery through disciplined workflows
**How we do it differently:** Scoped projects with defined outcomes instead of open-ended staff aug. Every engagement includes operational docs so the team isn't dependent on me afterward.
**Why that's better:** You know the cost upfront, you get a working system plus the knowledge to run it, and the engagement has a clear end date.
**Why customers choose us:** Real enterprise experience at SaaS-friendly pricing. Not a junior freelancer learning on your dime; not an agency charging $300/hr.

## Objections
| Objection | Response |
|-----------|----------|
| "We might just hire someone full-time" | A full-time SRE is $150-200k+. I can deliver a specific project for a fraction of that, and you'll have the docs to maintain it. Hire full-time when you have enough ongoing work to justify it. |
| "How do I know you'll understand our stack?" | I've worked across Azure, AWS, and GCP in production. I'll audit your current setup first and scope the project before you commit. |
| "What happens after you leave?" | Every engagement includes operational documentation — runbooks, architecture docs, troubleshooting guides. Your team can maintain and extend what I build. |

**Anti-persona:** Companies that want a long-term staff aug body to sit in standups. Companies with no budget for infrastructure work. Companies that need frontend/backend application development, not infrastructure.

## Switching Dynamics
**Push:** Current infrastructure is fragile, deployments are manual and scary, previous DevOps person left and no one understands what they built, approaching a compliance audit with gaps
**Pull:** Fixed-price predictability, enterprise-quality work without enterprise pricing, operational docs mean you're not dependent on the consultant
**Habit:** "We've been doing it this way and it mostly works" / "Our lead engineer handles deploys, it's fine for now"
**Anxiety:** "What if the consultant builds something we can't maintain?" / "What if it takes longer and costs more than quoted?"

## Customer Language
**How they describe the problem:**
- "We need someone who can set up our infrastructure properly"
- "Our deployments are a mess"
- "The last person who touched our Terraform left and nobody knows how it works"
- "We're deploying to production manually and it scares me"
**How they describe us:**
- (Need to collect — early stage)
**Words to use:** production-ready, infrastructure, pipelines, ship faster, reliable, reproducible, handoff-ready
**Words to avoid:** transform, revolutionize, cutting-edge, AI-powered, world-class, end-to-end, synergy, leverage
**Glossary:**
| Term | Meaning |
|------|---------|
| IaC | Infrastructure as Code — managing servers/cloud resources through code files instead of clicking in dashboards |
| CI/CD | Continuous Integration / Continuous Deployment — automated build, test, deploy pipelines |
| Multi-tenant | One platform serving multiple customers with isolated data and resources |
| GitOps | Managing infrastructure through Git repositories as the source of truth |

## Brand Voice
**Tone:** Direct, confident, no-BS
**Style:** Conversational but technical when needed. Speaks to engineers, not MBAs. Shows don't tell.
**Personality:** Competent, fast-moving, pragmatic, approachable, builder

## Proof Points
**Metrics:**
- 79-minute full infrastructure rebuild from zero (P3MS — Azure region quota limits required teardown/rebuild)
- 77 repos managed with centralized pipeline templates and automated validation (HFD)
- Zero-downtime migrations and deployments across engagements
- 3-file tenant onboarding with zero code changes (P3MS)
- SOC 2 compliance documentation updated based on delivered DR capability (Patentbots)
**Customers:** 3 SaaS companies across healthcare, govtech, and legal tech (anonymized). Enterprise experience at Paramount+ and LexisNexis.
**Testimonials:**
> (Need to collect)
**Value themes:**
| Theme | Proof |
|-------|-------|
| Production-ready | 79-min from-zero rebuild, zero-downtime deployments |
| Handoff-ready | Operational docs delivered with every engagement |
| Picks up context fast | Inherited incomplete Terraform twice, made it work both times |
| Multi-cloud | Azure, AWS, GCP production experience across clients |

## Goals
**Business goal:** Attract fixed-price SaaS infrastructure projects ($5k-$15k) to shift revenue mix from staff aug toward project-based work
**Conversion action:** Book a discovery call via Google Calendar
**Current metrics:** Website is currently a credibility validator for Upwork prospects, not a primary lead source. No analytics in place.
