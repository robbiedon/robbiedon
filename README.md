# Hi, I'm Rob.

I lead the affiliate community program at [Posh](https://posh.vip), an event ticketing platform, and I build the internal software that runs it.

**100+ merged pull requests** into Posh's production monorepo since August 2026: a daily lifecycle engine that turns affiliate behavior into an event log and exactly-once messaging, a password-gated public community site, a cohort competition platform built without touching the live site, a lead-gifting pipeline with hard budget rails, a CRM routing waterfall, and the dashboards that run all of it. Everything was built with AI-assisted development as a pair programmer, and I own the specs, the data model, the adversarial reviews, and the on-call.

That code is private. The public record is here:

**[robbiedon-portfolio](https://github.com/robbiedon/robbiedon-portfolio)**: eight case studies with architecture, decisions, incidents, and outcomes, plus three small open-source utilities extracted from production:

- `hubspot-paginate`: read past HubSpot's 10,000-result search ceiling without losing ties at window boundaries
- `neon-jsonb-guard`: a static check for the `could not determine data type of parameter` error inside `jsonb_build_object`
- `atomic-round-robin`: derived-pointer round-robin with id-pinned undo, in single SQL statements, for drivers without transactions

I also cofounded Duffl.

**Stack I work in:** TypeScript, Hono, React, Tailwind, Neon Postgres, Drizzle, Inngest, Vercel, MongoDB, Redshift, HubSpot, Iterable, Slack.
