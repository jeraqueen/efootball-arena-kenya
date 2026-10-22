# eFootball Arena Kenya

A mobile-friendly Kenyan community eFootball tournament MVP for Mobile and console knockout events.

## Current MVP
- Email/password sign-up and sign-in using Supabase Auth
- Player profile setup (display name, username, platform and optional gamer tag)
- Public list of open tournaments
- Free tournament registration and a personal entry list
- Database-backed tournament, registration, match, dispute and payout tables with row-level security
- Paid entry is intentionally disabled pending legal, payment and prize-handling checks

## Services
- GitHub: https://github.com/jeraqueen/efootball-arena-kenya
- Supabase project: `slmonbtuwlwykfipkmau`
- Cloudflare Worker: `efootball-arena-kenya`
- Site: https://efootball-arena-kenya.study254.workers.dev/

## Notes
The Cloudflare Worker serves the committed `index.html` from this repository. The first two free events are test events; fixtures, match result confirmation, dispute resolution, and prize administration still require further implementation before any paid or high-stakes tournament is run.
