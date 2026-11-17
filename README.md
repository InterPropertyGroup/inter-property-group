# INTER PROPERTY GROUP platform

Starter application for INTER PROPERTY GROUP LIMITED (UK company number 16816787).

## Product direction
The product and platform brand is **INTER PROPERTY GROUP**. This is intended to become an international, multi-agency property management platform.

## Stack
- Next.js / React / TypeScript
- Supabase / PostgreSQL / Auth / Storage
- Vercel hosting
- GitHub source control

## Current starter scope
- Branded agency dashboard
- Property portfolio screen
- International country and currency fields
- Initial multi-tenant database schema and row-level security policies

## Local setup
1. Install Node.js LTS.
2. Create a new Supabase project.
3. Copy `.env.example` to `.env.local`.
4. Add the Supabase project URL and anon key.
5. Review and apply `supabase/migrations/0001_initial_schema.sql` in the Supabase SQL editor.
6. Run `npm install`.
7. Run `npm run dev`.

## Important security and production work still required
This is a starter scaffold, not a production-ready property-management service. Before real data or external agency onboarding:
- Implement trusted organisation bootstrap and invitation flows.
- Add server-side authorisation and role-specific permissions for every module.
- Add audit logging, rate limits, secure file upload, backups and monitoring.
- Add organisation/workspace switching for users belonging to multiple agencies.
- Review RLS policies and test cross-tenant isolation.
- Add privacy, retention, data export/deletion and regional hosting decisions.
- Review legal, tax, client-money and tenancy workflows with qualified advisers in each operating country.

## Naming
- Brand/product: INTER PROPERTY GROUP
- Legal entity: INTER PROPERTY GROUP LIMITED
- Company number: 16816787

Do not place real customer or financial data in this starter until security review and production controls are complete.
