[README.md](https://github.com/user-attachments/files/33709567/README.md)
# Refugee Shield

**Practical digital safety for displaced communities.**
A flagship initiative of Refuge To Reach Tech Hub, built in Kakuma Refugee Camp, Kenya.

## Why this exists

Refugees are targeted every day by fake scholarship offers, fake resettlement forms, mobile money fraud, and unverified aid links. Most people have nobody to ask, and most safety advice is written in complex English for people with fast, reliable internet.

Refugee Shield is built by someone who teaches digital safety inside the camp, for the people who face these scams.

## What is in this repository

This repository holds the **Refugee Shield website prototype**: a single `index.html` file with no build step and no external dependencies. It uses Arial and inline SVG, so it loads quickly on slow connections.

The site includes:

- **Threat alerts and quick checks:** an educational sample alert and a search box that checks the example on the page (it cannot verify real links or numbers).
- **Scam practice:** three short scenarios (fake scholarship, mobile money PIN, unverified aid link) with no login, no score, and no judgement.
- **Google's Be Scam Ready game:** linked from the practice section. It is a separate, free game by Google and Filament Games and opens on Google's website. It is not part of this project.
- **Refugee Shield curriculum:** five modules (Understand, Identify, Prevent, Respond and Report, Support).
- **Anonymous reporting form:** collects scam type, channel, and a description, with no names and no legal-status questions. See "Current status" below.
- **Community section:** guidance for tech hubs, youth ambassadors, and supporting people without blame.

## Current status

This is an early prototype, and I want to be clear about what works today:

- The website, scenarios, and curriculum modules work.
- **The reporting form is not yet connected to a backend.** Until a secure endpoint is set in `REPORT_ENDPOINT` (near the bottom of `index.html`), submitting shows "Reporting is not connected yet. Nothing was sent."
- The facilitator guide (PDF) is not yet published.
- The site is in English only. Dinka, Nuer, Somali, Arabic, and Swahili versions are planned.
- The impact figures on the page are illustrative, not live programme statistics.

## The bigger vision

The full Refugee Shield platform is designed as a multilingual, offline-first digital safety app (PWA and Android) for displaced communities across East Africa. It is fully blueprinted, with a nine-month deployment roadmap, and is not yet built. Planned features:

- AI language simplification for confusing messages and documents
- Anonymous incident reporting
- Gamified phishing detection
- A verified opportunities directory

Languages planned: Dinka, Nuer, Somali, Arabic, and Swahili.

## Run it locally

No installation needed. Download `index.html` and open it in any browser.

To publish with GitHub Pages: **Settings → Pages → Deploy from branch → main → / (root) → Save**.

## Privacy and safety

- Do not enter names, phone numbers, document numbers, or passwords anywhere on the site.
- Screenshot files selected in the report form are never uploaded. Only whether a screenshot was selected is recorded.
- Before connecting the reporting form to a backend, decide who can read the reports, where they are stored, and for how long, and update the privacy policy on the page to match.

## Get involved

I am looking for partners, mentors, and funders who want to help build and pilot Refugee Shield with learners in Kakuma, and for developers and translators who can help with the app and with local-language content.

Open an issue or reach out through my GitHub profile.

## Credits

- **Built by:** Makuei Geu Makuei, cybersecurity specialist and community educator, Kakuma Refugee Camp, Kenya.
- **Be Scam Ready** is a game by Google, developed with Filament Games. All rights belong to their owners. This project only links to it.
- Scam scenarios and curriculum text are original educational content written for this project.

## Licence

Add a licence before inviting contributions. [MIT](https://choosealicense.com/licenses/mit/) is a simple option for open code. If you want to share the curriculum text more freely, consider [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) for the content.
