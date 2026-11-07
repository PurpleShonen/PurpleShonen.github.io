# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users

Primary: recruiters and hiring managers filling SOC / junior security analyst roles. They skim fast and want proof of hands-on skill before reaching out.

Secondary (first-class): learners and the infosec community who come for CTF and investigation writeups, tutorials, and the xSecIRC community.

## Product Purpose

The personal site of PurpleShonen (Rahul Joriya), an aspiring SOC analyst. It is a portfolio and knowledge log: blog writeups, projects, certifications, and an About page with résumé and PGP key. Success: a hiring visitor leaves with a clear picture of real, hands-on blue-team ability and a way to make contact; a learner finds and reads writeups.

## Positioning

Proof over claims: real tools built (Phishinator, SOC Lab), real investigation and CTF writeups, and verifiable Credly certifications. The owner is "aspiring" — the site must not imply current SOC employment.

## Operating Context

Static Astro site deployed on Cloudflare Workers from `main`. Content is edited through Sveltia CMS (`/admin`) writing Markdown/YAML into `src/content` and `src/data`. Blog posts are long-form technical writeups with code and screenshots. The About page embeds Credly badge iframes (fixed 150×270 white cards that cannot be restyled).

## Capabilities and Constraints

- Sections: home (hero + latest posts), blog (paginated, tags, subposts, TOC), projects, about (certs, résumé, PGP key), authors, tags. `/disuse` and `/kuden` pages exist but are not linked from navigation.
- Light/dark theme toggle via `data-theme`.
- Content and structure must be preserved; CMS-edited fields must keep working.

## Brand Commitments

- Name: PurpleShonen.
- Purple color identity (#800080 and lavender #e6e6fa) stays a core brand color.
- Light mode is the default theme; dark mode remains available from the toggle.
- The homepage opens with the dictionary-style definition: "SOC An·a·lyst /pronunciation/ noun".

## Evidence on Hand

- Projects with real links and thumbnails in `src/content/projects/` (Phishinator, SOC Lab Project, xSecIRC, steganography, and others).
- Blog writeups in `src/content/blog/` (Snyk Fetch the Flag 2026, PascalCTF 2026, Outpost24, OverTheWire Bandit, and others).
- Credly badges: Security+, CS50, ISC2 CC, LFS101, IBM Cybersecurity Fundamentals, ISO/IEC 27001 Lead Auditor; certificate images in `public/certificates/`.
- Résumé at `public/resume.pdf`. No testimonials, employers, or metrics exist; none may be invented.

## Product Principles

- Proof first: show projects, writeups, and certifications, not adjectives.
- Recruiters first, community always: the homepage serves the skimming hiring visitor without demoting the blog.
- Honest framing: "aspiring" SOC analyst; never imply roles or results that are not real.
- Content stays editable through the CMS.
