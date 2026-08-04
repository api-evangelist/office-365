# Office 365 (office-365)

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

Microsoft Office 365 is a cloud-based suite of productivity and collaboration applications that integrates all Microsoft's existing online applications into a single platform including email, calendar, files, Teams, and SharePoint.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/office-365/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Cloud
- Collaboration
- Documents
- Email
- Enterprise
- Productivity

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-28

## APIs

### Microsoft Graph API

The primary API for Office 365, providing access to data and intelligence in Microsoft 365, Windows 10, and Enterprise Mobility + Security.

**Human URL:** [https://developer.microsoft.com/en-us/graph](https://developer.microsoft.com/en-us/graph)

**Base URL:** `https://graph.microsoft.com/v1.0`

#### Tags

- Calendar
- Graph
- Mail
- SharePoint
- Teams
- Users

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/graph/overview)
- [OpenAPI](https://raw.githubusercontent.com/microsoftgraph/msgraph-metadata/master/openapi/v1.0/openapi.yaml)
- [Authentication](https://learn.microsoft.com/en-us/graph/auth/)
- [SDKs](https://learn.microsoft.com/en-us/graph/sdks/sdks-overview)
- [Change Log](https://developer.microsoft.com/en-us/graph/changelog)

### Outlook Mail API

Access email, manage folders, send mail, and manage mail settings via Microsoft Graph.

**Human URL:** [https://learn.microsoft.com/en-us/graph/outlook-mail-concept-overview](https://learn.microsoft.com/en-us/graph/outlook-mail-concept-overview)

**Base URL:** `https://graph.microsoft.com/v1.0/me/messages`

#### Tags

- Email
- Mail
- Outlook

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/graph/api/resources/mail-api-overview)

### Outlook Calendar API

Access and manage calendar events, meeting requests, and calendar groups.

**Human URL:** [https://learn.microsoft.com/en-us/graph/outlook-calendar-concept-overview](https://learn.microsoft.com/en-us/graph/outlook-calendar-concept-overview)

**Base URL:** `https://graph.microsoft.com/v1.0/me/calendar`

#### Tags

- Calendar
- Events
- Meetings

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/graph/api/resources/calendar)

### OneDrive API

Access and manage files stored in OneDrive and SharePoint.

**Human URL:** [https://learn.microsoft.com/en-us/onedrive/developer/](https://learn.microsoft.com/en-us/onedrive/developer/)

**Base URL:** `https://graph.microsoft.com/v1.0/me/drive`

#### Tags

- Files
- OneDrive
- Storage

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/graph/api/resources/onedrive)

### Microsoft Teams API

Integrate with Microsoft Teams for chat, channels, meetings, and collaboration.

**Human URL:** [https://learn.microsoft.com/en-us/graph/teams-concept-overview](https://learn.microsoft.com/en-us/graph/teams-concept-overview)

**Base URL:** `https://graph.microsoft.com/v1.0/teams`

#### Tags

- Chat
- Collaboration
- Teams

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/graph/api/resources/teams-api-overview)

## Common Properties

- [Website](https://www.microsoft.com/en-us/microsoft-365)
- [Documentation](https://developer.microsoft.com/en-us/microsoft-365)
- [Authentication](https://learn.microsoft.com/en-us/azure/active-directory/develop/)
- [Status](https://status.office365.com/)
- [Support](https://learn.microsoft.com/en-us/answers/products/)
- [Blog](https://devblogs.microsoft.com/microsoft365dev/)
- [Terms of Service](https://www.microsoft.com/en-us/servicesagreement)
- [Privacy Policy](https://privacy.microsoft.com/)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
