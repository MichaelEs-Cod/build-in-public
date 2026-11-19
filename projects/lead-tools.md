# Lead tools

Tools I use to find and talk to small local businesses in Spain that need a better online presence.

## Pieces

| Tool | What it does | A real number |
|---|---|---|
| Demo site robot | Every day it finds businesses in Madrid without a website and builds a demo site for each one | 43 demo sites by Oct 3, 2026 |
| Portable kit | The same robot as a zip anyone with Claude can install; it asks for the region and adapts language, phone format and messages | Tested in Madrid and São Paulo, 6 languages |
| Profile diagnosis | From a Google Maps link: public data, position in 5 searches, a score from 0 to 100 and one image the business owner understands at a glance | Max. 5 searches per lead, it stops if Google asks for a CAPTCHA |
| `/lead` command | One entry point for every lead: finds or creates the folder, keeps a sheet and warns me about leads waiting for an answer | 10/10 test cases |
| Prospecting button (Nyvon) | I type a niche and a zone; a robot on my PC runs an open-source Maps scraper and lists who has no website, with a WhatsApp link | 36 businesses in ~30 s, 12 without a site |
| Map grid | Position in Google Maps in a 5×5 grid of the city, like paid tools do | 125 searches in ~1h30, cost 0 |

## Rules

- I send every message myself. Nothing is sent automatically.
- No lead data in public posts or in this repository.

## Stack

Python, Playwright, Node, Docker, Cloudflare Pages, Google Sheets, Claude Code skills.

## What the AI did and what I decided

The AI wrote the code and the tests. I decided the offer, what the image shows, the limits (5 searches, manual sending) and I talk to every lead.
