# FarWork RO

Română: [README.ro.md](README.ro.md) · Demo video: se adaugă la publicare


A free mobile app for international workers in Romania (Nepal, India, Philippines, Sri Lanka, Bangladesh, Vietnam, Pakistan, Turkey, Arab countries, Thailand) and for their employers.

Available in 12 languages: Romanian, English, Nepali, Hindi, Tagalog, Sinhala, Bengali, Vietnamese, Urdu, Turkish, Arabic, Thai.

## What it does

- **2026 salary calculator and payslip checker**: net from gross and back, overtime, night and weekend pay, differences against what you actually received.
- **Cloud timesheet with photo proof**: one-tap check-in, visual calendar, proof photos, a clear history of hours worked.
- **Legal guide for OUG 32/2026**: 90-day countdown after the work contract, contract clauses explained simply, a case timeline you can export to PDF.
- **SOS**: emergency numbers (112, labour inspectorate, immigration office, embassies) one tap away.
- **Private vault**: your documents stay yours, with GDPR protection.
- **Community**: posts, city groups, polls, events, a local marketplace.
- **Safe housing, money, career, learning**: practical guides, remittances, Romanian language with exercises and audio.
- **Employer mode**: a separate space for companies, kept apart from workers' data.

## Who it is for

Workers coming to Romania who want to know their rights, pay and legal steps in their own language. And companies that want fair relations with their staff.

## Tech

Expo SDK 58, React Native, TypeScript, Supabase (auth, Postgres with RLS on all tables, storage).

## Run locally

```bash
npm install
npx expo start
```

Static web build: `npx expo export -p web`.

## Privacy

Personal data is never public. Community posts can be anonymous. See the privacy policy in `web-legal/`.

## Contact

support@farwork.ro
