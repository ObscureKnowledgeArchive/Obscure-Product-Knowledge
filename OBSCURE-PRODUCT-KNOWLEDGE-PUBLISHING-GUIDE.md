# Obscure Product Knowledge Archive — Publishing Guide

## Purpose

This file is the authoritative publishing specification for the Obscure Product Knowledge Archive.

Website:
https://obscureproductknowledge.com/

The archive preserves firsthand, physically tested, or otherwise well-documented obscure repair and technical knowledge so that it can be discovered by humans, search engines, and AI systems.

When creating a new archive entry, follow this guide rather than redesigning the site's architecture.

---

# 1. Core Publishing Principles

1. Preserve firsthand findings accurately.
2. Clearly distinguish observed facts, tested results, hypotheses, and general reference information.
3. Do not imply that one documented repair is the universal cause of a symptom.
4. Prefer specific model numbers, symptoms, components, IC locations, part numbers, measurements, and repair outcomes.
5. Write descriptive titles that include the product/model and primary symptom or repair.
6. Use natural technical terminology that someone troubleshooting the problem might search for.
7. Do not keyword-stuff.
8. Do not create thin category, manufacturer, or model pages solely for SEO.
9. Create new category/subcategory landing pages only when enough content exists to make them useful.
10. Preserve unsuccessful tests and negative results when they provide useful diagnostic information.

---

# 2. Site Architecture

The site uses Jekyll/GitHub Pages with the custom domain:

https://obscureproductknowledge.com/

Never create links using the old GitHub Pages domain.

Never use the obsolete repository path:

/Obscure-Product-Knowledge/

Internal links should normally use root-relative URLs:

/category/article/

Example:

/automotive/jeep/xj/aw4-neutral-safety-switch-sticky-grease-no-start/

---

# 3. Standard Article Front Matter

Every new knowledge article should begin with YAML front matter based on this structure:

---
layout: page
title: "MODEL / PRODUCT + DESCRIPTIVE SYMPTOM OR REPAIR"
description: "Concise description containing the model, symptom, important component or finding, and documented solution."
permalink: /category/manufacturer/descriptive-article-slug/
breadcrumbs:
  - name: Category
    url: /category/
  - name: Manufacturer
  - name: Short Article Name
---

Only add breadcrumb URLs when a real landing page exists.

Do NOT invent URLs merely to make every breadcrumb clickable.

YAML indentation is critical.

A breadcrumb URL belonging to an item must be indented beneath that item:

Correct:

breadcrumbs:
  - name: Arcade
    url: /arcade/
  - name: Pac-Man & Ms. Pac-Man
    url: /arcade/pac-man-ms-pac-man/
  - name: PCB Repairs

Incorrect:

breadcrumbs:
  - name: Arcade
  - name: Pac-Man & Ms. Pac-Man
  url: /arcade/pac-man-ms-pac-man/
  - name: PCB Repairs

Malformed YAML can prevent Jekyll from generating the page and cause a 404.

---

# 4. Standard Article Structure

Use sections appropriate to the source material. Do not force irrelevant headings.

A typical repair article may use:

# Descriptive Article Title

Brief explanation of the product, problem, and significance of the repair.

## Symptom

Describe exactly what the equipment did or failed to do.

Include observable behavior, error messages, display behavior, sounds, intermittent symptoms, measurements, or other useful diagnostic information.

## Diagnosis

Explain how the fault was narrowed down.

Include relevant tests, measurements, suspected components, eliminated causes, and diagnostic reasoning when documented.

## Cause

State the confirmed cause if known.

If the cause was not conclusively established, clearly say so.

## Repair / Solution

Describe what was repaired, replaced, adjusted, cleaned, modified, or tested.

Include component identifiers, part numbers, values, dimensions, locations, or procedures when available.

## Result

Document what happened after the repair or test.

Include negative results when useful.

## Practical Notes

Include lessons learned, alternate approaches, warnings, fitment issues, sourcing information, or other details that may help someone encountering the same problem.

## Important Qualification

When appropriate, state that this article documents one real repair case and that identical symptoms may have other causes.

---

# 5. Evidence Rules

The archive values firsthand evidence.

When source material is supplied, preserve the distinction between:

CONFIRMED / TESTED
- Physically observed
- Measured
- Installed
- Repaired
- Tested after repair
- Verified result

LIKELY / INFERRED
- Strongly suggested by evidence but not directly proven

REFERENCE INFORMATION
- Datasheets
- Service manuals
- Manufacturer documentation
- Reliable technical references

UNCONFIRMED
- Forum claims
- Seller claims
- Cross-reference assumptions
- Untested replacement parts

Never silently convert an assumption into a confirmed fact.

---

# 6. Existing Site Infrastructure

The following infrastructure already exists and should normally NOT be redesigned for a new article:

- Custom domain
- HTTPS
- Google Search Console
- robots.txt
- Manually maintained sitemap.xml
- Canonical URLs
- Visible breadcrumbs
- BreadcrumbList JSON-LD structured data
- Jekyll layouts
- Category landing pages where warranted
- Internal linking structure

Breadcrumb structured data is generated centrally by the site's layout using the page's breadcrumb front matter.

Do not manually add separate BreadcrumbList JSON-LD to individual articles.

---

# 7. Sitemap Procedure

