# Twilio ISV SMS Onboarding Demo

A clickable prototype that shows how an ISV marketing platform can onboard its customers to SMS with Twilio. It covers two markets:

- **🇺🇸 United States** uses a toll-free number, the Compliance Embeddable, and the Compliance Toolkit.
- **🇪🇸 Spain** uses an alphanumeric sender ID registered with the CNMC, plus the AlphaSender API.

**Live demo:** https://joshskifstrom.github.io/twilio-isv-onboarding-demo/

## Controls

| Key | Action |
|---|---|
| `→` / `←` | Next / previous step |
| `1` / `2` | Switch to US / Spain |
| `B` | Toggle the behind-the-scenes panel |
| `N` | Toggle the talk track |
| `W` | Outline the embedded Compliance Embeddable area (US) |
| `R` | Reset |

This is a single static `index.html` with no build step and no dependencies. All data is fictional, and no real API calls are made.
