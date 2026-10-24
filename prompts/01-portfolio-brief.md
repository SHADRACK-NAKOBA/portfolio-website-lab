# Prompt 1 – The portfolio brief (paste this into Claude Design)

**How to use:** in [Step 2](../docs/02-build-in-claude-design.md) you attach `Portfolio_Data.xlsx` and `profile.jpg`, then paste **everything inside the grey box** below as your message. Change only the three lines marked `<< CHANGE >>`.

> 💡 One complete, detailed first message gets a better result **and uses less of your Claude usage limit** than many small back-and-forth messages.

```
Build me a personal portfolio website: one page, professional, ready to export as a
standalone HTML file and host publicly for recruiters.

MY CONTENT
- Use ONLY the information in the attached spreadsheet Portfolio_Data.xlsx
  (tabs: About Me, Skills, Projects, Experience, Credentials).
- Ignore any row or cell that starts with "EXAMPLE" and the "Example" column - those are
  instructions, not my data.
- Do NOT invent anything: no made-up skills, employers, numbers, certifications or links.
  If a section in the spreadsheet is empty, leave that section out of the site completely.
  Do not add placeholder text like "Your Name" or "Lorem ipsum".
- Use the attached photo (profile.jpg) as my profile photo in the hero section.
  Embed the photo inside the HTML so it still shows after I export a single HTML file.

SECTIONS (in this order, skip any that are empty)
1. Hero: my name, title, tagline, photo, location, and buttons for Email, LinkedIn, GitHub.
2. About: my short bio and what I'm open to.
3. Projects: one card per project with the problem, what I built, the tech as small tags,
   the result, and a "View on GitHub" button using my link. This is the most important
   section - make it stand out.
4. Skills: grouped by category as clean rows of tags.
5. Experience: timeline, most recent first.
6. Certifications, Education & Achievements.
7. Contact: a clear call to action with my email and links.

DESIGN
- Style: << CHANGE: modern dark / minimal light / bold and colourful / surprise me >>
- Accent colour: << CHANGE: e.g. deep blue #2348C5, or "choose one that fits" >>
- Clean, modern typography, generous spacing, subtle scroll animations.
- A slim sticky navigation bar with links to each section.
- Fully responsive: must look good on a phone, since recruiters often open links on mobile.
- Good contrast and readable font sizes (accessibility).

TECHNICAL
- One self-contained HTML file (inline CSS/JS) that works when opened directly.
- Add a proper <title> (my name - my title), a meta description, Open Graph tags
  (og:title, og:description) so the link previews nicely on LinkedIn, and a simple favicon
  made from my initials.
- All external links open in a new tab.
- Footer: "(c) <current year> <my name>".

<< CHANGE (optional): add any extra request here, e.g. "Add a 'Download resume' button
   linking to resume.pdf" or delete this line >>

When you finish, list anything from my spreadsheet you could not use and why.
```