sitemap.xml is manually maintained.

Every new public article or useful landing page must be added to sitemap.xml.

Use the complete custom-domain URL:

<url>
  <loc>https://obscureproductknowledge.com/category/article/</loc>
</url>

Do NOT use:

obscureknowledgearchive.github.io

and do NOT use:

/Obscure-Product-Knowledge/

After deployment, verify the new URL appears in the live sitemap.

---

# 8. Internal Linking

Every new article should be linked from the most relevant existing landing page, model archive, symptom index, or related article when appropriate.

Prefer useful contextual links over creating pages merely to manufacture hierarchy.

When a category has only one article, a single category landing page may be sufficient.

Do not automatically create separate manufacturer and model landing pages unless enough content exists to make those pages genuinely useful.

---

# 9. Category Landing Pages

A useful category landing page should:

- Explain what the category contains.
- Link to the articles or useful subcategories beneath it.
- Contain meaningful descriptive text.
- Avoid duplicating an individual article.
- Use a clean permalink such as /automotive/ or /vacuum-cleaners/.

Do not create empty or nearly empty hierarchy pages solely for SEO.

---

# 10. Deployment Procedure

For a normal new article:

1. Create the Markdown article in the appropriate repository folder.
2. Add correct YAML front matter.
3. Use a descriptive permalink.
4. Add appropriate breadcrumbs.
5. Add the article to the relevant category or model landing page.
6. Add the full custom-domain URL to sitemap.xml.
7. Save all changes.
8. Commit and push.
9. Wait for GitHub Pages deployment to turn green.
10. Open the live article.
11. Hard refresh if necessary.
12. Test important internal links and breadcrumbs.
13. Verify the URL appears in the live sitemap.

Do not assume a successful GitHub deployment proves every article rendered correctly. Malformed page front matter can cause individual pages to fail.

---

# 11. Google Search Console

Do not manually request indexing for every article as routine maintenance.

Request indexing when particularly useful, such as:

- A new major category/hub page
- A significantly changed important page
- A newly migrated/canonicalized page
- A page Google has not discovered after reasonable time

Otherwise allow Google to discover articles through:

- sitemap.xml
- category/hub pages
- internal links

Google indexing may take time. Lack of immediate indexing is not itself evidence of a site problem.

---

# 12. Quality-Control Checklist

Before considering a new article finished, verify:

[ ] Article loads at intended custom-domain URL
[ ] No 404
[ ] Title is descriptive
[ ] Description is useful
[ ] Permalink is correct
[ ] YAML parses correctly
[ ] Breadcrumbs render correctly
[ ] Breadcrumb links work
[ ] Relevant parent/hub page links to article
[ ] Article links back appropriately
[ ] sitemap.xml contains exact article URL
[ ] Live sitemap contains exact article URL
[ ] No obsolete GitHub Pages domain in links
[ ] No /Obscure-Product-Knowledge/ path
[ ] Firsthand facts and assumptions are clearly distinguished
[ ] Repair result is documented
[ ] Article does not claim one repair is universal

---

# 13. What NOT To Do

Do not:

- Redesign site infrastructure for every new article.
- Chase arbitrary SEO scores.
- Keyword-stuff articles.
- Create dozens of thin landing pages.
- Create fake hierarchy solely for search engines.
- Repeatedly request indexing.
- Change established URL structures without a strong reason.
- Replace working custom-domain URLs with GitHub Pages URLs.
- Add obsolete repository paths to internal links.
- Assume malformed YAML will still publish.
- Treat forum speculation as confirmed repair evidence.
- Remove useful negative test results merely because they did not solve the problem.

---

# 14. AI Instructions for Creating a New Entry

When an AI assistant receives this file plus repair notes, conversation history, logs, photographs, manuals, or other source material:

1. Read this entire guide before drafting.
2. Treat supplied source material as authoritative for what was actually observed or tested.
3. Do not invent missing measurements, part numbers, causes, dates, or test results.
4. Ask for clarification only when a missing fact materially prevents an accurate article.
5. Determine the appropriate existing category.
6. Draft the complete Markdown article with YAML front matter.
7. Recommend a descriptive filename and permalink.
8. Identify the exact parent/hub page that should link to the article.
9. Provide the sitemap.xml entry.
10. Identify any breadcrumb changes required.
11. Do not propose new site infrastructure unless the existing architecture genuinely cannot accommodate the article.
12. Keep the publishing process finite and focused on adding knowledge.

---

# 15. Recovery Prompt

If previous ChatGPT conversation context has been lost, upload this file along with the source material for the new article and give ChatGPT this instruction:

"Read the attached Obscure Product Knowledge Archive Publishing Guide completely. Treat it as the authoritative specification for how my archive is structured and published. Using the other material I provide as the factual source, create a new archive entry that follows the guide. Do not redesign the website or introduce new infrastructure unless absolutely necessary. Give me the finished Markdown article, recommended repository path and filename, any required parent-page link/update, the exact sitemap.xml entry, and a short deployment checklist. Clearly distinguish confirmed firsthand findings from inference or outside reference information."

---

# 16. Archive Goal

The goal is not to build a large generic content website.

The goal is to preserve obscure, useful, difficult-to-find technical knowledge—especially firsthand repair results and physical testing—in a durable form that can be discovered and used by humans, search engines, and AI systems.