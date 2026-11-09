# Code With Faizan — Portfolio

A static, single-page portfolio with a supporting AI-product planning article and downloadable project resources.

## Contents

- `index.html` — portfolio homepage, conversion-focused project enquiry flow, product and project case studies.
- `insights/how-to-scope-an-ai-product.html` — SEO-friendly guide to scoping an AI-enabled product.
- `Faizan_Resume.pdf` — updated one-page resume.
- `Project_Brief_Checklist.pdf` — downloadable one-page project brief checklist.
- `screenshots/` — the original Android project screenshots used in the case studies.
- `og-image.jpg` — updated social-sharing image.
- `robots.txt` and `sitemap.xml` — crawler access and sitemap.

## Run locally

No package installation or build step is required. Open `index.html` in a browser, or serve the folder with any static web server.

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Deploy

This is a static site. Import the repository into Vercel and select **Other** as the framework preset. Use the portfolio folder as the project root, leave the build command empty, and deploy the static files. No environment variables are required for the portfolio itself.

Before attaching a new custom domain, update the canonical URL, Open Graph URL, article canonical URL and the sitemap host in the HTML/XML files.

## Enquiry flow and intentional limits

- The primary CTA opens a prefilled `mailto:` draft. It does not submit to a server.
- There is no contact-form backend, booking-calendar integration, mailing-list capture, email sequence or analytics provider configured.
- Public pricing, client testimonials, client logos, project budgets and booking availability were not added because no verified values were provided.
- The direct phone/WhatsApp contact link was removed from the public page and resume; email and established portfolio links remain.
- ArtifactLoop is explicitly marked as in active development. Agentic Bot is identified as an early-stage concept. Planned capabilities are not presented as finished features.

## Content integrity

The portfolio uses project details and counts that were present in the supplied portfolio/resume or the public ScanMate repository. Conversion statistics from the supplied essay were not copied into the site because the essay did not include traceable primary-source links for the specific claims.
