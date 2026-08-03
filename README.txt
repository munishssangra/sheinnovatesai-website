She Innovates AI — Website Files
=================================
Site:    https://sheinnovatesai.com
Owner:   Tandeep Sangra
Email:   team@sheinnovatesai.com
Repo:    https://github.com/munishssangra/sheinnovatesai-website
Updated: August 2026

=================================
RELATED PRODUCT — AI SEARCH VISIBILITY INTELLIGENCE PLATFORM
=================================

A separate, related product lives at https://audit.sheinnovatesai.com — NOT part of
this repo. Different hosting stack: static HTML frontend on GitHub Pages, backend on
Vercel (serverless functions) + Supabase (lead storage). Update it via its own
separate repo, not this one.

  - AI Visibility Check   — free, live today, the current self-serve scan tool
  - AI Citation Tracker    — paid subscription, in development (MVP2)

See PRODUCT ROADMAP section below for full detail. This main site's llms.txt now
cross-references the platform's pages so AI systems can find and cite both properties
correctly.

=================================
DEPLOYMENT — GITHUB PAGES (LIVE)
=================================

Step 1 — Unzip into your local repo folder:
  cd ~/Desktop
  unzip -o FINAL_PUSH.zip -d sheinnovatesai-website

Step 2 — Navigate to the repo:
  cd ~/Desktop/sheinnovatesai-website

Step 3 — Stage, commit, and force push:
  git rm -r --cached .
  git add -A
  git commit -m "Complete site update: August 2026"
  git push origin main --force

Step 4 — Wait 2–3 minutes, then check:
  https://sheinnovatesai.com

NOTE: Open in an incognito window to bypass browser cache.

If you get a "permission denied" error on push:
  git remote set-url origin https://munishssangra@github.com/munishssangra/sheinnovatesai-website.git
  Then push again. Use a GitHub Personal Access Token as your password.
  Generate one at: github.com → Settings → Developer settings → Personal access tokens

=================================
AFTER DEPLOYING — ACTION CHECKLIST
=================================

□ Submit sitemap to Bing Webmaster Tools (CRITICAL — feeds ChatGPT Browse)
  https://bing.com/webmasters
  Sitemap URL: https://sheinnovatesai.com/sitemap.xml

□ Submit sitemap to Google Search Console
  https://search.google.com/search-console
  Sitemap URL: https://sheinnovatesai.com/sitemap.xml

□ Request indexing for 5 priority pages in Google Search Console:
  1. https://sheinnovatesai.com/
  2. https://sheinnovatesai.com/aeo-services/
  3. https://sheinnovatesai.com/tandeep-sangra/
  4. https://sheinnovatesai.com/what-is-aeo/
  5. https://sheinnovatesai.com/blog/

□ Validate schema on key pages:
  https://search.google.com/test/rich-results
  Test: /aeo-services/ | /tandeep-sangra/ | /what-is-aeo/ | /ai-seo-pricing/

□ Verify robots.txt is live:
  https://sheinnovatesai.com/robots.txt

□ Verify llms.txt is live:
  https://sheinnovatesai.com/llms.txt

□ Verify sitemap is live:
  https://sheinnovatesai.com/sitemap.xml

=================================
SITE STATISTICS (AUGUST 2026)
=================================

Total pages:   54 HTML pages + 404.html
Blog posts:    14 expert AI SEO guides
Sitemap URLs:  53
Special files: sitemap.xml, robots.txt, llms.txt, favicon.svg, .nojekyll

NOTE: Figures above cover this repo (sheinnovatesai.com) only. The AI Search
Visibility Intelligence Platform (audit.sheinnovatesai.com) is tracked separately —
see PRODUCT ROADMAP section.

=================================
COMPLETE FILE STRUCTURE
=================================

ROOT FILES
----------
index.html              Homepage — AI Visibility Research Company, AEO, GEO, LLM Optimization
404.html                Custom 404 — enhanced with nav, footer, 9 explore cards
favicon.svg             Site favicon — navy background with amber "S"
sitemap.xml             XML sitemap (53 URLs, submit to Google + Bing)
robots.txt              Crawler permissions — all AI bots explicitly welcome
llms.txt                AI system context file — structured briefing for LLMs, now includes
                        the AI Search Visibility Intelligence Platform product section
