# Healthcare software — performance, integrations, and operational ownership

[← Back to profile](../README.md)

**My role:** hands-on architecture, implementation, technical leadership, releases, and production support.

**Stack:** C# · ASP.NET Core · SQL Server · TypeScript · Linux containers · Valkey/Redis · Hangfire

## The problem

Healthcare software has to support the people operating it throughout the day. Slow queries, background-job contention, and integration failures interrupt work across teams.

At Octo Dev, I lead five engineers and coordinate 11 external healthcare and pharmaceutical integrations. My work connects customer discovery and technical design with implementation, rollout, and handoff.

## Performance work

On one constrained healthcare platform, I worked across the database, hosting, real-time messaging, and background-processing layers:

| Area | Change / result |
| --- | --- |
| Database | Optimized high-load stored procedures; database CPU consumption fell by approximately 10×. |
| Critical workflow | Reduced latency from more than 45 seconds to roughly 100 milliseconds. |
| Hosting | Migrated legacy hosting to Linux containers. |
| Shared state | Added a Valkey-backed real-time backplane and shared API rate-limit state across replicas. |
| Background work | Reconfigured Hangfire to support horizontal scaling. |

The performance figures are approximate outcomes from that platform, rather than a general benchmark or capacity guarantee.

## Integration ownership

I work through the full lifecycle: define the business behavior, agree on API and callback contracts, implement the connection, and make failures recoverable for operators. That includes retries, duplicate handling, authorization boundaries, and clear handoff procedures.

I also build LLM document workflows with Claude, GPT, and Gemini to extract structured information, apply decision logic, and trigger downstream actions.

## What this demonstrates

The ability to investigate problems across system boundaries, lead delivery while staying close to the code, and remain accountable for the result in production. This public summary excludes client source code, records, and internal integration details.
