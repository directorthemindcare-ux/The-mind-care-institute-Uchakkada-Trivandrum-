# Mind Care Institute App — V7

A production-oriented PWA starter for Mind Care Institute with three role areas:
- Parent / Family
- Therapist / Staff
- Director / Admin

## Included
- Official MC logo
- Installable PWA manifest + service worker
- Role-based interface
- Client, appointment, session-note, assessment, progress and report modules
- Local demo persistence
- Supabase/PostgreSQL schema from V6

## Demo
Open `index.html` in a browser or serve this folder with a local web server. Select a role and use any demo username/password.

## Production deployment
1. Create a Supabase project.
2. Run `supabase_schema.sql` in the Supabase SQL editor.
3. Configure authentication and role/profile records.
4. Replace demo localStorage actions with Supabase client calls.
5. Host the PWA on HTTPS (for example Vercel/Netlify/Cloudflare Pages).
6. Never put service-role keys in browser code.
7. Use minimum necessary access, audit logs, backups, consent and retention policies for clinical data.

This package is a deployment-ready starter, not a certified medical-record system. Obtain appropriate legal, privacy and clinical review before storing real patient data.
