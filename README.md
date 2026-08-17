# Darewise

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Darewise Entertainment is a European game studio — Paris, London and Barcelona — founded by AAA industry veterans and building **Life Beyond**, a free-to-play sci-fi MMO on Unreal Engine 5 set on the alien world Dolos, with Web3 asset ownership (NFTs and ERC-20 tokens) and player-driven settlement and governance. Animoca Brands announced the acquisition of a majority stake in April 2022 and the studio now operates as **Life Beyond Studios** at [lifebeyondstudios.com](https://www.lifebeyondstudios.com/).

**No API surface.** Darewise publishes no API, developer portal or API documentation. Probed 2026-08-17: no OpenAPI, Swagger, GraphQL, MCP or A2A document on any host it operates; every `/.well-known/*` path and `/llms.txt` on the live host return a real origin 404; no `api.`, `docs.` or `developer.` subdomain resolves in DNS on either domain; and the legacy brand host `www.darewise.com` refuses TCP on 443 and 80 (last archived HTTP 200: 2025-04-21) while its DNS still carries live Google Workspace mail with SPF and DMARC `p=quarantine`.

The one first-party developer artifact the studio ships is [`@darewise/asyncapi-template-cpp-ue`](https://github.com/Darewise/asyncapi-template-cpp-ue) — an Apache-2.0 AsyncAPI Generator template (`cpp-ue`) that renders a compilable Unreal Engine C++ module from an AsyncAPI 3.x document, last released v0.1.3 on 2023-12-11. It is tooling, not a client SDK, and the studio publishes no AsyncAPI document of its own.

Source: portfolio company of [serena](https://github.com/api-evangelist/serena) — legacy site https://www.darewise.com/ (offline)
