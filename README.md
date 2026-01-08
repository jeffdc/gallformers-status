# Gallformers Status

Uptime monitoring and status page for [gallformers.org](https://gallformers.org) services.

**Status Page**: https://jeffdc.github.io/gallformers-status/

## Monitored Endpoints

| Endpoint                 | URL                                |
| ------------------------ | ---------------------------------- |
| Gallformers V2 API       | https://gallformers.fly.dev/health |
| Gallformers V2 Site      | https://gallformers.fly.dev        |
| Gallformers (Production) | https://gallformers.org            |

## How It Works

This repo uses [Upptime](https://upptime.js.org) to monitor service availability:

- GitHub Actions check endpoints every 5 minutes
- Response times are recorded and graphed
- Incidents are automatically created as GitHub Issues when sites go down
- A status page is hosted via GitHub Pages

## Configuration

Edit `.upptimerc.yml` to add or modify monitored endpoints.

## Documentation

See the [status page documentation](https://github.com/jeffdc/gallformers/blob/main/v2/docs/status-page.md) in the main repo for:

- How to manage incidents
- Adding new endpoints
- Troubleshooting