.nojekyll               GitHub Pages build bypass (required)
README.txt              This file

SERVICE PAGES
-------------
aeo-services/           Answer Engine Optimization — pricing under review
geo-services/           Generative Engine Optimization — pricing under review
llm-optimization/       LLM Optimization Consulting — pricing under review
ai-visibility-consultant/ AI Visibility Consulting — from $2,500/month (retainer)
ai-seo-audit/           AI SEO Audit — from $247 (one-time, credited to projects)
schema-markup-services/ Schema Markup & Structured Data — from $147
llm-content-strategy/   LLM Content Strategy — pricing under review
ai-citation-monitoring/ AI Citation Monitoring — from $300/month
services/               Full services menu page
ai-seo-pricing/         Transparent pricing for all services

ABOUT / COMPANY PAGES
----------------------
tandeep-sangra/         Tandeep Sangra bio, credentials, methodology
about/                  About She Innovates AI — mission and story
contact/                Book a Free Strategy Call
testimonials/           Client testimonials with star ratings
case-studies/           Measurable results from real projects

EDUCATIONAL PAGES (LEARN)
--------------------------
what-is-aeo/            What is AEO? — complete explainer
what-is-geo/            What is GEO? — complete explainer
what-is-llm-optimization/  What is LLM Optimization?
aeo-vs-geo-vs-ai-seo/   AEO vs GEO vs AI SEO — key differences
ai-seo-vs-traditional-seo/  AI SEO vs Traditional SEO
how-chatgpt-ranks-brands/   How ChatGPT ranks and cites brands
how-perplexity-cites-sources/  How Perplexity selects citations
google-ai-mode-seo/     Google AI Overviews optimization guide 2026
ai-seo-glossary/        AI SEO Glossary — 35+ terms defined
ai-seo-checklist/       Free 50-Point AI SEO Checklist (interactive, no gate)

INDUSTRY PAGES
--------------
ai-seo-for-saas/        AI SEO for SaaS Startups
ai-seo-for-ai-products/ AI SEO for AI Product Companies
ai-seo-for-b2b-tech/    AI SEO for B2B Tech Companies
ai-seo-for-consultants/ AI SEO for Consultants & Independent Experts
ai-seo-for-fintech/     AI SEO for FinTech Companies
ai-seo-for-agencies/    AI SEO for Marketing Agencies
ai-seo-for-healthcare/  AI SEO for Healthcare Tech
ai-seo-for-edtech/      AI SEO for EdTech Platforms
ai-seo-for-ecommerce/   AI SEO for eCommerce & D2C Brands
ai-seo-for-web3/        AI SEO for Web3 Startups

BLOG — 14 EXPERT GUIDES (APRIL 2026)
--------------------------------------
blog/                           Blog index page
blog/how-to-rank-in-chatgpt/              Apr 1, 2026
blog/why-your-brand-is-invisible-to-ai/   Apr 3, 2026
blog/aeo-vs-seo-whats-different/          Apr 5, 2026
blog/schema-markup-for-ai-citations/      Apr 8, 2026
blog/ai-seo-audit-complete-guide/         Apr 9, 2026
blog/how-perplexity-ranks-content/        Apr 10, 2026
blog/geo-guide-generative-engine-optimization/  Apr 11, 2026
blog/llms-txt-complete-guide/             Apr 12, 2026
blog/entity-seo-for-ai-search/            Apr 13, 2026
blog/ai-seo-for-saas-companies/           Apr 14, 2026
blog/google-ai-overviews-optimization/    Apr 15, 2026
blog/ai-seo-content-strategy/             Apr 16, 2026
blog/tandeep-sangra-ai-seo-expert/        Apr 17, 2026 (authority/entity post)
blog/ai-citation-monitoring-guide/        Apr 18, 2026

