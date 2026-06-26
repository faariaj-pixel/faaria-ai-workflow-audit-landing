# Faaria Jessani — AI Workflow & Automation Audit Landing Page

A conversion-focused static landing page for Faaria Jessani's primary offer: the AI Workflow & Automation Audit for service-based businesses and operations teams.

## Live deployment

- Live Vercel URL: https://faaria-ai-workflow-audit-landing.vercel.app/
- GitHub repository: https://github.com/faariaj-pixel/faaria-ai-workflow-audit-landing
- Vercel project: faaria-ai-workflow-audit-landing

## Strategy summary

- Page goal: Convert visitors into discovery calls for an AI Workflow & Automation Audit.
- Target visitor: Service-based business owners, consultants, and operations teams that want practical AI adoption support but are overwhelmed by tools or unclear workflows.
- Core promise: Move from manual, inconsistent processes to clear, documented, AI-supported workflows that save time, reduce errors, and improve operational execution.
- Primary CTA: Book a 30-minute AI Automation Discovery Call.
- Secondary CTA: Request/download the AI Workflow Readiness Checklist.
- Design direction: Premium, warm, strategic-tech, authority-led, beginner-friendly.

## Files

- `index.html` — semantic landing page markup with SEO and Open Graph tags.
- `styles.css` — responsive premium design system.
- `checklist.html` — printable AI Workflow Readiness Checklist lead magnet.
- `og-image.svg` — branded Open Graph/social sharing image.
- `README.md` — setup, deployment, and QA notes.

## Local preview

From this folder:

```bash
python3 -m http.server 4173
```

Then open:

```text
http://localhost:4173
```

## Review notes and pending tasks

A separate review file is included so you can come back later without searching through the chat:

```text
NEXT_STEPS_AND_REVIEW_NOTES.md
```

Open it for the pending task list, recommended version 2 improvements, and prompts you can paste back into Leo when you are ready to make changes.

## Required replacements before publishing widely

The primary discovery CTA now opens a pre-filled email to `faariajess@gmail.com`. Replace it with a booking link later if you prefer Calendly, TidyCal, SavvyCal, or HubSpot Meetings.

The checklist CTA now links to `checklist.html`, a printable 25-question AI Workflow Readiness Checklist. If you later create an email opt-in form or hosted download, replace the checklist links with that URL.

The Open Graph image now uses `og-image.svg`. Replace it with a polished PNG/JPG brand asset later if desired.

## Proof/assets to add later

Do not invent these. Add only when real:

- Client testimonials.
- Before/after workflow screenshots.
- Measurable automation results such as hours saved or faster turnaround.
- Pilot audit case study.
- Email opt-in or CRM-connected AI Workflow Readiness Checklist form.
- Professional headshot or branded image.

## GitHub repository

The repository was created through Composio/GitHub:

```text
https://github.com/faariaj-pixel/faaria-ai-workflow-audit-landing
```

To connect this local folder to the remote manually if needed:

```bash
git remote add origin https://github.com/faariaj-pixel/faaria-ai-workflow-audit-landing.git
git push -u origin main
```

## Vercel deployment

The production deployment was created through Composio/Vercel:

```text
https://faaria-ai-workflow-audit-landing.vercel.app/
```

Static-site settings:

- Framework: Other / no framework
- Build command: blank
- Output directory: blank / project root

## QA checklist

- Hero names the audience and outcome clearly.
- One primary offer: AI Workflow & Automation Audit.
- One primary CTA: discovery call.
- Discovery CTA uses `mailto:faariajess@gmail.com`; checklist CTA links to `checklist.html`.
- No fake testimonials, fake logos, fake numbers, or fake guarantees.
- Mobile responsive CSS included.
- Accessible semantic HTML and skip link included.
- Anchors: `#method`, `#offer`, `#proof`, `#faq`, `#contact`, `#readiness-checklist`; checklist page links back to the main page.
- Static-site ready for Vercel.
