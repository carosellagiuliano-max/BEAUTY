# BeautifyPRO Demo on Replit

This repository is a presentation build of BeautifyPRO. Keep it in mock mode unless
real Supabase, SMTP and payment credentials are deliberately configured.

## Commands

- Preview: `pnpm dev:replit`
- Build: `pnpm build`
- Production start: `pnpm start:replit`

The Replit config binds Next.js to `0.0.0.0` and uses Replit's `PORT`
environment variable. If `PORT` is not set, it falls back to `3000`.

## Demo Accounts

- Admin: `admin@beautifypro.demo` / `beauty-admin-demo`
- Customer: `kunde@beautifypro.demo` / `beauty-kunde-demo`
- Staff: `staff@beautifypro.demo` / `beauty-staff-demo`

## Deployment Notes

- Do not add production secrets to Git.
- Add real secrets only through Replit Secrets if this demo is later connected to
  a real backend.
- The current deployment target is a mock-data demo for presentations.
