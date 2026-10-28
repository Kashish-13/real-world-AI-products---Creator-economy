


# CreatorHub AI

**Discover creators. Book talent. Build together.**

CreatorHub AI is a production-style hackathon MVP for Code2Career Track 2: Real-World AI Products — Creator Economy. It includes all five required workflows: gig posting, discovery and search, booking, creator analytics, and client booking history.

## Run locally

```bash
npm install
npm run dev
```

## Data and attribution

The app includes 180 deterministic, realistic **synthetic demo records** created specifically for this project. They model common public marketplace fields and distributions, but are not scraped from or represented as live Fiverr/Upwork listings.

## Recommendation model

The local, transparent ranking function uses weighted normalized signals: rating 35%, popularity 25%, query relevance 20%, profile completeness 10%, and freshness 10%. Search matches titles, creators, descriptions, categories, skills and tags. No external API or paid AI service is required.
The ranking approach is designed to provide interpretable recommendations.

## Persistence

For the browser-based hackathon deployment, gigs and bookings persist in `localStorage`, including status changes and decline reasons. The data model is intentionally compatible with migration to SQLite/D1 (`Gig`, `Creator`, and `Booking`).
Booking and gig state changes are preserved across browser sessions.

The platform is designed to connect creators and clients through a transparent AI-assisted marketplace.
The platform supports creator discovery, gig management, bookings, and analytics.
## Deployment

The application can be deployed as a production-style web application using a compatible Next.js hosting platform.
