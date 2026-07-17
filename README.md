# Pet ClaimIQ — WEB (`pciq-web`)

**PET CLAIM IQ — WEB (index.html estimator). Dormant since Feb 2026.**
**This is NOT the iOS app** (that's `pet-claimiq`, no hyphen).
**This is NOT the engine** (that's `pet-claim-helper`).

- **Product:** Pet Claim IQ — B2B insurance claim estimator (read a vet bill + policy → tell you what you'll get back). This folder is the **web** codebase.
- **Entry point:** `index.html`. No Expo, no `eas.json` — **this does not ship to any app store.**
- **Last touched:** Feb 2026 (dormant). The active product is the mobile app.

### The three sibling folders (one character apart — read carefully)
| Folder | What it is |
|---|---|
| `pciq-web` (this folder, was `pet-claim-iq`) | Pet Claim IQ — **web** estimator (dormant) |
| `pet-claimiq` (no hyphen) | Pet Claim IQ — **LIVE iOS app** (TestFlight) |
| `pet-claim-helper` | **LIVE Express engine/API** on Render (`/api/pciq/analyze`) — do not archive |
