# Faaria Jessani — AI Workflow & Automation Audit Landing Page

A conversion-focused static landing page for Faaria Jessani's primary offer: the AI Workflow & Automation Audit for service-based businesses and operations teams.

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

## Required replacements before publishing

The page intentionally uses placeholder CTA links. Replace both `mailto:faaria@example.com` links in `index.html` with one of these:

1. Your booking link, such as Calendly, TidyCal, SavvyCal, or HubSpot Meetings.
2. Your real business email address.
3. A form/lead-capture URL for the AI Workflow Readiness Checklist.

Also replace `og-image-placeholder.png` with a real Open Graph image if available.

## Proof/assets to add later

Do not invent these. Add only when real:

- Client testimonials.
- Before/after workflow screenshots.
- Measurable automation results such as hours saved or faster turnaround.
- Pilot audit case study.
- Real AI Workflow Readiness Checklist download link.
- Professional headshot or branded image.

## Manual GitHub deployment

GitHub CLI is not currently installed in this WSL environment, so use these manual steps after creating a GitHub repository:

```bash
git init
git add .
git commit -m "Add AI workflow audit landing page"
git branch -M main
git remote add origin <your-github-repo-url>
git push -u origin main
```

## Manual Vercel deployment

Vercel CLI is not currently installed in this WSL environment. To deploy manually:

1. Push this folder to GitHub.
2. Go to https://vercel.com/new.
3. Import the GitHub repository.
4. Framework preset: Other.
5. Build command: leave blank.
6. Output directory: leave blank or use `.`.
7. Deploy.

## QA checklist

- Hero names the audience and outcome clearly.
- One primary offer: AI Workflow & Automation Audit.
- One primary CTA: discovery call.
- Placeholder links are clearly marked.
- No fake testimonials, fake logos, fake numbers, or fake guarantees.
- Mobile responsive CSS included.
- Accessible semantic HTML and skip link included.
- Anchors: `#method`, `#offer`, `#proof`, `#faq`, `#contact`, `#readiness-checklist`.
- Static-site ready for Vercel.
