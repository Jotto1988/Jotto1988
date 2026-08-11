Hi there, I'm Jarrit Hosking.

Founder @ Forge Vertical | Lead Architect of Aurora Repair

I build enterprise operating systems for the automotive, logistics, and hospitality
sectors — vertical SaaS that automates complex workflows using AI and cloud-native
architecture. Self-taught, AI-directed development: if I can describe a system
clearly enough, I can build it end-to-end and ship it to production.

Not everything here is a business. Some of it is curiosity and craft — built to
learn something, test an idea, or just because it was fun to figure out. All of
it is built the same way: real code, real accountability, no shortcuts on the
parts that matter.

## Current Ventures

- **[Forge Vertical](https://forgevertical.com/)** — Venture studio building
  high-value vertical software, with AI/GEO indexing infrastructure as a core
  service.
- **[Aurora Repair](https://aurora-repair.com/)** — AI-driven vehicle damage
  assessment platform bridging insurers and repairers, currently processing
  live claims in South Africa. 🇿🇦
- **[TripSpace Global](https://tripspaceglobal.com/)** — Commission-free
  accommodation marketplace, live and processing real bookings and payments.

## Open Source

- **[Task Bridge](https://github.com/Jotto1988/task-bridge)** (new) — An open
  concept for routing AI-generated human-in-the-loop work back to real people,
  with bug-bounty-style claim locking, turnaround windows, and mutual
  reputation. Published for the community to test, critique, and build on.

## Tech Stack

**Core:** Node.js, TypeScript, Python, Hono
**Cloud:** Google Cloud Platform (Cloud Functions, Secret Manager, Cloud Run), Cloudflare
**Database:** Firestore (NoSQL), Cloud SQL
**AI/ML:** Vision API, Custom OCR Models
**Payments:** PayFast integration (South African market)

## Security & Practices

- **Access control by design:** server-side execution logic, no client-side
  exposure of sensitive operations, managed secrets.
- **Data-handling discipline:** architecture built with POPIA/GDPR principles
  in mind — access control, encryption, and audit trails treated as
  requirements, not afterthoughts.
- Independently found and fixed a real Firestore access-control bug in
  production — the kind of thing that only shows up under careful, systematic
  review, not luck.
