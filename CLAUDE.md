# yeichnicholas/yeichnicholas: GitHub profile README

This repo renders the README on github.com/yeichnicholas. It holds a `README.md` and the
images it references. There is no build, no tests, no deploy step.

**A push to `main` here is publication.** The change is visible to anyone who opens his
profile within seconds. Treat every edit as outward-facing: get explicit approval before
pushing, and never push a draft.

## What this page is for

It supports the CTO track. The audience is Jaime Sepulveda, SPM, and anyone evaluating Nick
as a technical hire. It is not a hobby profile. Keep the framing on operations
infrastructure and shipped work, not on learning in public.

Current positioning, matching the rest of his properties:

- Building the automation layer for **Strategic Property Management (SPM)** ahead of joining
  as CTO.
- **LeaseLoom** (leaseloom.org) is the product proof point.
- **Yeich Media** (yeichmedia.com) is AI operations advisory, currently paused.

## Rules for images

- Use PNG, not SVG. GitHub's markdown pipeline is unreliable about SVG inside an HTML
  `<img>` tag.
- Check the alpha channel before adding a badge or logo. A transparent background with dark
  artwork disappears in GitHub's dark theme. The OpenAI badge here is safe because its card
  interior is opaque white.
- Size with an HTML `<img width="...">`. Bare markdown image syntax renders full width.

## Third-party marks

The OpenAI Select Partner badge is used under OpenAI's sharing guidance:

- Used **as provided**, unmodified.
- The phrase is **"OpenAI Select Partner"** exactly.
- Links to `https://openai.com/business/partners/`, the URL their guidance gives.
- The credential belongs to **YeichMedia LLC**, and the line under the badge says so. This
  is a personal profile, so an unattributed badge would read as a claim about Nick rather
  than about the company that holds the tier.

Full guidance and the asset kit live in the AI Executive Assistant repo under
`Brand Assests/`.

## Local copies

Work from this clone. `~/git-recovery-backups/yeichnicholas` is a stale copy and commits
made there will not reach GitHub.
