# F5 Load Balancer

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

APIs for managing F5 BIG-IP Load Balancer configuration, monitoring, and operations. F5 BIG-IP is an application delivery controller that provides intelligent traffic management, load balancing, and application security.

**Areas:** Application Delivery · BIG-IP · Load Balancer · Networking · Traffic Management

## F5 Load Balancer on APIs.io

Everything profiled for F5 Load Balancer is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/f5-load-balancer/](https://apis.io/providers/f5-load-balancer/)** — or go straight to one of the APIs or properties below.

### APIs (17)

- [F5 Load Balancer Config API](https://apis.io/apis/f5-load-balancer/f5-load-balancer-config-api/) — Retrieve the original device configuration before Declarative Onboarding modifications were applied.
- [F5 Load Balancer Data Groups API](https://apis.io/apis/f5-load-balancer/f5-load-balancer-data-groups-api/) — Manage internal and external data groups used for address, string, and integer lookups in traffic processing decisions.
- [F5 Load Balancer Declarations API](https://apis.io/apis/f5-load-balancer/f5-load-balancer-declarations-api/) — Submit, retrieve, and manage AS3 declarations that describe the desired application services configuration state on the BIG-IP system.
- [F5 Load Balancer Info API](https://apis.io/apis/f5-load-balancer/f5-load-balancer-info-api/) — Retrieve version and capability information about the installed AS3 extension.
- [F5 Load Balancer Inspect API](https://apis.io/apis/f5-load-balancer/f5-load-balancer-inspect-api/) — Inspect the current state of BIG-IP configuration classes known to Declarative Onboarding.
- [F5 Load Balancer iRules API](https://apis.io/apis/f5-load-balancer/f5-load-balancer-irules-api/) — Manage iRules for custom traffic management logic using the F5 Tcl-based scripting language.
- [F5 Load Balancer Monitors API](https://apis.io/apis/f5-load-balancer/f5-load-balancer-monitors-api/) — Configure health monitors that verify the availability and performance of nodes, pool members, and services.
- [F5 Load Balancer Nodes API](https://apis.io/apis/f5-load-balancer/f5-load-balancer-nodes-api/) — Manage backend server nodes identified by IP address or FQDN that serve as the foundation for pool member definitions.
- [F5 Load Balancer Policies API](https://apis.io/apis/f5-load-balancer/f5-load-balancer-policies-api/) — Manage local traffic policies that provide rule-based traffic steering and content manipulation capabilities.
- [F5 Load Balancer Pool Members API](https://apis.io/apis/f5-load-balancer/f5-load-balancer-pool-members-api/) — Manage individual server members within load balancing pools including their state, ratio, priority group, and connection limits.
- [F5 Load Balancer Pools API](https://apis.io/apis/f5-load-balancer/f5-load-balancer-pools-api/) — Manage pools of backend servers for load distribution and health monitoring.
- [F5 Load Balancer Profiles API](https://apis.io/apis/f5-load-balancer/f5-load-balancer-profiles-api/) — Manage traffic profiles that define how the BIG-IP processes different types of network traffic including HTTP, TCP, SSL, and persistence.
- [F5 Load Balancer SNAT Pools API](https://apis.io/apis/f5-load-balancer/f5-load-balancer-snat-pools-api/) — Manage SNAT (Secure Network Address Translation) pools that define translation addresses for outbound connections.
- [F5 Load Balancer SSL Certificates API](https://apis.io/apis/f5-load-balancer/f5-load-balancer-ssl-certificates-api/) — Manage SSL certificates and keys used for TLS/SSL termination and re-encryption on virtual servers.
- [F5 Load Balancer System API](https://apis.io/apis/f5-load-balancer/f5-load-balancer-system-api/) — Access system-level information and configuration including device status, software versions, and global settings.
- [F5 Load Balancer Tasks API](https://apis.io/apis/f5-load-balancer/f5-load-balancer-tasks-api/) — Monitor the status of asynchronous declaration processing tasks.
- [F5 Load Balancer Virtual Servers API](https://apis.io/apis/f5-load-balancer/f5-load-balancer-virtual-servers-api/) — Manage virtual servers that direct client traffic to appropriate server pools based on configured rules and profiles.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [F5 Load Balancer Agentic Access](https://apis.io/agentic-access/f5-load-balancer/f5-load-balancer-agentic-access/)

#### Collections (20)

Postman and Open Collection request collections.

- [F5 Load Balancer F5 BIG-IP Application Services 3 Extension (AS3) API](https://apis.io/collections/f5-load-balancer/open-f5-load-balancer-as3/)
- [F5 Load Balancer F5 BIG-IP Application Services 3 Extension (AS3) Config API](https://apis.io/collections/f5-load-balancer/open-f5-load-balancer-config-api/)
- [F5 Load Balancer F5 BIG-IP Application Services 3 Extension (AS3) Config Data Groups API](https://apis.io/collections/f5-load-balancer/open-f5-load-balancer-data-groups-api/)
- [F5 Load Balancer F5 BIG-IP Application Services 3 Extension (AS3) Config Declarations API](https://apis.io/collections/f5-load-balancer/open-f5-load-balancer-declarations-api/)
- [F5 Load Balancer F5 BIG-IP Declarative Onboarding (DO) API](https://apis.io/collections/f5-load-balancer/open-f5-load-balancer-declarative-onboarding/)
- [F5 Load Balancer F5 BIG-IP iControl REST API](https://apis.io/collections/f5-load-balancer/open-f5-load-balancer-icontrol-rest/)
- [F5 Load Balancer F5 BIG-IP Application Services 3 Extension (AS3) Config Info API](https://apis.io/collections/f5-load-balancer/open-f5-load-balancer-info-api/)
- [F5 Load Balancer F5 BIG-IP Application Services 3 Extension (AS3) Config Inspect API](https://apis.io/collections/f5-load-balancer/open-f5-load-balancer-inspect-api/)
- [F5 Load Balancer F5 BIG-IP Application Services 3 Extension (AS3) Config iRules API](https://apis.io/collections/f5-load-balancer/open-f5-load-balancer-irules-api/)
- [F5 Load Balancer F5 BIG-IP Application Services 3 Extension (AS3) Config Monitors API](https://apis.io/collections/f5-load-balancer/open-f5-load-balancer-monitors-api/)
- [F5 Load Balancer F5 BIG-IP Application Services 3 Extension (AS3) Config Nodes API](https://apis.io/collections/f5-load-balancer/open-f5-load-balancer-nodes-api/)
- [F5 Load Balancer F5 BIG-IP Application Services 3 Extension (AS3) Config Policies API](https://apis.io/collections/f5-load-balancer/open-f5-load-balancer-policies-api/)
- [F5 Load Balancer F5 BIG-IP Application Services 3 Extension (AS3) Config Pool Members API](https://apis.io/collections/f5-load-balancer/open-f5-load-balancer-pool-members-api/)
- [F5 Load Balancer F5 BIG-IP Application Services 3 Extension (AS3) Config Pools API](https://apis.io/collections/f5-load-balancer/open-f5-load-balancer-pools-api/)
- [F5 Load Balancer F5 BIG-IP Application Services 3 Extension (AS3) Config Profiles API](https://apis.io/collections/f5-load-balancer/open-f5-load-balancer-profiles-api/)
- [F5 Load Balancer F5 BIG-IP Application Services 3 Extension (AS3) Config SNAT Pools API](https://apis.io/collections/f5-load-balancer/open-f5-load-balancer-snat-pools-api/)
- [F5 Load Balancer F5 BIG-IP Application Services 3 Extension (AS3) Config SSL Certificates API](https://apis.io/collections/f5-load-balancer/open-f5-load-balancer-ssl-certificates-api/)
- [F5 Load Balancer F5 BIG-IP Application Services 3 Extension (AS3) Config System API](https://apis.io/collections/f5-load-balancer/open-f5-load-balancer-system-api/)
- [F5 Load Balancer F5 BIG-IP Application Services 3 Extension (AS3) Config Tasks API](https://apis.io/collections/f5-load-balancer/open-f5-load-balancer-tasks-api/)
- [F5 Load Balancer F5 BIG-IP Application Services 3 Extension (AS3) Config Virtual Servers API](https://apis.io/collections/f5-load-balancer/open-f5-load-balancer-virtual-servers-api/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [F5 Load Balancer Authentication](https://apis.io/security/f5-load-balancer/f5-load-balancer-authentication/)
- [F5 Load Balancer Domain Security](https://apis.io/security/f5-load-balancer/f5-load-balancer-domain-security/)
- [F5 Load Balancer Trust Center](https://apis.io/security/f5-load-balancer/f5-load-balancer-trust-center/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [F5 Load Balancer Plans Pricing](https://apis.io/plans/f5-load-balancer/f5-load-balancer-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [F5 Load Balancer Rate Limits](https://apis.io/rate-limits/f5-load-balancer/f5-load-balancer-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [F5 Load Balancer Finops](https://apis.io/finops/f5-load-balancer/f5-load-balancer-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.f5.com)
- [Documentation](https://clouddocs.f5.com/api/)
- [Support](https://www.f5.com/services/support)
- [Blog](https://www.f5.com/company/blog)
- [Terms of service](https://www.f5.com/company/policies/terms-of-use)
- [Privacy policy](https://www.f5.com/company/policies/privacy-notice)
- [GitHub](https://github.com/F5Networks)

## API Evangelist rating

**Kin Score 35.5** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 78.6 |
| Contract quality | 51.9 |
| Contract governance | 0.0 |
| Operational transparency | 10.5 |
| Developer ergonomics | 26.2 |
| Access clarity | 36.8 |

**Agent readiness 17.9** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 24.5** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/f5-load-balancer/](https://apis.io/providers/f5-load-balancer/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for F5 Load Balancer: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/f5-load-balancer/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
