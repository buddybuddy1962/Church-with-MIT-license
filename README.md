church/README.md
# church MVP

Two-window Electron + React church projector MVP with offline provisioning and licensing UI.

## Features
- Two synchronized windows: Display and Control
- Manual offline provisioning flow (stubbed for MVP)
- Seed data for KJV and RVR-1909
- About Licensing section in README
- Minimal SQLite scaffolding (seed data path included)

## Licensing
This project uses the MIT License. See LICENSE for full terms.

## Setup (local development)
- Install dependencies: npm install
- Run: npm run start (Electron app)
- Development notes:
  - The Display window shows Bible text; the Control window is for adding songs and provisioning

## Provisioning (offline)
- Use the Offline Provisioning panel to set seed data, checksums, and provisioning metadata.
- Seed data exists in src/data/seed/bibles.json.

## How to contribute
- Fork this repo, implement features, and submit a PR. Ensure licensing info remains visible in README.
