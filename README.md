# Prince Hands-on Lab: Build & Publish Your AI-Powered Portfolio Website

Build a professional portfolio website with **Claude Design**, publish it **free** on **Netlify**, and put the link where recruiters look: LinkedIn, your CV, job applications. No coding needed.

| | |
|---|---|
| **Time** | 60–90 minutes (most of it is filling in your details well) |
| **Cost** | **Free.** Claude Design is on the Claude Free plan; Netlify's free plan hosts the site. A custom domain is optional (~$10–15/year). |
| **Level** | Beginner. No coding required. |
| **You need** | A Claude account, a free Netlify account, a profile photo, and ideally your 3 Prince lab projects on GitHub |

---

## Project overview

**The problem.** Recruiters spend seconds on each candidate. A CV *lists* skills; a portfolio *proves* them, with real projects, links to working code, and a professional presence. Most people never build one because they think they need to be web developers.

**What you will build.** A one-page, mobile-friendly portfolio website with your photo, bio, projects (linked to your GitHub labs), skills, experience and credentials, live at a public link like `https://your-name.netlify.app`.

**How it works**

```
 1. PREPARE              2. BUILD               3. REFINE             4. EXPORT            5. PUBLISH           6. SHARE
 Portfolio_Data.xlsx ──► Claude Design ───────► chat + comments ───► Standalone HTML ──► Netlify (free) ───► LinkedIn, CV,
 + profile.jpg           (Output → Design)      + ready prompts       (index.html)         your-name.netlify.app  applications
```

**Why this approach:**
- **Your data drives the design.** The spreadsheet makes you think through your story *before* using AI, so the site is specific to you and not generic.
- **Claude never invents.** The brief tells Claude to use only your spreadsheet. Empty sections are left out, with no fake skills or placeholder text.
- **Standalone HTML** is one file that works anywhere and costs nothing to host.
- **Projects first.** Your Prince lab repos become portfolio projects, which is proof of work recruiters can click on.

---

## Lab steps

| # | Step | What you do |
|---|---|---|
| 0 | [Get the lab files](docs/00-get-the-files.md) | Download this repo (template + prompts) |
| 1 | [Prepare your content](docs/01-prepare-your-content.md) | Fill in `Portfolio_Data.xlsx`, prepare your photo |
| 2 | [Build it in Claude Design](docs/02-build-in-claude-design.md) | Attach your files, paste the brief, generate the site |
| 3 | [Refine your design](docs/03-refine-your-design.md) | Improve it with chat, comments and ready-made prompts |
| 4 | [Export the HTML](docs/04-export-html.md) | Download your site as one HTML file |
| 5 | [Publish on Netlify](docs/05-publish-on-netlify.md) | Get a free public link and give it a professional name |
| 6 | [Update your site later](docs/06-update-your-site.md) | Change content without changing your link |
| 7 | [Share it everywhere](docs/07-share-it-everywhere.md) | LinkedIn, CV, email signature, GitHub profile |
| 8 | [Make it stand out](docs/08-make-it-stand-out.md) | Final quality checklist + optional custom domain |
| 9 | [Troubleshooting](docs/09-troubleshooting.md) | Fixes for every common problem |
| 10 | [Optional: host on GitHub Pages](docs/10-optional-github-pages.md) | Alternative free hosting with Git |

> **Stuck?** Go to [Troubleshooting](docs/09-troubleshooting.md).

---

## Repository layout

```
portfolio-website-lab/
├── README.md
├── docs/                          <- click-by-click guide (steps 0-10)
├── templates/
│   └── Portfolio_Data.xlsx        <- fill this in (step 1)
├── prompts/
│   ├── 01-portfolio-brief.md      <- the main prompt for Claude Design (step 2)
│   ├── 02-refinement-prompts.md   <- copy-paste improvements (step 3)
│   └── 03-update-later.md         <- add projects/certs/jobs later (step 6)
└── examples/
    └── final-checklist.md         <- tick every box before you share your link
```

## Summary

In this lab you:
- **Organised your professional story** in a structured template: identity, skills, projects with results, experience, credentials.
- **Generated a custom portfolio** with Claude Design from your own data, with clear rules against invented content.
- **Refined it** with chat, inline comments and targeted prompts, and checked it on mobile.
- **Exported** a self-contained HTML site and **published it free** on Netlify with a professional URL.
- **Put the link to work** on LinkedIn, your CV and applications, with a plan to keep it updated.

---

*Prince Hands-on Labs.*
