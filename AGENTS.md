# AGENTS.md — Rules for Paul Marrandino's personal website

These rules apply to any AI agent (Claude or otherwise) working in this folder.

## Source of truth
- The CV is `Paul Marrandino Resume 2026.docx` (there is no `cv.pdf` yet). Site content must match it. Don't invent roles, dates, metrics, awards or skills.
- Page order: Summary → Portfolio → then the CV's section order: Professional Experience → Education → Volunteering → Interests.
- Portfolio lists Paul's public GitHub projects (live link + code link + screenshot); descriptions come from each repo's README/description.
- Public profiles: LinkedIn https://www.linkedin.com/in/paulmarrandino/ and GitHub https://github.com/pdino25.

## Never publish
- Home street address or apartment number. City-level location ("New York, NY") is fine.
- Personal phone numbers.
- Email addresses (personal or Google work email) unless Paul explicitly provides one for the site. Approved for the site: paulmarrandino@gmail.com (Email button). Never publish marrandino@google.com.
- Google-confidential information beyond what is already in the CV: internal project names, unreleased products, headcount plans, names of colleagues or candidates, compensation.
- Names or contact details of other people (references, managers, candidates).
- Credentials, API keys, tokens, analytics IDs, or any secret, in any file.
- Personal documents (the .docx/.pdf CV, IDs, transcripts) to a public repo, unless Paul asks for a downloadable CV.

## Ask Paul first
- Before any `git push`, creating a GitHub repo, enabling GitHub Pages, or deploying anywhere.
- Before adding, removing or rewording CV facts (metrics, titles, dates).
- Before adding a photo, a downloadable CV, a contact form, or any third-party script (analytics, fonts excepted, embeds, trackers).
- Before deleting or overwriting existing files.
- Before buying or pointing a custom domain.

## Fine without asking
- Layout, styling, spacing, accessibility and performance fixes that don't change content.
- Opening the site locally in a browser to check it.

## Style
- Vibe: professional but casual. Clear, confident, warm. No buzzword padding.
- Colors: Columbia blue (#B9D9EB) as the accent, deep navy (#0B2545-ish) for text and headers, white/off-white backgrounds. Keep contrast WCAG AA.
- Navigation: streamlined. One sticky top bar with section links, plus overview tiles that jump to sections. No nested menus.
- Tech: plain static HTML + CSS (+ minimal vanilla JS). No build step, no frameworks, no external JS libraries. Google Fonts allowed.
- Works on phones (no horizontal scroll), keyboard navigable, respects reduced-motion.
- Writing: first-person or neutral third-person consistently; use the CV's wording for facts; US English; dates as "Mon YYYY".
