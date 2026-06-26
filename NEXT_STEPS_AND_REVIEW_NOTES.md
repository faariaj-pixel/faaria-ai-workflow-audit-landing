# Landing Page Next Steps and Review Notes

Use this file when you come back to review and revise the landing page.

## Live links

- Live Vercel page: https://faaria-ai-workflow-audit-landing.vercel.app/
- GitHub repository: https://github.com/faariaj-pixel/faaria-ai-workflow-audit-landing
- Local project folder: `/home/faaria/workspace/faaria-ai-workflow-audit-landing`

## Current status

Completed:

- Landing page created as static HTML/CSS.
- GitHub repository created through Composio.
- Files committed to GitHub.
- Vercel production deployment created through Composio.
- Production URL verified as publicly accessible.
- Local copy exists in the WSL project folder.

## Must-do before sharing widely

These are the important pending items.

1. Replace email CTA with a booking link when ready
   - Current CTA: pre-filled email to `faariajess@gmail.com`
   - File: `index.html` and `checklist.html`
   - Optional upgrade: replace with a Calendly/TidyCal/HubSpot meeting link.

2. Connect the AI Workflow Readiness Checklist to lead capture when ready
   - Current CTA links directly to `checklist.html`, a printable 25-question checklist.
   - Optional upgrade: replace with a CRM/email opt-in form or hosted PDF download.

3. Upgrade the Open Graph image if desired
   - Current image: `og-image.svg`
   - Optional upgrade: replace with a professionally designed PNG/JPG branded preview image for LinkedIn, WhatsApp, etc.

4. Review all copy for accuracy
   - Confirm the offer name.
   - Confirm the CTA wording.
   - Confirm the proof points are accurate and comfortable to publish.
   - Confirm whether the tone feels like you: clear, practical, warm, strategic, beginner-friendly, credible.

5. Decide whether this page should stay on the Vercel subdomain or move to a custom domain
   - Current live URL: `https://faaria-ai-workflow-audit-landing.vercel.app/`
   - Later option: connect a custom domain or subdomain.

## Proof/assets to add when available

Do not invent these. Add only real proof.

- Client testimonials.
- Pilot audit results.
- Measurable hours saved.
- Before/after workflow examples.
- Screenshots of automation workflows.
- Sample audit output.
- Professional headshot or branded founder photo.
- A short case study.

## Recommended version 2 improvements

1. Add a lead capture form for the checklist.
2. Turn the HTML checklist into a designed PDF download if preferred.
3. Add a short “What you receive after the audit” visual section.
4. Add a real case study or pilot example once available.
5. Add analytics/event tracking for CTA clicks.
6. Add a better social sharing image.
7. Add a short founder/photo section to build trust.
8. Add stronger examples of workflows you audit, such as onboarding, reporting, follow-ups, intake, SOPs, and document preparation.
9. Consider adding a simple pricing or “starting at” section only if you are ready to publish pricing.
10. Consider adding a form instead of only email/booking links.

## How to preview locally

From WSL:

```bash
cd /home/faaria/workspace/faaria-ai-workflow-audit-landing
python3 -m http.server 4173
```

Then open:

```text
http://localhost:4173
```

## How to ask Leo for changes later

Copy/paste one of these prompts:

```text
Leo, open my landing page project at /home/faaria/workspace/faaria-ai-workflow-audit-landing and help me revise the copy based on my notes.
```

```text
Leo, review NEXT_STEPS_AND_REVIEW_NOTES.md in my landing page project and help me make the pending changes.
```

```text
Leo, update the CTA links on my landing page. My booking link is: [paste link].
```

```text
Leo, I reviewed the live landing page and want these changes: [paste notes]. Please update the page, commit to GitHub, deploy to Vercel with Composio, and verify the live URL.
```

## Deployment reminder

After edits, the workflow should be:

1. Edit local files.
2. Preview locally.
3. Commit changes.
4. Push/update GitHub through Composio or git.
5. Redeploy/update Vercel through Composio.
6. Verify live URL returns HTTP 200 and shows the expected content.
