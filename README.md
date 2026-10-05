# BBP A2P SMS Opt-In Funnel

SMS opt-in landing page for Blackbook Properties' A2P 10DLC registration.

**URL:** https://messages.blackbookproperties.com

## Files

| File | What it is |
|---|---|
| `index.html` | Program A: client & partner SMS opt-in (conversational / transactional) |
| `realtors.html` | Program B: property alerts opt-in for real estate professionals (`/realtors`, alias `/agents`) — marketing use case, A2P campaign #2 |
| `A2P-CAMPAIGN-REALTORS.md` | Copy-paste answers for registering campaign #2 in Twilio Trust Hub |
| `terms.html` | Terms and conditions (`/terms`) |
| `privacy.html` | Privacy policy (`/privacy` and `/privacy-policy`) |
| `default.conf` | nginx configuration (clean routes without `.html`) |
| `docker-compose.yml` | nginx container + Traefik labels (automatic SSL) |

## Deploy to the VPS

1. Copy this folder to the VPS (where Traefik runs).
2. Inside the folder, run:

```bash
docker compose up -d
```

3. Traefik detects the container and issues the SSL certificate automatically.

## Updating content

The HTML files are mounted as read-only volumes. Edit the file and reload the page — no container restart needed (if nginx caches, run `docker compose restart`).
