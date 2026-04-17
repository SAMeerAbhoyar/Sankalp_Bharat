# CarbonLens Work Done Tracker

This document tracks the cleaned and current project direction.

## Completed

- Finalized product identity as a smart ESG control tower for manufacturing SMEs
- Locked the product positioning to operations and governance first
- Kept AI as a supporting layer rather than the system core
- Restricted Scope 3 to a limited and realistic MVP
- Created and aligned the main project docs around CarbonLens
- Cleaned conflicting documentation that had pushed OCR-heavy and oversized MVP scope
- Updated README, idea, CRD, PRD, architecture, task plan, and pitch notes for one consistent story
- Generated `schema.sql` and established Supabase Postgres database architecture natively
- Implemented Database Postgres Triggers for automated Issue generation
- Provisioned Next.js codebase in the `/carbon-lens` directory
- Integrated `@supabase/ssr` database utilities and environment variables
- Created highly robust Calculation Engine Service backing Phase 2 requirements

## Current Status

- Core Database is live and secured with Row Level Security (RLS)
- Backend calculation logic (Phase 2 core) is actively established
- Ready to seed specific factor data and bridge APIs to the React frontend

## Removed or Simplified

- OCR-first ingestion assumptions from MVP scope
- Massive Scope 3 expectations from early planning
- Overly enterprise-heavy branch/task structure
- Duplicate README variants not needed for the project

## Next Recommended Work

1. Finalize the canonical tech stack in docs
2. Create implementation scaffolding
3. Seed demo data (Emission Factors)
4. Build core flows in this order:
   - Next.js Form Actions bridging Calculation Service
   - auth (Supabase session linkage)
   - data entry UI
   - dashboard
   - governance UI
   - report summary
   - AI-smart summary layer
