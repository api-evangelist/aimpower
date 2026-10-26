# Brainsuite.ai (formerly aimpower)

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

Brainsuite.ai GmbH -- founded in 2020 in Hamburg as **aimpower GmbH**, now registered at
Kuddewoerde, Schleswig-Holstein -- builds **Brainsuite**, an AI creative-effectiveness platform
that predicts how an advertising asset will perform before any media budget is committed. Built on
applied consumer-neuroscience models, it scores video, static, packaging, shelf, out-of-home,
digital-banner and social-media creative against an ACE (Advertising Creative Effectiveness) score
and effectiveness pillars covering attention, persuasion, strategic fit, processing ease, emotional
engagement and branding.

Alongside the self-serve application at `app.brainsuite.ai`, the company sells a **Creative
Effectiveness API** that partner platforms -- generative-AI tools, creative production suites,
ad-tech and activation stacks, digital-asset-management systems and creator networks -- embed so
that every asset their customers produce is scored in-workflow.

## What this profile found

The API is real and running: `https://api.brainsuite.ai/brainsuite` is named as the public API base
by the company's own anonymously reachable runtime configuration document, and every path on that
host answers `HTTP 401 {"message":"Unauthorized"}`. But **no machine-readable contract is
published** -- no OpenAPI, GraphQL SDL, AsyncAPI, MCP server, agent card, SDK or public reference.
The provider's own support article states that step one of onboarding is "Request API credentials &
documentation", so the reference ships privately with the credentials.

What *is* public and was captured here: a working **OpenID Connect discovery document** for the
Amazon Cognito user pool behind the platform (authorization endpoints on `auth.brainsuite.ai`), a
**35-entry dated changelog** running 2024-11-05 to 2026-09-06, a **four-tier plan ladder** that
publishes seats but no prices, a Vanta **trust centre** whose certifications render client-side and
could not be read, and a GDPR/EU-residency posture (AWS `eu-central-1`, SSE-S3, no model training on
customer data).

- Company: https://brainsuite.ai/en/
- API: https://brainsuite.ai/en/creative-effectiveness-api/
- Former domains: `aimpower.ai` and `aimpower.de` now 301 to `brainsuite.ai`
- Listing source: https://equityzen.com/company/aimpower
