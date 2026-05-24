# Lokal — Hyperlocal Service Discovery

A voice-first hyperlocal service marketplace starting with plumbers in Roorkee.
Built to solve a real pain: finding reliable local service providers is broken in Tier-2/3 Indian cities.

## Stack
- Next.js 15 (App Router) + TypeScript
- Postgres (Neon) + PostGIS + Drizzle ORM
- Clerk authentication
- Tailwind CSS + shadcn/ui
- Leaflet maps
- Groq LLM for search intent parsing
- Sentry + Posthog for monitoring

## Status
🚧 In active development — Week 1 MVP

## Roadmap
- [x] Project setup
- [ ] Database schema + vendor registration
- [ ] Search with geospatial queries
- [ ] Hindi voice search (Week 3)
- [ ] WhatsApp integration (Week 4)
- [ ] Multiple service categories (Week 5)

## Local Development
```bash
npm install
cp .env.example .env.local  # then fill in your keys
npm run dev
```

## Built by
[Your name] — [your X/twitter] — [your LinkedIn]