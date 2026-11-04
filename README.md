# Threadwell · a customer success portfolio

In 2019 I built a customer success department from scratch. This is how I'd build it today, with AI agents in the loop.

**See it live:** https://odydyna.github.io/threadwell

Threadwell is a fictional B2B SaaS company: a year round team connection platform for remote and hybrid companies of 100 to 500 people. Wobbly Goat Analytics is its fictional customer. Every name, number and date here is made up.

## What's here

| Path | What it is |
|---|---|
| `docs/` | The portfolio page: the company, the customer success AI loop, a before and after, and the case study. |
| `skills/discovery-call-prep/` | Claude skill that prepares a CSM for a discovery call. |
| `skills/onboarding-kickoff/` | Claude skill that plans a new customer's first 30 days, including how to bring skeptics in. |
| `skills/renewal-prep/` | Claude skill that prepares a renewal 120 days out with an honest value review. |
| `dist/` | Each skill as a zip, ready to upload to Claude (Settings, Capabilities, Skills). |
| `test-inputs/` | Sample Wobbly Goat account data for trying the renewal skill. |
| `decks/` | Source for the four customer decks: onboarding kickoff, month 3 check in, six month review, annual value review. |

## How the skills learn

Each skill ends with a **Lessons learned** log. When a call teaches us something, a person approves a change to the skill, and every future call benefits. AI does the noticing. People do the deciding.

## About me

Olivia Dydyna · customer success · https://www.linkedin.com/in/oliviadydyna