NOTE: 13 additional posts published May–July 2026 (law firms, doctors & clinics,
real estate, healthcare, social platforms, AI Overviews traffic, SEO relevance).
See llms.txt Blog Posts section for the complete, current list with dates and URLs.

UTILITY PAGES
-------------
privacy-policy/         Privacy Policy
terms-of-service/       Terms of Service
sitemap-page/           Human-readable sitemap

=================================
PRICING SUMMARY (CONSISTENT ACROSS ALL PAGES)
=================================

Quick Start (one-time):
  Citation Snapshot:         from $97
  Schema Markup Setup:       from $147
  AI Visibility Audit:       from $247

Project-Based (one-time):
  AEO / GEO / LLM project:  pricing under review, contact for current rate

Monthly Retainer (ongoing):
  AI Visibility Consulting:  from $2,500/month
  AI Citation Monitoring:    from $300/month (standalone)

NOTE: Audit cost ($247) is credited in full toward any follow-on project.

⚠ IMPORTANT: If any external document (pitch deck, investor materials, internal
guides) shows a $697/month retainer figure, that is INCORRECT and does not match
this site or llms.txt. The confirmed, current retainer price is $2,500/month —
verify and correct any document showing otherwise before sharing it externally.

⚠ UNCONFIRMED: This README previously listed "LLM Visibility Report ($197)" as a
Quick Start item. llms.txt (August 2026) does not mention this product at all, but
does list "Citation Snapshot ($97)" as a similar quick-start item not previously in
this README. These may be the same offering renamed, or two genuinely different
products — this has NOT been confirmed either way. Verify directly before treating
either name/price as final.

=================================
PRODUCT ROADMAP — AI SEARCH VISIBILITY INTELLIGENCE PLATFORM
=================================

Separate product at https://audit.sheinnovatesai.com. Full technical detail lives in
the Product_Roadmap_How_It_Works document; this is the high-level summary.

MVP1 — LIVE TODAY
  AI Visibility Check: free, one-time scan across 5 categories (Schema & Structured
  Data, Entity Authority, AI Crawlability, Trust Signals, Content Machine-Readability).
  A work email is required to run the scan.

MVP2 — IN DEVELOPMENT
  AI Citation Tracker: paid subscription, weekly automated tracking of whether
  ChatGPT and Perplexity actually cite the brand for real target queries.
  Plus four additional capabilities:
    - Persona-Driven Query Generation — auto-suggests realistic buyer-persona
      queries instead of requiring manual entry (manual add/edit always available)
    - Persona-Driven Intelligence — builds buyer personas from brand content
    - Prompt Simulation & Content Opportunities — surfaces competitor citation
      gaps outside the tracked query set
    - Smart Fix Suggestions — auto-drafted schema/page-edit fixes, always
      reviewed by a human expert before delivery, never sent automatically

MVP3 — PLANNED
  Expand tracking to Google AI Mode and Gemini/Copilot. Deepen enterprise
  reporting tier. Planned once MVP2 has validated real subscriber demand.

Pricing (product, self-serve):
  AI Visibility Check:    Free
  AI Citation Tracker:    $89–199/month (final price point still being finalised —
                          see Features_and_Pricing_Math document for full reasoning)

=================================
RECENT UPDATES (APRIL 2026)
=================================

Navigation & Footer
  ✓ Blog added to header Learn mega menu, footer Learn column, and mobile nav
  ✓ "Case Studies" footer link fixed → /case-studies/ (was pointing to /testimonials/)
  ✓ Nav CTA text: "30 mins, no obligation, real insights"

Design & Visibility
  ✓ Favicon (favicon.svg) added to all 54 pages
  ✓ Hyperlinks on dark backgrounds: amber #F59E0B (was invisible blue)
  ✓ Footer logo tagline opacity: 0.55 (was 0.25)
  ✓ Footer nav links opacity: 0.65 (was 0.40)
  ✓ Footer copyright text opacity: 0.50 (was 0.20)
  ✓ "Before AEO" citation text opacity: 0.70 (was 0.30)

