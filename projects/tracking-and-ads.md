# Tracking and ads analysis

I come from Google Ads. Now I use code to check that the numbers are true before any money is spent.

## Pieces

| Work | Lesson | Real number |
|---|---|---|
| Tracking skill ([public repo](https://github.com/MichaelEs-Cod/claude-skill-advanced-tracking)) | Test the published page, not only the preview | 68/68 checks on the live page |
| Tracking an online store | A purchase is counted once, by the server, with the real value | 70/70 checks, 7 visitor scenarios |
| Site I can't edit | Everything through Google Tag Manager, with an automated test | 30/30 checks |
| Ad account audit through the API (read-only) | One wrong letter in a conversion label | ~279 € in 4 months with 0 conversions recorded |
| Meta ads audit through the official MCP | I locked every write tool before using it | 42/42 write tools need my confirmation |
| Performance Max audit | The robot optimizes for what you count as a conversion | 94 % of the spend went to Discover |

## Stack

Google Tag Manager, GA4, Google Ads API (read-only), Meta MCP, Playwright tests, Python.

## What the AI did and what I decided

The AI pulled the data, wrote the scripts and the reports. I decided what to measure, what counts as a real contact, the locks, and what to change in each account (with the client's approval).
