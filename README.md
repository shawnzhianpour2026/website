# Shawline Truck — Towing Website

Static website (HTML/CSS/JS, no build step) for Shawline Truck towing & roadside assistance.

## Pages
- `index.html` — Home: hero banner, stats, services, why us, how it works, testimonials, service area, call-to-action, map
- `about.html` — About: story, stats, values, fleet, team, call-to-action
- `contact.html` — Contact: contact info, request form, FAQ, map

Open `index.html` in a browser to view it.

## Before going live, replace the placeholders
| Placeholder | Where |
|---|---|
| `(555) 123-4567` / `tel:+15551234567` | all pages (phone + call buttons) |
| `info@shawlinetruck.com` | all pages |
| `123 Main Street, Your City, ST 00000` | all pages |
| Map `q=123+Main+Street` in the `<iframe>` | `index.html`, `contact.html` |
| Service-area names, stats and testimonials | `index.html`, `about.html` |

The contact form currently only shows a thank-you message. To receive submissions,
point it at a form service such as Formspree (set `action` and `method="POST"` on
`#contact-form` and remove the submit handler in `js/main.js`).
