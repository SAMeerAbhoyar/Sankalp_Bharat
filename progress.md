# CarbonLens Progress

## Current Status

Documentation planning pack created. Project concept, scope, design direction, system architecture, API shape, and demo flow are now documented and aligned.

## Decision Log

- Selected product name: `CarbonLens`
- Chosen audience: manufacturing SMEs
- Chosen build strategy: practical MVP
- Positioning: single source of truth for ESG and GHG data
- Core value: actionability plus accountability, not dashboarding alone
- Scope 3 approach: limited but meaningful
- AI role: optional enhancement, not core logic

## Completed Items

- Problem statement interpretation
- Project ideation
- CRD planning
- UX and design planning
- Technical stack definition
- System architecture planning
- Data model outline
- API contract draft
- Demo script draft
- Pitch notes draft
- Initialized Next.js `carbon-lens` repository scaffolding
- Setup Supabase Auth / PostgreSQL database
- Designed and executed `schema.sql` establishing 7 core relational tables
- Implemented Row-Level Security (RLS) and Webhook Triggers for automated governance
- Built `src/lib/services/emissions.ts` core Calculation Engine for Scope 1, 2, and CSV batch processing.

## In Progress

- Next.js Server Actions and API Routing integration
- Seeding the `emission_factors` database table
- Connecting calculation logic to Next.js Client components

## Blockers

- No active blockers. The database is successfully connected to the codebase.

## Risks

- Scope creep during implementation
- Over-focus on AI instead of core flows
- Underestimating seeded data preparation
- Spending too much time on export polish

## Next Immediate Tasks

- Seed the `emission_factors` and `organizations` tables in Supabase
- Build Server Actions bridging the frontend forms to the `emissions.ts` calculation service
- Develop the Dashboard UI components mapped to our backend APIs

## Demo Readiness Checklist

- [x] Problem and solution story defined
- [x] Core MVP scope defined
- [x] User roles documented
- [x] Main screens planned
- [x] Data entities listed
- [x] API contract drafted
- [x] Demo script prepared
- [x] Pitch notes prepared
- [ ] Implementation started
- [ ] Seeded demo data created
- [ ] UI demo built
- [ ] Report output built

## Timestamped Updates

- `2026-04-17 11:29 IST` Problem statement sourced from `SKB-P1.pdf`
- `2026-04-17 11:40 IST` Product direction narrowed to practical MVP for manufacturing SMEs
- `2026-04-17 11:55 IST` Documentation-only hackathon planning pack approved
- `2026-04-17 12:10 IST` Documentation files created for implementation handoff

## Notes From Reviews Or Pivots

- Keep the narrative grounded in real operational pain
- Do not present the solution as full regulatory compliance software
- Protect time for a polished and simple demo story