Functionality
  ✓ FAQ accordion fixed on all 53 pages (CSS/JS mismatch resolved)
  ✓ ai-citation-monitoring FAQ: invisible .fu class → visible .fade-up
  ✓ 404 page: broken CSS :root block fixed (hero background now renders)

Content & Pages
  ✓ ai-seo-checklist: rebuilt as simple static page (removed OTP/gate flow)
  ✓ ai-seo-checklist: sidebar added (CTA, live score counter, service links)
  ✓ 404: fully rebuilt with nav, footer, and 9-card explore grid
  ✓ Industry pages (8 pages): banner hero description centred
  ✓ Pricing Quick Start card: shows audit deliverables (not sub-service prices)

Pricing
  ✓ Monthly Retainer updated: $1,500/mo → $2,500/mo (across all pages)
  ✓ Pricing page Quick Start card: clear, no confusing sub-prices
  ✓ All pricing consistent across homepage, services, pricing, and industry pages

Trust Badges (Homepage)
  ✓ Updated to: ✓ Serving Global Clients | ✓ 4–6 Wk Results | ✓ Hire Us on Upwork

SEO / AI Crawlability
  ✓ robots.txt: updated with all 2026 AI crawlers (OAI-SearchBot, ClaudeBot, Gemini-AI,
    cohere-ai, Applebot-Extended, FacebookBot, Applebot, msnbot)
  ✓ llms.txt: fully expanded with all pages, pricing, blog dates, entity info
  ✓ Sitemap: includes all 53 URLs including all 14 blog posts

=================================
RECENT UPDATES (AUGUST 2026)
=================================

Positioning
  ✓ Brand description updated: "AI SEO consultancy" → "AI Visibility Research
    Company" across llms.txt and preferred citation format (consistency fix)
  ✓ Industry list in llms.txt citation format broadened to match the actual
    10 industry pages (was narrowly scoped to "B2B SaaS and technology brands")

Pricing
  ✓ AI Visibility Audit corrected: $297 → $247 (llms.txt and this README now match)
  ✓ Schema Markup Setup corrected: $150 → $147 (llms.txt and this README now match)
  ✓ Flagged: external documents referencing a $697/month retainer are incorrect —
    confirmed current price is $2,500/month, matching this site and llms.txt
  ✓ Removed stale $1,500-per-project pricing for AEO, GEO, LLM Optimization
    Consulting, and LLM Content Strategy — marked "pricing under review" pending
    confirmation of current rates, rather than displaying a number known to be wrong

Contact
  ✓ Primary contact email updated: tan.sangra@gmail.com → team@sheinnovatesai.com
    (this file and llms.txt)

Product
  ✓ llms.txt expanded with a full AI Search Visibility Intelligence Platform section
  ✓ 9 new product pages built for audit.sheinnovatesai.com: Home, How It Works,
    Capabilities, Persona Intelligence, Smart Fix Suggestions, Roadmap, Solutions,
    Use Cases, Pricing — separate repo, cross-referenced from this site's llms.txt
  ✓ Web3 industry page added (ai-seo-for-web3/) — was missing from this README's
    Industry Pages list, now included

=================================
TECHNICAL NOTES
=================================

- Static HTML — no server-side processing, no database, no CMS
- All images (logo, Tandeep photo) are embedded as base64 data URIs
- All pages are fully self-contained (single index.html per page)
- JSON-LD schema markup embedded in every page
- Mobile responsive — tested at 320px, 768px, 1024px, 1440px
- Fonts: Google Fonts (Sora, DM Serif Display) loaded via CDN
- No JavaScript dependencies — all JS is vanilla, inline
- FAQ accordion: uses CSS max-height transition + classList toggle
- Performance: Sora font weight 300 and JetBrains Mono removed (unused)
- Content-visibility:auto applied to off-screen sections
- All links use absolute paths (/page/) — no relative path issues

NOTE: The above applies to this repo (sheinnovatesai.com) only. The AI Search
Visibility Intelligence Platform (audit.sheinnovatesai.com) is a separate stack:
static HTML frontend + Vercel serverless functions + Supabase database, not
covered by these notes.

=================================
